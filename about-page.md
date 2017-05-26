<!DOCTYPE html PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">
<html>
  <head>
    <meta http-equiv="Content-Type" content="text/html;charset=UTF-8">
    <meta name="viewport" content="initial-scale=1.0,minimum-scale=1.0,maximum-scale=1.0,width=device-width,user-scalable=no"/>
    <link title="new" rel="stylesheet" href="style.css" type="text/css">
    <title>Alain Mebsout</title>

    <script type="text/javascript">

      var _gaq = _gaq || [];
      _gaq.push(['_setAccount', 'UA-34455508-1']);
      _gaq.push(['_trackPageview']);

      (function() {
      var ga = document.createElement('script'); ga.type = 'text/javascript'; ga.async = true;
      ga.src = ('https:' == document.location.protocol ? 'https://ssl' : 'http://www') + '.google-analytics.com/ga.js';
      var s = document.getElementsByTagName('script')[0]; s.parentNode.insertBefore(ga, s);
      })();

    </script>
  </head>

  <body>

<!--------------------------- TOP MENU --------------------------------->
    <div id="menu-banner">
      <div id="menu_box">

    <div id="name">Alain Mebsout</div>

    <div class="menu-item">

    <ul id="nav">
      <li>
        <a class="current_tab" href=".">About</a>
      </li>


      <li>
        <a href="software.html">Software</a>

        <ul id="subnav">
          <li><a href="software.html#kind2">Kind 2</a></li>
          <li><a href="software.html#cubicle">Cubicle</a></li>
          <li><a href="software.html#alt-ergo">Alt-Ergo</a></li>
          <li><a href="software.html#altgr-ergo">AltGr-Ergo</a></li>
          <li><a href="software.html#proof-manager">Proof-Manager</a></li>
        </ul>

      </li>


      <li>
        <a href="publications.html">Publications</a>
      </li>

    </ul>

    </div>
      </div>
    </div>
<!--------------------------------------------------------------->


    <div id="content">


      <div class="card">

    <span class="picture">
      <!-- <img src="images/moi.png" class="picture"/> -->
    </span>

      <h2>Contact</h2>
    <table>
      <tr>
        <th>Snail mail</th>
        <th><img src="images/me.jpg"></th>
        <td>
                Department of Computer Science <br/>
                The University of Iowa <br/>
                14 MacLean Hall <br/>
                Iowa City, IA 52242 <br/>
                USA<br/>
        </td>
      </tr>
      <tr>
        <th>Office</th>
        <th><img src="images/office.png"></th>
        <td>
          MLH 201G<br/>
        </td>
      </tr>
      <tr>
        <th>Telephone</th>
        <th><img src="images/phone.png"></th>
        <td>
         <?php
           $lang = $_SERVER['HTTP_ACCEPT_LANGUAGE'];
               switch ($lang){
           case "en-us":
                       /* echo "0"; */
         break;
           default:
         echo "+1 ";
         break;
           }
              ?>(319) 335-0745
        </td>
      </tr>
      <tr>
        <th>E-mail</th>
        <th><img src="images/email.png"></th>
        <td>
          alain-mebsout AT uiowa.edu
        </td>
      </tr>

    </table>

      </div>

      <div class="card">

      <h2>About me</h2>

      <p>
        Im a technology enthusiast
      </p>

      <p>
          I am a MSc at West Universisty of Timisoara.
      </p>

      <p>
    My area of interes is cloud computing, artificial inteligence and transhumanism.
      </p>
      </div>



      <div class="card">



      </div>


    </div>

  </body>

</html>
