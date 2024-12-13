# KarDarChamanFaravone.php
https://quera.org/problemset/4065?tab=description
<?php
list($a, $b, $l) = explode(" ", readline("Enter 3 numbers: "));
$a = (int)$a;
$b = (int)$b;
$l = (int)$l;
$s = 0;
$k = $l +1;
for($i = 1; $i < $k; $i++){
	if($i % 2 != 0){
		$s += $a;
	}else{
		$s += $b;
	}
}
echo $s;
