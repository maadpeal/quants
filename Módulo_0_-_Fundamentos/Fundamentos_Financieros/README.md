# Fundamentos Financieros:

## 1. **Aritmética Financiera**:
   - **Interés simple y compuesto**:
     - Cálculo de intereses
       
       ![interes simple](https://github.com/maadpeal/quants/blob/main/imagenes/intereses.png)
       
       Es la misma formula para el interes simple y para el interes compuesto.

       Si se desea por ejemplo sacar el interes o el monto que obtendre de aqui a tres años lo unico que hay que hacer es modificar la t=3, Y se hace la operacion teniendo como resultado el monto que se obtendria si se invierte tanto el capital inicial como sus intereses.
       
     - Capitalización

       La capitalización es el proceso mediante el cual el dinero aumenta de valor con el tiempo gracias a los intereses.
       
     - Descuento
    
       Es el calculo del valor presente de un flujo futuro

       ![descuento](https://github.com/maadpeal/quants/blob/main/imagenes/descuento.png)

       Mediante esta formula podemos calcular el valor presente de multiples periodos de tiempo en base a la t de la formula.

       ![gradica descuento](https://github.com/maadpeal/quants/blob/main/imagenes/descuento_grafica.jpeg)

       Mediante la grafica de arriba podemos observar como el inicio de un proceso de capitalizacion es el descuento de otros y asi sucesivamente.

       Por ejemplo los 422 es el descuento de los 1000 proyectados

       
   - **Valor presente y futuro**:
     - Valor presente:
       
       ![formula de valor presente](https://github.com/maadpeal/quants/blob/main/imagenes/valor_presente.png)
       
       VP = valor presente
       
       VF = Valor futuro
       
       r = rendimiento
       
       Ejemplo:
       
       VF = 197.950
       
       r = 7% anual
       
       Si quiero saber cuanto debe ser el capital para obtener ese valor futuro a esa tasa se debe aplicar la formula de arriba.
       
       VP = 197.950 / 1 + 0.07 = 185.000
       
       De esta manera se puede saber si vale la pena o no una inversion, si es mejor recibir o hacer una inversion ahora, o si es mejor hacer algo diferente con el dinero.
       
     - Valor presente neto (VPN)

       ![Valor presente neto](https://github.com/maadpeal/quants/blob/main/imagenes/VPN.png)

       COSTO: Es el costo de la inversion actualmente

       VP = valor futuro(de la inversion a evaluar)/ 1 + r(donde r, es el rendimiento con el que se quiere comparar)

       Ejemplo:

       Un amigo me pide prestado 1000 unds y me dice que el año que viene me devolvera 1070

       Ese dinero de 1000unds lo tienes invertido a una tasa anual del 10% de interes por lo que quieres evaluar si te es factible prestar ese dinero a la tasa que te propone tu amigo o no.

       VPN = -1000 + (1070/1.1)
       
       VPN = -1000 + 972.72 = -27.27

       Como el valor final es negativo no vale la pena hacer la inversión propuesta porque te daria un rendimiento mejor invirtiendolo por tu cuenta.

       
     - Valor futuro
    
       El valor futuro de una operacion es el valor presente multiplicado por la cantidad de meses del interes en cuestion.

       Por ejemplo:

       10.000 * 1 + 0.10(el interes anual o de cualquier periodo que corresponda) = 11.000
       
   - **Tasas de interés y descuento**:
     - Tasa nominal y efectiva

           - En la **tasa nominal** no se toma en cuenta la capitalizacion (agregar los intereses al capital para generar mas intereses).
           - En la **tasa efectiva** si se toma en cuenta la capitalizacion (mediante el interes compuesto), generalmente la tasa efectiva tendera a ser mayor que la nominal.
           - La tasa nominal se denomina TIN, y la tasa efectiva se denomina TAE.
           - Ejemplo:
              Capital inicial = 10.000
              Tasa anual = 12%
              Capitalizacion = mensual.
              Comparación:
              Sin capitalización, el interés fue de $1,200.
              Con capitalización mensual, el interés fue de $1,268.25.
       
     - Tasas equivalentes

           - Dos tasas son equivalentes si producen el mismo resultado financiero al final de un periodo determinado.
           - Por ejemplo una tasa a corto plazo puede ser equivalente a una de largo plazo.
           - Es importante esto porque permite transformar una tasa a otra.
           - Formula : (1 + Tasa a convertir)^n = (1 + Tasa equivalente)
              La "tasa a convertir" es la tasa que ya conocemos.
              "n" es el número de periodos por el cual la tasa se aplicará (por ejemplo, si queremos pasar de mensual a anual, n=12).
              La "tasa equivalente" es la tasa que buscamos.

     - Descuento comercial y bancario

   **Importancia**: La aritmética financiera es esencial en la toma de decisiones de inversión y financiamiento. Comprender los conceptos de interés y valor temporal del dinero es fundamental en finanzas.

   **Lo que podrás hacer**: Una vez que domines la aritmética financiera, podrás evaluar inversiones, calcular préstamos, determinar el valor presente de flujos de efectivo y tomar decisiones financieras sólidas.

   **Proyectos sugeridos**:
   1. Calcular el rendimiento de una inversión a través de la fórmula del valor presente neto.
   2. Analizar la viabilidad financiera de un proyecto utilizando el método de tasa interna de retorno.
   3. Estimar el costo total de un préstamo con interés compuesto.
   4. Evaluar diferentes opciones de financiamiento para un proyecto empresarial.
   5. Determinar la tasa de descuento adecuada para un proyecto de inversión.


