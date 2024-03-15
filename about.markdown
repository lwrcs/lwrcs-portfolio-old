---
layout: page
title: About
permalink: /about/
---

<section class="about-section">
  <div class="container">
    <h2>About Me</h2>
    <p>Welcome to my corner of the internet. Here's a little bit about me:</p>
    <p>I'm passionate about [insert your interests here], and I love [describe what you love to do]. Feel free to reach out to me with any questions or just to say hello!</p>
  </div>
</section>

<section class="contact-section">
  <div class="container">
    <h2>Contact Me</h2>
    <p>Have a question or want to get in touch? Fill out the form below:</p>
    <form action="https://formspree.io/f/xkndvwal" method="POST" class="contact-form">
      <div class="form-group">
        <label for="email">Your Email:</label>
        <input type="email" id="email" name="email" required>
      </div>
      <div class="form-group">
        <label for="message">Your Message:</label>
        <textarea id="message" name="message" required></textarea>
      </div>
      <button type="submit">Send</button>
    </form>
  </div>
</section>

<style>
  /* General Styles */
  body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f8f9fa;
  }
  .container {
    max-width: 800px;
    margin: 0 auto;
    padding: 0 20px;
  }
  h2 {
    font-size: 2.5em;
    margin-bottom: 20px;
    color: #333;
  }
  p {
    font-size: 1.1em;
    line-height: 1.6;
    color: #555;
  }
  /* About Section Styles */
  .about-section {
    padding: 50px 0;
    text-align: center;
    background-color: #fff;
    box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
    border-radius: 15px;
    margin-bottom: 40px;
  }
  /* Contact Section Styles */
  .contact-section {
    padding: 50px 0;
    text-align: center;
    background-color: #f8f9fa;
  }
  .contact-form {
    max-width: 500px;
    margin: 0 auto;
    display: flex;
    flex-direction: column;
    align-items: center;
    background-color: #fff;
    padding: 30px;
    border-radius: 10px;
    box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
  }
  .form-group {
    margin-bottom: 20px;
  }
  .form-group label {
    display: block;
    margin-bottom: 5px;
    font-weight: bold;
    color: #333;
  }
  input[type="email"],
  textarea {
    width: 100%;
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 5px;
    font-size: 1em;
  }
  button[type="submit"] {
    padding: 12px 30px;
    background-color: #007bff;
    color: #fff;
    border: none;
    border-radius: 25px;
    cursor: pointer;
    transition: background-color 0.3s ease;
    font-size: 1.1em;
  }
  button[type="submit"]:hover {
    background-color: #0056b3;
  }
</style>

