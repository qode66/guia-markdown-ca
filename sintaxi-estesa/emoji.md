# Emoji

Hi ha dues maneres d'afegir emoji als fitxers Markdown: copiar i enganxar l'emoji en el text formatat per Markdown, o escriure _codis curts emoji_.

## Copiar i enganxar emoji

En la majoria dels casos, simplement podeu copiar un emoji des d'una font com [Emojipedia](https://emojipedia.org/) i enganxar-lo al document. Moltes aplicacions Markdown mostraran automàticament els emojis en el text formatat amb Markdown. Els fitxers HTML i PDF que exporteu des de la vostra aplicació Markdown haurien de mostrar els emojis.

> **Consell:** Si esteu utilitzant un generador de llocs estàtic, assegureu-vos que [codifica pàgines HTML com UTF-8.](https://www.w3.org/International/tutorials/tutorial-char-enc)

## Utilitzant codis de substitució Emoji

Algunes aplicacions Markdown permeten inserir emoji escrivint codis de substitució emoji. Aquests comencen i acaben amb dos punts i inclouen el nom d'un emoji.

```text
Ha marxat acampada! :tent: Torna aviat.

Això és tan divertit! :joy:
```

La sortida renderitzada es veu així:

Ha marxat acampada! ⛺ Torna aviat.

Això és tan divertit! 😂

> **Nota:** Podeu utilitzar aquesta [llista de codis curts d'emojis](https://gist.github.com/rxaviers/7360908"), però recordeu que els codis curts d'emojis varien d'aplicació a aplicació. Consulteu la documentació de la vostra aplicació Markdown per a més informació.

## Vegeu també

[Guia Markdown](../README.md)
