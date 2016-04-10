Viendo lo útil que resulta tener un procedimiento que ponga todas las bolitas de un color que queramos, siguiendo la misma idea de _reutilización_, vamos a crear un procedimiento que **mueva todas las veces que queramos el cabezal**. Además de un número, vamos a necesitar la dirección en la cual querremos movernos.

> Creá un procedimiento `MoverN(cantidad,direccion)` que haga que el cabezal se desplace la cantidad especificada de veces en la dirección indicada.

La idea es poder usarlo desde un program así:

```gbs
program{
  MoverN(3,Oeste)
}
```