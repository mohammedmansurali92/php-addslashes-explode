# php-addslashes-explode
add slashes  and explode function
<?php
//built in function  // string function=100(addslashes, explode)
//addslashes= +add \slash
//explode = string=>array
$name="My name is 'Mohammead Mansur' Ali";
echo addslashes($name);
echo "<br>";
//explode
$str="My name is mansur ali";
print_r (explode(" ",$str));
echo "<br>";
$value=" I love and like Dhaka and Bangladesh";
print_r (explode(" ",$value));
?>
