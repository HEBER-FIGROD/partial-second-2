# partial-second-2
dfd codigo

Heber Emmanuel Figueroa Rodríguez


### Ejercicio 1 FOR. Contar del 1 hasta el 10 y sumar los valores.

#### 1.1 Análisis
Se necesita utilizar el simbolo de proceso para asignar la variable suma=0, despues utilizar el simbolo de ciclo de for para hacer un contador de i=1; i<=10; i++, en caso de que i sea menor a 10 se utiliza otro simbolo de proceso para ingresar s=s+i y se regressa al ciclo hasta que i sea mayor a 10 y al final se utiliza un simboo de salida para imprimir la suma de los numeos.

#### 1.2 DIAGRAMA DE FLUJO DE DATOS
[![0.jpg](https://i.postimg.cc/SQcrpp5f/0.jpg)](https://postimg.cc/K4vLnCm1)

#### 1.3 PRUEBA DE ESCRITORIO
|s=0|i  |i<=10|i++|s=s+i|s|
|---|---|-----|---|-----|-|
|0  |1  |si   |1  |1    |1|
|0  |1  |si   |2  |2    |2|
|0  |2  |si   |3  |3    |3|
|0  |3  |si   |4  |4    |4|
|0  |4  |si   |5  |5    |5|
|0  |5  |si   |6  |6    |6|
|0  |6  |si   |7  |7    |7|
|0  |7  |si   |8  |8    |8|
|0  |8  |si   |9  |9    |9|
|0  |9  |si   |10 |10   |10|
|0  |10 |si   |11 |     |55|
|0  |11 |no   |

#### 1.4 ENTRADAS
NINGUNA

#### 1.5 SALIDA
S

### 1.6 CICLO FOR
i=1; i<=10; i++

###  1.7 CODIGO

```dart
void main(List<String> args) {
   int s = 0;
   for (var i = 1; i <= 10; i++) {
    s += i;
    }
    print("La suma de los valores es: $s");
    }
```



### Ejecicio 1 Do/While. Contar del 1 al 10 y sumar los valores.

#### 1.1 Análisis
Se necesita utilizar el simbolo de proceso para asignar la variable de s=0 y c=1, despues se utiliza otro simbolo de proceso para asignar s=c+s, volvemos a utilizar otro simbolo de proceso para asignar c=c+1, despues se utiliza un simbolo de decision para preguntar si c<=10, en caso de que si sea asi se regresa al simbolo de proceso de s=c+s, hasta que c sea = a 10 y finalmente utilizamos un sibolo de salida para imprimir s.

#### 1.2 DIAGRAMA DE FLUJO DE DATOS
[![1.jpg](https://i.postimg.cc/VkbKVbjD/1.jpg)](https://postimg.cc/qN4ctqD3)

#### 1.3 PRUEBA DE ESCRITORIO
|s=0|c=1|s=c+s|c=c+1|c<=10|s|
|---|---|-----|-----|-----|-|
|0  |1  |1    |2    |si   |1|
|   |   |2    |3    |si   |2|
|   |   |3    |4    |si   |3|
|   |   |4    |5    |si   |4|
|   |   |5    |6    |si   |5|
|   |   |6    |7    |si   |6|
|   |   |7    |8    |si   |7|
|   |   |8    |9    |si   |8|
|   |   |9    |10   |si   |9|
|   |   |10   |11   |no   |10|
|   |   |     |     |     |55|

#### 1.4 ENTRADAS
NINGUNA

#### 1.5 SALIDA
S

### 1.6 PROCESO
S=0
C=1
S=C+S
C=C+1

### 1.7 DECISION
C<=10

### 1.8 CODIGO
```dart
void main(List<String> args) {
    int s = 0, c = 1;

     do {
     s += c;
     c++;
    } while (c <= 10);
    print("El resultado de la suma de los valores es:$s");
    }
```



### Ejercicio 1 While. Contar del 1 al 10 y sumar los valores.

#### 1.1 ANÁLISIS
Se necesita utilizar el simbolo de proceso para asignar la variable de s=0 y c=1, despues se utiliza un simbolo de decision para preguntar si c<=10, en caso de que si sea asi se utiliza un simbolo de proceso que asigna las variables de s=c+s, despues se utiliza otro simbolo de proceso que asigna las variables de c=c+1, despues de regresa al simbolo de decision y asi repetidamente hasta que c sea mayor a 10 y finalmente utilizamos un sibolo de salida para imprimir s.

#### 1.2 DIAGRAMA DE FLUJO DE DATOS
[![2.jpg](https://i.postimg.cc/52bR6STT/2.jpg)](https://postimg.cc/1f7Hdw9r)

#### 1.3 PRUEBA DE ESCRITORIO
|s=0|c=1|C<=10|s=s+c|c=c+1|s|
|---|---|-----|-----|-----|-|
|0  |1  |si   |1    |2    |1|
|   |   |si   |2    |3    |2|
|   |   |si   |3    |4    |3|
|   |   |si   |4    |5    |4|
|   |   |si   |5    |6    |5|
|   |   |si   |6    |7    |6|
|   |   |si   |7    |8    |7|
|   |   |si   |8    |9    |8|
|   |   |si   |9    |10   |9|
|   |   |si   |10   |11   |10|
|   |   |no   |     |     |55|

#### 1.4 ENTRADAS
NINGUNA

#### 1.5 SALIDA
S

### 1.6 PROCESO
S=0
C=1
S=C+S
C=C+1

### 1.7 DECISION
C<=10

### 1.8 CODIGO
```dart
// Contar del 1 hasta el 10 y sumar los valores.
  void main(List<String> args) {
  int s = 0, c = 1;

  while (c <= 10) {
    s += c;
    c++;
   }
   print("El resultado de la suma de los valores es:$s");
   } //while
```




### Ejercicio 2 FOR. Obtenga la suma de los primero 5 numeros pares.

#### 2.1 Análisis
Se necesita utilizar el simbolo de proceso para asignar la variable suma=0, despues utilizar el simbolo de ciclo de for para hacer un contador de i=2; i<=10; i=i+2, en caso de que i sea menor a 10 se utiliza otro simbolo de proceso para ingresar s=s+i y se regressa al ciclo hasta que i sea mayor a 10 y al final se utiliza un simboo de salida para imprimir la suma de los numeos.

#### 2.2 DIAGRAMA DE FLUJO DE DATOS
[![3.jpg](https://i.postimg.cc/MKvFRGpb/3.jpg)](https://postimg.cc/rK2j2MWK)

#### 1.3 PRUEBA DE ESCRITORIO
|s=0|i  |i<=10|i+2|s=s+i|s|
|---|---|-----|---|-----|-|
|0  |2  |si   |2  |2    |2|
|0  |4  |si   |4  |4    |4|
|0  |6  |si   |6  |6    |6|
|0  |8  |si   |8  |8    |8|
|0  |10 |si   |10 |10   |10|
|0  |   |si   |12 |     |30|
|0  |   |no   |

#### 1.4 ENTRADAS
NINGUNA

#### 1.5 SALIDA
S

### 1.6 CICLO FOR
i=1; i<=10; i++

###  1.7 CODIGO
```dart
void main(List<String> args) {
  int s = 0;
  for (var i = 2; i <= 10; i = i + 2) {
    s = s + i;
   }
    print("resultado de la suma de numeros pares es:$s");
    } //For
```


### Ejecicio 2 Do/While. Obtenga la suma de los primeros 5 numero pares.

#### 2.1 Análisis
Se necesita utilizar el simbolo de proceso para asignar la variable de s=0 y c=1, despues se utiliza otro simbolo de proceso para asignar s=s+c*2, volvemos a utilizar otro simbolo de proceso para asignar c=c+1, despues se utiliza un simbolo de decision para preguntar si c<=5, en caso de que si sea asi se regresa al simbolo de proceso de s=s+c*2, hasta que c sea mayor a 5 y finalmente utilizamos un sibolo de salida para imprimir s.

#### 2.2 DIAGRAMA DE FLUJO DE DATOS
[![4.jpg](https://i.postimg.cc/sXpvTW4F/4.jpg)](https://postimg.cc/YGCr9hP8)

#### 2.3 PRUEBA DE ESCRITORIO
|s=0|c=1|s=s+c*2|c=c+1|c<=5|s|
|---|---|-----|-----|-----|-|
|0  |1  |2    |2    |si   |2|
|   |   |4    |3    |si   |4|
|   |   |6    |4    |si   |6|
|   |   |8    |5    |si   |8|
|   |   |10   |6    |no   |10|
|   |   |     |     |     |30|

#### 2.4 ENTRADAS
NINGUNA

#### 2.5 SALIDA
S

### 2.6 PROCESO
S=0
C=1
S=S+C*2
C=C+1

### 2.7 DECISION
C<=5

### 2.8 CODIGO
```dart
void main(List<String> args) {
   int s = 0, c = 1;
   while (c <= 5) {
    s = s + c * 2;
    c = c + 1;
   }
    print("resultado de la suma de numeros pares:$s");
   } //While
```


### Ejercicio 2 While. Obtener la suma de los primeros 5 numeros pares.

#### 2.1 ANÁLISIS
Se necesita utilizar el simbolo de proceso para asignar la variable de s=0 y c=1, despues se utiliza un simbolo de decision para preguntar si c<=5, en caso de que si sea asi se utiliza un simbolo de proceso que asigna las variables de s=s+C*2, despues se utiliza otro simbolo de proceso que asigna las variables de c=c+1, despues de regresa al simbolo de decision y asi repetidamente hasta que c sea mayor a 5 y finalmente utilizamos un sibolo de salida para imprimir s.

#### 2.2 DIAGRAMA DE FLUJO DE DATOS
[![5.jpg](https://i.postimg.cc/633GpqdF/5.jpg)](https://postimg.cc/946fxWgB)

#### 2.3 PRUEBA DE ESCRITORIO
|s=0|c=1|C<=5 |s=s+c*2|c=c+1|s|
|---|---|-----|-----|-----|-|
|0  |1  |si   |2    |2    |2|
|   |   |si   |4    |3    |4|
|   |   |si   |6    |4    |6|
|   |   |si   |8    |5    |8|
|   |   |si   |10   |6    |10|
|   |   |no   |     |     |30|


#### 12.4 ENTRADAS
NINGUNA

#### 2.5 SALIDA
S

### 2.6 PROCESO
S=0
C=1
S=S+C*2
C=C+1

### 2.7 DECISION
C<=5

### 2.8 CODIGO
```dart  
void main(List<String> args) {
  int s = 0, c = 1;

  do {
    s = s + c * 2;
    c = c + 1;
  } while (c <= 5);
   print("la suma de numeros pares es:$s");
   } //Do While
```


### Ejercicio 3 FOR. Almacene en un array el numero n leido del teclado, el tamaño del array es 10.

#### 3.1 Análisis
Se necesita utilizar el simbolo de proceso para asignar el array A[10], despues se utiliza el simboo de entrada para almacenar los elementos en n, despues utilizar el simbolo de ciclo de for para hacer un contador de i=0; i<=9; i=i+1, en caso de que i sea menor a 10 se utiliza otro simbolo de proceso para ingresar A [i]= N, y se regressa al ciclo hasta que i sea mayor a 10 y al final se utiliza un simboo de salida para imprimir A.

#### 3.2 DIAGRAMA DE FLUJO DE DATOS
[![6.jpg](https://i.postimg.cc/B6bpvv1Y/6.jpg)](https://postimg.cc/mzxCXBjC)

#### 3.3 PRUEBA DE ESCRITORIO
|A[10]|i  |i<10 |i+1|A[i]=N|A |
|-----|---|-----|---|------|--|
|0   |0   |0<10 |   |0     |0 |
|1   |1   |1<10 |1  |1     |1 |
|2   |2   |2<10 |2  |2     |2 |
|3   |3   |3<10 |3  |3     |3 |
|4   |4   |4<10 |4  |4     |4 |
|5   |5   |5<10 |5  |5     |5 |
|6   |6   |6<10 |6   |6     |6 |
|7   |7   |7<10 |7  |7    |7 |
|8   |8   |8<10 |8  |8     |8 |
|9   |9   |9<10 |9  |9     |9 |




#### 3.4 ENTRADAS
N

#### 3.5 SALIDA
A

### 3.6 CICLO FOR
i=0; i<=9; i++

###  3.7 CODIGO
```dart  
import 'dart:io';

  //Leer 10 numeros del teclado y ponerlos en una lista.
  void main14() {
  var arra = new List.filled(10, 0);
  stdout.write("Dame diez numeros\n ");
  stdout.write("----------\n");
  for (var i = 0; i <= 9; i++) {
    String? s = stdin.readLineSync();
    if (s != null) {
      int n = int.parse(s);
      arra[i] = n;
    }
   }
   stdout.write("aqui esta la lista, $arra");
  }
```


### Ejecicio 3 Do/While. Almacene en un array el numero n leido del teclado, el tamaño del array es 10.

#### 3.1 Análisis
Se necesita utilizar el simbolo de proceso para asignar el array A[10], despues se utiliza el simboo de entrada para almacenar los elementos en n, DESPUES VOLVEMOS A UTILIZAR EL SIMBOLO DE PROCESO PARA ASIGANAR C=0, POSTERIORMENTE SE VUELVE A UTILIZAR OTRO SIMBOLO DE PROCESO PARA ASIGNAR C AL ARRAY A[C]= N, VOLVEMOS A UTILIZAR OTRO SIMBOLO DE PROCESO PARA ASIGNAR C=C+1, DESPUES UTILIZAMOS UN SIMBOLO DE DECISION PARA PREGUNTAR SI C<=9, EN CASO DE QUE SI SE ASI ENTONCES NOS REGRESAMOS AL SIMBOLO DE PROCESO DONDE A[C]=N, Y ASI SUCESIVAMENTE HASTA QUE C SEA =9 Y FINALMENTE UTILIZAMOS UN SIMBOLO DE SALIDA PARA IMPRIMIR A.

#### 3.2 DIAGRAMA DE FLUJO DE DATOS
[![7.jpg](https://i.postimg.cc/wTw18tyZ/7.jpg)](https://postimg.cc/9rqmyQBY)

#### 3.3 PRUEBA DE ESCRITORIO
|A[10]|N |C=0|A[C]=N|C=C+1 |C<=9|A |
|-----|--|---|------|------|----|--|
|0    |0 |0  |0     |0     |0<=9|[0]|
|1    |1 |1  |1     |1     |1<=9|[0,1]|
|2    |2 |2  |2     |2     |2<=9|[0,1,2]|
|3    |3 |3  |3     |3     |3<=9|[0,1,2,3]|
|4    |4 |4  |4     |4     |4<=9|[0,1,2,3,4]
|5    |5 |5  |5     |5     |5<=9|[0,1,2,3,4,5]|
|6    |6 |6  |6     |6     |6<=9|[0,1,2,3,4,5,6]|
|7    |7 |7  |7     |7     |7<=9|[0,1,2,3,4,5,6,7]|
|8    |8 |8  |8     |8     |8<=9|[0,1,2,3,4,5,6,7,8]|
|9    |9 |9  |9     |9     |9<=9|[0,1,2,3,4,5,6,7,8,9]|

#### 3.4 ENTRADAS
N

#### 3.5 SALIDA
A

### 3.6 PROCESO
A[10]
C=0
A[C]=N
C=C+1

### 3.7 DECISION
C<=9

### 3.8 CODIGO

```dart
import 'dart:io';

  void main() {
  var arra = new List.filled(10, 0);
  stdout.write("Dame diez numeros\n ");
  stdout.write("----------\n");
  int i = 0;
  do {
    String? s = stdin.readLineSync();
    if (s != null) {
      int n = int.parse(s);
      arra[i] = n;
      i++;
    }
   } while (i <= 9);
   stdout.write("Tu lista es $arra ");
   }
```



### Ejecicio 3 While. Almacene en un array el numero n leido del teclado, el tamaño del array es 10.

#### 3.1 Análisis
Se necesita utilizar el simbolo de proceso para asignar el array A[10], despues se utiliza el simboo de entrada para almacenar los elementos en n, DESPUES VOLVEMOS A UTILIZAR EL SIMBOLO DE PROCESO PARA ASIGANAR C=0, DESPUES UTILIZAMOS UN SIMBOLO DE DECISION PARA PREGUNTAR SI C<=9, EN CASO DE QUE SI SE ASI ENTONCES ASIGNAMOS UN  SIMBOLO DE PROCESO DONDE A[C]=N, POSTERIORMENTE SE VUELVE A UTILIZAR OTRO SIMBOLO DE PROCESO PARA ASIGNAR C AL ARRAY A[C]= N, VOLVEMOS A UTILIZAR OTRO SIMBOLO DE PROCESO PARA ASIGNAR A[C]=N, POSTERIORMENTE UTILIZAMOS OTRO SIMBOLO DE PROCESO PRA INGRESAR C=C+1 Y SE REGRESA AL SIMBOLO DE DECISION Y ASI SUSCIVAMENTE HASTA QUE C SEA IGUAL A 9 Y FINALMENTE INGRESAMOS UN SIMBOLO DE SALIDA PARA IMPRIMIR A.

#### 3.2 DIAGRAMA DE FLUJO DE DATOS
[![8.jpg](https://i.postimg.cc/FHxT0XR0/8.jpg)](https://postimg.cc/G4HP1Nvp)

#### 3.3 PRUEBA DE ESCRITORIO
|A[10]|N |C=0|C<=9|A[C]=N |C=C+1|A |
|-----|--|---|------|------|----|--|
|0    |0 |0  |0<=9     |0     |1|[0]|
|1    |1 |1  |1<=9     |1     |2|[0,1]|
|2    |2 |2  |2<=9     |2     |3|[0,1,2]|
|3    |3 |3  |3<=9     |3     |4|[0,1,2,3]|
|4    |4 |4  |4<=9     |4     |5|[0,1,2,3,4]
|5    |5 |5  |5<=9     |5     |6|[0,1,2,3,4,5]|
|6    |6 |6  |6<=9     |6    |7|[0,1,2,3,4,5,6]|
|7    |7 |7  |7<=9     |7     |8|[0,1,2,3,4,5,6,7]|
|8    |8 |8  |8<=9     |8     |9|[0,1,2,3,4,5,6,7,8]|
|9    |9 |9  |9<=9     |9     |10|[0,1,2,3,4,5,6,7,8,9]|

#### 3.4 ENTRADAS
N

#### 3.5 SALIDA
A

### 3.6 PROCESO
A[10]
C=0
A[C]=N
C=C+1

### 3.7 DECISION
C<=9

### 3.8 CODIGO
```dart
import 'dart:io';

//Leer 10 numeros del teclado y ponerlos en una lista.
  void main() {
  var arra = new List.filled(10, 0);
  stdout.write("Dame diez numeros\n ");
  stdout.write("----------\n");
  int i = 0;
  while (i <= 9) {
    String? s = stdin.readLineSync();
    if (s != null) {
      int ner = int.parse(s);
      arra[i] = ner;
    }
    i++;
  }
  stdout.write("Tu lista es, $arra ");
  }
```




### Ejercicio 4 FOR. Almacene lo n numeros leidos del teclado en un vector de 10 elementos.

#### 4.1 Análisis
Se necesita utilizar el simbolo de proceso para asignar el array A[10], despues utilizar el simbolo de ciclo de for para hacer un contador de i=0; i<=9; i=i+1, en caso de que i sea menor a 10 se utiliza el simboo de entrada para almacenar los elementos en n, despues se utiliza otro simbolo de proceso para ingresar A [i]= N, y se regressa al ciclo hasta que i sea mayor a 10 y al final se utiliza un simboo de salida para imprimir A.

#### 4.2 DIAGRAMA DE FLUJO DE DATOS
[![9.jpg](https://i.postimg.cc/TwW246p4/9.jpg)](https://postimg.cc/phRtm3Qf)

#### 4.3 PRUEBA DE ESCRITORIO
|A[10]|i  |i<10 |i+1|A[i]=N|A |
|-----|---|-----|---|------|--|
|0   |0   |0<10 |   |0     |[0] |
|1   |1   |1<10 |1  |1     |[0,1] |
|2   |2   |2<10 |2  |2     |[0,1,2] |
|3   |3   |3<10 |3  |3     |[0,1,2,3]|
|4   |4   |4<10 |4  |4     |[0,1,2,3,4]|
|5   |5   |5<10 |5  |5     |[0,1,2,3,4,5]|
|6   |6   |6<10 |6   |6     |[0,1,2,3,4,5,6]|
|7   |7   |7<10 |7  |7    |[0,1,2,3,4,5,6,7]|
|8   |8   |8<10 |8  |8     |[0,1,2,3,4,5,6,7,8]|
|9   |9   |9<10 |9  |9     |[0,1,2,3,4,5,6,7,8,9]|

#### 4.4 ENTRADAS
N

#### 4.5 SALIDA
A

#### 4.6 CICLO FOR
i=0; i<=9; i++

####  4.7 CODIGO
```dart
void main() {
  var arr = <int>[0, 1, 2, 3, 4, 5, 6, 7, 8, 9,];

  for (var i = 0; i <= 9; i++) {
    arr[i + 1] = i;
  }
  print(arr);
}
```




### Ejecicio 4 Do/While. Almacene lo n numeros leidos del teclado en un vector de 10 elementos.

#### 4.1 Análisis
Se necesita utilizar el simbolo de proceso para asignar el array A[10],  DESPUES SE  UTILIZA EL SIMBOLO DE PROCESO PARA ASIGANAR C=0, despues utilizar el simboo de entrada para almacenar los elementos en n, POSTERIORMENTE SE VUELVE A UTILIZAR OTRO SIMBOLO DE PROCESO PARA ASIGNAR C AL ARRAY A[C]= N, VOLVEMOS A UTILIZAR OTRO SIMBOLO DE PROCESO PARA ASIGNAR C=C+1, DESPUES UTILIZAMOS UN SIMBOLO DE DECISION PARA PREGUNTAR SI C<=9, EN CASO DE QUE SI SE ASI ENTONCES NOS REGRESAMOS AL SIMBOLO DE PROCESO DONDE A[C]=N, Y ASI SUCESIVAMENTE HASTA QUE C SEA =9 Y FINALMENTE UTILIZAMOS UN SIMBOLO DE SALIDA PARA IMPRIMIR A.

#### 4.2 DIAGRAMA DE FLUJO DE DATOS
[![10.jpg](https://i.postimg.cc/63KbDV3x/10.jpg)](https://postimg.cc/JyTQXkZp)

#### 3.3 PRUEBA DE ESCRITORIO
|A[10]|N |C=0|A[C]=N|C=C+1 |C<=9|A |
|-----|--|---|------|------|----|--|
|0    |0 |0  |0     |0     |0<=9|[0]|
|1    |1 |1  |1     |1     |1<=9|[0,1]|
|2    |2 |2  |2     |2     |2<=9|[0,1,2]|
|3    |3 |3  |3     |3     |3<=9|[0,1,2,3]|
|4    |4 |4  |4     |4     |4<=9|[0,1,2,3,4]
|5    |5 |5  |5     |5     |5<=9|[0,1,2,3,4,5]|
|6    |6 |6  |6     |6     |6<=9|[0,1,2,3,4,5,6]|
|7    |7 |7  |7     |7     |7<=9|[0,1,2,3,4,5,6,7]|
|8    |8 |8  |8     |8     |8<=9|[0,1,2,3,4,5,6,7,8]|
|9    |9 |9  |9     |9     |9<=9|[0,1,2,3,4,5,6,7,8,9]|

#### 4.4 ENTRADAS
N

#### 4.5 SALIDA
A

### 4.6 PROCESO
A[10]
C=0
A[C]=N
C=C+1

### 4.7 DECISION
C<=9

### 4.8 CODIGO
```dart
void main() {
  var arr = <int>[0, 1, 2, 3, 4, 5, 6, 7, 8, 9,];
  int c = 0;
  do {
    arr[0 + c] = c;
    c = c + 1;
  } while (c <= 9);
  print(arr);
}//dowhile
```



### Ejecicio 4 While. Almacene lo n numeros leidos del teclado en un vector de 10 elementos.

#### 4.1 Análisis
Se necesita utilizar el simbolo de proceso para asignar el array A[10],  DESPUES VOLVEMOS A UTILIZAR EL SIMBOLO DE PROCESO PARA ASIGANAR C=0, DESPUES UTILIZAMOS UN SIMBOLO DE DECISION PARA PREGUNTAR SI C<=9, EN CASO DE QUE SI SE ASI ENTONCES se utiliza el simboo de entrada para almacenar los elementos en n, despues ASIGNAMOS UN  SIMBOLO DE PROCESO DONDE A[C]=N, POSTERIORMENTE UTILIZAMOS OTRO SIMBOLO DE PROCESO PRA INGRESAR C=C+1 Y SE REGRESA AL SIMBOLO DE DECISION Y ASI SUSCIVAMENTE HASTA QUE C SEA IGUAL A 9 Y FINALMENTE INGRESAMOS UN SIMBOLO DE SALIDA PARA IMPRIMIR A.

#### 4.2 DIAGRAMA DE FLUJO DE DATOS
[![11.jpg](https://i.postimg.cc/ryPC4Cky/11.jpg)](https://postimg.cc/w3Dm8NMn)

#### 4.3 PRUEBA DE ESCRITORIO
|A[10]|N |C=0|C<=9|A[C]=N |C=C+1|A |
|-----|--|---|------|------|----|--|
|0    |0 |0  |0<=9     |0     |1|[0]|
|1    |1 |1  |1<=9     |1     |2|[0,1]|
|2    |2 |2  |2<=9     |2     |3|[0,1,2]|
|3    |3 |3  |3<=9     |3     |4|[0,1,2,3]|
|4    |4 |4  |4<=9     |4     |5|[0,1,2,3,4]
|5    |5 |5  |5<=9     |5     |6|[0,1,2,3,4,5]|
|6    |6 |6  |6<=9     |6    |7|[0,1,2,3,4,5,6]|
|7    |7 |7  |7<=9     |7     |8|[0,1,2,3,4,5,6,7]|
|8    |8 |8  |8<=9     |8     |9|[0,1,2,3,4,5,6,7,8]|
|9    |9 |9  |9<=9     |9     |10|[0,1,2,3,4,5,6,7,8,9]|

#### 4.4 ENTRADAS
N

#### 4.5 SALIDA
A

### 4.6 PROCESO
A[10]
C=0
A[C]=N
C=C+1

### 4.7 DECISION
C<=9

### 4.8 CODIGO
```dart
void main() {
  var arr = <int>[0, 1, 2, 3, 4, 5, 6, 7, 8, 9,];
  int c = 0;
  while (c <= 9) {
    arr[0 + c] = c;
    c = c + 1;
  }
  print(arr);
}
```



### Ejercicio 5 FOR. Almacene un contador negativo en un vector, el conteo es de 10 a 0.

#### 5.1 Análisis
Se necesita utilizar el simbolo de proceso para asignar el array A[11], despues utilizar el simbolo de ciclo de for para hacer un contador de i=10; i>=0; i=i-1, en caso de que i sea mayor o igual a 0, se utiliza el simboo de entrada para almacenar los elementos en n, despues se utiliza otro simbolo de proceso para ingresar A [10-i]= N, y se regressa al ciclo hasta que i sea igual a 0 y al final se utiliza un simboo de salida para imprimir A.

#### 5.2 DIAGRAMA DE FLUJO DE DATOS
[![12.jpg](https://i.postimg.cc/JnJHvgnP/12.jpg)](https://postimg.cc/S2SKzgcM)

#### 5.3 PRUEBA DE ESCRITORIO
|A[11]|i  |i>=0 |N  |A[10-i]=N|i-1|A  |
|-----|---|-----|---|---------|---|---|
|0    |10 |10>=0|10 |A[10-10] |9  |[0]|
|1    |9  |9>=0 |9  |A[10-9]  |8  |[0,1]|
|2    |8  |8>=0 |8  |A[10-8]  |7  |[0,1,2]|
|3    |7  |7>=0 |7  |A[10-7]  |6  |[0,1,2,3]|
|4    |6  |6>=0 |6  |A[10-6]  |5  |[0,1,2,3,4]|
|5    |5  |5>=0 |5  |A[10-5]  |4  |[0,1,2,3,4,5]|
|6    |4  |4>=0 |4  |A[10-4]  |3  |[0,1,2,3,4,5,6]|
|7    |3  |3>=0 |3  |A[10-3]  |2  |[0,1,2,3,4,5,6,7]|
|8    |2  |2>=0 |2  |A[10-2]  |1  |[0,1,2,3,4,5,6,7,8]|
|9    |1  |1>=0 |1  |A[10-1]  |0  |[0,1,2,3,4,5,6,7,8,9]|
|10   |0  |0>=0 |0  |A[10-0]  |-1 |[0,1,2,3,4,5,6,7,8,9,10]|

#### 5.4 ENTRADAS
N

#### 5.5 SALIDA
A

#### 5.6 CICLO FOR
i=10; i>=0; i-1

#### 5.7 PROCESO
A[11]
A[10-i]=N

####  5.8 CODIGO
```dart
//Almacene un contador negativo en un vector, el conteo es de 10 a 0.

  void main33() {
  var arr = <int>[0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10];
  int c = 10;
  for (var i = 10; i >= 0; i--) {
    arr[10 - i] = i;
  }
  print(arr);
 }
```

### Ejercicio 5 DO/WHILE. Almacene un contador negativo en un vector, el conteo es de 10 a 0.


#### 5.1 Análisis
Se necesita utilizar el simbolo de proceso para asignar el array A[11],  DESPUES SE  UTILIZA EL SIMBOLO DE PROCESO PARA ASIGANAR C=10, POSTERIORMENTE SE VUELVE A UTILIZAR OTRO SIMBOLO DE PROCESO PARA ASIGNAR C AL ARRAY A[C]= N, VOLVEMOS A UTILIZAR OTRO SIMBOLO DE PROCESO PARA ASIGNAR C=C-1, DESPUES UTILIZAMOS UN SIMBOLO DE DECISION PARA PREGUNTAR SI C>=0, EN CASO DE QUE SI SE ASI ENTONCES NOS REGRESAMOS AL SIMBOLO DE PROCESO DONDE A[C]=N, Y ASI SUCESIVAMENTE HASTA QUE C SEA =0 Y FINALMENTE UTILIZAMOS UN SIMBOLO DE SALIDA PARA IMPRIMIR A.

#### 5.2 DIAGRAMA DE FLUJO DE DATOS
[![13.jpg](https://i.postimg.cc/sXH3zFf5/13.jpg)](https://postimg.cc/BLFr5VKv)

#### 5.3 PRUEBA DE ESCRITORIO
|A[11]|C  |A[10-C]=A|C=C-1 |C>=0 |A |
|-----|---|---------|------|-----|--|
|0    |10 |A[10-10] |9     |10>=0|[0]|
|1    |9  |A[10-9]  |8     |9>=0 |0,1]|
|2    |8  |A[10-8]  |7     |8>=0 |[0,1,2]|
|3    |7  |A[10-7]  |6     |7>=0 |[0,1,2,3]|
|4    |6  |A[10-6]  |5     |6>=0 |[0,1,2,3,4]
|5    |5  |A[10-5]  |4     |5>=0 |[0,1,2,3,4,5]|
|6    |4  |A[10-4]  |3     |4>=0 |[0,1,2,3,4,5,6]|
|7    |3  |A[10-3]  |2     |3>=0 |[0,1,2,3,4,5,6,7]|
|8    |2  |A[10-2]  |1     |2>=0 |[0,1,2,3,4,5,6,7,8]|
|9    |1  |A[10-1]  |0     |1>=0 |[0,1,2,3,4,5,6,7,8,9]|
|10   |0  |A[10-0]  |      |0>=0 |[0,1,2,3,4,5,6,7,8,9,10]|

#### 5.4 ENTRADAS
NINGUNA

#### 5.5 SALIDA
A

### 5.6 PROCESO
A[11]
C=10
A[C]=A
C=C-1

### 5.7 DECISION
C>=0

### 5.8 CODIGO
```dart
void main() {
  var arr = <int>[0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10];
  int c = 10;
  do {
    arr[10 - c] = c;
    c = c - 1;
  } while (c >= 0);
  print(arr);
  }//dowhile
```




### Ejercicio 5 WHILE. Almacene un contador negativo en un vector, el conteo es de 10 a 0.

#### 5.1 Análisis
Se necesita utilizar el simbolo de proceso para asignar el array A[11],  DESPUES VOLVEMOS A UTILIZAR EL SIMBOLO DE PROCESO PARA ASIGANAR C=10, DESPUES UTILIZAMOS UN SIMBOLO DE DECISION PARA PREGUNTAR SI C>=0, EN CASO DE QUE SI SE ASI ENTONCES ASIGNAMOS UN  SIMBOLO DE PROCESO DONDE A[10-C]=A, POSTERIORMENTE UTILIZAMOS OTRO SIMBOLO DE PROCESO PRA INGRESAR C=C-1 Y SE REGRESA AL SIMBOLO DE DECISION Y ASI SUSCIVAMENTE HASTA QUE C SEA IGUAL A 0 Y FINALMENTE INGRESAMOS UN SIMBOLO DE SALIDA PARA IMPRIMIR A.

#### 5.2 DIAGRAMA DE FLUJO DE DATOS
[![14.jpg](https://i.postimg.cc/ZYM4Wh8Q/14.jpg)](https://postimg.cc/hhTHY638)

#### 5.3 PRUEBA DE ESCRITORIO
|A[11]|C  |C>=0     |A[10-C]=A|C=C-1 |A |  
|-----|---|---------|---------|------|--|
|0    |10 |10>=0    |A[10-10] |9     |[0]|
|1    |9  |9>=0     |A[10-9]  |8     |0,1]|
|2    |8  |8>=0     |A[10-8]  |7     |[0,1,2]|
|3    |7  |7>=0     |A[10-7]  |6     |[0,1,2,3]|
|4    |6  |6>=0     |A[10-6]  |5     |[0,1,2,3,4]|
|5    |5  |5>=0     |A[10-5]  |4     |[0,1,2,3,4,5]
|6    |4  |4>=0     |A[10-4]  |3     |[0,1,2,3,4,5,6]|
|7    |3  |3>=0     |A[10-3]  |2     |[0,1,2,3,4,5,6,7]|
|8    |2  |2>=0     |A[10-2]  |1     |[0,1,2,3,4,5,6,7,8]|
|9    |1  |1>=0     |A[10-1]  |0     |[0,1,2,3,4,5,6,7,8,9]|
|10   |0  |0>=0     |A[10-0]  |1>=0  |[0,1,2,3,4,5,6,7,8,9,10]|

#### 5.4 ENTRADAS
NINGUNA

#### 5.5 SALIDA
A

### 5.6 PROCESO
A[11]
C=10
A[10-C]=A
C=C-1

### 5.7 DECISION
C>=0

### 5.8 CODIGO
```dart
void main() {
  var arr = <int>[0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10];
  int c = 10;
  while (c >= 0) {
    arr[10 - c] = c;
    c = c - 1;
  }
  print(arr);
  }
```



### Ejercicio 6 FOR. ALMACENE EN UN VECTOR DE TAMAÑO 10, TODOS LOS NÚMEROS PARES CAPTURADOS HASTA COMPLETAR TODOS.

#### 6.1 Análisis
Se necesita utilizar el simbolo de proceso para asignar el vector A[10], despues utilizar el simbolo de ciclo de for para hacer un contador de i=0; i<=9; i=i+1, en caso de que i sea mayor o menor a 10, se utiliza el simboo de entrada para almacenar los elementos en n, despues se utiliza un simbolo de decision para preduntar si N%2=0, en caso de que no sea asi se ingresa un simbolo de salida que dise que el numero tiene que ser par y se regresa al simbolo de entrada, en caso de que si sea asi se ingresa un simbolo de proceso para ingresar A [i]= N, y se regressa al ciclo hasta que i sea igual a 9 y al final se utiliza un simboo de salida para imprimir A.

#### 6.2 DIAGRAMA DE FLUJO DE DATOS
[![15.jpg](https://i.postimg.cc/85BQsDyx/15.jpg)](https://postimg.cc/njzwP8f1)

#### 6.3 PRUEBA DE ESCRITORIO
|A[10]|i  |i<=9 |N  |N%2=0  |A[i]=N   |i+1|A  |
|-----|---|-----|---|-------|---------|---|---|
|0    |0  |0<=9 |0  |NO     |         |1  ||
|1    |1  |1<=9 |1  |NO     |         |2  ||
|2    |2  |2<=9 |2  |SI     |A[2]     |3  |[2]|
|3    |3  |3<=9 |3  |NO     |         |4  |[2]|
|4    |4  |4<=9 |4  |SI     |A[4]     |5  |[2,4]|
|5    |5  |5<=9 |5  |NO     |         |6  |[2,4]|
|6    |6  |6<=9 |6  |SI     |A[6]     |7  |[2,4,6]|
|7    |7  |7<=9 |7  |NO     |         |8  |[2,4,6]|
|8    |8  |8<=9 |8  |SI     |A[8]     |9  |[2,4,6,8]|
|9    |9  |9<=9 |9  |NO     |         |10 |[2,4,6,8]|


#### 6.4 ENTRADAS
N

#### 6.5 SALIDA
"TIENE QUE SER PAR"
A

#### 6.6 CICLO FOR
i=0; i<=9; i++

#### 6.7 PROCESO
A[10]
A[i]=N

#### 6.8 DECISION
N%2=0

#### 6.9 CODIGO






### Ejercicio 6 DO/WHILE. ALMACENE EN UN VECTOR DE TAMAÑO 10, TODOS LOS NÚMEROS PARES CAPTURADOS HASTA COMPLETAR TODOS.


#### 6.1 Análisis
Se necesita utilizar el simbolo de proceso para asignar el array A[10],  DESPUES SE  UTILIZA EL SIMBOLO DE PROCESO PARA ASIGANAR C=0, VOLVEMOS A UTILIZAR OTRO SIMBOLO DE PROCESO PARA ASIGNAR C=C+1, DESPUES UTILIZAMOS UN SIMBOLO DE DECISION PARA PREGUNTAR SI C<=9, EN CASO DE QUE SI SEA ASI SE UTILIZA UN SIMBOLO DE ENTRADA PARA ASIGNAR LOS VALORES A N, SE UTILIZA OTRO SIMBOLO DE DECISION PARA PREGUNTAR SU N%2=0, SI EN NO ENTONCES SE UTILIZA UN SIMBOLO DE SALIA QUE IMPRIME "TIENE QUE SER PAR" Y SE REGRESA AL SIMBOLO DE PROCESO PARA PEDIR OTRO NUMERO, EN CASO DE QUE N%2=0 SI SEA ASI, SE UTILIZA OTRO SIMBOLO DE PROCESO PARA ASIGNAR C AL VECTOR A[C]= N, Y SE REGRESA AL SIMBOLO DE PROECESO QUE DICE C=C+1, Y ASI SUCESIVAMENTE HASTA QUE C SEA IGUAL A 9, SI EN EL SIMBOLO DE DECISION DE C<=9 NO SEA ASI SE INGRESA UN SIMBOLO DE SALIDA QUE IMPRIME A.

#### 6.2 DIAGRAMA DE FLUJO DE DATOS
[![16.jpg](https://i.postimg.cc/50JJttVW/16.jpg)](https://postimg.cc/ns3gRpr3)

#### 6.3 PRUEBA DE ESCRITORIO
|A[10]|C  |C=C+1 |C<=9 |N  |N%2=0  |A[C]=N   |A  |
|-----|---|------|-----|---|-------|---------|---|
|0    |0  |      |0<=9 |0  |NO     |         ||
|1    |1  |1     |1<=9 |1  |NO     |         ||
|2    |2  |2     |2<=9 |2  |SI     |A[2]     |[2]|
|3    |3  |3     |3<=9 |3  |NO     |         |[2]|
|4    |4  |4     |4<=9 |4  |SI     |A[4]     |[2,4]|
|5    |5  |5     |5<=9 |5  |NO     |         |[2,4]|
|6    |6  |6     |6<=9 |6  |SI     |A[6]     |[2,4,6]|
|7    |7  |7     |7<=9 |7  |NO     |         |[2,4,6]|
|8    |8  |8     |8<=9 |8  |SI     |A[8]     |[2,4,6,8]|
|9    |9  |9     |9<=9 |9  |NO     |         |[2,4,6,8]|

#### 6.4 ENTRADAS
N

#### 6.5 SALIDA
A
"TIENE QUE SER PAR" 

### 6.6 PROCESO
A[10]
C=0
C=C-1
A[C]=A

### 6.7 DECISION
C<=9
N%2=0

### 6.8 CODIGO







### Ejercicio 6 WHILE. ALMACENE EN UN VECTOR DE TAMAÑO 10, TODOS LOS NÚMEROS PARES CAPTURADOS HASTA COMPLETAR TODOS.


#### 6.1 Análisis
Se necesita utilizar el simbolo de proceso para asignar el array A[10],  DESPUES SE  UTILIZA EL SIMBOLO DE PROCESO PARA ASIGANAR C=0, DESPUES UTILIZAMOS UN SIMBOLO DE DECISION PARA PREGUNTAR SI C<=9, SI ES ASI ENTONCES UTILIZAMOS OTRO SIMBOLO DE PROCESO PARA ASIGNAR C=C+1,DESPUES SE UTILIZA UN SIMBOLO DE ENTRADA PARA ASIGNAR LOS VALORES A N, SE VUELVE A UTILIZAR OTRO SIMBOLO DE DECISION PARA PREGUNTAR SU N%2=0, EN CASO DE QUE NO SEA ASI ENTONCES SE UTILIZA UN SIMBOLO DE SALIA QUE IMPRIME "TIENE QUE SER PAR" Y SE REGRESA AL SIMBOLO DE PROCESO PARA PEDIR OTRO NUMERO, EN CASO DE QUE N%2=0 SI SEA ASI, SE UTILIZA OTRO SIMBOLO DE PROCESO PARA ASIGNAR C AL VECTOR A[C]= N, Y SE REGRESA AL SIMBOLO DE DECISION QUE DICE C<=9, Y ASI SUCESIVAMENTE HASTA QUE C SEA IGUAL A 9, SI EN EL SIMBOLO DE DECISION DE C<=9 NO SEA ASI SE INGRESA UN SIMBOLO DE SALIDA QUE IMPRIME A.

#### 6.2 DIAGRAMA DE FLUJO DE DATOS
[![17.jpg](https://i.postimg.cc/FFL3fj6Q/17.jpg)](https://postimg.cc/nMnCgQZd)

#### 6.3 PRUEBA DE ESCRITORIO
|A[10]|C  |C<=9 |C=C+1 |N  |N%2=0  |A[C]=N   |A  |
|-----|---|-----|------|---|-------|---------|---|
|0    |0  |0<=9 |1     |1  |NO     |         ||
|1    |1  |1<=9 |2     |2  |SI     |A[2]     |[2]|
|2    |2  |2<=9 |3     |3  |NO     |         |[2]|
|3    |3  |3<=9 |4     |4  |SI     |A[4]     |[2]|
|4    |4  |4<=9 |5     |5  |NO     |         |[2,4]|
|5    |5  |5<=9 |6     |6  |SI     |A[6]     |[2,4]|
|6    |6  |6<=9 |7     |7  |NO     |         |[2,4,6]|
|7    |7  |7<=9 |8     |8  |SI     |A[8]     |[2,4,6]|
|8    |8  |8<=9 |9     |9  |NO     |         |[2,4,6,8]|
|9    |9  |9<=9 |10    |10 |SI     |A[10]    |[2,4,6,8,10]|

#### 6.4 ENTRADAS
N

#### 6.5 SALIDA
A
"TIENE QUE SER PAR" 

### 6.6 PROCESO
A[10]
C=0
C=C-1
A[C]=A

### 6.7 DECISION
C<=9
N%2=0

### 6.8 CODIGO







### Ejercicio 7 FOR.OBTEN LA CANTIDAD DE ALUMNOS APROBADOS, LA CALIFICACION ES DE 0-10 EL MAXIMO DE ALUMNOS ES 15.

#### 7.1 Análisis
Se necesita utilizar el simbolo de proceso para asignar el vector A[15], despues utilizar el simbolo de ciclo de for para hacer un contador de i=0; i<15; i=i+1, en caso de que i sea mayor o menor a 15, se utiliza el simboo de entrada para almacenar los elementos en ALUMNO, despues se utiliza un simbolo de decision para preduntar si ALUMNO_CAL>=6, en caso de que no sea asi se ingresa un simbolo de salida que IMPRIME "REPROBADO" y se regresa al simbolo de entrada, en caso de que si sea asi se ingresa un simbolo de proceso para ingresar A [i]= APROBADO, y se regressa al ciclo hasta que i sea igual a 14 y al final se utiliza un simboo de salida para imprimir A.

#### 7.2 DIAGRAMA DE FLUJO DE DATOS
[![18.jpg](https://i.postimg.cc/66VW8qBQ/18.jpg)](https://postimg.cc/7b68cxGv)

#### 7.3 PRUEBA DE ESCRITORIO
|A[15]|i  |i<15 |ALUMNO|ALUMNO_CAL>=6|A[i]=APROBADO|i+1|A  |
|-----|---|-----|------|-------------|-------------|---|---|
|0    |0  |0<15 |0     |NO           |REPROBO      |1  |   |
|1    |1  |1<15 |1     |NO           |REPROBO      |2  |   |
|2    |2  |2<15 |2     |NO           |REPROBO      |3  ||
|3    |3  |3<15 |3     |NO           |REPROBO      |4  ||
|4    |4  |4<15 |4     |NO           |REPROBO      |5  ||
|5    |5  |5<15 |5     |NO           |REPROBO      |6  ||
|08   |6  |6<15 |6     |SI           |A[6]         |7  ||
|06   |7  |7<15 |7     |SI           |A[7]         |8  ||
|07   |8  |8<15 |8     |SI           |A[8]         |9  ||
|08   |9  |9<15 |9     |SI           |A[9]         |10 ||
|09   |10 |10<15|10    |SI           |A[10]        |11 ||
|08   |11 |11<15|11    |SI           |A[11]        |12 ||
|09   |12 |12<15|12    |SI           |A[12]        |13 ||
|10   |13 |13<15|13    |SI           |A[13]        |14 ||
|10   |14 |14<15|14    |SI           |A[14]        |   |[9]|

#### 7.4 ENTRADAS
ALUMNO

#### 7.5 SALIDA
"REPROBO"
A

#### 7.6 CICLO FOR
i=0; i<=14; i++

#### 7.7 PROCESO
A[15]
A[i]=APROBADO

#### 7.8 DECISION
ALUMNO_CAL>=6

#### 7.9 CODIGO
```dart
alumnos = list(range(15))
  p_aprobados = 0
  j = 0

  for i in alumnos: 
    while(True):
        calificacion = int(input("Ingresa la calificación >>"))
        if (calificacion >= 0 and calificacion <= 10):
            break
        else:
            print("Calificación fuera de rango. Intenta de nuevo")
 
    if (calificacion < 6):
     alumnos[i] = "R"
    else:
     p_aprobados = calificacion + p_aprobados
     j = j + 1
     alumnos[i] = "A"

  print("\033[33;1m",alumnos,"\033[39m")
  print("El promedio de calificación de los aprobados es de >>",round(p_aprobados/j,2))
  print("El total de aprobados fueron >> ",j)
  print("El total de reprobados fueron >> ",(len(alumnos)-j))
```


### Ejercicio 7 DO/WHILE .OBTEN LA CANTIDAD DE ALUMNOS APROBADOS, LA CALIFICACION ES DE 0-10 EL MAXIMO DE ALUMNOS ES 15.

#### 7.1 Análisis
Se necesita utilizar el simbolo de proceso para asignar el vector A[15], DESPUES SE  UTILIZA EL SIMBOLO DE PROCESO PARA ASIGANAR C=0, VOLVEMOS A UTILIZAR OTRO SIMBOLO DE PROCESO PARA ASIGNAR C=C+1, DESPUES UTILIZAMOS UN SIMBOLO DE DECISION PARA PREGUNTAR SI C<=14, EN CASO DE QUE SI SEA ASI SE UTILIZA UN SIMBOLO DE ENTRADA PARA ASIGNAR LOS VALORES A ALUMNO, despues se utiliza un simbolo de decision para preduntar si ALUMNO_CAL>=6, en caso de que no sea asi se ingresa un simbolo de salida que IMPRIME "REPROBADO" y se regresa al simbolo de entrada, en caso de que si sea asi se ingresa un simbolo de proceso para ingresar A [i]= APROBADO, y se regressa al SIMBOLO DE PROCESO DE C=C+1 Y ASI SUCECIVAMENTE HASTA QUE C SEA IGUAL A 14 Y FINALMENTE SE IMPRIME A.

#### 7.2 DIAGRAMA DE FLUJO DE DATOS
[![19.jpg](https://i.postimg.cc/0QkhBkJ8/19.jpg)](https://postimg.cc/Z9Qf9hcg)

#### 7.3 PRUEBA DE ESCRITORIO
|A[15]|C  |C<15  |ALUMNO|ALUMNO_CAL>=6|A[C]=APROBADO|C=C+1 |A  |
|-----|---|------|------|-------------|-------------|------|---|
|0    |0  |0<15  |0     |NO           |REPROBO      |1     |   |
|1    |1  |1<15  |1     |NO           |REPROBO      |2     |   |
|2    |2  |2<15  |2     |NO           |REPROBO      |3     |   |
|3    |3  |3<15  |3     |NO           |REPROBO      |4     |   |
|4    |4  |4<15  |4     |NO           |REPROBO      |5     |   |
|5    |5  |5<15  |5     |NO           |REPROBO      |6     |   |
|08   |6  |6<15  |6     |SI           |A[6]         |7     |   |
|06   |7  |7<15  |7     |SI           |A[7]         |8     |   |
|07   |8  |8<15  |8     |SI           |A[8]         |9     |   |
|08   |9  |9<15  |9     |SI           |A[9]         |10    |   |
|09   |10 |10<15 |10    |SI           |A[10]        |11    |   |
|08   |11 |11<15 |11    |SI           |A[11]        |12    |   |
|09   |12 |12<15 |12    |SI           |A[12]        |13    |   |
|10   |13 |13<15 |13    |SI           |A[13]        |14    |   |
|10   |14 |14<15 |14    |SI           |A[14]        |      |[9]   |

#### 7.4 ENTRADAS
ALUMNO

#### 7.5 SALIDA
"REPROBO"
A

#### 7.6 PROCESO
A[15]
A[i]=APROBADO
C=0
C=C+1

#### 7.7 DECISION
ALUMNO_CAL>=6
C<=14

#### 7.8 CODIGO
```dart
Calificaciones=int(input("Ingrese la cantidad de calificaciones"))
    vec=[]
    n=0

   cont = 0
   while(True):
    calificacion=int(input("Calificacion: "))
    n=n+calificacion
    vec.append(calificacion)
    cont += 1
    if(cont>=Calificaciones):
        break;
        
   aprobado=0

   promedioAprobados = 0
   for h in vec:
    if h>=5:
        aprobado=aprobado+1
        promedioAprobados = promedioAprobados + h

   promedioAprobados = promedioAprobados / aprobado

  reprobado=0
    for k in vec:
    if k<=5:
        reprobado=reprobado+1

   print("Cantidad de aprobados:", aprobado)
   print("Cantidad de reprobados:", reprobado)
    print("Promedio de aprobados:", promedioAprobados)
```




### Ejercicio 7 WHILE .OBTEN LA CANTIDAD DE ALUMNOS APROBADOS, LA CALIFICACION ES DE 0-10 EL MAXIMO DE ALUMNOS ES 15.

#### 7.1 Análisis
Se necesita utilizar el simbolo de proceso para asignar el vector A[15], DESPUES SE  UTILIZA EL SIMBOLO DE PROCESO PARA ASIGANAR C=0, VOLVEMOS A UTILIZAR OTRO SIMBOLO DE PROCESO PARA ASIGNAR C=C+1, ### Ejercicio 7 DO/WHILE .OBTEN LA CANTIDAD DE ALUMNOS APROBADOS, LA CALIFICACION ES DE 0-10 EL MAXIMO DE ALUMNOS ES 15.

#### 7.1 Análisis
Se necesita utilizar el simbolo de proceso para asignar el vector A[15], DESPUES SE  UTILIZA EL SIMBOLO DE PROCESO PARA ASIGANAR C=0, DESPUES UTILIZAMOS UN SIMBOLO DE DECISION PARA PREGUNTAR SI C<15, EN CASO DE QUE SI SEA ASI SE UTILIZA UN SIMBOLO DE ENTRADA PARA ASIGNAR LOS VALORES A ALUMNO,VOLVEMOS A UTILIZAR OTRO SIMBOLO DE PROCESO PARA ASIGNAR C=C+1, despues se utiliza un simbolo de decision para preduntar si ALUMNO_CAL>=6, en caso de que no sea asi se ingresa un simbolo de salida que IMPRIME "REPROBADO" y se regresa al simbolo de entrada, en caso de que si sea asi se ingresa un simbolo de proceso para ingresar A [i]= APROBADO, y se regressa al SIMBOLO DE DECISION DE C<15 Y ASI SUCECIVAMENTE HASTA QUE C SEA IGUAL A 14 Y FINALMENTE SE IMPRIME A.

#### 7.2 DIAGRAMA DE FLUJO DE DATOS
[![20.jpg](https://i.postimg.cc/2SxH5TF0/20.jpg)](https://postimg.cc/0zbGWY4S)

#### 7.3 PRUEBA DE ESCRITORIO
|A[15]|C  |C<15  |ALUMNO|ALUMNO_CAL>=6|A[C]=APROBADO|C=C+1 |A  |
|-----|---|------|------|-------------|-------------|------|---|
|0    |0  |0<15  |0     |NO           |REPROBO      |1     |   |
|1    |1  |1<15  |1     |NO           |REPROBO      |2     |   |
|2    |2  |2<15  |2     |NO           |REPROBO      |3     |   |
|3    |3  |3<15  |3     |NO           |REPROBO      |4     |   |
|4    |4  |4<15  |4     |NO           |REPROBO      |5     |   |
|5    |5  |5<15  |5     |NO           |REPROBO      |6     |   |
|08   |6  |6<15  |6     |SI           |A[6]         |7     |   |
|06   |7  |7<15  |7     |SI           |A[7]         |8     |   |
|07   |8  |8<15  |8     |SI           |A[8]         |9     |   |
|08   |9  |9<15  |9     |SI           |A[9]         |10    |   |
|09   |10 |10<15 |10    |SI           |A[10]        |11    |   |
|08   |11 |11<15 |11    |SI           |A[11]        |12    |   |
|09   |12 |12<15 |12    |SI           |A[12]        |13    |   |
|10   |13 |13<15 |13    |SI           |A[13]        |14    |   |
|10   |14 |14<15 |14    |SI           |A[14]        |      |[9]   |

#### 7.4 ENTRADAS
ALUMNO

#### 7.5 SALIDA
"REPROBO"
A

#### 7.6 PROCESO
A[15]
A[i]=APROBADO
C=0
C=C+1

#### 7.7 DECISION
ALUMNO_CAL>=6
C<=14

#### 7.8 CODIGO
```dart
Calificaciones=int(input("Ingrese la cantidad de calificaciones"))
  vec=[]
  n=0

  cont = 0
 while(cont < Calificaciones):
    calificacion=int(input("Calificacion: "))
    n=n+calificacion
    vec.append(calificacion)
    cont += 1
        
aprobado=0

promedioAprobados = 0
for h in vec:
    if h>=5:
        aprobado=aprobado+1
        promedioAprobados = promedioAprobados + h

promedioAprobados = promedioAprobados / aprobado

reprobado=0
for k in vec:
    if k<=5:
        reprobado=reprobado+1

print("Cantidad de aprobados:", aprobado)
print("Cantidad de reprobados:", reprobado)
print("Promedio de aprobados:", promedioAprobados)
```


### Ejercicio 8 FOR. CAPTURE N NUMEROS  EN EL RANGO [LI,LS] DEONDE:  LI= LIMITE INFERIOR Y LS= LIMITE SUPERIOR, PARA LS<LS Y LI>0.
OBTENGA: 
*CANTIDAD DE NUMEOS PARES Y SU PROMEDIO.
*CANTIDAD DE NUMEROS IMPARES Y SU PROMEDIO.
*¿QUE PROMEDIO ES MAYOR?

#### 8.1 Análisis
SE NECESITA UTILIZAR UN SIMBOLO DE PROCESO PARA INGRESAR SP=0, SI=0, CP=0, CI=0, PP=0, PI=0, DESPUES SE UTLIZA UN SIMBOLO DE SALIDA PARA PEDIR EL LIMITE INFERIOR, DESPUES SE UTILIZA UN SIMBOLO DE ENTRADA PARA INGRESAR EL LI, DESPUES SE UTLIZA UN SIMBOLO DE DECISION PARA PREGUNTAR SI LI>0, EN CASO DE QUE NO SEA ASI SE UTILIZA UN SIMBOLO DE SALIDA PARA IMPRIMIR QUE EL LS TIENE QUE SER MAYO A 0 Y SE REGRESA AL SIMBOLO DE SALIDA PARA PEDIR OTRO LI, EN CASO DE QUE SI SEA ASI ENTONCES SE UTILZA UN SIMBOLO DE SALIDA PARA PEDIR EL LIMITE SUPERIOR, DESPUES SE UTILIZA UN SIMBOLO DE ENTRADA PARA INGRESAR EL LS, DESPUES SE VUELVE A UTILZAR UN SIMBOLO DE DECISION PARA PREGUNTAR SI LS>LI, EN CASO DE QUE NO SEA ASI SE UTILIZA UN SIMBOLO DE SALIDA PARA IMPRIMIR QUE EL LS TIENE QUE SER MAYOR A LI Y SER REGRESA AL SIMBOLO DE SALIDA PARAA PEDIR OTRO LS, EN CASO DE QUE LS SI SEA MAYOR A LI ENTONCES SE UTILIZA UN SIMBOLO DE SALIDA PARA PREGUNAR CUANTOS NUMEROS INGRESARA, DESPUES SE UTILIZA UN SIMBOLO DE ENTRADA PARA INGRESAR LA CANTIDAD DE NUMEROROS EN N, DESPUES SE UTILIZA UN SIMBOLO DE DECISION PARA PREGUNTAR SI N>0, EN CASO DE QUE NO SEA ASI ENTONCES SE UTILIZA OTRO SIMBOLO DE SALIDA QUE DICE QUE EL N TIENE QUE SER MAYOR A 0 Y SE REGRESA AL SIMBOLO DE SALIDA PARA PEDIR OTRA CANTIDAD DE NUMEROS, EN CASO DE QUE N SI SEA MAYOR A 0 ENTONCES SE UTILIZA UN SIMBOLO DE CICLO DONDE i=0; i>=N; i++, DESPUES SE UTILIZA UN SIMBOLO DE SALIDA PARA PEDIR UN NUMERO DE N, Y ESE NUMERO SE INGRESA EN UN SIMBOLO DE ENTRADA COMO NUM, POSTERIORMENTE SE UTILIZA UN SIMBOLO DE DECISION PARA PREGUNTAR SI NUM>=LI, AND, NUM<=LS, EN CASO DE QUE NO SEA ASI SE UTILIZA UN SIMBOLO DE SALIDA PARA IMPRIMIR QUE EL NUM TIENE QUE ESTAR ENTRE EL LI Y EL LS, PERO SI SI ES ASI SE UTILIZA OTRO SIMBOLO DE DECISION PARA DECIR SI NUM%2=0 SI LA RESPUETA ES NO ENTONCES SE UTILIZA UN SIMBOLO DE PROCESO PARA DECIR QUE S=SI+NUM, DESPUES SE UTILIZA OTRO SIMBOLO DE PROCESO PARA DECIR QUE CI=CI+1, EN CASO DE QUE LA RESPUESTA SEA SI SE UTILIZA UN SIMBOLO DE PROCESO PARA DECIR QUE SP=SP+NUM, DESPUES UTILIZAMOS OTRO SIMBOLO DE ROCESO PARA DECIR QUE CP=CP+1, DESPUES NOS REGRESAMOS AL CICLO FOR, Y ASI SUCESIVAMENTE HASTA QUE i SEA IGUAL A N, DESPUES SE UTILIZA UN CIMBOLO DE PROCESO PARA INGRESAR EL CP, CI, DESPUES UTILIZAMOS OTRO SIMBOLO DE PROCESO PARA DECIR QUE EL PP=SP/CP Y EL PI=SI/CI, DESPUES EL PP Y EL PI LO INGRESAMOS EN UN SIMBOLO DE ENTRADA, DESPUES UTILIZAMOS UN SIMBOLO DE DECISION PARA PREGUNTAR SI PP>PI, EN CASO DE QUE NO SEA ASI SE UTILIZA UN SIMBOLO DE SALIDA QUE IMPRIME QUE EL PI ES MAYOR A PP, PERO SI LA RESPUESTA ES SI ENTONCES SE UTILIZA UN SIMBOLO DE SALIDA QUE IMPRIME QUE EL PP ES MAYOR A PI.

#### 8.2 DIAGRAMA DE FLUJO DE DATOS
[![21.jpg](https://i.postimg.cc/dVs0szfL/21.jpg)](https://postimg.cc/RNYmGb4B)

#### 8.3 PRUEBA DE ESCRITORIO
|SP |CP |PP |SI |CI |PI |LI |LI>0|LS |LS>LI|N  |N>0|i=1|i<=N|NUM|NUM>=LI, NUM<=LS|NUM%2=0|SP=SP+NUM|CP=CP+1|SI=SI+NUM|CI=CI+1|i++|PP=SP/CP|PI=SI/CI|PP>PI|
|---|---|---|---|---|---|---|----|---|-----|---|---|---|----|---|----------------|-------|---------|-------|---------|-------|---|--------|--------|-----|
|0  |0  |0  |0  |0  |0  |5  |SI  |99 |SI   |4  |SI |1  |1<=4|6  |6>=5, 6<=99     |SI     |6        |1      |0        |0      |2  |        |        |     |
|6  |1  |0  |0  |0  |   |   |    |   |     |   |   |2  |2<=4|87 |87>=5, 87<=99   |NO     |6        |1      |87       |1      |3  |        |        |     |
|6  |1  |0  |87 |1  |0  |   |    |   |     |   |   |3  |3<=4|98 |98>=5, 98<=99   |SI     |104      |2      |87       |1      |4  |        |        |     |
|104|2  |0  |87 |1  |0  |   |    |   |     |   |   |4  |4<=4|77 |77>=5, 77<=99   |NO     |104      |2      |164      |2      |4  |104/2   |164/2   |52>81|

#### 8.4 ENTRADAS
LI
LS
N
NUM
PP
PI

#### 8.5 SALIDA
"LIMITE INFERIOR"
"LIMITE SUPERIOR"
"EL PP ES MAYOR A PI"
"EL PI ES MAYOR AL PP"

#### 8.6 CICLO FOR
i=1; i<=N; i++

#### 8.7 PROCESO
CP=0
SP=0
CI=0
SI=0
PP=0
PI=0
SP=SP+NUM
SI=SI+NUM
CP=CP+1
CI=CI+1
PP=SP/CP
PI=SI/CI

#### 8.8 DECISION
LI>0
LS>LI
N>0
NUM>=LI
NUM<=LS
NUM%2=0
PP>PI

#### 8.9 CODIGO
```dart
sp=0
cp=0
pp=0
si=0
ci=0
pi=0
li=-1
ls=-1
n=-1
num=-1

while(li<0):
    li = int(input("Limite inferior: "))
    
    if(li<0):
        print("Tiene que ser mayor a 0")
        
while(ls<li):
    ls = int(input("Limite superior: "))
    
    if(ls<li):
        print("Tiene que ser mayor que el limite inferior")
        
while(n<0):
    n = int(input("¿Cuantos numeros? "))
    
    if(n<0):
        print("Tiene que ser mayor a 0")
    
for i in range(n): 
    while(num<=li or num>=ls):
        num = int(input("Dame un numero de LI y LS: "))
        
        if(num<=li or num>=ls):
            print("Tiene que estar dentro del LI al LS")

    if(num%2==0):
        sp=sp+num
        cp=cp+1
    else:
        si=si+num
        ci=ci+1
        
    num=-1       
         
if(sp==0 or cp==0):
    pp=0
else:
    pp=sp/cp
    
if(si==0 or ci==0):
    pi=0
else:
    pi=si/ci
    
if(pp>pi):
    print("El PP es mayor que el PI")
else:
    print("El PI es mayor que el PP")
```





### Ejercicio 8 DO/WHILE. CAPTURE N NUMEROS  EN EL RANGO [LI,LS] DEONDE:  LI= LIMITE INFERIOR Y LS= LIMITE SUPERIOR, PARA LS<LS Y LI>0.
OBTENGA: 
*CANTIDAD DE NUMEOS PARES Y SU PROMEDIO.
*CANTIDAD DE NUMEROS IMPARES Y SU PROMEDIO.
*¿QUE PROMEDIO ES MAYOR?

#### 8.1 Análisis
SE NECESITA UTILIZAR UN SIMBOLO DE PROCESO PARA INGRESAR C=0, SP=0, SI=0, CP=0, CI=0, PP=0, PI=0, DESPUES SE UTLIZA UN SIMBOLO DE SALIDA PARA PEDIR EL LIMITE INFERIOR, DESPUES SE UTILIZA UN SIMBOLO DE ENTRADA PARA INGRESAR EL LI, DESPUES SE UTLIZA UN SIMBOLO DE DECISION PARA PREGUNTAR SI LI>0, EN CASO DE QUE NO SEA ASI SE UTILIZA UN SIMBOLO DE SALIDA PARA IMPRIMIR QUE EL LS TIENE QUE SER MAYO A 0 Y SE REGRESA AL SIMBOLO DE SALIDA PARA PEDIR OTRO LI, EN CASO DE QUE SI SEA ASI ENTONCES SE UTILZA UN SIMBOLO DE SALIDA PARA PEDIR EL LIMITE SUPERIOR, DESPUES SE UTILIZA UN SIMBOLO DE ENTRADA PARA INGRESAR EL LS, DESPUES SE VUELVE A UTILZAR UN SIMBOLO DE DECISION PARA PREGUNTAR SI LS>LI, EN CASO DE QUE NO SEA ASI SE UTILIZA UN SIMBOLO DE SALIDA PARA IMPRIMIR QUE EL LS TIENE QUE SER MAYOR A LI Y SER REGRESA AL SIMBOLO DE SALIDA PARAA PEDIR OTRO LS, EN CASO DE QUE LS SI SEA MAYOR A LI ENTONCES SE UTILIZA UN SIMBOLO DE SALIDA PARA PREGUNAR CUANTOS NUMEROS INGRESARA, DESPUES SE UTILIZA UN SIMBOLO DE ENTRADA PARA INGRESAR LA CANTIDAD DE NUMEROROS EN N, DESPUES SE UTILIZA UN SIMBOLO DE DECISION PARA PREGUNTAR SI N>0, EN CASO DE QUE NO SEA ASI ENTONCES SE UTILIZA OTRO SIMBOLO DE SALIDA QUE DICE QUE EL N TIENE QUE SER MAYOR A 0 Y SE REGRESA AL SIMBOLO DE SALIDA PARA PEDIR OTRA CANTIDAD DE NUMEROS, EN CASO DE QUE N SI SEA MAYOR A 0 ENTONCES SE UTILIZA UN SIMBOLO DE PROCESO PARA DECIR QUE C=C+1, DESPUES SE UTILIZA UN SIMBOLO DE SALIDA PARA PEDIR UN NUMERO DE N, Y ESE NUMERO SE INGRESA EN UN SIMBOLO DE ENTRADA COMO NUM, POSTERIORMENTE SE UTILIZA UN SIMBOLO DE DECISION PARA PREGUNTAR SI NUM>=LI, AND, NUM<=LS, EN CASO DE QUE NO SEA ASI SE UTILIZA UN SIMBOLO DE SALIDA PARA IMPRIMIR QUE EL NUM TIENE QUE ESTAR ENTRE EL LI Y EL LS, PERO SI SI ES ASI SE UTILIZA OTRO SIMBOLO DE DECISION PARA DECIR SI NUM%2=0 SI LA RESPUETA ES NO ENTONCES SE UTILIZA UN SIMBOLO DE PROCESO PARA DECIR QUE S=SI+NUM, DESPUES SE UTILIZA OTRO SIMBOLO DE PROCESO PARA DECIR QUE CI=CI+1, EN CASO DE QUE LA RESPUESTA SEA SI SE UTILIZA UN SIMBOLO DE PROCESO PARA DECIR QUE SP=SP+NUM, DESPUES UTILIZAMOS OTRO SIMBOLO DE ROCESO PARA DECIR QUE CP=CP+1, DESPUES NOS REGRESAMOS AL SMBOLO DE PROCESO DE C=C+1, Y ASI SUCESIVAMENTE HASTA QUE C SEA IGUAL A N, DESPUES SE UTILIZA UN SIMBOLO DE PROCESO PARA INGRESAR EL CP, CI, DESPUES UTILIZAMOS OTRO SIMBOLO DE PROCESO PARA DECIR QUE EL PP=SP/CP Y EL PI=SI/CI, DESPUES EL PP Y EL PI LO INGRESAMOS EN UN SIMBOLO DE ENTRADA, DESPUES UTILIZAMOS UN SIMBOLO DE DECISION PARA PREGUNTAR SI PP>PI, EN CASO DE QUE NO SEA ASI SE UTILIZA UN SIMBOLO DE SALIDA QUE IMPRIME QUE EL PI ES MAYOR A PP, PERO SI LA RESPUESTA ES SI ENTONCES SE UTILIZA UN SIMBOLO DE SALIDA QUE IMPRIME QUE EL PP ES MAYOR A PI.

#### 8.2 DIAGRAMA DE FLUJO DE DATOS
[![22.jpg](https://i.postimg.cc/rF3KJhZm/22.jpg)](https://postimg.cc/8jdpkbSQ)

#### 8.3 PRUEBA DE ESCRITORIO
|C  |SP |CP |PP |SI |CI |PI |LI |LI>0|LS |LS>LI|N  |N>0|C+1|C<=N|NUM|NUM>=LI, NUM<=LS|NUM%2=0|SP=SP+NUM|CP=CP+1|SI=SI+NUM|CI=CI+1|PP=SP/CP|PI=SI/CI|PP>PI|
|---|---|---|---|---|---|---|---|----|---|-----|---|---|---|----|---|----------------|-------|---------|-------|---------|-------|--------|--------|-----|
|0  |0  |0  |0  |0  |0  |0  |5  |SI  |99 |SI   |4  |SI |1  |1<=4|6  |6>=5, 6<=99     |SI     |6        |1      |0        |0      |        |        |     |
|1  |6  |1  |0  |0  |0  |   |   |    |   |     |   |   |2  |2<=4|87 |87>=5, 87<=99   |NO     |6        |1      |87       |1      |        |        |     |
|2  |6  |1  |0  |87 |1  |0  |   |    |   |     |   |   |3  |3<=4|98 |98>=5, 98<=99   |SI     |104      |2      |87       |1      |        |        |     |
|3  |104|2  |0  |87 |1  |0  |   |    |   |     |   |   |4  |4<=4|77 |77>=5, 77<=99   |NO     |104      |2      |164      |2      |104/2   |164/2   |52>81|

#### 8.4 ENTRADAS
LI
LS
N
NUM
PP
PI

#### 8.5 SALIDA
"LIMITE INFERIOR"
"LIMITE SUPERIOR"
"EL PP ES MAYOR A PI"
"EL PI ES MAYOR AL PP"

#### 8.6 PROCESO
C=0
CP=0
SP=0
CI=0
SI=0
PP=0
C=C+1
PI=0
SP=SP+NUM
SI=SI+NUM
CP=CP+1
CI=CI+1
PP=SP/CP
PI=SI/CI

#### 8.7 DECISION
LI>0
LS>LI
N>0
NUM>=LI
NUM<=LS
NUM%2=0
PP>PI

#### 8.8 CODIGO
```dart
# Capture n números en el rango [Li,Ls] donde: 
# -Li = Limite inferior
# -Ls limite superior para li<ls y li>0
#                  Obtenga:
# - Cantidad de números pares y su promedio
# - Cantidad de números impares y su promedio
# - ¿Qué promedio es mayor?

print("Dame Límite inferior: ")
Li = int(input())
while Li<0:
    print("El límite inferior debe ser mayor a 0")
    print("Dame Límite inferior: ")
    Li = int(input())

print("Dame límite superior: ")
Ls = int(input())
while Ls<=Li:
    print("El límite superior no puede ser menor o igual al limite inferior")
    print("Dame límite superior: ")
    Ls = int(input())

pares = 0
impares = 0

lista=[]
for x in range(10):
    valor=int(input("Ingrese un valor entero: "))
    lista.append(valor)
print(lista)

for a in lista:
    if a % 2 == 0:
        pares = pares + a
    else:
        impares = impares + a
print("La suma de los números pares es: ",pares)
print("La suma de los números impares es: ",impares)

prom_pares = pares / a
prom_impares = impares / a

print("El promedio de los números pares es: ",prom_pares)
print("El promedio de los números impares es: ",prom_impares)
```






### Ejercicio 8 WHILE. CAPTURE N NUMEROS  EN EL RANGO [LI,LS] DEONDE:  LI= LIMITE INFERIOR Y LS= LIMITE SUPERIOR, PARA LS<LS Y LI>0.
OBTENGA: 
*CANTIDAD DE NUMEOS PARES Y SU PROMEDIO.
*CANTIDAD DE NUMEROS IMPARES Y SU PROMEDIO.
*¿QUE PROMEDIO ES MAYOR?

#### 8.1 Análisis
SE NECESITA UTILIZAR UN SIMBOLO DE PROCESO PARA INGRESAR C=0, SP=0, SI=0, CP=0, CI=0, PP=0, PI=0, DESPUES SE UTLIZA UN SIMBOLO DE SALIDA PARA PEDIR EL LIMITE INFERIOR, DESPUES SE UTILIZA UN SIMBOLO DE ENTRADA PARA INGRESAR EL LI, DESPUES SE UTLIZA UN SIMBOLO DE DECISION PARA PREGUNTAR SI LI>0, EN CASO DE QUE NO SEA ASI SE UTILIZA UN SIMBOLO DE SALIDA PARA IMPRIMIR QUE EL LS TIENE QUE SER MAYO A 0 Y SE REGRESA AL SIMBOLO DE SALIDA PARA PEDIR OTRO LI, EN CASO DE QUE SI SEA ASI ENTONCES SE UTILZA UN SIMBOLO DE SALIDA PARA PEDIR EL LIMITE SUPERIOR, DESPUES SE UTILIZA UN SIMBOLO DE ENTRADA PARA INGRESAR EL LS, DESPUES SE VUELVE A UTILZAR UN SIMBOLO DE DECISION PARA PREGUNTAR SI LS>LI, EN CASO DE QUE NO SEA ASI SE UTILIZA UN SIMBOLO DE SALIDA PARA IMPRIMIR QUE EL LS TIENE QUE SER MAYOR A LI Y SER REGRESA AL SIMBOLO DE SALIDA PARAA PEDIR OTRO LS, EN CASO DE QUE LS SI SEA MAYOR A LI ENTONCES SE UTILIZA UN SIMBOLO DE SALIDA PARA PREGUNAR CUANTOS NUMEROS INGRESARA, DESPUES SE UTILIZA UN SIMBOLO DE ENTRADA PARA INGRESAR LA CANTIDAD DE NUMEROROS EN N, DESPUES SE UTILIZA UN SIMBOLO DE DECISION PARA PREGUNTAR SI N>0, EN CASO DE QUE NO SEA ASI ENTONCES SE UTILIZA OTRO SIMBOLO DE SALIDA QUE DICE QUE EL N TIENE QUE SER MAYOR A 0 Y SE REGRESA AL SIMBOLO DE SALIDA PARA PEDIR OTRA CANTIDAD DE NUMEROS, EN CASO DE QUE N SI SEA MAYOR A 0 ENTONCES SE UTILIZA UN SIMBOLO DE PROCESO PARA DECIR QUE C=C+1, DESPUES SE UTILIZA UN SIMBOLO DE SALIDA PARA PEDIR UN NUMERO DE N, Y ESE NUMERO SE INGRESA EN UN SIMBOLO DE ENTRADA COMO NUM, POSTERIORMENTE SE UTILIZA UN SIMBOLO DE DECISION PARA PREGUNTAR SI NUM>=LI, AND, NUM<=LS, EN CASO DE QUE NO SEA ASI SE UTILIZA UN SIMBOLO DE SALIDA PARA IMPRIMIR QUE EL NUM TIENE QUE ESTAR ENTRE EL LI Y EL LS, PERO SI SI ES ASI SE UTILIZA OTRO SIMBOLO DE DECISION PARA DECIR SI NUM%2=0 SI LA RESPUETA ES NO ENTONCES SE UTILIZA UN SIMBOLO DE PROCESO PARA DECIR QUE S=SI+NUM, DESPUES SE UTILIZA OTRO SIMBOLO DE PROCESO PARA DECIR QUE CI=CI+1, EN CASO DE QUE LA RESPUESTA SEA SI SE UTILIZA UN SIMBOLO DE PROCESO PARA DECIR QUE SP=SP+NUM, DESPUES UTILIZAMOS OTRO SIMBOLO DE ROCESO PARA DECIR QUE CP=CP+1, DESPUES NOS REGRESAMOS AL SMBOLO DE PROCESO DE C=C+1, Y ASI SUCESIVAMENTE HASTA QUE C SEA IGUAL A N, DESPUES SE UTILIZA UN SIMBOLO DE PROCESO PARA INGRESAR EL CP, CI, DESPUES UTILIZAMOS OTRO SIMBOLO DE PROCESO PARA DECIR QUE EL PP=SP/CP Y EL PI=SI/CI, DESPUES EL PP Y EL PI LO INGRESAMOS EN UN SIMBOLO DE ENTRADA, DESPUES UTILIZAMOS UN SIMBOLO DE DECISION PARA PREGUNTAR SI PP>PI, EN CASO DE QUE NO SEA ASI SE UTILIZA UN SIMBOLO DE SALIDA QUE IMPRIME QUE EL PI ES MAYOR A PP, PERO SI LA RESPUESTA ES SI ENTONCES SE UTILIZA UN SIMBOLO DE SALIDA QUE IMPRIME QUE EL PP ES MAYOR A PI.

#### 8.2 DIAGRAMA DE FLUJO DE DATOS
[![23.jpg](https://i.postimg.cc/yNzkXd6x/23.jpg)](https://postimg.cc/fVBzMM9Q)

#### 8.3 PRUEBA DE ESCRITORIO
|C  |SP |CP |PP |SI |CI |PI |LI |LI>0|LS |LS>LI|N  |N>0|C+1|C<=N|NUM|NUM>=LI, NUM<=LS|NUM%2=0|SP=SP+NUM|CP=CP+1|SI=SI+NUM|CI=CI+1|PP=SP/CP|PI=SI/CI|PP>PI|
|---|---|---|---|---|---|---|---|----|---|-----|---|---|---|----|---|----------------|-------|---------|-------|---------|-------|--------|--------|-----|
|0  |0  |0  |0  |0  |0  |0  |5  |SI  |99 |SI   |4  |SI |1  |1<=4|6  |6>=5, 6<=99     |SI     |6        |1      |0        |0      |        |        |     |
|1  |6  |1  |0  |0  |0  |   |   |    |   |     |   |   |2  |2<=4|87 |87>=5, 87<=99   |NO     |6        |1      |87       |1      |        |        |     |
|2  |6  |1  |0  |87 |1  |0  |   |    |   |     |   |   |3  |3<=4|98 |98>=5, 98<=99   |SI     |104      |2      |87       |1      |        |        |     |
|3  |104|2  |0  |87 |1  |0  |   |    |   |     |   |   |4  |4<=4|77 |77>=5, 77<=99   |NO     |104      |2      |164      |2      |104/2   |164/2   |52>81|

#### 8.4 ENTRADAS
LI
LS
N
NUM
PP
PI

#### 8.5 SALIDA
"LIMITE INFERIOR"
"LIMITE SUPERIOR"
"EL PP ES MAYOR A PI"
"EL PI ES MAYOR AL PP"

#### 8.6 PROCESO
C=0
CP=0
SP=0
CI=0
SI=0
PP=0
C=C+1
PI=0
SP=SP+NUM
SI=SI+NUM
CP=CP+1
CI=CI+1
PP=SP/CP
PI=SI/CI

#### 8.7 DECISION
LI>0
LS>LI
N>0
NUM>=LI
NUM<=LS
NUM%2=0
PP>PI

#### 8.8 CODIGO
```dart
# Capture n números en el rango [Li,Ls] donde: 
# -Li = Limite inferior
# -Ls limite superior para li<ls y li>0
#                  Obtenga:
# - Cantidad de números pares y su promedio
# - Cantidad de números impares y su promedio
# - ¿Qué promedio es mayor?

print("Dame Límite inferior: ")
Li = int(input())
while Li<0:
    print("El límite inferior debe ser mayor a 0")
    print("Dame Límite inferior: ")
    Li = int(input())

print("Dame límite superior: ")
Ls = int(input())
while Ls<=Li:
    print("El límite superior no puede ser menor o igual al limite inferior")
    print("Dame límite superior: ")
    Ls = int(input())

pares = 0
impares = 0

lista=[]
for x in range(10):
    valor=int(input("Ingrese un valor entero: "))
    lista.append(valor)
print(lista)

for a in lista:
    if a % 2 == 0:
        pares = pares + a
    else:
        impares = impares + a
print("La suma de los números pares es: ",pares)
print("La suma de los números impares es: ",impares)

prom_pares = pares / a
prom_impares = impares / a

print("El promedio de los números pares es: ",prom_pares)
print("El promedio de los números impares es: ",prom_impares)
```





### Ejercicio 9 FOR. OBTEN LA FRECUENCIA DE N CALIFICACIONES ENTRE [1,10], INDIQUE LA CANTIDAD DE REPROBADOS Y LA CANTIDAD DE APROBADOS, EL PROMEDIO DE APROBADOS Y PROMEDIO GENERAL.

#### 9.1 Análisis
SE NECESITA UTILIZAR UN SIMBOLO DE PROCESO PARA INDICAR QUE EL VECTOR SERA CALIFICAIONES [1,10], DESPUES SE UTILIZA UN SIMBOLO DE SALIDA PARA PREGUNTAR CUANTAS CALIICAIONES, DESPUES SE UTILIZA UN SIMBOLO DE ENTARADA PARA INGRESAR LAS CANTIDADES EN LA VARIABLE N, DESPUES SE UTILIZA UN SIMBOLO DE DECISION PARA PREGUNTAR SI N>0, SI NO ES MAYOR SE UTILIZA UN SMBOLO DE SALIDA QUE DICE QUE TIENE QUE SER MAYOR A 0, Y SI SI ES MAYOR SE UTILIZA UN SIMBOLO DE CICLO DE FOR QUE DICE i=0; i<=N; i++; DESPUES SE UTILIZA UN SIMBOLO DE PROCESO QUE DIE QUE CALIFICACION [1,10], DESPUES EL VALOR SE ALMACENA EN C EN UN SIMBOLO DE ENTRADA, DESPUES SE UTILIZA UN SIMBOLO DE DECISION QUE PREGUNTA SI C>, AND C<=10, SI NO ES ASI ENTONCES  SE UTILIZA UN SIMBOLO DE SALIDA QUE IMPRIME QUE C TIENE QUE ESTAR ENTRE 1,10], EN CASO DE QUE SI SEA ASI ENTONCES SE UTILIZA UN SIMBOLO DE PROCESO QUE DICE QUE CAL[C]++, Y SE REGRESA AL CICLO Y ASI SUCESIVAMENTE HASTA QUE i SEAA <=N, DESPUES SE UTLIZA UN SIMBOLO DE SALIDA QUE IMPRIME CAL, DESPUES SE UTILIZA UN SIMBOLO DE PROCESO QUE ALMACENA LOS VALORES: CR=0, CA=0, PA=0, PR=0, SR=0 SA=0, DESPUES VOLVEMOS A LLAMAR LA VARIABLE N EN UN SIMBOLO DE ENTRADA, DESPUES INSERTAMOS UN CICLO PARA INDICAR QUE i=0; i<=N; i++, DESPUES SE UTILIZA UN SIMBOLO DE SALIDA PARA PEDIR UN NUMERO DEL 1 AL 10, DESPUES ESE NUMERO SE ALMACENA EN LA VARIBLE NUM EN UN SIMBOLO DE ENTRADA, DESPUES SE UTILIZA UN SIMBOLO DE DECISION PARA PREGUNTAR SI NUM>0, NUM<=10, SI ES NO SE UTILIZA UN SIMBOLO DE SALIDA QUE IMPRIME UE NUM TIENE QUE ESTAR ENTRE 1 Y 10, SI ES I ENTONCES SE UTILIZA UN SIMBOLO DE DECISION QUE PREGUNTA SI NUM>=6, SI ES CORRECTO SE UTILIZA UN SIMBOLO DE PROCESO QUE INDICA QUE SA=SA+NUM, CA=CA+1, LA RESPUESTA ES NO ENTONCES SE UTILIZA UN SIMBOLO DE PROCESO QUE DICE QUE SR=SR+NUM, CR=CR+1, DESPUES NOS REGRESEAMOS AL CICLO FOR Y ASI SUCECIVANMENTE HASTA QUE i=N, DESPUES UTILIZAMOS UN SIMBOLO DE PROCESO PARA INDICAR QUE PA=SP/CA, PR=SR/CR, FINALMENTE AGREGAMOS OTRO SIMBOLO DE SALIDA QUE INDICA QUE PR=(PA+PR)/2.

#### 9.2 DIAGRAMA DE FLUJO DE DATOS
[![24.jpg](https://i.postimg.cc/rwhqzwd7/24.jpg)](https://postimg.cc/Hr7qhH9t)

#### 9.3 PRUEBA DE ESCRITORIO
|CAL[1,10]|N  |N>0 |i  |i<=N|CAL[1,10]|C  |C>0, C<=10|CAL[C]++|i++|CAL|
|---------|---|----|---|----|---------|---|----------|--------|---|---|
|9        |4  |4>0 |0  |0<=4| 0        |9  |9>0, 9<=0 |10      |1  |9  |
|9        |   |    |1  |1<=4|1         |9  |9>0, 9<=0 |10      |2  |9  |
|8        |4  |4>0 |0  |2<=4| 2        |8  |8>0, 8<=0 |9       |3  |8  |
|7        |   |    |1  |3<=4|  3       |7  |7>0, 7<=0 |8       |4  |7  |




|CR |CA |PR |PA |PG |SR |SA |N  |i  |i<=n|NUM|NUM>0,NUM<=10|NUM>=6|CA+1|SA+NUM|CR+1|SR+NUM|i++|PA=SA/CA|PR=SR/CR|PG=(PR+PA)/2|PG |
|---|---|---|---|---|---|---|---|---|----|---|-------------|------|----|------|----|------|---|--------|--------|------------|---|
|0  |0  |0  |0  |0  |0  |0  |4  |0  |0< 4|8  |8>=0,8<=10   |8>=6  |1   |8     |0   |0     |1  |
|0  |1  |0  |0  |0  |0  |8  |4  |1  |1< 4|5  |5>=0,5<=10   |5>=6  |1   |8     |1   |5     |2  |
|1  |1  |0  |0  |0  |5  |8  |4  |2  |2< 4|9  |9>=0,9<=10   |9>=6  |2   |17    |1   |5     |3  |
|1  |2  |0  |0  |0  |5  |7  |4  |3  |3< 4|3  |3>=0,3<=10   |3>=6  |2   |17    |2   |8     |4  |17/2    |8/4     |(8.5+4)/2   |6.25|



#### 9.4 ENTRADAS
N
C
NUM

#### 9.5 SALIDA
CR, CA
CAL

#### 9.6 PROCESO
CAL[C]++
C=0
CA=0
SA=0
CR=0
SR=0
PP=0
PR=0
PG=0
SA=SA+NUM
SR=SR+NUM
CA=CA+1
CR=CR+1
PG=(PA+PR)/2
PS=SR/CR

#### 9.7 DECISION
N>0
C>0
C<=10
NUM>0
NUM<=10
NUM>=6

#### 9.8 CICLO FOR
i=0; i<=N; i++
i=0; i<=N; i++

#### 9.9 CODIGO
```dart
Calificaciones=int(input("Ingrese la cantidad de calificaciones"))
vec=[]
n=0

for i in range(1,Calificaciones+1):
    calificacion=int(input("Calificacion: "))
    n=n+calificacion
    vec.append(calificacion)

promedio=n/len(vec)

npromedio=0
for j in vec:
    if j>promedio:
        npromedio=npromedio+1

aprobado=0

#Primero inicializas el contador
promedioAprobados = 0
for h in vec:
    if h>5:
        aprobado=aprobado+1
        #Va sumando cada unas de las notas
        promedioAprobados = promedioAprobados + h

#Luego saca el promedio sumatoria / cantidad de aprobados 
promedioAprobados = promedioAprobados / aprobado

reprobado=0
for k in vec:
    if k<=5:
        reprobado=reprobado+1

print("Max Calificacion", max(vec)) 
print("Min calificacion", min(vec))
print("Promedio:", promedio)
print("Superiores a promedio:", npromedio)
print("Cantidad de aprobados:", aprobado)
print("Promedio de aprobados:", promedioAprobados)
print("Desaprobados:", reprobado)
```





### Ejercicio 9 DO/WHILE. OBTEN LA FRECUENCIA DE N CALIFICACIONES ENTRE [1,10], INDIQUE LA CANTIDAD DE REPROBADOS Y LA CANTIDAD DE APROBADOS, EL PROMEDIO DE APROBADOS Y PROMEDIO GENERAL.

#### 9.1 Análisis
SE NECESITA UTILIZAR UN SIMBOLO DE PROCESO PARA INDICAR QUE EL VECTOR SERA CALIFICAIONES [1,10] Y C=0, DESPUES SE UTILIZA UN SIMBOLO DE SALIDA PARA PREGUNTAR CUANTAS CALIICAIONES, DESPUES SE UTILIZA UN SIMBOLO DE ENTARADA PARA INGRESAR LAS CANTIDADES EN LA VARIABLE N, DESPUES SE UTILIZA UN SIMBOLO DE DECISION PARA PREGUNTAR SI N>0, SI NO ES MAYOR SE UTILIZA UN SMBOLO DE SALIDA QUE DICE QUE TIENE QUE SER MAYOR A 0, Y SI SI ES MAYOR SE UTILIZA UN SIMBOLO DEPROCESO PARA INDICAR CALIFICACION [1,10], DESPUES EL VALOR SE ALMACENA EN C EN UN SIMBOLO DE ENTRADA, DESPUES SE UTILIZA UN SIMBOLO DE DECISION QUE PREGUNTA SI C>, AND C<=10, SI NO ES ASI ENTONCES  SE UTILIZA UN SIMBOLO DE SALIDA QUE IMPRIME QUE C TIENE QUE ESTAR ENTRE [1,10], EN CASO DE QUE SI SEA ASI ENTONCES SE UTILIZA UN SIMBOLO DE PROCESO QUE DICE QUE CAL[C]++ Y C=C+1, DESPUES SE UTILIZA UN SIMBOLO DE DECISION PARA PREGUNTAR SI C<=N, SI ES ASI SE REGRESA AL SIMBOLO DE PORCESO DE CALIFICACION [1,10,], PERO SI ES NO ENTONCES SE UTILIZA UN SIMBOLO DE SALIDA QUE IMPRIME CAL, DESPUES SE UTILIZA UN SIMBOLO DE PROCESO QUE ALMACENA LOS VALORES: C=0, CR=0, CA=0, PA=0, PR=0, SR=0, SA=0, DESPUES VOLVEMOS A LLAMAR LA VARIABLE N EN UN SIMBOLO DE ENTRADA, DESPUES SE UTILIZA UN SIMBOLO DE SALIDA PARA PEDIR UN NUMERO DEL 1 AL 10, DESPUES ESE NUMERO SE ALMACENA EN LA VARIBLE NUM EN UN SIMBOLO DE ENTRADA, DESPUES SE UTILIZA UN SIMBOLO DE DECISION PARA PREGUNTAR SI NUM>0, NUM<=10, SI ES NO SE UTILIZA UN SIMBOLO DE SALIDA QUE IMPRIME UE NUM TIENE QUE ESTAR ENTRE 1 Y 10, SI ES ASI ENTONCES SE UTILIZA UN SIMBOLO DE DECISION QUE PREGUNTA SI NUM>=6, SI ES CORRECTO SE UTILIZA UN SIMBOLO DE PROCESO QUE INDICA QUE SA=SA+NUM, CA=CA+1, LA RESPUESTA ES NO ENTONCES SE UTILIZA UN SIMBOLO DE PROCESO QUE DICE QUE SR=SR+NUM, CR=CR+1, DESPUES UTILIZAMOS OTRO SIMBOLO DE DECISION PARA PREGUNTAR SI C<=N, SI ES NO SE REGRESA AL SIMBOLO DE ENTRADA PARA PEDIR OTRO NUMERO, PERO SI ES SI ENTONCES  UTILIZAMOS UN SIMBOLO DE PROCESO PARA INDICAR QUE PA=SP/CA, PR=SR/CR, FINALMENTE AGREGAMOS OTRO SIMBOLO DE SALIDA QUE INDICA QUE PR=(PA+PR)/2.

#### 9.2 DIAGRAMA DE FLUJO DE DATOS
[![25.jpg](https://i.postimg.cc/zfFw21Yk/25.jpg)](https://postimg.cc/v1D6DkB1)

#### 9.3 PRUEBA DE ESCRITORIO
|CAL[1,10]|N  |N>0 |C  |C<=N|CAL[1,10]|C  |C>0, C<=10|CAL[C]++|C+1|CAL|
|---------|---|----|---|----|---------|---|----------|--------|---|---|
|9        |4  |4>0 |0  |0<=4|0        |9  |9>0, 9<=0 |10      |1  |9  |
|9        |   |    |1  |1<=4|1        |9  |9>0, 9<=0 |10      |2  |9  |
|8        |4  |4>0 |0  |2<=4|2        |8  |8>0, 9<=0 |9       |3  |8  |
|7        |   |    |1  |3<=4|3        |7  |7>0, 9<=0 |8       |4  |7  |




|CR |CA |PR |PA |PG |SR |SA |N  |C  |C<=n|NUM|NUM>0,NUM<=10|NUM>=6|CA+1|SA+NUM|CR+1|SR+NUM|C+1|PA=SA/CA|PR=SR/CR|PG=(PR+PA)/2|PG |
|---|---|---|---|---|---|---|---|---|----|---|-------------|------|----|------|----|------|---|--------|--------|------------|---|
|0  |0  |0  |0  |0  |0  |0  |4  |0  |0< 4|8  |8>=0,8<=10   |8>=6  |1   |8     |0   |0     |1  |
|0  |1  |0  |0  |0  |0  |8  |4  |1  |1< 4|5  |5>=0,5<=10   |5>=6  |1   |8     |1   |5     |2  |
|1  |1  |0  |0  |0  |5  |8  |4  |2  |2< 4|9  |9>=0,9<=10   |9>=6  |2   |17    |1   |5     |3  |
|1  |2  |0  |0  |0  |5  |7  |4  |3  |3< 4|3  |3>=0,3<=10   |3>=6  |2   |17    |2   |8     |4  |17/2    |8/4     |(8.5+4)/2   |6.25|



#### 9.4 ENTRADAS
N
C
NUM

#### 9.5 SALIDA
CR, CA
CAL

#### 9.6 PROCESO
CAL[C]++
C=0
CA=0
SA=0
CR=0
SR=0
PP=0
PR=0
PG=0
SA=SA+NUM
SR=SR+NUM
CA=CA+1
CR=CR+1
PG=(PA+PR)/2
PS=SR/CR

#### 9.7 DECISION
N>0
C>0
C<=10
NUM>0
NUM<=10
NUM>=6

#### 9.8 CODIGO
```dart
Calificaciones=int(input("Ingrese la cantidad de calificaciones"))
vec=[]
n=0

cont = 0
while(True):
    calificacion=int(input("Calificacion: "))
    n=n+calificacion
    vec.append(calificacion)
    cont += 1
    if(cont>=Calificaciones):
        break;

promedio=n/len(vec)

npromedio=0
for j in vec:
    if j>promedio:
        npromedio=npromedio+1

aprobado=0

#Primero inicializas el contador
promedioAprobados = 0
for h in vec:
    if h>=5:
        aprobado=aprobado+1
        #Va sumando cada unas de las notas
        promedioAprobados = promedioAprobados + h

#Luego saca el promedio sumatoria / cantidad de aprobados 
promedioAprobados = promedioAprobados / aprobado

reprobado=0
for k in vec:
    if k<=5:
        reprobado=reprobado+1

print("Max Calificacion", max(vec)) 
print("Min calificacion", min(vec))
print("Promedio:", promedio)
print("Superiores a promedio:", npromedio)
print("Cantidad de aprobados:", aprobado)
print("Promedio de aprobados:", promedioAprobados)
print("Desaprobados:", reprobado)
```


### Ejercicio 9 WHILE. OBTEN LA FRECUENCIA DE N CALIFICACIONES ENTRE [1,10], INDIQUE LA CANTIDAD DE REPROBADOS Y LA CANTIDAD DE APROBADOS, EL PROMEDIO DE APROBADOS Y PROMEDIO GENERAL.

#### 9.1 Análisis
SE NECESITA UTILIZAR UN SIMBOLO DE PROCESO PARA INDICAR QUE EL VECTOR SERA CALIFICAIONES [1,10] Y C=0, DESPUES SE UTILIZA UN SIMBOLO DE SALIDA PARA PREGUNTAR CUANTAS CALIICAIONES, DESPUES SE UTILIZA UN SIMBOLO DE ENTARADA PARA INGRESAR LAS CANTIDADES EN LA VARIABLE N, DESPUES SE UTILIZA UN SIMBOLO DE DECISION PARA PREGUNTAR SI N>0, SI NO ES MAYOR SE UTILIZA UN SMBOLO DE SALIDA QUE DICE QUE TIENE QUE SER MAYOR A 0, Y SI SI ES MAYOR SE UTILIZA UN SIMBOLO DEPROCESO PARA INDICAR CALIFICACION [1,10], DESPUES EL VALOR SE ALMACENA EN C EN UN SIMBOLO DE ENTRADA, DESPUES SE UTILIZA UN SIMBOLO DE DECISION QUE PREGUNTA SI C>, AND C<=10, SI NO ES ASI ENTONCES  SE UTILIZA UN SIMBOLO DE SALIDA QUE IMPRIME QUE C TIENE QUE ESTAR ENTRE [1,10], EN CASO DE QUE SI SEA ASI ENTONCES SE UTILIZA UN SIMBOLO DE PROCESO QUE DICE QUE CAL[C]++ Y C=C+1, DESPUES SE UTILIZA UN SIMBOLO DE DECISION PARA PREGUNTAR SI C<=N, SI ES ASI SE REGRESA AL SIMBOLO DE PORCESO DE CALIFICACION [1,10,], PERO SI ES NO ENTONCES SE UTILIZA UN SIMBOLO DE SALIDA QUE IMPRIME CAL, DESPUES SE UTILIZA UN SIMBOLO DE PROCESO QUE ALMACENA LOS VALORES: C=0, CR=0, CA=0, PA=0, PR=0, SR=0, SA=0, DESPUES VOLVEMOS A LLAMAR LA VARIABLE N EN UN SIMBOLO DE ENTRADA, DESPUES UTILIZAMOS OTRO SIMBOLO DE DECISION PARA PREGUNTAR SI C<=N, SI NO ES ASI SE DESPUES SE UTILIZA UN SIMBOLO DE SALIDA PARA PEDIR UN NUMERO DEL 1 AL 10, DESPUES ESE NUMERO SE ALMACENA EN LA VARIBLE NUM EN UN SIMBOLO DE ENTRADA, DESPUES SE UTILIZA UN SIMBOLO DE DECISION PARA PREGUNTAR SI NUM>0, NUM<=10, SI ES NO SE UTILIZA UN SIMBOLO DE SALIDA QUE IMPRIME UE NUM TIENE QUE ESTAR ENTRE 1 Y 10, SI ES ASI ENTONCES SE UTILIZA UN SIMBOLO DE DECISION QUE PREGUNTA SI NUM>=6, SI ES CORRECTO SE UTILIZA UN SIMBOLO DE PROCESO QUE INDICA QUE SA=SA+NUM, CA=CA+1, LA RESPUESTA ES NO ENTONCES SE UTILIZA UN SIMBOLO DE PROCESO QUE DICE QUE SR=SR+NUM, CR=CR+1, PERO SI EL SIMBOLO DE DECISION DE C<=N ES NO ES SI ENTONCES  UTILIZAMOS UN SIMBOLO DE PROCESO PARA INDICAR QUE PA=SP/CA, PR=SR/CR, FINALMENTE AGREGAMOS OTRO SIMBOLO DE SALIDA QUE INDICA QUE PR=(PA+PR)/2.

#### 9.2 DIAGRAMA DE FLUJO DE DATOS
[![26.jpg](https://i.postimg.cc/QtNwx3Q6/26.jpg)](https://postimg.cc/SX5DDHt8)

#### 9.3 PRUEBA DE ESCRITORIO
|CAL[1,10]|N  |N>0 |C  |C<=N|CAL[1,10]|C  |C>0, C<=10|CAL[C]++|C+1|CAL|
|---------|---|----|---|----|---------|---|----------|--------|---|---|
|9        |4  |4>0 |0  |0<=4|0        |9  |9>0, 9<=0 |10      |1  |9  |
|9        |   |    |1  |1<=4|1        |9  |9>0, 9<=0 |10      |2  |9  |
|8        |4  |4>0 |0  |2<=4|2        |8  |8>0, 9<=0 |9       |3  |8  |
|7        |   |    |1  |3<=4|3        |7  |7>0, 9<=0 |8       |4  |7  |




|CR |CA |PR |PA |PG |SR |SA |N  |C  |C<=n|NUM|NUM>0,NUM<=10|NUM>=6|CA+1|SA+NUM|CR+1|SR+NUM|C+1|PA=SA/CA|PR=SR/CR|PG=(PR+PA)/2|PG |
|---|---|---|---|---|---|---|---|---|----|---|-------------|------|----|------|----|------|---|--------|--------|------------|---|
|0  |0  |0  |0  |0  |0  |0  |4  |0  |0< 4|8  |8>=0,8<=10   |8>=6  |1   |8     |0   |0     |1  |
|0  |1  |0  |0  |0  |0  |8  |4  |1  |1< 4|5  |5>=0,5<=10   |5>=6  |1   |8     |1   |5     |2  |
|1  |1  |0  |0  |0  |5  |8  |4  |2  |2< 4|9  |9>=0,9<=10   |9>=6  |2   |17    |1   |5     |3  |
|1  |2  |0  |0  |0  |5  |7  |4  |3  |3< 4|3  |3>=0,3<=10   |3>=6  |2   |17    |2   |8     |4  |17/2    |8/4     |(8.5+4)/2   |6.25|



#### 9.4 ENTRADAS
N
C
NUM

#### 9.5 SALIDA
CR, CA
CAL

#### 9.6 PROCESO
CAL[C]++
C=0
CA=0
SA=0
CR=0
SR=0
PP=0
PR=0
PG=0
SA=SA+NUM
SR=SR+NUM
CA=CA+1
CR=CR+1
PG=(PA+PR)/2
PS=SR/CR

#### 9.7 DECISION
N>0
C>0
C<=10
NUM>0
NUM<=10
NUM>=6

#### 9.8 CODIGO
```dart
Calificaciones=int(input("Ingrese la cantidad de calificaciones"))
vec=[]
n=0

cont = 0
while(cont < Calificaciones):
    calificacion=int(input("Calificacion: "))
    n=n+calificacion
    vec.append(calificacion)
    cont += 1

promedio=n/len(vec)

npromedio=0
for j in vec:
    if j>promedio:
        npromedio=npromedio+1

aprobado=0

#Primero inicializas el contador
promedioAprobados = 0
for h in vec:
    if h>=5:
        aprobado=aprobado+1
        #Va sumando cada unas de las notas
        promedioAprobados = promedioAprobados + h

#Luego saca el promedio sumatoria / cantidad de aprobados 
promedioAprobados = promedioAprobados / aprobado

reprobado=0
for k in vec:
    if k<=5:
        reprobado=reprobado+1

print("Max Calificacion", max(vec)) 
print("Min calificacion", min(vec))
print("Promedio:", promedio)
print("Superiores a promedio:", npromedio)
print("Cantidad de aprobados:", aprobado)
print("Promedio de aprobados:", promedioAprobados)
print("Desaprobados:", reprobado)
```

### EJERCICIO 10: PIDE 2 NUMEROS Y DI CUAL ES MAYOR

#### 10.1 ANALISIS
SE UTILIZA UN SIMBOLO DE SALIDA PARA PEDIR 2 NUMEROS, DESPUES SE UTILIZA EL SIMBOLO DE ENTRADA PARA INGRESAR N1, DESPUES SE TULIZA OTRO SIMOLO DE ENTRADA PARA IMGRESAR N2, POSTERIORMENTE SE UTILIZA UN SIMBOLO DE DECISION PARA PREGUNTAR SI N2>N2, SI SI ES ASI ENTONCES SE UTILIZA UN SIMBOLO DE SALIDA QUE IMPROME QUE EL N1 ES MAYOR, DE LO CONTRARIO SE IMPRIME QUE EL N2 ES MAYOR.

#### 10.2 DIAGRAMA DE FLIJO DE DATOS
[![1.jpg](https://i.postimg.cc/8zX0Jyq8/1.jpg)](https://postimg.cc/5Xv3Dm4p)

#### 10.3 PRUEBA DE ESCRITORIO
|N1 |N2 |N1>N2|N1 MAYOR|N2 MAYOR|
|---|---|-----|--------|--------|
|2  |9  |NO   |        |*       |

#### 10.4 ENTRADA
N1
N2

#### 10.5 SALIDA
N1 MAYOR
N2 MAYOR

#### 10.6 DECISION
N1>N2

#### 10.7 CODIGO



### EJERCICIO 11: CATURE 10 NUMEROS ENTEROS POSITIVOS

#### 11.1 ANALISIS
SE UTILIZA UN SIMBOLO DE PROCESO DONDE A[11], DESPUES SE UTILIZA EL CICLO FOR i=1; i<=10; i++, DESPUES SE UTILIZA EL SIMBOLO DE ENTRADA PARA N, DESPUES SE UTILIZA EL SIMBOLO DE PROCESO DEONDE A[i]=N, DESPUES SE REGRESA AL CICLO FOR Y ASI SUECIVAMENTE HASTA QUE I SEA 10 Y FINALMENTE SE IMPRIME A.

#### 11.2 DIAGRAMA DE FLIJO DE DATOS
[![2.jpg](https://i.postimg.cc/qqCkShyq/2.jpg)](https://postimg.cc/QKhGWM6Z)

#### 11.3 PRUEBA DE ESCRITORIO
|A[11] |i=1 |i<=10|N |A[i]|i++|A |
|------|----|-----|--|----|---|--|
|0     |1   |1<=10|1 |1   |2  |1 |
|1     |2   |2<=10|2 |2   |3  |2 |
|2     |3   |3<=10|3 |3   |4  |3 |
|3     |4   |4<=10|4 |4   |5  |4 |
|4     |5   |5<=10|5 |5   |6  |5 |
|5     |6   |6<=10|6 |6   |7  |6 |
|6     |7   |7<=10|7 |7   |8  |7 |
|7     |8   |8<=10|8 |8   |9  |8 |
|8     |9   |9<=10|9 |8   |10 |9 |
|9     |10  |10<=10|10|9  |1  |10 |


#### 11.4 ENTRADA
N

#### 11.5 SALIDA
A

#### 11.6 CICLO FOR
i=1; i<=10; i++

#### 11.7 CODIGO



### EJERCICIO 12: CATURE 10 NUMEROS ENTEROS POSITIVOS, DIGA CUAL ES MAYOR Y CUAL ES MENOR.

#### 12.1 ANALISIS
SE UTILIZA UN SIMBOLO DE PROCESO DONDE A[11], DESPUES SE UTILIZA EL CICLO FOR i=1; i<=10; i++, DESPUES SE UTILIZA EL SIMBOLO DE ENTRADA PARA N, DESPUES SE UTILIZA EL SIMBOLO DE DECISION PARA PREGUNTAR SI N>0 SI NO ES ASI SE UTILIZA UN SIMBOLO DE SALIDA PARA IMPRIMIR QUE N TIENE QUE SER MAYOR A 0 Y SE REGRESA AL SIMBOLO DE ENTRADA PARA PEDIR OTRAN, EN CASO DE QUE N SI SEA MAYOR A 0 SE UTILIZA UN SIMBOLO DE PROCESO DONDE NUM[i]=N, DESPUES SE REGRESA AL CICLO FOR Y ASI SUECIVAMENTE HASTA QUE I SEA 10 Y FINALMENTE SE IMPRIME NUM, DESPUES SE UTILIZA UN SIMBOLO DE PROCESO DONDE MAYOR=0, DESPUES SE UTILIZA OTRO SIMBOLO DE CICLO PARA i=1; i<=10; i++; DESPUES SE PREGUNTA SI MAYOR>NUM[i], SI NO ES ASI SE UTILIZA UN SIMBOLO DE PROCESO DONDE MAYOR=NUM[i], Y EN CASO DE QUE MAYOR SI SEA MAYOR A NUM[i] SE REGRESA AL CICLO Y ASI SUCECIBAMENTE HASTA QUE I SEA 10, DESPUES SE UTILIZA UN SIMBOLO DE SALIDA PARA IMPRIMIR MAYOR, DESPUES SE UTILIZA UN SIMBOLO DE PROCESO DONDE MENOR=MAYOR, DESPUES VOLVEMOS A UTILIZAR UN SIMBOLO FOR PARA PREGUNTAR SI MENOR<NUM[i], EN CASO DE QUE NO SEA ASI SE UTILIZA UN SIMBOLO PROCESO DONDE MENOR=NUM[i], DESPUES SE REGRESA AL SIMBOLO DE FOR, FINALMENTE IMPRIMIMOS MENOR.

#### 12.2 DIAGRAMA DE FLIJO DE DATOS
[![44.jpg](https://i.postimg.cc/htK5gzBt/44.jpg)](https://postimg.cc/ykrPyNxM)

#### 12.3 PRUEBA DE ESCRITORIO
|A[11] |i=1 |i<=10|N |A[i]|N>0|NUM[i]=N|i++|NUM|MAYOR|i |i<=10|MAYOR>NUM[i]|MAYOR=NUM[i]|i++|MAYOR|MENOR=MAYOR|i |i<=10|MENOR<NUM[i]|MENOR=NUM[i]|i++|MENOR|
|------|----|-----|--|----|---|--------|---|---|-----|--|-----|------------|------------|---|-----|-----------|--|-----|------------|------------|---|-----|
|0     |1   |1<=10|1 |1   |1>0|1       |2  |1  |0    |1 |1<=10|0>1         |1           |2  |     |10         |1 |1<=10|10<1        |1           |2  |     |
|1     |2   |2<=10|2 |2   |2>0|2       |3  |2  |1    |2 |2<=10|1>2         |2           |3  |     |           |2 |2<=10|1<2         |            |3  |     |
|2     |3   |3<=10|3 |3   |3>0|3       |4  |3  |2    |3 |3<=10|2>3         |3           |4  |     |           |3 |3<=10|1<3         |            |4  |     |     
|3     |4   |4<=10|4 |4   |4>0|4       |5  |4  |3    |4 |4<=10|3>4         |4           |5  |     |           |4 |4<=10|1<4         |            |5  |     |
|4     |5   |5<=10|5 |5   |5>0|5       |6  |5  |4    |5 |5<=10|4>5         |5           |6  |     |           |5 |5<=10|1<5         |            |6  |     |
|5     |6   |6<=10|6 |6   |6>0|6       |7  |6  |5    |6 |6<=10|5>6         |6           |7  |     |           |6 |6<=10|1<6         |            |7  |     |
|6     |7   |7<=10|7 |7   |7>0|7       |8  |7  |6    |7 |7<=10|6>7         |7           |8  |     |           |7 |7<=10|1<7         |            |8  |     |
|7     |8   |8<=10|8 |8   |8>0|8       |9  |8  |7    |8 |8<=10|7>8         |8           |9  |     |           |8 |8<=10|1<8         |            |9  |     |
|8     |9   |9<=10|9 |8   |9>0|9       |10 |9  |8    |9 |9<=10|8>9         |9           |10 |     |           |9 |9<=10|1<9         |            |10 |     |
|9     |10  |10<=10|10|9  |10>0|10     |   |10 |9    |10|10<=10|9>10       |10          |   |10   |           |10|10<=10|1<10       |            |   |1    | 


#### 12.4 ENTRADA
N

#### 12.5 SALIDA
NUM
MAYOR
MENOR

#### 12.6 CICLO FOR
i=1; i<=10; i++

#### 12.7 CODIGO


### EJERCICIO 13: OBTEN LA DISTANCIA MAYOR ENTRE 2 NUMEROS CONCECUTIVOS EN UNA LISTA DE 10 NUMEROS.

#### 13.1 ANALISIS
SE UTILIZA UN SIMBOLO DE PROCESO DONDE DIS[9] Y NUM[10], DESPUES SE UTILIZA EL CICLO FOR i=1; i<=9; i++, DESPUES SE UTILIZA EL SIMBOLO DE ENTRADA PARA N, DESPUES SE UTILIZA EL SIMBOLO DE DECISION PARA PREGUNTAR SI N>0 SI NO ES ASI SE UTILIZA UN SIMBOLO DE SALIDA PARA IMPRIMIR QUE N TIENE QUE SER MAYOR A 0 Y SE REGRESA AL SIMBOLO DE ENTRADA PARA PEDIR OTRAN, EN CASO DE QUE N SI SEA MAYOR A 0 SE UTILIZA UN SIMBOLO DE PROCESO DONDE NUM[i]=N, DESPUES SE REGRESA AL CICLO FOR Y ASI SUECIVAMENTE HASTA QUE I SEA 9, DESPUES SE UTILIZA OTRO CICLO DE FOR DONDE i=1; i<9; i++, DESPUES SE UTILIZA UN SIMBOLO DE PROCESO DONDE NUM[i]-NUM[i+1], despues se utiliza un simbolo de decision donde DIS<=, SI NO ES ASI SE UTILIZA UN SIMBOLO DE PROCESO DONDE D[i]=DIS, EN CASO DE QUE SEA SI SE UTILIZA UN SIMBOLO DE PROCESO DONDE D[i]=DIS*-1, Y SE REGRESA AL CICLO HASTA QUE i SEA 9, DESPUES SE UTILIZA UN SIMBOLO DE PROCESO DONDE MAYOR=0, DESPUES SE UTILIZA OTRO SIMBOLO DE CICLO PARA i=1; i<9; i++; DESPUES SE PREGUNTA SI MAYOR>NUM[i], SI NO ES ASI SE UTILIZA UN SIMBOLO DE PROCESO DONDE MAYOR=NUM[i], Y EN CASO DE QUE MAYOR SI SEA MAYOR A NUM[i] SE REGRESA AL CICLO Y ASI SUCECIBAMENTE HASTA QUE I SEA 8, DESPUES SE UTILIZA UN SIMBOLO DE SALIDA PARA IMPRIMIR MAYOR.

#### 13.2 DIAGRAMA DE FLIJO DE DATOS
[![4.jpg](https://i.postimg.cc/qBWffXQc/4.jpg)](https://postimg.cc/WtmYgZBt)

#### 13.3 PRUEBA DE ESCRITORIO
|DIS[9],NUM[10]|i=1 |i<=9 |N |N>0|NUM[i]=N|i++|i  |i<9|DIS=NUM[i]-NUM[i+1]|DIS<0|D[i]=DIS|D[i]=DIS*-1|i++|
|--------------|----|-----|--|---|--------|---|---|---|-------------------|-----|--------|-----------|---|
|0             |1   |1<=9 |1 |1>0|1       |2  |1  |1<9|1                  |1<0  |        |           |2  |
|1             |2   |2<=9 |2 |2>0|2       |3  |2  |2<9|1                  |1<0  |||3| 
|2             |3   |3<=9 |3 |3>0|3       |4  |3  |3<9|1                  |1<0  |||4|
|3             |4   |4<=9 |4 |4>0|4       |5  |4  |4<9|1                  |1<0  |||5|
|4             |5   |5<=9 |5 |5>0|5       |6  |5  |5<9|1                  |1<0  |||6|
|5             |6   |6<=9 |6 |6>0|6       |7  |6  |6<9|1                  |1<0  |||7|
|6             |7   |7<=9 |7 |7>0|7       |8  |7  |7<9|1                  |1<0  |||8|
|7             |8   |8<=9 |8 |8>0|8       |9  |8  |8<9|1                  |1<0  |||9|
|8             |9   |9<=9 |9 |9>0|9       |   |9  |   |1                  |1<0  |1       |  
|9             |


|MAYOR|i |i<9|MAYOR>D[i]|MAYOR=D[i]|i++|MAYOR|
|-----|--|---|----------|----------|---|-----|
|O    |1 |1<9|0>1       |1|2|
|1    |2 |2<9|1<2       | 2 |3|
|2    |3 |3<9|2<3       | 3|4|
|3    |4 |4<9|3<4       |4|5|
|4    |5 |5<9|4<5       |5|6|
|5    |6 |6<9|5<6       |6|7|
|6    |7 |7<9|6<7       |7|8|
|7    |8 |8<9|7<8       |8|9|
|8    |  |   |          |||9|
#### 13.4 ENTRADA
N

#### 13.5 SALIDA
MAYOR

#### 13.6 CICLO FOR
i=1; i<=10; i++

#### 13.7 CODIGO



### EJERCICIO 14: ESCRIBA UN DFD QUE ESCRIBA:
# 1
# 11
# 111
# 1111
# 11111

#### 14.1 ANALISIS
SE UTILIZA UN SIMBOLO DE CICLO DE FOR DONDE i=1; i<=5; i++, DESPUES SE UTILIZA OTRO CICLO DE FOR DONDE j=1; j<=i;j++, despues se utiliza un simbolo de salida para imprimir 1 y se regresa al segundo ciclo y del segundo ciclo al primero.

#### 14.2 DIAGRAMA DE FLIJO DE DATOS
[![5.jpg](https://i.postimg.cc/4y3hzHmw/5.jpg)](https://postimg.cc/ygwdKdhS)

#### 14.3 PRUEBA DE ESCRITORIO
|i  |i<=5|j  |j<=i|*     |i++ |j++ |
|---|----|---|----|------|----|----|
|1  |1<=5|1  |1<=1|1     |1   |1   | 
|2  |2<=5|2  |2<=2|11    |2   |2   |
|3  |3<=5|3  |3<=3|111   |3   |3   |
|4  |4<=5|4  |4<=4|1111  |4   |4   |
|5  |5<=5|5  |5<=5|11111 |5   |5   |
                   
#### 14.4 ENTRADA
Ninguna

#### 14.5 SALIDA
1

#### 14.6 CICLO FOR
i=1; i<=5; i++
j=1; j<=i; j++

#### 14.7 CODIGO
