<html>
<head></head>
<body>
	<form action="" method="POST">
		Masukan Bintang 
		<input type = "text" name="bintang"> 
		<input type = "submit" name="submit" value="submit">
	</form>
</body>
</html>

<?php
	if(isset($_POST['submit'])){
	$batas = $_POST['bintang'];
	
	$tengah=($batas/2)+0.5;
		for ($baris =1; $baris <=$batas; $baris++){
			for ($kolom=1; $kolom <=$batas; $kolom++){
					if($baris==1 or $baris==$batas or $kolom==$tengah){
						echo "*";
					}else{
						echo "=";		
					}
			}
			echo "<br>";
		}
	}
?>
