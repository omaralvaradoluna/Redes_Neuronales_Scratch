# Dado el tamaño de los datos, no se pueden cargar a GitHub directamente, pero se pueden encontrar en

# https://challengedata.ens.fr/participants/challenges/31/

Hay que registrarse en la página, luego registrarse en el proyecto para tener acceso.

El problema trata de buscar un algoritmo de clasificación que ayude a crear estrategias de inversión en criptomonedas, basado en el "sentimiento" extraído de noticias y redes sociales.

Por cada hora de trading se contabilizó la ocurrencia de algunos terminos, tales como 'adoption' y 'hack', en un selecto numero de cuentas influyentes de twitter y en algunos foros como 'Bitcointalk'.

Se han creado 10 temas diferentes, algunos positivos y otros negativos y se han contabilizado las palabras antes mencionadas, antes de una normalización.

Dado un tema y un tema, hemos visto los conteos de las últimas 48 horas y se estandarizaron esos conteos. El resultado se multiplicó por el conteo promedio por hora y se dividió por el conteo promedio por hora de todo el entrenamiento

Se agregaron 5 características correspondientes a los precios finales en periodos de 1 hr, 6 hrs, 12 hrs, 24 hrs y 48 hrs El objetivo es predecir si el precio del Bitcoin tendrá un retorno (en la próxima hora) que sea de mas del 0.2%, entre -0.2% y 0.2% o menos al -0.2%.
