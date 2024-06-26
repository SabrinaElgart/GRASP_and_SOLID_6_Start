Se modifica la clase *Recipe* para aplicar el patrón *ADAPTER*. 

En la clase Recipe se agregan los siguiente métodos:
Método *GetCookTime()*, el cual me retorna el tiempo de los pasos de la receta.
Método *StartCountdown()*, el cual comienza el conteo.
Método *Cook()*, el cual me sirve para para decirle al timer que comience el conteo 
Se crea la clase *TimerAdapter* usando el patrón *ADAPTER*. Defino una clase anidada llamada TimerAdapter que implementa la interfaz TimerClient,acá se ve claramente el uso de dicho patrón, ya que TimerAdapter permite a la clase Recipe interactúe con otra clase o interfaz que no inicialmente no funcionaría sin el uso del patrón. En este caso la clase TimerAdaprter perimite que la clase Recipe interactúe con CountdownTimer.



