# Semana03Jueves.md
Semana 03 - Día Jueves - 08/12/2022

# Multiplication Tables with For

Algoritmo CalculadoraPara
	
	Imprimir " Introducir valor a multiplicar "
	Leer X
	Imprimir " Tabla del ", X	
	Imprimir " "
	
	Para Mult <- 1 Hasta 10 Con Paso 1 Hacer
		
		Resul = Mult * X
		Imprimir X, " * ", Mult, " = ", Resul
				
	Fin Para
	
FinAlgoritmo


# Ascending and Descending Numbers

Algoritmo AsciendeDesciende
	
	Imprimir " Introduzca número inicial "
	Leer X
	
	Para Resul <- X Hasta 0 Con Paso -1 Hacer
		
		Imprimir Resul
				
	Fin Para
	
FinAlgoritmo


# Greetings

Algoritmo Greetings
	
	X <- 0
	Res = "s"
	
	Mientras Res = "S" O Res = "s" Hacer
		
	Imprimir " Indicar la hora actual "
	Leer Hora
	
	Si Hora >= 0 Y Hora <= 12 Entonces
		
		Imprimir " Buenos días "
				
	FinSi
	
	Si Hora >= 13 Y Hora <= 18 Entonces
		
		Imprimir " Buenas tardes "
		
	FinSi
	
	Si Hora >= 19 Y Hora <= 23
		
		Imprimir " Buenas noches "
		
	FinSi
	
	Imprimir " Desea ejecutar de nuevo el programa S / N "
	Leer Res
	
	X = X + 1
		
	FinMientras
	
	Imprimir " Cantidad de ejecuciones ", X
	
FinAlgoritmo
