<!-- <!DOCTYPE html> -->

<html>
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="description" content="">
    <meta name="author" content="">
    <link rel="stylesheet" href="lib/style.css">
    <title>Thrift Store Drop Off</title> 
    <script src="lib/script.js"></script> 
  </head>

  <body>
   
    <nav>
        <ul>
        <li>
        <a href="index.html">Lorem</a></li>
        <li>
        <a href="index.html">Ipsum</a></li>
        <li class="notMobile">
        <a href="index.html">Lorem</a></li>
        <li><a href="index.html">Ispum</a></li> 
        <li><a href="index.html">Lorem</a></li>
        <li><a href="index.html">Ipsum</a></li>
        </ul>
    </nav>
     <header>
        <h1>Lorem Ipsum</h1>
    </header>
     
    <main>
     
    <img src="https://i.ibb.co/0D8mgVt/Shutterstock-free-logo.jpg" alt="Shutterstock free logo" border="0">
    <h3>Thrift store drop off</h3>
      <p>Product: <input type="text" id="item" name="item" onkeydown = "if (event.keyCode == 13) document.getElementById('btnSubmit').click()" 
      maxlength="18" placeholder="enter item < 19 characters" /> </p>
      <p id="costLabel" >Cost: &nbsp;&nbsp;<input type="text" id="cost" name="cost" /></p> <br> 
      <input class="button" id="btnSubmit" name="submit" type="button" value="Add Item" onclick="addShoppinglist(item.value, cost.value)" /><br>
      <p id="MyList"></p>
      <p id="MyCart"></p>   
    <center><input class="button" id="about" name="about" type="button" value="about" onclick="about()" /> </center>
      <center><p id="sharelist"></p></center>
      <center><p id="sharebutton"></p></center>

     



  </main>
  </body>

  <footer>
         <a href="http://rvchourofcode.com" target="_blank">Join the Rock Valley College Hour of Code Family</a><br>
         Stuart Bernath<br>
            3301 N Mulford Rd,<br> Rockford, IL 61114<br>
            <a href="mailto:stuart@bernath.com">stuart@bernath.com</a><br>
            555-555-5555<br>
  </footer>

  
</html>
