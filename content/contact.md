---
title: "Contact"
description: "Contact"
date: 2019-05-09T19:04:10+02:00
---

<form method="POST" action="https://formspree.io/baptiste.jacquemet@gmail.com">
  <label for="name">Name *</label>
  <input type="text" name="name" placeholder="Your Name" required >
  <label for="email">Email *</label>
  <input type="email" name="email" placeholder="Your email" required >
  <label for="subject">Subject *</label>
  <input type="text" name="subject" placeholder="Subject" required >
  <label for="message">Message *</label>
  <textarea name="message" placeholder="Content of your message" required ></textarea>
  <input type="text" name="_gotcha" style="display:none" />
  <button type="submit" class="submit">Send</button>
</form>