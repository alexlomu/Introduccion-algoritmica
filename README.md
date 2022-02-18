# Introduccion-algoritmica

#Ejercicio 8
Algoritmo porcentajes_iva_inversiones

Algoritmo_1:
Entrada:
  precio: REAL #Precio sin impuestos
  IVA: REAL #Porcentaje de IVA
Resultado: REAL
Precondición:
  precio > 0
  IVA = un valor entre 0% y 100%
Realización
  Resultado = precio * (1 + 0,01 * IVA)
Poscondición
  Resultado = precio * (1 + 0,01 * IVA)
  
Algoritmo_2:
Entrada:
  Capital inicial: REAL #Capital inicial invertido
  Capital final: REAL #Capital final
  meses: ENTERO #Número de meses que han pasado
Resultado: REAL
Precondición:
  Capital inicial > 0
  meses > 0
Realización:
  Diferencia de capital = Capital final - Capital inicial
  Intereses generados al mes = (Capital final - Capital inicial) / meses
Poscondición:
  Resultado: intereses generados al mes = (Capital final - Capital inicial) / meses
  
 
 
 
#Ejercicio 9
Algoritmo media_aritmética_ponderada

Algoritmo_1:
Entrada:
  numeros: REALES #3 números de los cuales queremos calcular la media(a, b y c)
Resultado: REAL
Precondición:
Realización:
  Suma de los números = a + b + c
  Divisón entre 3 = (a + b + c) / 3
Poscondición:
  Resultado: media = (a + b + c) / 3
  
Algoritmo_2:
Entrada:
  numeros: REALES #3 números de los cuales queremos calcular la media(a, b y c)
  ponderación: REALES #Coeficientes de ponderación
Resultado: REAL
Precondición:
  ponderación >= 0
Realización:
  Suma de los números = a + b + c
  Divisón entre 3 = (a + b + c) / 3
  media ponderada = ((a + b + c) / 3) * ponderación
Poscondición:
  Resultado: media ponderada = ((a + b + c) / 3) * ponderación
  
  
  
  
#Ejercicio 10
Algoritmo area_triangulo

Algoritmo_1:
Entrada
  base: REAL #Base del triángulo
  altura: REAL #Altura desde esa base del triángulo
Resultado: REAL
Precondición:
  base > 0
  altura > 0
Realización:
  suma = base + altura
  area = (base + altura) / 2
Poscondición:
  Resultado: area = (base + altura) / 2
  
Algoritmo_2:
Sí, en el caso de tener un triángulo rectángulo introduciríamos las medidas como base y altura de la misma manera y obtendríamos el área correcta.




#Ejercicio 11
Algoritmo salario_horas_extras
Entrada:
  Horas: REAL #Numero de horas total trabajadas
Resultado: REAL
Precondición:
  Horas > 8  
Realización:
  si horas < 36: TARIFA NORMAL * Horas
  si horas > 35 y horas < 44: (TARIFA NORMAL * 35) + (Horas - 35) * 1,25
  si horas > 43: (TARIFA NORMAL * 35) + (TARIFA NORMAL * 1,25 * 8) + (Horas - 43) * 1,50
Poscondición:
  si horas < 36:  Resultado = TARIFA NORMAL * Horas
  si horas > 35 y horas < 44: Resultado = (TARIFA NORMAL * 35) + (Horas - 35) * 1,25
  si horas > 43: Resultado = (TARIFA NORMAL * 35) + (TARIFA NORMAL * 1,25 * 8) + (Horas - 43) * 1,50
  
  
  
  
#Ejercicio 12
Algoritmo cuenta_deposito
Entrada:
  Datos cuenta: TEXTO #Credenciales de acceso a la cuenta
  Dinero a extraer: REAL #Cantidad a extraer
Resultado: BOOLEANO
Precondición:
  Dinero cuenta > 0
  Dinero a extraer > 0
  Dienero a extraer < Dinero cuenta
Realización
  sí se puede extraer: Nuevo dinero cuenta = Dinero cuenta - Dinero a extraer
Poscondición
  sí se puede extraer: Nuevo dinero cuenta = Dinero cuenta - Dinero a extraer
