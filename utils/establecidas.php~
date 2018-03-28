<?php
error_reporting(E_ALL);
ini_set("display_errors", 1);
$final = '"xxx"';
$comando = "netstat -putna |grep ESTABLISHED | awk {'print $1,$4,$5,$6,$final'}";
$red = str_replace("\n","",explode("xxx", shell_exec($comando)));

//header('Content-Type: application/json');
echo json_encode($red);



?>
