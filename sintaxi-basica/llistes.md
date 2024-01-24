## Llistes

Podeu organitzar els elements en llistes ordenades i desordenades.

[Llistes ordenades](./llistes-ordenades.md)  
[Llistes no ordenades](./llistes-no-ordenades.md)

### Afegint elements a les llistes

[Paràgrafs](#paràgrafs)  
[Bloc de cites](#cites-de-bloc)  
[Imatges](#imatges)  
[Llistes](#llistes)

Per afegir un altre element a una llista tot preservant la continuïtat de la llista, sagneu l'element quatre espais o una pestanya, tal com es mostra als exemples següents.

> <strong>Consell:</strong> si les coses no es veuen com espereu, comproveu que hàgiu sagnat els elements de la llista quatre espais o una pestanya.

#### Paràgrafs

```
* Aquest és el primer element de la llista.
* Aquí teniu el segon element de la llista.

     He d'afegir un altre paràgraf a sota del segon element de la llista.

* I aquí teniu el tercer element de la llista.
```

La sortida renderitzada té aquest aspecte:

- Aquest és el primer element de la llista.
- Aquí teniu el segon element de la llista.

  He d'afegir un altre paràgraf a sota del segon element de la llista.

- I aquí teniu el tercer element de la llista.

#### Cites de bloc

```
* Aquest és el primer element de la llista.
* Aquí teniu el segon element de la llista.

     > Una cita de bloc es veuria bé a sota del segon element de la llista.

* I aquí teniu el tercer element de la llista.
```

La sortida renderitzada té aquest aspecte:

- Aquest és el primer element de la llista.
- Aquí teniu el segon element de la llista.

  > Una cita de bloc es veuria bé a sota del segon element de la llista.

- I aquí teniu el tercer element de la llista.

#### Blocs de codi

[Blocs de codi](#blocs-de-codi) normalment tenen quatre espais sagnats o una tabulació. Quan estiguin en una llista, sagneu-los vuit espais o dues tabuladors.

```
1. Obriu el fitxer.
2. Cerqueu el bloc de codi següent a la línia 21:

         <html>
           <head>
             <title>Prova</title>
           </head>

3. Actualitzeu el títol perquè coincideixi amb el nom del vostre lloc web.
```

La sortida renderitzada té aquest aspecte:

1. Obriu el fitxer.
2. Cerqueu el bloc de codi següent a la línia 21:

   ```text
   <html>
     <head>
       <title>Prova</title>
     </head>
   ```

3. Actualitzeu el títol perquè coincideixi amb el nom del vostre lloc web.

#### Imatges

```
1. Obriu el fitxer que conté la mascota de Linux.
2. Sorprèn la seva bellesa.

     ![Tux, la mascota de Linux](/assets/images/tux.png)

3. Tanqueu el fitxer.
```

La sortida renderitzada té aquest aspecte:

1. Obriu el fitxer que conté la mascota de Linux.
2. Sorprèn la seva bellesa.

   <img src="https://mdg.imgix.net/assets/images/tux.png" class="img-fluid" alt="Tux, la mascota de Linux" loading="lazy" sizes="100vw">

3. Tanqueu el fitxer.

#### Llistes

Podeu niar una llista no ordenada en una llista ordenada, o viceversa.

```
1. Primer element
2. Segon article
3. Tercer tema
     - Element sagnat
     - Element sagnat
4. Quart ítem
```

La sortida renderitzada té aquest aspecte:

1. Primer element
2. Segon article
3. Tercer tema
   - Element sagnat
   - Element sagnat
4. Quart ítem

## Vegeu també

[Llistes ordenades](./llistes-ordenades.md)  
[Llistes no ordenades](./llistes-no-ordenades.md)

[Guia Markdown](../README.md)
