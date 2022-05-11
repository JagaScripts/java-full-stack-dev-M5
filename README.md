# java-full-stack-dev-M5
Este repositorio corresponde a ejercicios realizados en la formación de Java Full Stack Developer, concretamente a la M5 - Introducción a las API REST

Capturas de pantalla de cada uno de los pasos.

<details>
  <summary>Descarga postman.</summary>
<br>
  <img src="https://github.com/JagaScripts/java-full-stack-dev-M5/blob/master/posmanDonwload.jpg">
 <br>
<p align="justify">Captura de la descarga.</p>
  </details>
<br>

<details>
  <summary>Instalacion postman.</summary>
<br>
  <img src="https://github.com/JagaScripts/java-full-stack-dev-M5/blob/master/postmantInstalado.jpg">
 <br>
<p align="justify">Captura de la descarga.</p>
  </details>
<br>

La API gratuita REST Countries (https://restcountries.com/) tiene configurados las URI para el GET de cada uno de los siguientes endpoints:

1. All countries.

<details>
  <summary>Captura all countries </summary>
<br>
  <img src="https://github.com/JagaScripts/java-full-stack-dev-M5/blob/master/all.jpg">
 <br>
  <p align="justify">JSON ALL.</p>

[JSON all](https://github.com/JagaScripts/java-full-stack-dev-M5/blob/master/all.json "JSON all")

  </details>
<br>

2. Nombre.

<details>
  <summary>Nombre </summary>
<br>
  <img src="https://github.com/JagaScripts/java-full-stack-dev-M5/blob/master/name.jpg">
 <br>
<p align="justify">JSON Name.</p>
  
 ``` js
[{"name":{"common":"Uruguay","official":"Oriental Republic of Uruguay","nativeName":{"spa":{"official":"República Oriental del Uruguay","common":"Uruguay"}}},"tld":[".uy"],"cca2":"UY","ccn3":"858","cca3":"URY","cioc":"URU","independent":true,"status":"officially-assigned","unMember":true,"currencies":{"UYU":{"name":"Uruguayan peso","symbol":"$"}},"idd":{"root":"+5","suffixes":["98"]},"capital":["Montevideo"],"altSpellings":["UY","Oriental Republic of Uruguay","República Oriental del Uruguay"],"region":"Americas","subregion":"South America","languages":{"spa":"Spanish"},"translations":{"ara":{"official":"جمهورية الأوروغواي الشرقية","common":"الأوروغواي"},"ces":{"official":"Uruguayská východní republika","common":"Uruguay"},"cym":{"official":"Oriental Republic of Uruguay","common":"Uruguay"},"deu":{"official":"Republik Östlich des Uruguay","common":"Uruguay"},"est":{"official":"Uruguay Idavabariik","common":"Uruguay"},"fin":{"official":"Uruguayn itäinen tasavalta","common":"Uruguay"},"fra":{"official":"République orientale de l'Uruguay","common":"Uruguay"},"hrv":{"official":"Orijentalna Republika Urugvaj","common":"Urugvaj"},"hun":{"official":"Uruguayi Keleti Köztársaság","common":"Uruguay"},"ita":{"official":"Repubblica Orientale dell'Uruguay","common":"Uruguay"},"jpn":{"official":"ウルグアイ東方共和国","common":"ウルグアイ"},"kor":{"official":"우루과이 동방 공화국","common":"우루과이"},"nld":{"official":"Oosterse Republiek Uruguay","common":"Uruguay"},"per":{"official":"جمهوری اروگوئه","common":"اروگوئه"},"pol":{"official":"Wschodnia Republika Urugwaju","common":"Urugwaj"},"por":{"official":"República Oriental do Uruguai","common":"Uruguai"},"rus":{"official":"Восточной Республики Уругвай","common":"Уругвай"},"slk":{"official":"Uruguajská východná republika","common":"Uruguaj"},"spa":{"official":"República Oriental del Uruguay","common":"Uruguay"},"swe":{"official":"Republiken Uruguay","common":"Uruguay"},"urd":{"official":"جمہوریہ شرقیہ یوراگوئے","common":"یوراگوئے"},"zho":{"official":"乌拉圭东岸共和国","common":"乌拉圭"}},"latlng":[-33.0,-56.0],"landlocked":false,"borders":["ARG","BRA"],"area":181034.0,"demonyms":{"eng":{"f":"Uruguayan","m":"Uruguayan"},"fra":{"f":"Uruguayenne","m":"Uruguayen"}},"flag":"\uD83C\uDDFA\uD83C\uDDFE","maps":{"googleMaps":"https://goo.gl/maps/tiQ9Baekb1jQtDSD9","openStreetMaps":"https://www.openstreetmap.org/relation/287072"},"population":3473727,"gini":{"2019":39.7},"fifa":"URU","car":{"signs":["ROU"],"side":"right"},"timezones":["UTC-03:00"],"continents":["South America"],"flags":{"png":"https://flagcdn.com/w320/uy.png","svg":"https://flagcdn.com/uy.svg"},"coatOfArms":{"png":"https://mainfacts.com/media/images/coats_of_arms/uy.png","svg":"https://mainfacts.com/media/images/coats_of_arms/uy.svg"},"startOfWeek":"monday","capitalInfo":{"latlng":[-34.85,-56.17]},"postalCode":{"format":"#####","regex":"^(\\d{5})$"}}]
```
[JSON Name](https://github.com/JagaScripts/java-full-stack-dev-M5/blob/master/name.json "JSON Name")

  </details>
<br>

3. Nombre.

<details>
  <summary>Nombre con full text true.</summary>
<br>
  <img src="https://github.com/JagaScripts/java-full-stack-dev-M5/blob/master/nameFullTextTrue.jpg">
 <br>
<p align="justify">JSON con full text true.</p>
  
 ``` js
[{"name":{"common":"Uruguay","official":"Oriental Republic of Uruguay","nativeName":{"spa":{"official":"República Oriental del Uruguay","common":"Uruguay"}}},"tld":[".uy"],"cca2":"UY","ccn3":"858","cca3":"URY","cioc":"URU","independent":true,"status":"officially-assigned","unMember":true,"currencies":{"UYU":{"name":"Uruguayan peso","symbol":"$"}},"idd":{"root":"+5","suffixes":["98"]},"capital":["Montevideo"],"altSpellings":["UY","Oriental Republic of Uruguay","República Oriental del Uruguay"],"region":"Americas","subregion":"South America","languages":{"spa":"Spanish"},"translations":{"ara":{"official":"جمهورية الأوروغواي الشرقية","common":"الأوروغواي"},"ces":{"official":"Uruguayská východní republika","common":"Uruguay"},"cym":{"official":"Oriental Republic of Uruguay","common":"Uruguay"},"deu":{"official":"Republik Östlich des Uruguay","common":"Uruguay"},"est":{"official":"Uruguay Idavabariik","common":"Uruguay"},"fin":{"official":"Uruguayn itäinen tasavalta","common":"Uruguay"},"fra":{"official":"République orientale de l'Uruguay","common":"Uruguay"},"hrv":{"official":"Orijentalna Republika Urugvaj","common":"Urugvaj"},"hun":{"official":"Uruguayi Keleti Köztársaság","common":"Uruguay"},"ita":{"official":"Repubblica Orientale dell'Uruguay","common":"Uruguay"},"jpn":{"official":"ウルグアイ東方共和国","common":"ウルグアイ"},"kor":{"official":"우루과이 동방 공화국","common":"우루과이"},"nld":{"official":"Oosterse Republiek Uruguay","common":"Uruguay"},"per":{"official":"جمهوری اروگوئه","common":"اروگوئه"},"pol":{"official":"Wschodnia Republika Urugwaju","common":"Urugwaj"},"por":{"official":"República Oriental do Uruguai","common":"Uruguai"},"rus":{"official":"Восточной Республики Уругвай","common":"Уругвай"},"slk":{"official":"Uruguajská východná republika","common":"Uruguaj"},"spa":{"official":"República Oriental del Uruguay","common":"Uruguay"},"swe":{"official":"Republiken Uruguay","common":"Uruguay"},"urd":{"official":"جمہوریہ شرقیہ یوراگوئے","common":"یوراگوئے"},"zho":{"official":"乌拉圭东岸共和国","common":"乌拉圭"}},"latlng":[-33.0,-56.0],"landlocked":false,"borders":["ARG","BRA"],"area":181034.0,"demonyms":{"eng":{"f":"Uruguayan","m":"Uruguayan"},"fra":{"f":"Uruguayenne","m":"Uruguayen"}},"flag":"\uD83C\uDDFA\uD83C\uDDFE","maps":{"googleMaps":"https://goo.gl/maps/tiQ9Baekb1jQtDSD9","openStreetMaps":"https://www.openstreetmap.org/relation/287072"},"population":3473727,"gini":{"2019":39.7},"fifa":"URU","car":{"signs":["ROU"],"side":"right"},"timezones":["UTC-03:00"],"continents":["South America"],"flags":{"png":"https://flagcdn.com/w320/uy.png","svg":"https://flagcdn.com/uy.svg"},"coatOfArms":{"png":"https://mainfacts.com/media/images/coats_of_arms/uy.png","svg":"https://mainfacts.com/media/images/coats_of_arms/uy.svg"},"startOfWeek":"monday","capitalInfo":{"latlng":[-34.85,-56.17]},"postalCode":{"format":"#####","regex":"^(\\d{5})$"}}]
```
[JSON Name con full text true](https://github.com/JagaScripts/java-full-stack-dev-M5/blob/master/namefull.json "JSON Name con full text true")

  </details>
<br>

4. Codigo.

<details>
  <summary>Codigo .</summary>
<br>
  <img src="https://github.com/JagaScripts/java-full-stack-dev-M5/blob/master/code.jpg">
 <br>
<p align="justify">JSON code.</p>
  
 ``` js
[{"name":{"common":"Paraguay","official":"Republic of Paraguay","nativeName":{"grn":{"official":"Tetã Paraguái","common":"Paraguái"},"spa":{"official":"República de Paraguay","common":"Paraguay"}}},"tld":[".py"],"cca2":"PY","ccn3":"600","cca3":"PRY","cioc":"PAR","independent":true,"status":"officially-assigned","unMember":true,"currencies":{"PYG":{"name":"Paraguayan guaraní","symbol":"₲"}},"idd":{"root":"+5","suffixes":["95"]},"capital":["Asunción"],"altSpellings":["PY","Republic of Paraguay","República del Paraguay","Tetã Paraguái"],"region":"Americas","subregion":"South America","languages":{"grn":"Guaraní","spa":"Spanish"},"translations":{"ara":{"official":"جمهورية باراغواي","common":"باراغواي"},"ces":{"official":"Paraguayská republika","common":"Paraguay"},"cym":{"official":"Republic of Paraguay","common":"Paraguay"},"deu":{"official":"Republik Paraguay","common":"Paraguay"},"est":{"official":"Paraguay Vabariik","common":"Paraguay"},"fin":{"official":"Paraguayn tasavalta","common":"Paraguay"},"fra":{"official":"République du Paraguay","common":"Paraguay"},"hrv":{"official":"Republika Paragvaj","common":"Paragvaj"},"hun":{"official":"Paraguayi Köztársaság","common":"Paraguay"},"ita":{"official":"Repubblica del Paraguay","common":"Paraguay"},"jpn":{"official":"パラグアイ共和国","common":"パラグアイ"},"kor":{"official":"파라과이 공화국","common":"파라과이"},"nld":{"official":"Republiek Paraguay","common":"Paraguay"},"per":{"official":"جمهوری پاراگوئه","common":"پاراگوئه"},"pol":{"official":"Republika Paragwaju","common":"Paragwaj"},"por":{"official":"República do Paraguai","common":"Paraguai"},"rus":{"official":"Республика Парагвай","common":"Парагвай"},"slk":{"official":"Paraguajská republika","common":"Paraguaj"},"spa":{"official":"República de Paraguay","common":"Paraguay"},"swe":{"official":"Republiken Paraguay","common":"Paraguay"},"urd":{"official":"جمہوریہ پیراگوئے","common":"پیراگوئے"},"zho":{"official":"巴拉圭共和国","common":"巴拉圭"}},"latlng":[-23.0,-58.0],"landlocked":true,"borders":["ARG","BOL","BRA"],"area":406752.0,"demonyms":{"eng":{"f":"Paraguayan","m":"Paraguayan"},"fra":{"f":"Paraguayenne","m":"Paraguayen"}},"flag":"\uD83C\uDDF5\uD83C\uDDFE","maps":{"googleMaps":"https://goo.gl/maps/JtnqG73WJn1Gx6mz6","openStreetMaps":"https://www.openstreetmap.org/relation/287077"},"population":7132530,"gini":{"2019":45.7},"fifa":"PAR","car":{"signs":["PY"],"side":"right"},"timezones":["UTC-04:00"],"continents":["South America"],"flags":{"png":"https://flagcdn.com/w320/py.png","svg":"https://flagcdn.com/py.svg"},"coatOfArms":{"png":"https://mainfacts.com/media/images/coats_of_arms/py.png","svg":"https://mainfacts.com/media/images/coats_of_arms/py.svg"},"startOfWeek":"monday","capitalInfo":{"latlng":[-25.28,-57.57]},"postalCode":{"format":"####","regex":"^(\\d{4})$"}}]
```
[JSON codigo](https://github.com/JagaScripts/java-full-stack-dev-M5/blob/master/code.json "JSON codigo")

  </details>
<br>

5. Codigos.

<details>
  <summary>Codigos.</summary>
<br>
  <img src="https://github.com/JagaScripts/java-full-stack-dev-M5/blob/master/codes.jpg">
 <br>
<p align="justify">JSON codes.</p>
  
 ``` js
[{"name":{"common":"Paraguay","official":"Republic of Paraguay","nativeName":{"grn":{"official":"Tetã Paraguái","common":"Paraguái"},"spa":{"official":"República de Paraguay","common":"Paraguay"}}},"tld":[".py"],"cca2":"PY","ccn3":"600","cca3":"PRY","cioc":"PAR","independent":true,"status":"officially-assigned","unMember":true,"currencies":{"PYG":{"name":"Paraguayan guaraní","symbol":"₲"}},"idd":{"root":"+5","suffixes":["95"]},"capital":["Asunción"],"altSpellings":["PY","Republic of Paraguay","República del Paraguay","Tetã Paraguái"],"region":"Americas","subregion":"South America","languages":{"grn":"Guaraní","spa":"Spanish"},"translations":{"ara":{"official":"جمهورية باراغواي","common":"باراغواي"},"ces":{"official":"Paraguayská republika","common":"Paraguay"},"cym":{"official":"Republic of Paraguay","common":"Paraguay"},"deu":{"official":"Republik Paraguay","common":"Paraguay"},"est":{"official":"Paraguay Vabariik","common":"Paraguay"},"fin":{"official":"Paraguayn tasavalta","common":"Paraguay"},"fra":{"official":"République du Paraguay","common":"Paraguay"},"hrv":{"official":"Republika Paragvaj","common":"Paragvaj"},"hun":{"official":"Paraguayi Köztársaság","common":"Paraguay"},"ita":{"official":"Repubblica del Paraguay","common":"Paraguay"},"jpn":{"official":"パラグアイ共和国","common":"パラグアイ"},"kor":{"official":"파라과이 공화국","common":"파라과이"},"nld":{"official":"Republiek Paraguay","common":"Paraguay"},"per":{"official":"جمهوری پاراگوئه","common":"پاراگوئه"},"pol":{"official":"Republika Paragwaju","common":"Paragwaj"},"por":{"official":"República do Paraguai","common":"Paraguai"},"rus":{"official":"Республика Парагвай","common":"Парагвай"},"slk":{"official":"Paraguajská republika","common":"Paraguaj"},"spa":{"official":"República de Paraguay","common":"Paraguay"},"swe":{"official":"Republiken Paraguay","common":"Paraguay"},"urd":{"official":"جمہوریہ پیراگوئے","common":"پیراگوئے"},"zho":{"official":"巴拉圭共和国","common":"巴拉圭"}},"latlng":[-23.0,-58.0],"landlocked":true,"borders":["ARG","BOL","BRA"],"area":406752.0,"demonyms":{"eng":{"f":"Paraguayan","m":"Paraguayan"},"fra":{"f":"Paraguayenne","m":"Paraguayen"}},"flag":"\uD83C\uDDF5\uD83C\uDDFE","maps":{"googleMaps":"https://goo.gl/maps/JtnqG73WJn1Gx6mz6","openStreetMaps":"https://www.openstreetmap.org/relation/287077"},"population":7132530,"gini":{"2019":45.7},"fifa":"PAR","car":{"signs":["PY"],"side":"right"},"timezones":["UTC-04:00"],"continents":["South America"],"flags":{"png":"https://flagcdn.com/w320/py.png","svg":"https://flagcdn.com/py.svg"},"coatOfArms":{"png":"https://mainfacts.com/media/images/coats_of_arms/py.png","svg":"https://mainfacts.com/media/images/coats_of_arms/py.svg"},"startOfWeek":"monday","capitalInfo":{"latlng":[-25.28,-57.57]},"postalCode":{"format":"####","regex":"^(\\d{4})$"}}]
```
[JSON Codigos](https://github.com/JagaScripts/java-full-stack-dev-M5/blob/master/codes.json "JSON Codigos")

  </details>
<br>
6. Currency.

<details>
  <summary>Currency .</summary>
<br>
  <img src="https://github.com/JagaScripts/java-full-stack-dev-M5/blob/master/currency.jpg">
 <br>
<p align="justify">JSON Currency.</p>
  
 ``` js
[{"name":{"common":"Paraguay","official":"Republic of Paraguay","nativeName":{"grn":{"official":"Tetã Paraguái","common":"Paraguái"},"spa":{"official":"República de Paraguay","common":"Paraguay"}}},"tld":[".py"],"cca2":"PY","ccn3":"600","cca3":"PRY","cioc":"PAR","independent":true,"status":"officially-assigned","unMember":true,"currencies":{"PYG":{"name":"Paraguayan guaraní","symbol":"₲"}},"idd":{"root":"+5","suffixes":["95"]},"capital":["Asunción"],"altSpellings":["PY","Republic of Paraguay","República del Paraguay","Tetã Paraguái"],"region":"Americas","subregion":"South America","languages":{"grn":"Guaraní","spa":"Spanish"},"translations":{"ara":{"official":"جمهورية باراغواي","common":"باراغواي"},"ces":{"official":"Paraguayská republika","common":"Paraguay"},"cym":{"official":"Republic of Paraguay","common":"Paraguay"},"deu":{"official":"Republik Paraguay","common":"Paraguay"},"est":{"official":"Paraguay Vabariik","common":"Paraguay"},"fin":{"official":"Paraguayn tasavalta","common":"Paraguay"},"fra":{"official":"République du Paraguay","common":"Paraguay"},"hrv":{"official":"Republika Paragvaj","common":"Paragvaj"},"hun":{"official":"Paraguayi Köztársaság","common":"Paraguay"},"ita":{"official":"Repubblica del Paraguay","common":"Paraguay"},"jpn":{"official":"パラグアイ共和国","common":"パラグアイ"},"kor":{"official":"파라과이 공화국","common":"파라과이"},"nld":{"official":"Republiek Paraguay","common":"Paraguay"},"per":{"official":"جمهوری پاراگوئه","common":"پاراگوئه"},"pol":{"official":"Republika Paragwaju","common":"Paragwaj"},"por":{"official":"República do Paraguai","common":"Paraguai"},"rus":{"official":"Республика Парагвай","common":"Парагвай"},"slk":{"official":"Paraguajská republika","common":"Paraguaj"},"spa":{"official":"República de Paraguay","common":"Paraguay"},"swe":{"official":"Republiken Paraguay","common":"Paraguay"},"urd":{"official":"جمہوریہ پیراگوئے","common":"پیراگوئے"},"zho":{"official":"巴拉圭共和国","common":"巴拉圭"}},"latlng":[-23.0,-58.0],"landlocked":true,"borders":["ARG","BOL","BRA"],"area":406752.0,"demonyms":{"eng":{"f":"Paraguayan","m":"Paraguayan"},"fra":{"f":"Paraguayenne","m":"Paraguayen"}},"flag":"\uD83C\uDDF5\uD83C\uDDFE","maps":{"googleMaps":"https://goo.gl/maps/JtnqG73WJn1Gx6mz6","openStreetMaps":"https://www.openstreetmap.org/relation/287077"},"population":7132530,"gini":{"2019":45.7},"fifa":"PAR","car":{"signs":["PY"],"side":"right"},"timezones":["UTC-04:00"],"continents":["South America"],"flags":{"png":"https://flagcdn.com/w320/py.png","svg":"https://flagcdn.com/py.svg"},"coatOfArms":{"png":"https://mainfacts.com/media/images/coats_of_arms/py.png","svg":"https://mainfacts.com/media/images/coats_of_arms/py.svg"},"startOfWeek":"monday","capitalInfo":{"latlng":[-25.28,-57.57]},"postalCode":{"format":"####","regex":"^(\\d{4})$"}}]
```
[JSON Currency](https://github.com/JagaScripts/java-full-stack-dev-M5/blob/master/currency.json "JSON Currency")

  </details>
<br>
{et} en la documentación no aparece lo que si se puede buscar es {lang}
7. Currency.

<details>
  <summary>Lenguaje .</summary>
<br>
  <img src="https://github.com/JagaScripts/java-full-stack-dev-M5/blob/master/lang.jpg">
 <br>
<p align="justify">JSON Lenguaje.</p>
  
 ``` js
# java-full-stack-dev-M5
Este repositorio corresponde a ejercicios realizados en la formación de Java Full Stack Developer, concretamente a la M5 - Introducción a las API REST

Capturas de pantalla de cada uno de los pasos.

<details>
  <summary>Descarga postman.</summary>
<br>
  <img src="https://github.com/JagaScripts/java-full-stack-dev-M5/blob/master/posmanDonwload.jpg">
 <br>
<p align="justify">Captura de la descarga.</p>
  </details>
<br>

<details>
  <summary>Instalacion postman.</summary>
<br>
  <img src="https://github.com/JagaScripts/java-full-stack-dev-M5/blob/master/postmantInstalado.jpg">
 <br>
<p align="justify">Captura de la descarga.</p>
  </details>
<br>

La API gratuita REST Countries (https://restcountries.com/) tiene configurados las URI para el GET de cada uno de los siguientes endpoints:

1. All countries.

<details>
  <summary>Captura all countries </summary>
<br>
  <img src="https://github.com/JagaScripts/java-full-stack-dev-M5/blob/master/all.jpg">
 <br>
  <p align="justify">JSON ALL.</p>

[JSON all](https://github.com/JagaScripts/java-full-stack-dev-M5/blob/master/all.json "JSON all")

  </details>
<br>

2. Nombre.

<details>
  <summary>Nombre </summary>
<br>
  <img src="https://github.com/JagaScripts/java-full-stack-dev-M5/blob/master/name.jpg">
 <br>
<p align="justify">JSON Name.</p>
  
 ``` js
[{"name":{"common":"Uruguay","official":"Oriental Republic of Uruguay","nativeName":{"spa":{"official":"República Oriental del Uruguay","common":"Uruguay"}}},"tld":[".uy"],"cca2":"UY","ccn3":"858","cca3":"URY","cioc":"URU","independent":true,"status":"officially-assigned","unMember":true,"currencies":{"UYU":{"name":"Uruguayan peso","symbol":"$"}},"idd":{"root":"+5","suffixes":["98"]},"capital":["Montevideo"],"altSpellings":["UY","Oriental Republic of Uruguay","República Oriental del Uruguay"],"region":"Americas","subregion":"South America","languages":{"spa":"Spanish"},"translations":{"ara":{"official":"جمهورية الأوروغواي الشرقية","common":"الأوروغواي"},"ces":{"official":"Uruguayská východní republika","common":"Uruguay"},"cym":{"official":"Oriental Republic of Uruguay","common":"Uruguay"},"deu":{"official":"Republik Östlich des Uruguay","common":"Uruguay"},"est":{"official":"Uruguay Idavabariik","common":"Uruguay"},"fin":{"official":"Uruguayn itäinen tasavalta","common":"Uruguay"},"fra":{"official":"République orientale de l'Uruguay","common":"Uruguay"},"hrv":{"official":"Orijentalna Republika Urugvaj","common":"Urugvaj"},"hun":{"official":"Uruguayi Keleti Köztársaság","common":"Uruguay"},"ita":{"official":"Repubblica Orientale dell'Uruguay","common":"Uruguay"},"jpn":{"official":"ウルグアイ東方共和国","common":"ウルグアイ"},"kor":{"official":"우루과이 동방 공화국","common":"우루과이"},"nld":{"official":"Oosterse Republiek Uruguay","common":"Uruguay"},"per":{"official":"جمهوری اروگوئه","common":"اروگوئه"},"pol":{"official":"Wschodnia Republika Urugwaju","common":"Urugwaj"},"por":{"official":"República Oriental do Uruguai","common":"Uruguai"},"rus":{"official":"Восточной Республики Уругвай","common":"Уругвай"},"slk":{"official":"Uruguajská východná republika","common":"Uruguaj"},"spa":{"official":"República Oriental del Uruguay","common":"Uruguay"},"swe":{"official":"Republiken Uruguay","common":"Uruguay"},"urd":{"official":"جمہوریہ شرقیہ یوراگوئے","common":"یوراگوئے"},"zho":{"official":"乌拉圭东岸共和国","common":"乌拉圭"}},"latlng":[-33.0,-56.0],"landlocked":false,"borders":["ARG","BRA"],"area":181034.0,"demonyms":{"eng":{"f":"Uruguayan","m":"Uruguayan"},"fra":{"f":"Uruguayenne","m":"Uruguayen"}},"flag":"\uD83C\uDDFA\uD83C\uDDFE","maps":{"googleMaps":"https://goo.gl/maps/tiQ9Baekb1jQtDSD9","openStreetMaps":"https://www.openstreetmap.org/relation/287072"},"population":3473727,"gini":{"2019":39.7},"fifa":"URU","car":{"signs":["ROU"],"side":"right"},"timezones":["UTC-03:00"],"continents":["South America"],"flags":{"png":"https://flagcdn.com/w320/uy.png","svg":"https://flagcdn.com/uy.svg"},"coatOfArms":{"png":"https://mainfacts.com/media/images/coats_of_arms/uy.png","svg":"https://mainfacts.com/media/images/coats_of_arms/uy.svg"},"startOfWeek":"monday","capitalInfo":{"latlng":[-34.85,-56.17]},"postalCode":{"format":"#####","regex":"^(\\d{5})$"}}]
```
[JSON Name](https://github.com/JagaScripts/java-full-stack-dev-M5/blob/master/name.json "JSON Name")

  </details>
<br>

3. Nombre.

<details>
  <summary>Nombre con full text true.</summary>
<br>
  <img src="https://github.com/JagaScripts/java-full-stack-dev-M5/blob/master/nameFullTextTrue.jpg">
 <br>
<p align="justify">JSON con full text true.</p>
  
 ``` js
[{"name":{"common":"Uruguay","official":"Oriental Republic of Uruguay","nativeName":{"spa":{"official":"República Oriental del Uruguay","common":"Uruguay"}}},"tld":[".uy"],"cca2":"UY","ccn3":"858","cca3":"URY","cioc":"URU","independent":true,"status":"officially-assigned","unMember":true,"currencies":{"UYU":{"name":"Uruguayan peso","symbol":"$"}},"idd":{"root":"+5","suffixes":["98"]},"capital":["Montevideo"],"altSpellings":["UY","Oriental Republic of Uruguay","República Oriental del Uruguay"],"region":"Americas","subregion":"South America","languages":{"spa":"Spanish"},"translations":{"ara":{"official":"جمهورية الأوروغواي الشرقية","common":"الأوروغواي"},"ces":{"official":"Uruguayská východní republika","common":"Uruguay"},"cym":{"official":"Oriental Republic of Uruguay","common":"Uruguay"},"deu":{"official":"Republik Östlich des Uruguay","common":"Uruguay"},"est":{"official":"Uruguay Idavabariik","common":"Uruguay"},"fin":{"official":"Uruguayn itäinen tasavalta","common":"Uruguay"},"fra":{"official":"République orientale de l'Uruguay","common":"Uruguay"},"hrv":{"official":"Orijentalna Republika Urugvaj","common":"Urugvaj"},"hun":{"official":"Uruguayi Keleti Köztársaság","common":"Uruguay"},"ita":{"official":"Repubblica Orientale dell'Uruguay","common":"Uruguay"},"jpn":{"official":"ウルグアイ東方共和国","common":"ウルグアイ"},"kor":{"official":"우루과이 동방 공화국","common":"우루과이"},"nld":{"official":"Oosterse Republiek Uruguay","common":"Uruguay"},"per":{"official":"جمهوری اروگوئه","common":"اروگوئه"},"pol":{"official":"Wschodnia Republika Urugwaju","common":"Urugwaj"},"por":{"official":"República Oriental do Uruguai","common":"Uruguai"},"rus":{"official":"Восточной Республики Уругвай","common":"Уругвай"},"slk":{"official":"Uruguajská východná republika","common":"Uruguaj"},"spa":{"official":"República Oriental del Uruguay","common":"Uruguay"},"swe":{"official":"Republiken Uruguay","common":"Uruguay"},"urd":{"official":"جمہوریہ شرقیہ یوراگوئے","common":"یوراگوئے"},"zho":{"official":"乌拉圭东岸共和国","common":"乌拉圭"}},"latlng":[-33.0,-56.0],"landlocked":false,"borders":["ARG","BRA"],"area":181034.0,"demonyms":{"eng":{"f":"Uruguayan","m":"Uruguayan"},"fra":{"f":"Uruguayenne","m":"Uruguayen"}},"flag":"\uD83C\uDDFA\uD83C\uDDFE","maps":{"googleMaps":"https://goo.gl/maps/tiQ9Baekb1jQtDSD9","openStreetMaps":"https://www.openstreetmap.org/relation/287072"},"population":3473727,"gini":{"2019":39.7},"fifa":"URU","car":{"signs":["ROU"],"side":"right"},"timezones":["UTC-03:00"],"continents":["South America"],"flags":{"png":"https://flagcdn.com/w320/uy.png","svg":"https://flagcdn.com/uy.svg"},"coatOfArms":{"png":"https://mainfacts.com/media/images/coats_of_arms/uy.png","svg":"https://mainfacts.com/media/images/coats_of_arms/uy.svg"},"startOfWeek":"monday","capitalInfo":{"latlng":[-34.85,-56.17]},"postalCode":{"format":"#####","regex":"^(\\d{5})$"}}]
```
[JSON Name con full text true](https://github.com/JagaScripts/java-full-stack-dev-M5/blob/master/namefull.json "JSON Name con full text true")

  </details>
<br>

4. Codigo.

<details>
  <summary>Codigo .</summary>
<br>
  <img src="https://github.com/JagaScripts/java-full-stack-dev-M5/blob/master/code.jpg">
 <br>
<p align="justify">JSON code.</p>
  
 ``` js
[{"name":{"common":"Paraguay","official":"Republic of Paraguay","nativeName":{"grn":{"official":"Tetã Paraguái","common":"Paraguái"},"spa":{"official":"República de Paraguay","common":"Paraguay"}}},"tld":[".py"],"cca2":"PY","ccn3":"600","cca3":"PRY","cioc":"PAR","independent":true,"status":"officially-assigned","unMember":true,"currencies":{"PYG":{"name":"Paraguayan guaraní","symbol":"₲"}},"idd":{"root":"+5","suffixes":["95"]},"capital":["Asunción"],"altSpellings":["PY","Republic of Paraguay","República del Paraguay","Tetã Paraguái"],"region":"Americas","subregion":"South America","languages":{"grn":"Guaraní","spa":"Spanish"},"translations":{"ara":{"official":"جمهورية باراغواي","common":"باراغواي"},"ces":{"official":"Paraguayská republika","common":"Paraguay"},"cym":{"official":"Republic of Paraguay","common":"Paraguay"},"deu":{"official":"Republik Paraguay","common":"Paraguay"},"est":{"official":"Paraguay Vabariik","common":"Paraguay"},"fin":{"official":"Paraguayn tasavalta","common":"Paraguay"},"fra":{"official":"République du Paraguay","common":"Paraguay"},"hrv":{"official":"Republika Paragvaj","common":"Paragvaj"},"hun":{"official":"Paraguayi Köztársaság","common":"Paraguay"},"ita":{"official":"Repubblica del Paraguay","common":"Paraguay"},"jpn":{"official":"パラグアイ共和国","common":"パラグアイ"},"kor":{"official":"파라과이 공화국","common":"파라과이"},"nld":{"official":"Republiek Paraguay","common":"Paraguay"},"per":{"official":"جمهوری پاراگوئه","common":"پاراگوئه"},"pol":{"official":"Republika Paragwaju","common":"Paragwaj"},"por":{"official":"República do Paraguai","common":"Paraguai"},"rus":{"official":"Республика Парагвай","common":"Парагвай"},"slk":{"official":"Paraguajská republika","common":"Paraguaj"},"spa":{"official":"República de Paraguay","common":"Paraguay"},"swe":{"official":"Republiken Paraguay","common":"Paraguay"},"urd":{"official":"جمہوریہ پیراگوئے","common":"پیراگوئے"},"zho":{"official":"巴拉圭共和国","common":"巴拉圭"}},"latlng":[-23.0,-58.0],"landlocked":true,"borders":["ARG","BOL","BRA"],"area":406752.0,"demonyms":{"eng":{"f":"Paraguayan","m":"Paraguayan"},"fra":{"f":"Paraguayenne","m":"Paraguayen"}},"flag":"\uD83C\uDDF5\uD83C\uDDFE","maps":{"googleMaps":"https://goo.gl/maps/JtnqG73WJn1Gx6mz6","openStreetMaps":"https://www.openstreetmap.org/relation/287077"},"population":7132530,"gini":{"2019":45.7},"fifa":"PAR","car":{"signs":["PY"],"side":"right"},"timezones":["UTC-04:00"],"continents":["South America"],"flags":{"png":"https://flagcdn.com/w320/py.png","svg":"https://flagcdn.com/py.svg"},"coatOfArms":{"png":"https://mainfacts.com/media/images/coats_of_arms/py.png","svg":"https://mainfacts.com/media/images/coats_of_arms/py.svg"},"startOfWeek":"monday","capitalInfo":{"latlng":[-25.28,-57.57]},"postalCode":{"format":"####","regex":"^(\\d{4})$"}}]
```
[JSON codigo](https://github.com/JagaScripts/java-full-stack-dev-M5/blob/master/code.json "JSON codigo")

  </details>
<br>

5. Codigos.

<details>
  <summary>Codigos.</summary>
<br>
  <img src="https://github.com/JagaScripts/java-full-stack-dev-M5/blob/master/codes.jpg">
 <br>
<p align="justify">JSON codes.</p>
  
 ``` js
[{"name":{"common":"Paraguay","official":"Republic of Paraguay","nativeName":{"grn":{"official":"Tetã Paraguái","common":"Paraguái"},"spa":{"official":"República de Paraguay","common":"Paraguay"}}},"tld":[".py"],"cca2":"PY","ccn3":"600","cca3":"PRY","cioc":"PAR","independent":true,"status":"officially-assigned","unMember":true,"currencies":{"PYG":{"name":"Paraguayan guaraní","symbol":"₲"}},"idd":{"root":"+5","suffixes":["95"]},"capital":["Asunción"],"altSpellings":["PY","Republic of Paraguay","República del Paraguay","Tetã Paraguái"],"region":"Americas","subregion":"South America","languages":{"grn":"Guaraní","spa":"Spanish"},"translations":{"ara":{"official":"جمهورية باراغواي","common":"باراغواي"},"ces":{"official":"Paraguayská republika","common":"Paraguay"},"cym":{"official":"Republic of Paraguay","common":"Paraguay"},"deu":{"official":"Republik Paraguay","common":"Paraguay"},"est":{"official":"Paraguay Vabariik","common":"Paraguay"},"fin":{"official":"Paraguayn tasavalta","common":"Paraguay"},"fra":{"official":"République du Paraguay","common":"Paraguay"},"hrv":{"official":"Republika Paragvaj","common":"Paragvaj"},"hun":{"official":"Paraguayi Köztársaság","common":"Paraguay"},"ita":{"official":"Repubblica del Paraguay","common":"Paraguay"},"jpn":{"official":"パラグアイ共和国","common":"パラグアイ"},"kor":{"official":"파라과이 공화국","common":"파라과이"},"nld":{"official":"Republiek Paraguay","common":"Paraguay"},"per":{"official":"جمهوری پاراگوئه","common":"پاراگوئه"},"pol":{"official":"Republika Paragwaju","common":"Paragwaj"},"por":{"official":"República do Paraguai","common":"Paraguai"},"rus":{"official":"Республика Парагвай","common":"Парагвай"},"slk":{"official":"Paraguajská republika","common":"Paraguaj"},"spa":{"official":"República de Paraguay","common":"Paraguay"},"swe":{"official":"Republiken Paraguay","common":"Paraguay"},"urd":{"official":"جمہوریہ پیراگوئے","common":"پیراگوئے"},"zho":{"official":"巴拉圭共和国","common":"巴拉圭"}},"latlng":[-23.0,-58.0],"landlocked":true,"borders":["ARG","BOL","BRA"],"area":406752.0,"demonyms":{"eng":{"f":"Paraguayan","m":"Paraguayan"},"fra":{"f":"Paraguayenne","m":"Paraguayen"}},"flag":"\uD83C\uDDF5\uD83C\uDDFE","maps":{"googleMaps":"https://goo.gl/maps/JtnqG73WJn1Gx6mz6","openStreetMaps":"https://www.openstreetmap.org/relation/287077"},"population":7132530,"gini":{"2019":45.7},"fifa":"PAR","car":{"signs":["PY"],"side":"right"},"timezones":["UTC-04:00"],"continents":["South America"],"flags":{"png":"https://flagcdn.com/w320/py.png","svg":"https://flagcdn.com/py.svg"},"coatOfArms":{"png":"https://mainfacts.com/media/images/coats_of_arms/py.png","svg":"https://mainfacts.com/media/images/coats_of_arms/py.svg"},"startOfWeek":"monday","capitalInfo":{"latlng":[-25.28,-57.57]},"postalCode":{"format":"####","regex":"^(\\d{4})$"}}]
```
[JSON Codigos](https://github.com/JagaScripts/java-full-stack-dev-M5/blob/master/codes.json "JSON Codigos")

  </details>
<br>
6. Currency.

<details>
  <summary>Currency .</summary>
<br>
  <img src="https://github.com/JagaScripts/java-full-stack-dev-M5/blob/master/currency.jpg">
 <br>
<p align="justify">JSON Currency.</p>
  
 ``` js
[{"name":{"common":"Paraguay","official":"Republic of Paraguay","nativeName":{"grn":{"official":"Tetã Paraguái","common":"Paraguái"},"spa":{"official":"República de Paraguay","common":"Paraguay"}}},"tld":[".py"],"cca2":"PY","ccn3":"600","cca3":"PRY","cioc":"PAR","independent":true,"status":"officially-assigned","unMember":true,"currencies":{"PYG":{"name":"Paraguayan guaraní","symbol":"₲"}},"idd":{"root":"+5","suffixes":["95"]},"capital":["Asunción"],"altSpellings":["PY","Republic of Paraguay","República del Paraguay","Tetã Paraguái"],"region":"Americas","subregion":"South America","languages":{"grn":"Guaraní","spa":"Spanish"},"translations":{"ara":{"official":"جمهورية باراغواي","common":"باراغواي"},"ces":{"official":"Paraguayská republika","common":"Paraguay"},"cym":{"official":"Republic of Paraguay","common":"Paraguay"},"deu":{"official":"Republik Paraguay","common":"Paraguay"},"est":{"official":"Paraguay Vabariik","common":"Paraguay"},"fin":{"official":"Paraguayn tasavalta","common":"Paraguay"},"fra":{"official":"République du Paraguay","common":"Paraguay"},"hrv":{"official":"Republika Paragvaj","common":"Paragvaj"},"hun":{"official":"Paraguayi Köztársaság","common":"Paraguay"},"ita":{"official":"Repubblica del Paraguay","common":"Paraguay"},"jpn":{"official":"パラグアイ共和国","common":"パラグアイ"},"kor":{"official":"파라과이 공화국","common":"파라과이"},"nld":{"official":"Republiek Paraguay","common":"Paraguay"},"per":{"official":"جمهوری پاراگوئه","common":"پاراگوئه"},"pol":{"official":"Republika Paragwaju","common":"Paragwaj"},"por":{"official":"República do Paraguai","common":"Paraguai"},"rus":{"official":"Республика Парагвай","common":"Парагвай"},"slk":{"official":"Paraguajská republika","common":"Paraguaj"},"spa":{"official":"República de Paraguay","common":"Paraguay"},"swe":{"official":"Republiken Paraguay","common":"Paraguay"},"urd":{"official":"جمہوریہ پیراگوئے","common":"پیراگوئے"},"zho":{"official":"巴拉圭共和国","common":"巴拉圭"}},"latlng":[-23.0,-58.0],"landlocked":true,"borders":["ARG","BOL","BRA"],"area":406752.0,"demonyms":{"eng":{"f":"Paraguayan","m":"Paraguayan"},"fra":{"f":"Paraguayenne","m":"Paraguayen"}},"flag":"\uD83C\uDDF5\uD83C\uDDFE","maps":{"googleMaps":"https://goo.gl/maps/JtnqG73WJn1Gx6mz6","openStreetMaps":"https://www.openstreetmap.org/relation/287077"},"population":7132530,"gini":{"2019":45.7},"fifa":"PAR","car":{"signs":["PY"],"side":"right"},"timezones":["UTC-04:00"],"continents":["South America"],"flags":{"png":"https://flagcdn.com/w320/py.png","svg":"https://flagcdn.com/py.svg"},"coatOfArms":{"png":"https://mainfacts.com/media/images/coats_of_arms/py.png","svg":"https://mainfacts.com/media/images/coats_of_arms/py.svg"},"startOfWeek":"monday","capitalInfo":{"latlng":[-25.28,-57.57]},"postalCode":{"format":"####","regex":"^(\\d{4})$"}}]
```
[JSON Currency](https://github.com/JagaScripts/java-full-stack-dev-M5/blob/master/currency.json "JSON Currency")

  </details>
<br>
{et} en la documentación no aparece lo que si se puede buscar es {lang}
7. Lenguaje.

<details>
  <summary>Lenguaje .</summary>
<br>
  <img src="https://github.com/JagaScripts/java-full-stack-dev-M5/blob/master/lang.jpg">
 <br>
<p align="justify">JSON Lenguaje.</p>

[JSON Lenguaje](https://github.com/JagaScripts/java-full-stack-dev-M5/blob/master/lang.json "JSON Lenguaje")

  </details>
<br>
8. Capital.

<details>
  <summary>Capital .</summary>
<br>
  <img src="https://github.com/JagaScripts/java-full-stack-dev-M5/blob/master/capital.jpg">
 <br>
<p align="justify">JSON Capital.</p>

[JSON Capital](https://github.com/JagaScripts/java-full-stack-dev-M5/blob/master/capital.json "JSON Capital")

  </details>
<br>

En la version 3.1 de la api no aparece callingcode hemos cambiado la url para ver el calling code v2
9. CallingCode.

<details>
  <summary>CallingCode .</summary>
<br>
  <img src="https://github.com/JagaScripts/java-full-stack-dev-M5/blob/master/callingcode.jpg">
 <br>
<p align="justify">JSON CallingCode.</p>

[JSON CallingCode](https://github.com/JagaScripts/java-full-stack-dev-M5/blob/master/callingcode.json "JSON CallingCode")

  </details>
<br>

10. Region.

<details>
  <summary>Region .</summary>
<br>
  <img src="https://github.com/JagaScripts/java-full-stack-dev-M5/blob/master/region.jpg">
 <br>
<p align="justify">JSON Region.</p>

[JSON Region](https://github.com/JagaScripts/java-full-stack-dev-M5/blob/master/region.json "JSON Region")

  </details>
<br>

En la version 3.1 de la api no aparece callingcode hemos cambiado la url para ver el calling code v2
11. Region bloc.

<details>
  <summary>Region bloc</summary>
<br>
  <img src="https://github.com/JagaScripts/java-full-stack-dev-M5/blob/master/regionbloc.jpg">
 <br>
<p align="justify">JSON Region bloc.</p>

[JSON Region bloc](https://github.com/JagaScripts/java-full-stack-dev-M5/blob/master/regionbloc.json "JSON Region bloc")

  </details>
<br>

12.  Filtro.

<details>
  <summary>Filtro</summary>
<br>
  <img src="https://github.com/JagaScripts/java-full-stack-dev-M5/blob/master/filter.jpg">
 <br>
<p align="justify">JSON Filtro.</p>

[JSON Filtro](https://github.com/JagaScripts/java-full-stack-dev-M5/blob/master/filter.json "JSON Filtro")

  </details>
<br>

Sobre la API REST Countries realiza una consulta GET válida para cada uno de los end-points anteriores. Utiliza para ello la aplicación cliente POSTMAN (https://www.postman.com/).
```
[JSON Lenguaje](https://github.com/JagaScripts/java-full-stack-dev-M5/blob/master/lang.json "JSON Lenguaje")

  </details>
<br>
8. https://restcountries.com/v3.1/capital/{capital}

![image]()

En la version 3.1 de la api no aparece callingcode hemos cambiado la url para ver el calling code v2
9. https://restcountries.com/v2/callingcode/{callingcode}

![image]()

10. https://restcountries.com/v3.1/region/{region}

![image]()

En la version 3.1 de la api no aparece callingcode hemos cambiado la url para ver el calling code v2
11. https://restcountries.com/v2/regionalbloc/{regionalbloc}

![image]()

12. https://restcountries.com/v3.1/{service}?fields={field};{field};{field}

![image]()

Sobre la API REST Countries realiza una consulta GET válida para cada uno de los end-points anteriores. Utiliza para ello la aplicación cliente POSTMAN (https://www.postman.com/).
