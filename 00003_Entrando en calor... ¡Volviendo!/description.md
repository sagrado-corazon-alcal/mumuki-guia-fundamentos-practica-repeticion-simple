En la guía anterior, vimos que se podía usar `repeat` para hacer algo muchas veces. Hicimos un ejemplo que se llamaba `Diagonal4Azul`, que era más o menos así:

```puppet
procedure Diagonal4Azul(){
    repeat(4){
        Poner(Azul)
        Mover(Este)
        Mover(Norte)
    }
}
```

¿Te animás a definir el procedimiento `Diagonal4AzulVolviendo`? Este procedimiento debería _hacer lo mismo_ que `Diagonal4Azul`, pero tiene que dejar el cabezal **en la posición inicial**.

**¡Ojo!** No vale volver a escribir el código que ya escribiste en la guía pasada. ¡No hay que repetir código!
Entonces, podés usar `Diagonal4Azul()` sin definirlo. :wink:
