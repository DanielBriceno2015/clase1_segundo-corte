
# Definicion de sistema

## 1. Introduccion

Introduccion a modelamiento de sistemas


## 2. Definiciones

🔑 **sistema** es un conjunto de elementos interconectados que reciben una entrada, procesan información y generan una salida. Puede ser físico, químico, biológico o incluso económico.

🔑 **Ley de hooke** la deformación elástica que sufre un cuerpo es proporcional a la fuerza que produce tal deformación, siempre y cuando no se sobrepase el límite de elasticidad.

🔑 **friccion en seco** una fuerza que aparece entre dos superficies sólidas en contacto

🔑 **friccion estatica** fuerza que se opone al inicio del movimiento entre dos superficies en contacto, impidiendo que se deslicen una sobre la otra. 

🔑 **friccion por rodamiento** fuerza que se produce cuando dos cuerpos ruedan entre sí sin deslizarse.

🔑 **resorte** Un componente mecánico que almacena y libera energía. También se le conoce como muelle.


## 3. Sistemas mecanicos

 Todos los sistemas mecánicos presentan una naturaleza en su movimiento que le impulsa a oscilar, como cuando un objeto pende de un hilo en el techo y con la mano lo empujamos. O un zapato sobre una plataforma con resortes. Es bueno saber qué función matemática es la que mejor describe ese movimiento.

### 3.1 Resortes

![Logo](https://lh5.googleusercontent.com/proxy/impYKDTqatvEToDIQx9os0glPam37GF50lYM1l1fOykqj15JV2KjBg8tqq3Z4A4UJv1Exfw1R0az)

Figura 1. Ley de hooke

### 3.2 Amortiguadores

Movimiento Armónico Amortiguado es proporcional a la velocidad V en la mayoría de los casos de interés científico. Dicha fuerza tiene la forma      Fv = bV, donde b es una constante positiva que depende de las características del fluido que ocasiona la fricción, entre otras cosas. Esta fricción, también conocida como Fricción Viscosa, se representa mediante un diagrama que consiste en un pistón y un cilindro lleno de aceite:

![Logo](https://dademuchconnection.wordpress.com/wp-content/uploads/2017/07/null80.png)


Figura 2. Amortiguador


 ## 4. Ejercicios 
 
 📚 Hallar la funcion de transferencia 

![Logo]( https://dademuchconnection.wordpress.com/wp-content/uploads/2017/07/null185.png)

Figura 3. sistema masa resorte amortiguador amortiguador

Masa 
𝑚
m

Resorte con constante de rigidez 
𝑘
k

Amortiguador con coeficiente de fricción viscosa 
𝑐
c

Una fuerza externa 
𝐹
(
𝑡
)
F(t)

Desplazamiento de la masa 
𝑥
(
𝑡
)
x(t)

### Ley de newton

∑F=m 
x
¨
 (t)

### Diagrama cuerpo libre

                  ←  -k·x(t)   (resorte)
                  ←  -c·ẋ(t)   (amortiguador)
          ┌──────────────────┐
          │                  │
          │        m         │  →  F(t)
          │                  │
          └──────────────────┘



F resorte = -k·x(t)   (resorte)

F amortiguador =  -c·ẋ(t)   (amortiguador) 

Fuerza externa = F(t)

 ### Se suman todas las fuerzas

F(t)-c·ẋ(t)-k·x(t) = m ·ẋ


 ### Respuesta

m ·ẋ -c·ẋ(t)-k·x(t) = F(t)


 ## 6. Conclusion

El modelamiento de sistemas mecánicos mediante ecuaciones diferenciales es una herramienta fundamental en ingeniería y física para describir con precisión el comportamiento dinámico de estructuras y mecanismos. Al analizar fuerzas como la masa, el amortiguamiento y la rigidez, se obtienen ecuaciones que reflejan la relación entre entradas (como fuerzas aplicadas) y salidas (como desplazamientos o velocidades).

Este enfoque permite no solo comprender el funcionamiento del sistema, sino también predecir su respuesta ante diferentes condiciones, optimizar su diseño y desarrollar estrategias de control. La formulación matemática mediante ecuaciones diferenciales es, por tanto, una base esencial para la simulación, análisis y diseño de sistemas mecánicos complejos.


 ## 7. Referencias


 


 
