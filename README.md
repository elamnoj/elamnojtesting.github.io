<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Metopio - Network Error</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Lato:wght@300&display=swap');

    
    body{
      text-align: center;
      margin: 30px;
      font-family: 'Lato', sans-serif;
    }
  
    h1 {
      color: #1d84b5;
    }
    
    p, h2, h3 {
      color: #252d43;
    }
    

    .FAQ{
      padding-left: 50px;
      padding-right: 50px;
    }

    .collapsible {
      background-color: #1d84b5;
      color: white;
      cursor: pointer;
      padding: 18px;
      padding-left: 30px;
      padding-right: 30px;

      width: 100%;
      border: none;
      text-align: center;
      outline: none;
      font-size: 15px;
      margin-right: 30px;
    }

    .active, .collapsible:hover {
      background-color: #252d43;
    }

    .content {
      padding: 0 18px;

      max-height: 0;
      overflow: hidden;
      transition: max-height 0.2s ease-out;
      background-color: #ecf0f1;
    }
  </style>
</head>
<body>
  <div></div>
  <div class="main">
    <img src="https://i0.wp.com/public.metop.io/wp-content/uploads/2021/05/output-onlinepngtools.png?fit=844%2C459&amp;ssl=1" alt="" width="844" height="459" title="output-onlinepngtools">
    <br>
    <h1 class="text-center">Metopio is Experiencing an Upstream Network Error</h1>
    <h3>Sorry! It seems something is wrong with Metopio's network provider. Our team is investigating.</h3>
    <h3>If you need urgent assistance, please contact us at <a href="mailto:support@metop.io?subject=Urgent assistance">support@metop.io</a>.</h3>
    <br>
    <div class="FAQ">
      <h2>Additional info:</h2>
      <button class="collapsible">Is there something wrong with my browser or connection?</button>
        <div class="content">
          <p>No, this error originates with Metopio's network provider. More than likely meaning Metopio is not the only site affected by this outage.</p>
        </div>
      <button class="collapsible">When will Metopio be back online?</button>
        <div class="content">
          <p>Solutions to these issues can be difficult to assess, but we are working diligently to resolve it. You can sign up for updates at <a href="https://status.metop.io/">Metopio's status page</a> to be notified when Metopio is back online.</p>
        </div>
      <button class="collapsible">I have reports I need to run or data I need access to, what can I do?</button>
        <div class="content">
          <p>Contact us at <a href="mailto:support@metop.io?subject=Urgent assistance">support@metop.io</a> and we'll do our best to assist you.</p>
        </div> 
    </div>
    <br>
    <h3>Technical info on this error:</h3>
  ::CLOUDFLARE_ERROR_500S_BOX::
</div>
<div></div>
</body>
<script>
var coll = document.getElementsByClassName("collapsible");
var i;

for (i = 0; i < coll.length; i++) {
  coll[i].addEventListener("click", function() {
    this.classList.toggle("active");
    var content = this.nextElementSibling;
    if (content.style.maxHeight){
      content.style.maxHeight = null;
    } else {
      content.style.maxHeight = content.scrollHeight + "px";
    } 
  });
}
</script>
</html>
