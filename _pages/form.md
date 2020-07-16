---
title: "Contact Us"
layout: single
permalink: /form/

---


<form action="https://formspree.io/xgennrbv" 
method="POST">
    <label for="name">Name</label>
    <input type="text" id= "name" name="name" placeholder="John Doe" required>
    <label for="name">Email</label>
    <input type="email" id= "email" name="_replyto" placeholder="your@email.com" required>
    <label for="name">Phone</label>
    <input type="tel" id= "phone" name="phone" placeholder="123-456-7890" pattern="[0-9]{3}-[0-9]{3}-[0-9]{4}" required>
    <label for="message">Message</label>
    <textarea id="message" name="message" placeholder="Type here..." rows="10" cols="5"></textarea>
    <div class="g-recaptcha" data-sitekey="6LeKMK8ZAAAAAC4Xw8m75wJcj40ekvwaRbbJuCHP"></div>
    <label><button class="submitbtn" type="submit" value="Submit">Send</button></label>
</form>  


