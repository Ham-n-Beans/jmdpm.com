---
layout: single
title: "Contact"
permalink: /contact/
author_profile: false
---

<form id="contact" name="contact" accept-charset="UTF-8" enctype="multipart/form-data" method="post" action="https://formspree.io/f/xanewvbb" target="_blank">
    <div>
      <label id="name" for="name">Name
        <input id="name" name="name" type="text" spellcheck="false" maxlength="255" required placeholder="Your name">
      </label>
    </div>
    <div>
      <label id="title" for="title">Title
        <input id="title" name="title" type="text" spellcheck="false" maxlength="255" required placeholder="Your title">
      </label>
    </div>
    <div>
      <label id="company" for="company">Company
        <input id="company" name="company" type="text" spellcheck="false" maxlength="255" required placeholder="Company">
      </label>
    </div>
    <div>
      <label id="email" for="email">Email
        <input id="email" name="email" type="email" spellcheck="false" maxlength="255" required placeholder="email@address.com">
      </label>
    </div>
    <div>
      <label id="message" for="message">Message
        <textarea id="message" name="message" spellcheck="true" rows="10" cols="50" required></textarea>
      </label>
    </div>
    <div>
      <button id="saveForm" name="saveForm" class="btn btn--info btn--large" type="submit">Send message</button>
    </div>
  </form>