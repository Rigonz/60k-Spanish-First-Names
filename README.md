# 60k-Spanish-Names
60k Spanish Names Scraped from 12 Sources

## Presentation
The csv file includes over 60,000 names (antroponyms, first names) extracted from 12 sources of Spanish names.

Accents and duplicated names have been removed, while variants are not considered duplicates (f.eg. Manuel, Manu and Manolo are included as different entries).

The names included in the list are not necessarily of "Spanish origin" (Mohamed and Manuel or Yusuf and José are included): I am not making guesses on the degree of spaniardship, and if a name has been included in any of the repositories that I have used, that is enough for me.

The sources are mostly from Spain, but two large Argentinian repositories are also used.

It is not intended to be an exhaustive list of first names, but definitely it is a large enough database.

## Languages
These repositories include names in Spanish, Catalan, Galician and Vasque.

## Core Sources
The core sources are the following:
1.  https://www.ine.es/daco/daco42/nombyapel/nombres_por_edad_media.xls (Spanish names)
2.  http://www.idescat.cat/nadons/?lang=es for the years 1997, 2005 and 2019 (Catalan and Spanish names)
3.  https://www.abc.es/sociedad/abci-nombres-mas-raros-espana-entre-extincion-y-particular-201906191111_noticia.html (Spanish names)
4.  https://ca.wiktionary.org/wiki/Viccionari:Llista_de_noms_propis_en_catal%C3%A0 (Catalan names)
5.  http://justicia.gencat.cat/.content/tramits/noms/LlistatNoms.xml (Catalan and Spanish names)
6.  https://www.euroresidentes.com/significado-nombre/nombres-catalanes.htm (Catalan and Spanish names)
7.  https://www.eldiario.es/nidos/nombres_1_2922962.html (Spanish names)
8.  https://es.wikipedia.org/wiki/Categor%C3%ADa:Nombres_femeninos and https://es.wikipedia.org/wiki/Categor%C3%ADa:Nombres_masculinos (Spanish names)
9.  https://gl.wikipedia.org/wiki/Lista_de_nomes_femininos_en_galego and https://gl.wikipedia.org/wiki/Lista_de_nomes_masculinos_en_galego (Galician names)
10. https://es.wikipedia.org/wiki/Antroponimia_vasca (Vasque names)
11. http://www.chubut.gov.ar/apps/nombres/ (Spanish names)
12. https://www.scribd.com/doc/252875842/Listado-de-Nombres-Permitidos (Spanish names)

## Auxililary Sources
21. https://datos.gob.ar/dataset/otros-nombres-personas-fisicas/archivo/otros_2.1 includes over 9 million first names from Argentina. I have tried to use it but the data is often corrupted and most names are multiply composed (f.eg. "Silvana Tomasa Filomena" or "Claudio Ruben Gervasio"). A drastic cleaning still includes almost 3 million different names, which are presented as file "02 Names R1 ARG3.csv". Splitting them into single names and adding them to the main repository is a possibility.

## Fields
The records in the csv file have two fields: the name and the source (a list with the numeric codes used in the previous section).

## Encoding
Data is UTF-8.
