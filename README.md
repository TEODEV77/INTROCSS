# Intro CSS

Lenguaje de hojas de estilo utilizado para aplicar estilos y diseños a documentos HTML.

Permite definir cómo se verán los elementos en una página web.

# Selectores

## Selector de tipo

```
 p {

 }
```
### Se utilizan para seleccionar elementos HTML basados en el nombre de su etiqueta. 

## Selector de clase

```
 .class {

 }

 .button {

 }

 .layout {

 }
```

### Los selectores de clase seleccionan elementos que tienen un atributo de clase específico. Se denotan por un punto antes del nombre de la clase.

## Selector de ID

```
 #header {

 }

 #nav {

 }

 #test {

 }
```


### Los selectores de ID seleccionan un elemento con un atributo de ID único. Se denotan por un signo de almohadilla antes del nombre del ID. El ID debe ser único


## Selector de atributo

```
 a[href^="https"]  {
    => Reglas de estilo para todos los elementos <a> que tengan un atributo "href" que comience con "https"
 }
```

# Combinadores

## Selector de grupo

```
 h1, h2 {
    => Reglas de estilo para los elementos <h1>, <h2>
 }
```

### Permite seleccionar varios elementos a los que se aplicarán las mismas reglas.

## Selector descendente

```
 ul li {
    => Reglas de estilo para todos los elementos li que estén dentro de ul
 }

 ol li {
    => Reglas de estilo para todos los elementos li que estén dentro de ol
 }
```

### Los selectores descendentes se utilizan para seleccionar elementos secundarios dentro de un elemento principal.

## Selector descendente directo

```
 div > p {
    => Reglas de estilo para todos los elementos <p> que son descendientes directos de un elemento <div>
 }
```

### Seleccionan elementos secundarios que son directamente descendientes de un elemento principal
