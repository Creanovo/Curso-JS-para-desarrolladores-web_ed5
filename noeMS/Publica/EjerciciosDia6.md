**Ejercicios:**

Realiza los siguientes ejercicios usando en cada uno los tres tipos de bucles (Do...While, For, While )

**1 -**  Diseña un algoritmo para identificar a los clientes autorizados a entrar a nuestro sistema.
- Características:
	- La palabra clave es "Fictizia mola mucho"
	- Solo existen tres intentos
	- Si se pasan los tres intentos. Se despliega un mensaje informativo.

- Usando *for*
```javascript
    var pass = prompt('¿Cual es la pass?');
var numberControl = 1;

if (pass != "Fictizia mola mucho"){
    for (;numberControl < 3 && pass != "Fictizia mola mucho";) {
        console.log('La pass es incorrecta');
        numberControl++;
        pass = prompt('No es la contraseña correcta. Te quedan ' + ( 4-numberControl ) + ' intentos');
        
    }
} else {
    console.log('La pass es correcta! Estás dentro');
}
```

- Usando *while*
```javascript
    var pass = prompt('¿Cual es la pass?');
var numberControl = 1;

if (pass != "Fictizia mola mucho"){
    while (numberControl < 3 && pass != "Fictizia mola mucho") {
        console.log('La pass es incorrecta');
        numberControl++;
        pass = prompt('No es la contraseña correcta. Te quedan ' + ( 4-numberControl ) + ' intentos');
    }
} else {
    console.log('La pass es correcta! Estás dentro');
}
```

- Usando *Do...While*
```javascript
    // Tu solución
```


**2 -** Diseña un algoritmo que imprima los numeros del 1 al 100.

- Usando *for*
```javascript
for (var contador = 1; contador <=100; contador++) {
    console.log(contador)
}tador++;
}
```

- Usando *while*
```javascript

var contador=1;

while (contador <=100) {
    console.log(contador);
    
```

- Usando *Do...While*
```javascript
    var contador=1;

do {
    console.log(contador);
    contador++;
} while (contador<=100);
```

**3 -** Diseña un algoritmo que imprima los numeros del 100 al 0.

- Usando *for*
```javascript
   for (var contador = 100; contador >=0; contador--) {
    console.log(contador)
}
```

- Usando *while*
```javascript
    var contador=100;

while (contador >=0) {
    console.log(contador);
    contador--;
}
```

- Usando *Do...While*
```javascript
    // Tu solución
```


**4 -** Diseña un algoritmo que imprima los numeros pares entre 0 y 100.

- Usando *for*
```javascript
 for (var contador=0; contador <=100; contador++) {
    if (contador % 2 == 0) {
        console.log(contador);
    }
}
```

- Usando *while*
```javascript
    var contador=0;

while (contador<=100) {
    if(contador % 2 == 0) {
        console.log(contador)
    }
    contador++;
}
```

- Usando *Do...While*
```javascript
    var contador=0;

do {
    if (contador % 2 == 0){
        console.log(contador)
    }
    contador++;
} while (contador<=100);
```

**5 -** Diseña un algoritmo que imprima los números impares entre un número dado por el usuario y los siguientes 50 números.

- Usando *for*
```javascript
    //var numero = prompt("Dime un número");
for (var impar=0; impar<=50;) {
    if(numero % 2 !== 0) {
        console.log(numero);
        impar++;
    }
    numero++;
}
```

- Usando *while*
```javascript
    var numero = prompt("Dime un número"); 
var impar=0;
while (impar<=50) {
    if(numero % 2 !== 0) {
        console.log(numero);
        impar++
    }
    numero++;
}
```

- Usando *Do...While*
```javascript
    // Tu solución
```

**6 -** Diseña un algoritmo que imprima la suma de los 50 primeros numeros pares y el total de números impares partiendo de un número dado por el usuario

- Usando *for*
```javascript
    // Tu solución
```

- Usando *while*
```javascript
    // Tu solución
```

- Usando *Do...While*
```javascript
    // Tu solución
```

**7 -** Diseña un algoritmo introducido un numero y pasarlo a número romanos.
- Esperamos que el número sea menor de 50

![numeros_romanos](https://eloviparo.files.wordpress.com/2009/09/numeros-romans.jpg?w=466&h=172)

- Usando *for*
```javascript
    // Tu solución
```

- Usando *while*
```javascript
    // Tu solución
```

- Usando *Do...While*
```javascript
    // Tu solución
```