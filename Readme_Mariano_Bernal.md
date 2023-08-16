# Readme - Proyecto Integrador 1 


<p align=center><img src=https://d31uz8lwfmyn8g.cloudfront.net/Assets/logo-henry-white-lg.png><p>

# <h1 align=center> **PROYECTO INDIVIDUAL Nº2** </h1>

# <h1 align=center>**`DATA ANALYTICS - CRYPTOCURRENCY MARKET`**</h1>

##  <h2 align=center>**Mariano Bernal / Data Science FT - 13**

<p align="center">
<img src="https://github.com/marianobernal/PI_DA_Mariano_Bernal/blob/master/Archivos/Criptos.jpg?raw=true"  height=300>
</p>

A continuación les compartiré un breve resumen de los principales puntos que se fueron trabajando en el proyecto.  

<hr>  

# **Descripción del problema**

## Rol a desarrollar

Me sitúo en el puesto de Analista de Datos en una empresa de servicios financieros que se ha interesado en el mercado de criptomonedas debido a su crecimiento exponencial y el potencial de oportunidades de inversión para los clientes.  

El objetivos es realizar un análisis exhaustivo utilizando datos de la API CoinGecko para entender mejor el mercado de criptomonedas y presentar tus hallazgos y recomendaciones en un informe detallado.
<hr> 

# **Introducción a las criptomonedas**
  
Las criptomonedas son monedas digitales que utilizan la criptografía (La criptografía es el estudio y la práctica de técnicas para asegurar la comunicación y proteger la información de terceros no autorizados) para asegurar y verificar transacciones, así como para controlar la creación de nuevas unidades.   

A diferencia de las monedas tradicionales emitidas por gobiernos (conocidas como monedas fiduciarias), las criptomonedas operan en redes descentralizadas basadas en tecnología de cadena de bloques (blockchain). La cadena de bloques es un registro público y seguro de todas las transacciones realizadas con una criptomoneda en particular. <br><br>
La importancia de las criptomonedas en la actualidad radica en varios factores: <br>
+ Descentralización: Las criptomonedas funcionan en redes descentralizadas, lo que significa que no están controladas por una entidad central como un gobierno o un banco.<br><br>
+ Transferencias Globales: Las criptomonedas permiten transferencias de valor rápidas y globales sin necesidad de intermediarios bancarios o costosas tarifas de conversión de divisas. <br><br>
+ Seguridad: La tecnología de cadena de bloques proporciona un alto nivel de seguridad y transparencia.<br><br>
+ Innovación Tecnológica: Las criptomonedas han impulsado el desarrollo de tecnologías emergentes, como contratos inteligentes y aplicaciones descentralizadas (dApps), que tienen el potencial de revolucionar diversas industrias.<br><br>
+ Inversión y Rentabilidad: Algunas criptomonedas han experimentado un aumento significativo en su valor a lo largo del tiempo.<br><br>
+ Reserva de Valor y Cobertura: Algunos consideran ciertas criptomonedas, como Bitcoin, como una forma de reserva de valor similar al oro. En tiempos de incertidumbre económica, las personas pueden recurrir a las criptomonedas como cobertura contra la inflación y la devaluación de las monedas fiduciarias.<br>

En resumen, las criptomonedas han capturado la atención de personas de todo el mundo debido a su capacidad para transformar las finanzas y la tecnología. Aunque también han generado controversia y desafíos regulatorios, su influencia en la economía global y la innovación tecnológica continúa creciendo.  
<br>

## BLOCKCHAIN 


El blockchain es una tecnología descentralizada de registro distribuido que se ha destacado por su seguridad, transparencia y capacidad para garantizar la integridad de los datos. Sus principales características son:<br>
+ Estructura de Bloques: Es una cadena de bloques interconectados. Cada bloque contiene un conjunto de datos y un sello de tiempo. Los bloques están enlazados en orden cronológico y contienen un hash (un valor alfanumérico único) del bloque anterior.<br>
+ Decentralización: Esto significa que la información se almacena en múltiples nodos de una red distribuida, y cada nodo tiene una copia idéntica del blockchain completo.<br>
+ Consenso: Para agregar un nuevo bloque al blockchain, la red debe llegar a un consenso sobre su validez. En blockchain públicos como Bitcoin y Ethereum, se utiliza el mecanismo de Prueba de Trabajo (PoW) o Prueba de Participación (PoS) para validar las transacciones y agregar nuevos bloques. <br>
+ Inmutabilidad: Una vez que se agrega un bloque al blockchain, no se puede modificar ni eliminar sin afectar a todos los bloques posteriores. Esto crea una característica de inmutabilidad que protege contra la manipulación de datos y garantiza la integridad de la información.<br>
+ Transparencia: Cualquier transacción registrada en el blockchain es visible para todos los participantes.<br>
+ Seguridad Criptográfica: La información en el blockchain está protegida mediante técnicas de criptografía avanzada. Cada bloque contiene un hash que depende del contenido del bloque y del hash del bloque anterior. Esto crea un enlace seguro entre los bloques y dificulta la alteración de la cadena. <br>

