---
title: "Contact Us"
layout: single
permalink: /form
classes: wide

---

## Hello World

<script>
    function onSubmit(token) {
        console.log("form submitted");
        document.getElementById("contact-form").submit();
    }
</script>

<form action="https://formspree.io/xgennrbv" 
method="POST" id="contact-form">
    <div class="g-recaptcha" data-sitekey="6LeI8q4ZAAAAAEYWbqhRlTJUTKRWqQjuoqtJxn2v"></div>
    <label for="name">Name</label>
    <input type="text" id= "name" name="name" required>
    <label for="name">Email</label>
    <input type="email" id= "email" name="email" required>
    <label for="name">Phone</label>
    <input type="tel" id= "phone" name="phone" required>
    <input type="hidden" name="_captcha" value="true">
    <button type="submit" value="Submit">Send</button>
</form>  
