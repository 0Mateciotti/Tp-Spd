## Integrantes
- Matias Díaz
- Mateo Ciotti
- Franco Beltrán



## Proyecto


<img src="https://github.com/0Mateciotti/Tp-Spd/blob/main/tp%20Spd/imgs/sd.PNG" width="800"/>

## Descrpcion
Este programa enciende y apaga las luces de un semaforo con sus respectivos tiempo junto con un buzzer que serviria para gente con problemas de vista


## Funcion principal

~~~ C (lenguaje en el que esta escrito)
{
  void setup(){
  for(int i = 11; i <= 13; i++){
    
    pinMode(i, OUTPUT);
  }
  Serial.begin(9600);
}

void loop(){ 
  Serial.println(contador);
  prenderSemaforo(contador);
  contador++;
  
  if(contador > 2){
     contador = 0;
  }
}
}
~~~

## Links
-[ThinkerCad](https://www.tinkercad.com/things/cH9t92RmDnx?sharecode=_xB3hVR3bOvmrNtJ6t6uiYLAo18Vzqapgx48E0AKl6A)
