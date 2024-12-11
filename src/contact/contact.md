---
layout: base.njk
title: Contact Us
---

<h2>Get Involved</h2>
<p style="text-align: center;">Interested in volunteering? Send us a message!</p>

<form name="contact" method="POST" data-netlify="true">

<p>
<label for="name">Name:</label>
<input type="text" id="name" name="name" required>
</p>

<p>
<p style="text-align: center"> How would you like to participate? </p>
<input type="checkbox" id="volunteer" name="volunteer" value="Volunteer">
<label for="volunteer"> Volunteer </label><br>

<input type="checkbox" id="donate" name="donate" value="donate">
<label for="donate"> Donate an Item </label><br>

<p>
<label for="email">Email:</label>
<input type="email" id="email" name="email" required>
</p>

<p>
<label for="message">Message:</label>
<textarea id="message" name="message" required></textarea>
</p>

<p>
<button type="submit">Send</button>
</p>

</form>