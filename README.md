# find-the-length-count-no-of-words-revers-specific-string-of-agiven-string.
<?php
//find the lenght of the srting
$str="kamala instute of technology and science";
echo"length of string is".strlen($str)"."<br>";
//count no of word in a string
$len=str_word_count($str);
echo"numberof words in a given string is ".$len."<br>";
//resvers a string
$string="lokseh";
$length=strlen($string);
echo"reverse of "$string."is";
for($i=($length-1);$i>=0;$i-)
{
echo$string[$i];
}
echo"<br>";
// searching for speciall string
$mystring='hello,there';
if(strstr($myString,'hello'))
{
echo"text found";
{
else{
echo"text not found";
}
?>
