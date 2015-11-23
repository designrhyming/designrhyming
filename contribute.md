---
layout: contribute
title: Contribute
permalink: /contribute/
---

In its present stage, Rhyme by Design is gradually forming a team. Whether you're a designer, aspiring beatmaker, researcher, or someone who just wants to experiment with the idea and give input - you can get involved!

####Assembly Unit

The Assembly Unit will be the crowd-sourced collective of beat makers. If you're interested in gettin down with the team, you can submit a request to join the Rhyme by Design Slack team!

<form id="contactform" method="POST">
  <input class="contact-form" type="hidden" name="_next" value="https://rhymexdesign.github.io" />
  <label class="form-text" for="name">Your name</label>
  <input class="contact-form" type="text" name="name" placeholder="Your name">
  <label class="form-text" for="email">Your email</label>
  <input class="contact-form" type="email" name="_replyto" placeholder="Your email">
  <input class="contact-form" type="hidden" name="_subject" value="Rhyme X Design Request" />
  <label class="form-text" for="message">Why would you like to join Rhyme By Design?</label>
  <textarea class="contact-form" name="message" placeholder="Your message"></textarea>
  <input class="contact-form" type="text" name="_gotcha" style="display:none" />
  <input class="contact-button" type="submit" value="Send">
</form>

<script>
    var contactform =  document.getElementById('contactform');
    contactform.setAttribute('action', '//formspree.io/' + 'rhymexdesign' + '@' + 'gmail' + '.' + 'com');
</script>