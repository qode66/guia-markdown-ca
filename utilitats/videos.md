## Vídeos

Si la vostra aplicació Markdown admet [HTML](../sintaxi-basica/html.md), hauríeu de poder incrustar un vídeo al fitxer Markdown copiant i enganxant el codi HTML proporcionat per un lloc web de vídeos com YouTube o Vimeo. Si la vostra aplicació Markdown no admet HTML, no podeu incrustar un vídeo, però podeu acostar-vos afegint una [imatge](../sintaxi-basica/imatges.md) i un enllaç al vídeo. Podeu fer-ho amb pràcticament qualsevol vídeo de qualsevol servei de vídeo.

Com que YouTube ho facilita, els farem servir com a exemple. Preneu aquest vídeo, per exemple: `https://www.youtube.com/watch?v=8q2IjQOzVpE`. L'última part de l'URL (`8q2IjQOzVpE`) és l'identificador del vídeo. Podem agafar aquest DNI i posar-lo a la plantilla següent:

```prova
[![Text alternatiu de la imatge](https://img.youtube.com/vi/YOUTUBE-ID/0.jpg)](https://www.youtube.com/watch?v=YOUTUBE-ID)
```

YouTube genera automàticament una imatge per a cada vídeo (`https://img.youtube.com/vi/YOUTUBE-ID/0.jpg`), de manera que podem utilitzar-la i [enllaçar la imatge](../sintaxi-basica/imatges.md) al vídeo a YouTube. Després de substituir el text alternatiu de la imatge i afegir l'ID del vídeo, el nostre exemple és el següent en markdown:

```markdown
[![Less Than Jake — Scott Farcas ho pren a la barbeta](https://img.youtube.com/vi/PYCxct2e0zI/0.jpg)](https://www.youtube.com/watch?v= PYCxct2e0zI)
```

i en HTML:

```html
<a href="https://www.youtube.com/watch?v=PYCxct2e0zI" rel="nofollow"
  ><img
    src="https://img.youtube.com/vi/PYCxct2e0zI/0.jpg"
    width="480"
    height="360"
    alt="Menys que Jake — Scott Farcas s'ho porta a la barbeta"
/></a>
```

La sortida renderitzada té aquest aspecte:

<a href="https://www.youtube.com/watch?v=PYCxct2e0zI" rel="nofollow"><img src="https://img.youtube.com/vi/PYCxct2e0zI/0.jpg" width="480" height="360" alt="Menys que Jake — Scott Farcas s'ho porta a la barbeta"></a>

## Vegeu també

[HTML](../sintaxi-basica/html.md)  
[imatge](../sintaxi-basica/imatges.md)  
[enllaçar la imatge](../sintaxi-basica/imatges.md)

[Guia Markdown](../README.md)
