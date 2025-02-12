---
layout: page
title: "Contact"
permalink: /contact/
author_profile: true
---

Please fill out the form below to get in touch:

<form action="mailto:franz.buchmann07@gmail.com" method="post" enctype="text/plain" class="contact-form">
  <div class="form-group">
    <label for="contact-name">Name:</label>
    <input type="text" id="contact-name" name="name" required>
  </div>
  
  <div class="form-group">
    <label for="contact-email">Email:</label>
    <input type="email" id="contact-email" name="email" required>
  </div>
  
  <div class="form-group">
    <label for="contact-subject">Subject:</label>
    <input type="text" id="contact-subject" name="subject">
  </div>
  
  <div class="form-group">
    <label for="contact-message">Message:</label>
    <textarea id="contact-message" name="message" rows="5" required></textarea>
  </div>
  
  <div class="form-group">
    <button type="submit">Send Message</button>
  </div>
</form>