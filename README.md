## ¿Qué es el algoritmo de Luhn?

- Es un método creado por un científico de IBM que se utiliza para la verificación de números de identificación, los mas comunes en los que se utiliza es en los números de tarjetas de crédito como Visa, MasterCard o Diners, pero también se usan en el IMEI de los teléfonos móviles. 

- Este algoritmo es muy simple, nos dice que dado un número que contenga solamente dígitos [0-9], una tarjeta de crédito es válida si y solo si, multiplicando los números impares por 2, sumando los dígitos en las veces que de 2 o más, y por ultimo sumando todos los dígitos, el resultado debe ser 10, es decir que la suma módulo 10 debe ser igual a cero (Que termine en 0), esto para una tarjeta con 16 digitos.

#### Ejemplo - Número de tarjeta valido

![](https://i0.wp.com/www.pcihispano.com/contenido/uploads/2017/08/PAN_valido_luhn.png?resize=1024%2C383&ssl=1)

#### Ejemplo - Número de tarjeta invalido

![](https://i1.wp.com/www.pcihispano.com/contenido/uploads/2017/08/PAN_invalido.png?resize=1024%2C388&ssl=1)

#### Referencias:
- https://www.mundonets.com/algoritmo-de-luhn/
- https://www.pcihispano.com/el-algoritmo-de-luhn-y-su-importancia-para-la-validacion-de-tarjetas-de-pago/
