---
layout: base.njk
title: Contact
permalink: /contact/
---

<section class="contact">
  <div class="container flow">
<img src="/images/TP-GOLD-TRIM-400x400.png" alt="True Poet Digital Designs logo" width="400" height="400" class="contact-logo">
      </div>
    </div>

    <!-- Header title -->
    <h2 class="section-title">Contact Us</h2>

    <form name="contact" method="POST" data-netlify="true" id="contact-form">
      <input type="hidden" name="form-name" value="contact">

      <p>
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>
      </p>
      <p>
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>
      </p>
      <p>
        <label for="message">Message:</label>
        <textarea id="message" name="message" required></textarea>
      </p>

      <!-- Send Button -->
      <div class="form-btn-container">
        <button type="submit">Send</button>
      </div>
    </form>
  </div>
</section>
