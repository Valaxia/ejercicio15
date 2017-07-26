 <!DOCTYPE html>
 <html lang="en">
 <head>
 	<meta charset="UTF-8">
 	<title>Document</title>

 <script>
 	var calcularIMC = function(peso, estatura){
 	return peso / (estatura * estatura);
 }

 var interpretarIMC = function(peso, estatura){
 	var imc = calcularIMC(peso, estatura);
 	if (imc > 40){
 		return "sobrepeso";
 	} else if (imc >= 18) {
 		return "ok";
 	} else {
 		return "bajo peso";
 	}
 }

 resultado = interpretarIMC(30, 1.30);
 console.log(resultado);
 </script>
 </head>

 <body>
 	
 </body>
 </html>



 