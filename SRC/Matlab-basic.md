# In this notebook there is a litlee intruction for a "conditional operator" very basic, this is a course with Simulink-Matlab.

### The exercise is: Diseñe un diagrama de bloques condicional que muestre un 10 en la salida si el bloque condicional es mayor a 0 y si es menor que 0, deberá mostrar un 100.

#### Solution is easy, there are two forms for to solution this, first form is with dynamic input, with variable input and the second form is a constant input, here shows the first form.

![](https://github.com/jwilliamsee/Matlab-basic/blob/main/imagen/Matlab1.PNG)

![](https://github.com/jwilliamsee/Matlab-basic/blob/main/imagen/Matlab2.PNG)

    1. Block Repeating sequence
    2. Block Gain
    3. Two block constant
    4. Block Switch
    5. Block Display

## Block **Repeating sequence** connected to Gain, at the same time connected to middle terminal of switch block, output of switch connected to Display, the upper terminal of the Switch connected to the Gain with value 10 and the under terminal of the Switch connected to the Gain with value 100.
