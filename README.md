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
  <summary>Captura https://restcountries.com/v3.1/name/Uruguay </summary>
<br>
  <img src="https://github.com/JagaScripts/java-full-stack-dev-M5/blob/master/name.jpg">
 <br>
<p align="justify">JSON.</p>
  
 ``` js
[{"name":{"common":"Uruguay","official":"Oriental Republic of Uruguay","nativeName":{"spa":{"official":"República Oriental del Uruguay","common":"Uruguay"}}},"tld":[".uy"],"cca2":"UY","ccn3":"858","cca3":"URY","cioc":"URU","independent":true,"status":"officially-assigned","unMember":true,"currencies":{"UYU":{"name":"Uruguayan peso","symbol":"$"}},"idd":{"root":"+5","suffixes":["98"]},"capital":["Montevideo"],"altSpellings":["UY","Oriental Republic of Uruguay","República Oriental del Uruguay"],"region":"Americas","subregion":"South America","languages":{"spa":"Spanish"},"translations":{"ara":{"official":"جمهورية الأوروغواي الشرقية","common":"الأوروغواي"},"ces":{"official":"Uruguayská východní republika","common":"Uruguay"},"cym":{"official":"Oriental Republic of Uruguay","common":"Uruguay"},"deu":{"official":"Republik Östlich des Uruguay","common":"Uruguay"},"est":{"official":"Uruguay Idavabariik","common":"Uruguay"},"fin":{"official":"Uruguayn itäinen tasavalta","common":"Uruguay"},"fra":{"official":"République orientale de l'Uruguay","common":"Uruguay"},"hrv":{"official":"Orijentalna Republika Urugvaj","common":"Urugvaj"},"hun":{"official":"Uruguayi Keleti Köztársaság","common":"Uruguay"},"ita":{"official":"Repubblica Orientale dell'Uruguay","common":"Uruguay"},"jpn":{"official":"ウルグアイ東方共和国","common":"ウルグアイ"},"kor":{"official":"우루과이 동방 공화국","common":"우루과이"},"nld":{"official":"Oosterse Republiek Uruguay","common":"Uruguay"},"per":{"official":"جمهوری اروگوئه","common":"اروگوئه"},"pol":{"official":"Wschodnia Republika Urugwaju","common":"Urugwaj"},"por":{"official":"República Oriental do Uruguai","common":"Uruguai"},"rus":{"official":"Восточной Республики Уругвай","common":"Уругвай"},"slk":{"official":"Uruguajská východná republika","common":"Uruguaj"},"spa":{"official":"República Oriental del Uruguay","common":"Uruguay"},"swe":{"official":"Republiken Uruguay","common":"Uruguay"},"urd":{"official":"جمہوریہ شرقیہ یوراگوئے","common":"یوراگوئے"},"zho":{"official":"乌拉圭东岸共和国","common":"乌拉圭"}},"latlng":[-33.0,-56.0],"landlocked":false,"borders":["ARG","BRA"],"area":181034.0,"demonyms":{"eng":{"f":"Uruguayan","m":"Uruguayan"},"fra":{"f":"Uruguayenne","m":"Uruguayen"}},"flag":"\uD83C\uDDFA\uD83C\uDDFE","maps":{"googleMaps":"https://goo.gl/maps/tiQ9Baekb1jQtDSD9","openStreetMaps":"https://www.openstreetmap.org/relation/287072"},"population":3473727,"gini":{"2019":39.7},"fifa":"URU","car":{"signs":["ROU"],"side":"right"},"timezones":["UTC-03:00"],"continents":["South America"],"flags":{"png":"https://flagcdn.com/w320/uy.png","svg":"https://flagcdn.com/uy.svg"},"coatOfArms":{"png":"https://mainfacts.com/media/images/coats_of_arms/uy.png","svg":"https://mainfacts.com/media/images/coats_of_arms/uy.svg"},"startOfWeek":"monday","capitalInfo":{"latlng":[-34.85,-56.17]},"postalCode":{"format":"#####","regex":"^(\\d{5})$"}}]
```
[JSON Name](https://github.com/JagaScripts/java-full-stack-dev-M5/blob/master/name.json "JSON Name")

  </details>
<br>

2. https://restcountries.com/v3.1/name/{name}

![image]()

3. https://restcountries.com/v3.1/name/{name}?fullText=true

![image]()

4. https://restcountries.com/v3.1/alpha/{code}

![image]()

5. https://restcountries.com/v3.1/alpha?codes={code};{code};{code}

![image]()

6. https://restcountries.com/v3.1/currency/{currency}

![image]()

{et} en la documentación no aparece lo que si se puede buscar es {lang}
7. https://restcountries.com/v3.1/lang/{lang}

![image]()

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
