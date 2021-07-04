# Basecontroling-interface
basecontrolling.html
 <html> define the used language
 <head>declares the page's character encoding
            <meta>to inform the browser and  search engine how to deal with content 
             <link> to include external files on page
<iframe> to display a page inside an other one to style .CSS
<div>  contain code for buttons "LEFT,RIGHT,FRONT,BACK and STOP. Defined type ,value, name,style
   
*index.php
Set  connection to data base 
                          $connection = mysqli_connect($db_host, $db_user, $db_password, $db_db );

Check the connection 

                       if(mysqli_connect_errno()):
                         printf("Connect failed: %s\n", mysqli_connect_errno());
                          exit();
                           endif;

Query 
 
             $sql = mysqli_query($connection, "SELECT * FROM moving ORDER BY id DESC LIMIT 1");


* style .CSS
Contain formatting for html  page 
 Background ,header, center,forward, backward.


*slide and base .html 
   Combine the slider page  code and base control page code  to be one page 


Slide and base .php 
Connect  to the database
