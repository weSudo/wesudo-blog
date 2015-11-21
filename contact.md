---
layout: page
title: Reach out
subtitle: Have something in mind ?? Feel free!
---

<form action="https://formspree.io/wesudo.sh@gmail.com" method="POST" class="form" id="contact-form">
  
  <div class="row">
    <div class="col-xs-6">
      <input type="email" name="_replyto" class="form-control input-lg" placeholder="Email" title="Email"><br>
    </div>
    <div class="col-xs-6">
      <input type="text" name="name" class="form-control input-lg" placeholder="Name" title="Name"><br>
    </div>
  </div>
  <input type="hidden" name="_subject" value="New submission from wesudo.github.io">
  <textarea type="text" name="content" class="form-control input-lg" placeholder="Message" title="Message" required="required" rows="3"></textarea>
  <input type="text" name="_gotcha" style="display:none">
  <input type="hidden" name="_next" value="./aboutme?message=Your message was sent successfully, thanks!" />
  <div>
  <button onclick="thanksFunc()"type="submit" class="btn btn-lg btn-primary">Submit</button>
  </div>
  <script>
      function thanksFunc() 
      {
        alert("Thank You for reaching out!");
      }
    </script>
</form>