+ Aplicaciones de Contratos Inteligentes: Algunas implementaciones de blockchain, como Ethereum, permiten la ejecución de contratos inteligentes. Estos son programas autónomos que se ejecutan automáticamente cuando se cumplen ciertas condiciones predefinidas.

<p align="center">
<img src="https://github.com/marianobernal/PI_DA_Mariano_Bernal/blob/master/Archivos/Blockchain.png?raw=true"  height=300>
</p>

[Link Video Explicativo](https://www.youtube.com/watch?v=V9Kr2SujqHw)
<br>

## Generación de Criptomonedas

Las criptomonedas se generan a través de un proceso llamado "minería" en el caso de las criptomonedas basadas en Prueba de Trabajo (PoW), y a través de "validación" en el caso de las criptomonedas basadas en Prueba de Participación (PoS). Ahora bien, ¿Cómo funcionan?<br>
+ Minería (Prueba de Trabajo - PoW): En este método, los mineros utilizan poderosas computadoras para resolver complejos problemas matemáticos. Cuando un minero resuelve el problema, se le permite agregar un nuevo bloque a la cadena de bloques y se le recompensa con una cierta cantidad de la criptomoneda como recompensa. Ejemplos de criptomonedas PoW incluyen Bitcoin y Litecoin.

+ Validación (Prueba de Participación - PoS): En lugar de competir por resolver problemas matemáticos, en PoS, los validadores (stakers) poseen y bloquean una cierta cantidad de la criptomoneda en la red como garantía. La probabilidad de que un validador sea seleccionado para crear un nuevo bloque se basa en la cantidad de criptomoneda que han bloqueado y, a veces, en otros factores como el tiempo durante el cual han mantenido sus monedas bloqueadas. Los validadores son recompensados con tarifas de transacción y, a veces, con nuevas monedas. Ejemplos de criptomonedas PoS incluyen Ethereum 2.0 (que está en proceso de cambio de PoW a PoS) y Cardano.<br>
+ Recompensas y Emisión: Cuando se genera un nuevo bloque (ya sea a través de minería, validación u otro método), se pueden generar nuevas unidades de la criptomoneda. Estas nuevas unidades se utilizan para recompensar a los mineros o validadores por su trabajo y para aumentar la oferta total de la criptomoneda en circulación. <br>
<br>

## Bitcoin - Halving

Como bien sabemos, Bitcoin es ampliamente considerado como el líder del mercado en el espacio de las criptomonedas. Fue la primera criptomoneda en ser creada y lanzada en 2009 por una persona o grupo bajo el seudónimo de Satoshi Nakamoto. Desde entonces, Bitcoin ha mantenido su posición como la criptomoneda más reconocida, valiosa y ampliamente adoptada en el mundo. <br>

Además Bitcoin tiene la capitalización de mercado más grande entre todas las criptomonedas, un alto nivel de liquidez y tiene uno de los mayores volúmenes de negociación diarios en comparación con otras criptomonedas.<br>

Por otro lado, Bitcoin ha demostrado ser resistente y seguro a lo largo del tiempo. Su red blockchain ha estado operativa de manera continua desde su creación, lo que ha aumentado la confianza en su tecnología.<br>

Una última particularidad y que tiene además gran influencia en el precio de Bitcoin es lo que se conoce como **Halving**. El "halving" es un evento programado en algunas criptomonedas, que reduce a la mitad la recompensa que reciben los mineros por validar y confirmar transacciones en la red. Está diseñado para controlar la tasa de emisión de nuevas monedas y, en última instancia, limitar la oferta total de la criptomoneda. **Este ha sido un factor importante en la percepción de Bitcoin como reserva de valor**, el último fue en 2020 y el próximo se espera para el 2024.
<p align="center">
<img src="https://github.com/marianobernal/PI_DA_Mariano_Bernal/blob/master/Archivos/Halvings.jpg?raw=true"  height=300>
</p>

<hr> 

# **Trading y Principales Métricas**
Como se sabe, el mercado de las criptomonedas si bien ha tenido una tendencia alcista desde que surguió, cuenta con una volatilidad muy elevada en los precios de sus activos. <br>

Por esto, es muy importante que conozcamos algunos de los indicadores que se utilizar para analizar posibles compras y ventas y sobre todo que definamos/propongamos una estrategia a seguir.
<br>

## Algunas Métricas / KPIs
 
En este apartado analizaremos algunas de las métricas/KPIs que consideramos más útiles a la hora de invertir en criptomonedas. <br>
Las estrategias de trading utilizan indicadores técnicos y análisis de datos históricos para tomar decisiones sobre cuándo comprar o vender. Vamos a conocer el RSI y las medias móviles simples de 5, 10 y 200 días.

+ RSI (Relative Strength Index): El RSI es un indicador de impulso que mide la velocidad y el cambio de los movimientos de precios. Su valor oscila entre 0 y 100, y se utiliza para evaluar si un activo está sobrecomprado (RSI alto) o sobrevendido (RSI bajo). La estrategia de RSI implica: 
    + RSI Alto (Sobrecompra): Cuando el RSI está por encima de cierto umbral, como 70, se considera que el activo está sobrecomprado. Esto podría indicar que es un buen momento para considerar la venta, ya que el precio podría corregirse a la baja.

    + RSI Bajo (Sobrevendido): Cuando el RSI cae por debajo de un umbral, como 30, se considera que el activo está sobrevendido. Esto podría sugerir una oportunidad de compra, ya que el precio podría corregirse al alza.
<p align="center">
<img src="https://github.com/marianobernal/PI_DA_Mariano_Bernal/blob/master/Archivos/RSI.png?raw=true"  height=200>
</p>

+ Medias Móviles Simples (SMA) de 5, 10 y 200 días: Las medias móviles son indicadores que suavizan los movimientos de precios y ayudan a identificar tendencias a lo largo del tiempo. Las medias móviles simples se calculan tomando el promedio de los precios de cierre durante un período específico. La estrategia de medias móviles implica:
    + Cruce de Medias Móviles: Un cruce alcista de una SMA más corta (como la de 5 días) sobre una SMA más larga (como la de 10 días) puede considerarse una señal de compra. Por otro lado, un cruce bajista (SMA más corta cruzando por debajo de la SMA más larga) puede considerarse una señal de venta.

    + Confirmación de Tendencia: Las medias móviles también se utilizan para confirmar la dirección de la tendencia. Cuando el precio está por encima de una SMA de 200 días, se considera una tendencia alcista a largo plazo. Si está por debajo, se considera una tendencia bajista.

Es importante ajustar los períodos de las medias móviles según la volatilidad del activo y el horizonte de tiempo de trading.
<p align="center">
<img src="https://github.com/marianobernal/PI_DA_Mariano_Bernal/blob/master/Archivos/Medias%20M%C3%B3viles2.png?raw=true"  height=200>
</p>

Es importante tener en cuenta que estos indicadores son herramientas de análisis técnico y puede proporcionar señales falsas en ciertas condiciones del mercado. Por eso para reducir estos riesgos es importante combinar el análisis con varios indicadores.

# **Dashboard y Propuesta**
Para facilitar el conocimiento del negocio, brindar herramientas para la toma de decisiones y conocer posibles resultados de inversión hemos realizado un Dashboard en Power Bi  <br>

En el mismo, además de tener información para monitorear la evolución de métricas y kpis, hemos sumado un escenario donde evaluamos resultados de inversiones teóricas puras con RSI en base a información histórica recopilada.
<br>

## Estrategia RSI Pura
 


## **Enlaces útiles**

**`EDA`**: https://github.com/marianobernal/PI_DA_Mariano_Bernal/blob/master/EDA.ipynb 

**`Repositorio`**: https://github.com/marianobernal/PI_DA_Mariano_Bernal 

**`Dashboard PBI`**: https://github.com/marianobernal/PI_DA_Mariano_Bernal/blob/master/Archivos/DA_Mariano_Bernal.pbix 



