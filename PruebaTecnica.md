"""1. FizzBuzz
	* Desarrolle una solución para el siguiente problema:
		* Dada una secuencia de números (variable), mostrar un resultado cubriendo los siguientes  criterios de aceptación:
			* Para todos los múltiplos del número 5, en lugar del número, mostrar la palabra Buzz
			* Para todos los múltiplos del número 3, en lugar del número, mostrar la palabra Fizz
			* Para todos los múltiplos del número 3 y 5, en lugar del número, mostrar la palabra FizzBuzz
			* En caso de nos cumplirse nunguna condicion anterior, mostrar el número"""
lista= [2,4,5,10,15]
DEF FizzBuzz(list):
	resultado = []
	for i in list:
		if i % 5 == 0 and i%3 == 0:
			resultado.append('FizzBuzz')

		elif i % 5 == 0:
			resultado.append('Buzz')
		elif i%3 == 0:
			resultado.append('Fizz')


		else:
			resultado.append(i)

return resultado  
		

2. Guess my number
	* Desarrolle una solución para el siguiente problema:
		* Dada una secuencia de números (variable), seleccione un número a evaluar/adivinar, permita adivinar el número entre la secuencia previamente establecida
			* Si el número propuesto es menor, indicar el mensaje: **El número que buscas es mayor**
			* Si el número propuesto es mayor, indicar el mensaje: **El número que buscas es menor**
			* Si el número propuesto es igual, indicar el mensaje: **Correcto, ganaste**
			* La solución debe permitir establecer un nivel de dificultad para establecer el número de intentos máximo permitido, por ejemplo:
			 * Fácil = 8 intentos
			 * Medio = 5 intentos
			 * Difícil = 3

lista = [2,3,4,5]
evaluar = [2]
correcto =[5]
def guess_my_number(n,numC):
	if  n <  numC:
		print("El número que buscas es mayor")
	elif n > numC:
		print("El número que buscas es menor")
	elif n = numC:
		print("Correcto, ganaste")


