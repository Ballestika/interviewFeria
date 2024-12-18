# interviewFeria

## Ejercicio: Contador de Tiempo

Escribe una función llamada `contadorDeTiempo` que reciba un número de segundos y muestre en la consola un contador regresivo de segundos, desde el número dado hasta 0.

### Requisitos:

1. La función debe recibir un número entero de segundos como argumento.
2. Debes usar `setInterval` para actualizar el contador cada segundo.
3. El `setInterval` debe ser detenido usando `clearInterval` cuando el contador llegue a 0.
4. El contador debe ser mostrado en la consola cada vez que se actualiza.
5. Cuando el contador llegue a 0, debe mostrar el mensaje `"Tiempo agotado!"` en la consola.

### Ejemplo de uso:

Si llamas a la función con `contadorDeTiempo(5)`, el resultado esperado sería algo así:

```javascript
5  
4  
3  
2  
1  
Tiempo agotado!
```
