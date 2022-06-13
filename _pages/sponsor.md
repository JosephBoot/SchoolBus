---
layout: page
title: Sponsor
permalink: /sponsor
comments: false
---


<script type="text/javascript">var submitted=false;</script>
<script type="text/javascript">
$('#gform').on('submit', function(e) {
  $('#gform *').fadeOut(2000);
  $('#gform').prepend("Thank you for your sponsorship! If you haven't already, please send your donation of any amount to my Dads <a href='https://paypal.me/andyboot' target='_blank'>PayPal (click here)</a>.");
  });
</script>

<form name="gform" id="gform" enctype="text/plain" action="https://docs.google.com/forms/d/e/1FAIpQLSdfAj5JTNrrB9z54NLeJS0T6KyKp25OVQswLnB01tLmKXKgEA/formResponse?" target="hidden_iframe" onsubmit="submitted=true;">
  <div class="container">
    <div class="row">
      <div class="col-sm">
        <div class="form-group">
          <label for="entry.1973658680">First Name</label>
          <input type="text" class="form-control form-control-lg" id="entry.1973658680" placeholder="Enter first name" required>
          <small id="emailHelp" class="form-text text-muted">This will be what is shown in the gallery.</small>
        </div>
      </div>
      <div class="col-sm">
        <div class="form-group">
          <label for="entry.1616968964">Last Name</label>
          <input type="text" class="form-control form-control-lg" id="entry.1616968964" placeholder="Enter last name" required>
        </div>
      </div>
    </div>
    <div class="row">
      <div class="col-sm">
        <div class="form-group">
          <label for="entry.1746644615">Email address</label>
          <input type="email" class="form-control form-control-lg" id="entry.1746644615" aria-describedby="emailHelp" placeholder="Enter email" required>
          <small id="emailHelp" class="form-text text-muted">I'll never share your email with anyone else.</small>
        </div>
      </div>
    </div>
    <div class="row">
      <div class="col-sm">
        <div class="form-group">
          <label for="entry.916397285">Address</label>
          <input type="text" class="form-control form-control-lg" id="entry.916397285" aria-describedby="emailHelp" placeholder="Enter postal address">
          <small id="emailHelp" class="form-text text-muted">For GiftAid. Leave blank to opt out.</small>
        </div>
      </div>
    </div>
    <div class="row">
      <div class="col-sm">
        <div class="form-group">
          <label for="entry.87928567">Your picture request</label>
          <input type="text" class="form-control form-control-lg" id="entry.87928567" placeholder="Please provide full description">
        </div>
      </div>
    </div>
    <div class="row">
      <div class="col-sm">
        <button type="submit" class="btn btn-primary btn-lg">Submit</button>
      </div>
    </div>
  </div>  
</form>
<iframe name="hidden_iframe" id="hidden_iframe" style="display:none;" onload="if(submitted) {}"></iframe>

