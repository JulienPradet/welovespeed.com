---
title: Contact us
description: "Contact us"
i18n-key: contact
permalink: /en/contact/
layout: page
---

# {{ page.title }}

You have a question, a suggestion? Feel free to contact us.

<form id="contact-form" netlify-honeypot="cb" class="page__form js-form form" method="POST" action="contact" data-netlify="true">
  <fieldset>
    <label for="email">Your email (required):</label>
    <input type="email" name="email" id="email" required>
  </fieldset>
  <fieldset>
    <label for="message">Your message (required):</label>
    <textarea name="message" rows="10" id="message" required></textarea>
  </fieldset>
  <p><small>Note: although the email is required for us to answer you, feel free to use anonymous@anon.com if you wish to remain anonymous.</small></p>
  <fieldset>
    <div data-netlify-recaptcha="true"></div>
    <button type="submit" class="button" data-text="Send">
      <span class="button-inner">Send</span>
    </button>
  </fieldset>
</form>
