<!DOCTYPE html>

<html lang="en" >
<head>
    <title>Home Page</title>
    <meta charset="utf-8" />
    <link rel="stylesheet" href="StyleSheet1.css"/>
    <link rel="icon" href="favicon.ico" type="image/x-icon">
    <link rel="shortcut icon" href="favicon.ico" type="image/x-icon">
    <script
    src="http://ajax.googleapis.com/ajax/libs/jquery/1.10.1/jquery.min.js">
    </script>
    <script>
     function promptQuality() {
       var quality;
       quality = prompt ("Please type age greater than 16");
       if (quality <= 16) {
          alert("Age is less than 16. You are not old enough.");
       } else {
       alert ("Age is valid.");
       }//end if
       }//end function promptQuality
     </script>
    <script>
      $(document).ready (function() {
      $("button") .click (function () {
        $("a:even").css('color','#006600');
      });
      });
    </script>
</head>
<body>
  <div id="wrapper"> 
  <header>
    <h1 style="color:#32617c">Kay's Music List</h1>
    <h2 style="color:#32617c">New Artists of Music<hr></h2>
    <script>
      alert("Welcome to Kay's Music");
    </script>
  </header>
  <input type="button" value="Enter age"
      onclick="promptQuality();">
  <div id="nav">
      <ul><a li href="index.html">Home</a>
          <a li href="contact.html">Contact</a>
      </ul>
      <button>Click here</button>
  </div>
  <div id="rightcol">
<figure>
<img src="microphone.png" height="200" width="320" alt="classic microphone">
 <figcaption>
    classic microphone
 </figcaption>
 </figure>

