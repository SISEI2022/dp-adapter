# Adapter - Caso práctico

### Intención

Convierte una interface de una clase en otra interface que espera el Cliente. *Adapter* posibilita que clases puedan trabajar en conjunto a pesar de su incompatibilidad de interfaces.

### Clasificación

Patrón estructural

### Vista Estructural

![image](https://user-images.githubusercontent.com/55771796/173479309-143a9915-8192-4406-a501-f9da67bd72cc.png)

### Vista Dinámica

![image](https://user-images.githubusercontent.com/55771796/173479362-40ae317d-b874-4912-9aef-6fd2961c70bd.png)

### Ejemplo Real

Mediante la implementación del patrón de diseño Adapter crearemos un adaptador que nos permite interactuar de forma homogénea entre dos API bancarías, las cuales nos permite aprobar créditos personales, sin embargo, las dos API proporcionadas por los bancos cuenta con interfaces diferentes y aunque su funcionamiento es prácticamente igual, las interfaces expuestas son diferentes, lo que implica tener dos implementaciones diferentes para procesar los préstamos con cada banco. Mediante este patrón crearemos un adaptador que permitirá ocultar la complejidad de cada implementación del API, exponiendo una única interface compatible con las dos API proporcionadas, además que dejáramos el camino preparado por si el día de mañana llegara una nueva API bancaria.

![image](https://user-images.githubusercontent.com/55771796/173479431-ed9b40f8-f430-4e83-94fb-3e28b4bc19d7.png)

![image](https://user-images.githubusercontent.com/55771796/174155533-0c59a458-a1b0-4a9c-a8f2-4e4f01a76d0e.png)

### Ejecucion

```
gradle run
```
