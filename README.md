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
[
    {
        "name": {
            "common": "Mexico",
            "official": "United Mexican States",
            "nativeName": {
                "spa": {
                    "official": "Estados Unidos Mexicanos",
                    "common": "México"
                }
            }
        },
        "tld": [
            ".mx"
        ],
        "cca2": "MX",
        "ccn3": "484",
        "cca3": "MEX",
        "cioc": "MEX",
        "independent": true,
        "status": "officially-assigned",
        "unMember": true,
        "currencies": {
            "MXN": {
                "name": "Mexican peso",
                "symbol": "$"
            }
        },
        "idd": {
            "root": "+5",
            "suffixes": [
                "2"
            ]
        },
        "capital": [
            "Mexico City"
        ],
        "altSpellings": [
            "MX",
            "Mexicanos",
            "United Mexican States",
            "Estados Unidos Mexicanos"
        ],
        "region": "Americas",
        "subregion": "North America",
        "languages": {
            "spa": "Spanish"
        },
        "translations": {
            "ara": {
                "official": "الولايات المتحدة المكسيكية",
                "common": "المسكيك"
            },
            "ces": {
                "official": "Spojené státy mexické",
                "common": "Mexiko"
            },
            "cym": {
                "official": "United Mexican States",
                "common": "Mexico"
            },
            "deu": {
                "official": "Vereinigte Mexikanische Staaten",
                "common": "Mexiko"
            },
            "est": {
                "official": "Mehhiko Ühendriigid",
                "common": "Mehhiko"
            },
            "fin": {
                "official": "Meksikon yhdysvallat",
                "common": "Meksiko"
            },
            "fra": {
                "official": "États-Unis du Mexique",
                "common": "Mexique"
            },
            "hrv": {
                "official": "Sjedinjene Meksičke Države",
                "common": "Meksiko"
            },
            "hun": {
                "official": "Mexikói Egyesült Államok",
                "common": "Mexikó"
            },
            "ita": {
                "official": "Stati Uniti del Messico",
                "common": "Messico"
            },
            "jpn": {
                "official": "メキシコ合衆国",
                "common": "メキシコ"
            },
            "kor": {
                "official": "멕시코 합중국",
                "common": "멕시코"
            },
            "nld": {
                "official": "Verenigde Mexicaanse Staten",
                "common": "Mexico"
            },
            "per": {
                "official": "ایالات متحد مکزیک",
                "common": "مکزیک"
            },
            "pol": {
                "official": "Meksykańskie Stany Zjednoczone",
                "common": "Meksyk"
            },
            "por": {
                "official": "Estados Unidos Mexicanos",
                "common": "México"
            },
            "rus": {
                "official": "Мексиканские Соединённые Штаты",
                "common": "Мексика"
            },
            "slk": {
                "official": "Spojené štášy mexické",
                "common": "Mexiko"
            },
            "spa": {
                "official": "Estados Unidos Mexicanos",
                "common": "México"
            },
            "swe": {
                "official": "Mexikos förenta stater",
                "common": "Mexiko"
            },
            "urd": {
                "official": "ریاستہائے متحدہ میکسیکو",
                "common": "میکسیکو"
            },
            "zho": {
                "official": "墨西哥合众国",
                "common": "墨西哥"
            }
        },
        "latlng": [
            23.0,
            -102.0
        ],
        "landlocked": false,
        "borders": [
            "BLZ",
            "GTM",
            "USA"
        ],
        "area": 1964375.0,
        "demonyms": {
            "eng": {
                "f": "Mexican",
                "m": "Mexican"
            },
            "fra": {
                "f": "Mexicaine",
                "m": "Mexicain"
            }
        },
        "flag": "🇲🇽",
        "maps": {
            "googleMaps": "https://goo.gl/maps/s5g7imNPMDEePxzbA",
            "openStreetMaps": "https://www.openstreetmap.org/relation/114686"
        },
        "population": 128932753,
        "gini": {
            "2018": 45.4
        },
        "fifa": "MEX",
        "car": {
            "signs": [
                "MEX"
            ],
            "side": "right"
        },
        "timezones": [
            "UTC-08:00",
            "UTC-07:00",
            "UTC-06:00"
        ],
        "continents": [
            "North America"
        ],
        "flags": {
            "png": "https://flagcdn.com/w320/mx.png",
            "svg": "https://flagcdn.com/mx.svg"
        },
        "coatOfArms": {
            "png": "https://mainfacts.com/media/images/coats_of_arms/mx.png",
            "svg": "https://mainfacts.com/media/images/coats_of_arms/mx.svg"
        },
        "startOfWeek": "monday",
        "capitalInfo": {
            "latlng": [
                19.43,
                -99.13
            ]
        },
        "postalCode": {
            "format": "#####",
            "regex": "^(\\d{5})$"
        }
    },
    {
        "name": {
            "common": "Honduras",
            "official": "Republic of Honduras",
            "nativeName": {
                "spa": {
                    "official": "República de Honduras",
                    "common": "Honduras"
                }
            }
        },
        "tld": [
            ".hn"
        ],
        "cca2": "HN",
        "ccn3": "340",
        "cca3": "HND",
        "cioc": "HON",
        "independent": true,
        "status": "officially-assigned",
        "unMember": true,
        "currencies": {
            "HNL": {
                "name": "Honduran lempira",
                "symbol": "L"
            }
        },
        "idd": {
            "root": "+5",
            "suffixes": [
                "04"
            ]
        },
        "capital": [
            "Tegucigalpa"
        ],
        "altSpellings": [
            "HN",
            "Republic of Honduras",
            "República de Honduras"
        ],
        "region": "Americas",
        "subregion": "Central America",
        "languages": {
            "spa": "Spanish"
        },
        "translations": {
            "ara": {
                "official": "جمهورية هندوراس",
                "common": "هندوراس"
            },
            "ces": {
                "official": "Honduraská republika",
                "common": "Honduras"
            },
            "cym": {
                "official": "Republic of Honduras",
                "common": "Honduras"
            },
            "deu": {
                "official": "Republik Honduras",
                "common": "Honduras"
            },
            "est": {
                "official": "Hondurase Vabariik",
                "common": "Honduras"
            },
            "fin": {
                "official": "Hondurasin tasavalta",
                "common": "Honduras"
            },
            "fra": {
                "official": "République du Honduras",
                "common": "Honduras"
            },
            "hrv": {
                "official": "Republika Honduras",
                "common": "Honduras"
            },
            "hun": {
                "official": "Hondurasi Köztársaság",
                "common": "Honduras"
            },
            "ita": {
                "official": "Repubblica di Honduras",
                "common": "Honduras"
            },
            "jpn": {
                "official": "ホンジュラス共和国",
                "common": "ホンジュラス"
            },
            "kor": {
                "official": "온두라스 공화국",
                "common": "온두라스"
            },
            "nld": {
                "official": "Republiek Honduras",
                "common": "Honduras"
            },
            "per": {
                "official": "جمهوری هندوراس",
                "common": "هُندوراس"
            },
            "pol": {
                "official": "Republika Hondurasu",
                "common": "Honduras"
            },
            "por": {
                "official": "República de Honduras",
                "common": "Honduras"
            },
            "rus": {
                "official": "Республика Гондурас",
                "common": "Гондурас"
            },
            "slk": {
                "official": "Honduraská republika",
                "common": "Honduras"
            },
            "spa": {
                "official": "República de Honduras",
                "common": "Honduras"
            },
            "swe": {
                "official": "Republiken Honduras",
                "common": "Honduras"
            },
            "urd": {
                "official": "جمہوریہ ہونڈوراس",
                "common": "ہونڈوراس"
            },
            "zho": {
                "official": "洪都拉斯共和国",
                "common": "洪都拉斯"
            }
        },
        "latlng": [
            15.0,
            -86.5
        ],
        "landlocked": false,
        "borders": [
            "GTM",
            "SLV",
            "NIC"
        ],
        "area": 112492.0,
        "demonyms": {
            "eng": {
                "f": "Honduran",
                "m": "Honduran"
            },
            "fra": {
                "f": "Hondurienne",
                "m": "Hondurien"
            }
        },
        "flag": "🇭🇳",
        "maps": {
            "googleMaps": "https://goo.gl/maps/BbeJK8Sk2VkMHbdF8",
            "openStreetMaps": "https://www.openstreetmap.org/relation/287670"
        },
        "population": 9904608,
        "gini": {
            "2019": 48.2
        },
        "fifa": "HON",
        "car": {
            "signs": [
                "HN"
            ],
            "side": "right"
        },
        "timezones": [
            "UTC-06:00"
        ],
        "continents": [
            "North America"
        ],
        "flags": {
            "png": "https://flagcdn.com/w320/hn.png",
            "svg": "https://flagcdn.com/hn.svg"
        },
        "coatOfArms": {
            "png": "https://mainfacts.com/media/images/coats_of_arms/hn.png",
            "svg": "https://mainfacts.com/media/images/coats_of_arms/hn.svg"
        },
        "startOfWeek": "monday",
        "capitalInfo": {
            "latlng": [
                14.1,
                -87.22
            ]
        },
        "postalCode": {
            "format": "@@####",
            "regex": "^([A-Z]{2}\\d{4})$"
        }
    },
    {
        "name": {
            "common": "Uruguay",
            "official": "Oriental Republic of Uruguay",
            "nativeName": {
                "spa": {
                    "official": "República Oriental del Uruguay",
                    "common": "Uruguay"
                }
            }
        },
        "tld": [
            ".uy"
        ],
        "cca2": "UY",
        "ccn3": "858",
        "cca3": "URY",
        "cioc": "URU",
        "independent": true,
        "status": "officially-assigned",
        "unMember": true,
        "currencies": {
            "UYU": {
                "name": "Uruguayan peso",
                "symbol": "$"
            }
        },
        "idd": {
            "root": "+5",
            "suffixes": [
                "98"
            ]
        },
        "capital": [
            "Montevideo"
        ],
        "altSpellings": [
            "UY",
            "Oriental Republic of Uruguay",
            "República Oriental del Uruguay"
        ],
        "region": "Americas",
        "subregion": "South America",
        "languages": {
            "spa": "Spanish"
        },
        "translations": {
            "ara": {
                "official": "جمهورية الأوروغواي الشرقية",
                "common": "الأوروغواي"
            },
            "ces": {
                "official": "Uruguayská východní republika",
                "common": "Uruguay"
            },
            "cym": {
                "official": "Oriental Republic of Uruguay",
                "common": "Uruguay"
            },
            "deu": {
                "official": "Republik Östlich des Uruguay",
                "common": "Uruguay"
            },
            "est": {
                "official": "Uruguay Idavabariik",
                "common": "Uruguay"
            },
            "fin": {
                "official": "Uruguayn itäinen tasavalta",
                "common": "Uruguay"
            },
            "fra": {
                "official": "République orientale de l'Uruguay",
                "common": "Uruguay"
            },
            "hrv": {
                "official": "Orijentalna Republika Urugvaj",
                "common": "Urugvaj"
            },
            "hun": {
                "official": "Uruguayi Keleti Köztársaság",
                "common": "Uruguay"
            },
            "ita": {
                "official": "Repubblica Orientale dell'Uruguay",
                "common": "Uruguay"
            },
            "jpn": {
                "official": "ウルグアイ東方共和国",
                "common": "ウルグアイ"
            },
            "kor": {
                "official": "우루과이 동방 공화국",
                "common": "우루과이"
            },
            "nld": {
                "official": "Oosterse Republiek Uruguay",
                "common": "Uruguay"
            },
            "per": {
                "official": "جمهوری اروگوئه",
                "common": "اروگوئه"
            },
            "pol": {
                "official": "Wschodnia Republika Urugwaju",
                "common": "Urugwaj"
            },
            "por": {
                "official": "República Oriental do Uruguai",
                "common": "Uruguai"
            },
            "rus": {
                "official": "Восточной Республики Уругвай",
                "common": "Уругвай"
            },
            "slk": {
                "official": "Uruguajská východná republika",
                "common": "Uruguaj"
            },
            "spa": {
                "official": "República Oriental del Uruguay",
                "common": "Uruguay"
            },
            "swe": {
                "official": "Republiken Uruguay",
                "common": "Uruguay"
            },
            "urd": {
                "official": "جمہوریہ شرقیہ یوراگوئے",
                "common": "یوراگوئے"
            },
            "zho": {
                "official": "乌拉圭东岸共和国",
                "common": "乌拉圭"
            }
        },
        "latlng": [
            -33.0,
            -56.0
        ],
        "landlocked": false,
        "borders": [
            "ARG",
            "BRA"
        ],
        "area": 181034.0,
        "demonyms": {
            "eng": {
                "f": "Uruguayan",
                "m": "Uruguayan"
            },
            "fra": {
                "f": "Uruguayenne",
                "m": "Uruguayen"
            }
        },
        "flag": "🇺🇾",
        "maps": {
            "googleMaps": "https://goo.gl/maps/tiQ9Baekb1jQtDSD9",
            "openStreetMaps": "https://www.openstreetmap.org/relation/287072"
        },
        "population": 3473727,
        "gini": {
            "2019": 39.7
        },
        "fifa": "URU",
        "car": {
            "signs": [
                "ROU"
            ],
            "side": "right"
        },
        "timezones": [
            "UTC-03:00"
        ],
        "continents": [
            "South America"
        ],
        "flags": {
            "png": "https://flagcdn.com/w320/uy.png",
            "svg": "https://flagcdn.com/uy.svg"
        },
        "coatOfArms": {
            "png": "https://mainfacts.com/media/images/coats_of_arms/uy.png",
            "svg": "https://mainfacts.com/media/images/coats_of_arms/uy.svg"
        },
        "startOfWeek": "monday",
        "capitalInfo": {
            "latlng": [
                -34.85,
                -56.17
            ]
        },
        "postalCode": {
            "format": "#####",
            "regex": "^(\\d{5})$"
        }
    },
    {
        "name": {
            "common": "Argentina",
            "official": "Argentine Republic",
            "nativeName": {
                "grn": {
                    "official": "Argentine Republic",
                    "common": "Argentina"
                },
                "spa": {
                    "official": "República Argentina",
                    "common": "Argentina"
                }
            }
        },
        "tld": [
            ".ar"
        ],
        "cca2": "AR",
        "ccn3": "032",
        "cca3": "ARG",
        "cioc": "ARG",
        "independent": true,
        "status": "officially-assigned",
        "unMember": true,
        "currencies": {
            "ARS": {
                "name": "Argentine peso",
                "symbol": "$"
            }
        },
        "idd": {
            "root": "+5",
            "suffixes": [
                "4"
            ]
        },
        "capital": [
            "Buenos Aires"
        ],
        "altSpellings": [
            "AR",
            "Argentine Republic",
            "República Argentina"
        ],
        "region": "Americas",
        "subregion": "South America",
        "languages": {
            "grn": "Guaraní",
            "spa": "Spanish"
        },
        "translations": {
            "ara": {
                "official": "جمهورية الأرجنتين",
                "common": "الأرجنتين"
            },
            "ces": {
                "official": "Argentinská republika",
                "common": "Argentina"
            },
            "cym": {
                "official": "Gweriniaeth yr Ariannin",
                "common": "Ariannin"
            },
            "deu": {
                "official": "Argentinische Republik",
                "common": "Argentinien"
            },
            "est": {
                "official": "Argentina Vabariik",
                "common": "Argentina"
            },
            "fin": {
                "official": "Argentiinan tasavalta",
                "common": "Argentiina"
            },
            "fra": {
                "official": "République argentine",
                "common": "Argentine"
            },
            "hrv": {
                "official": "Argentinski Republika",
                "common": "Argentina"
            },
            "hun": {
                "official": "Argentin Köztársaság",
                "common": "Argentína"
            },
            "ita": {
                "official": "Repubblica Argentina",
                "common": "Argentina"
            },
            "jpn": {
                "official": "アルゼンチン共和国",
                "common": "アルゼンチン"
            },
            "kor": {
                "official": "아르헨티나 공화국",
                "common": "아르헨티나"
            },
            "nld": {
                "official": "Argentijnse Republiek",
                "common": "Argentinië"
            },
            "per": {
                "official": "جمهوری آرژانتین",
                "common": "آرژانتین"
            },
            "pol": {
                "official": "Republika Argentyńska",
                "common": "Argentyna"
            },
            "por": {
                "official": "República Argentina",
                "common": "Argentina"
            },
            "rus": {
                "official": "Аргентинская Республика",
                "common": "Аргентина"
            },
            "slk": {
                "official": "Argentínska republika",
                "common": "Argentína"
            },
            "spa": {
                "official": "República Argentina",
                "common": "Argentina"
            },
            "swe": {
                "official": "Republiken Argentina",
                "common": "Argentina"
            },
            "urd": {
                "official": "جمہوریہ ارجنٹائن",
                "common": "ارجنٹائن"
            },
            "zho": {
                "official": "阿根廷共和国",
                "common": "阿根廷"
            }
        },
        "latlng": [
            -34.0,
            -64.0
        ],
        "landlocked": false,
        "borders": [
            "BOL",
            "BRA",
            "CHL",
            "PRY",
            "URY"
        ],
        "area": 2780400.0,
        "demonyms": {
            "eng": {
                "f": "Argentine",
                "m": "Argentine"
            },
            "fra": {
                "f": "Argentine",
                "m": "Argentin"
            }
        },
        "flag": "🇦🇷",
        "maps": {
            "googleMaps": "https://goo.gl/maps/Z9DXNxhf2o93kvyc6",
            "openStreetMaps": "https://www.openstreetmap.org/relation/286393"
        },
        "population": 45376763,
        "gini": {
            "2019": 42.9
        },
        "fifa": "ARG",
        "car": {
            "signs": [
                "RA"
            ],
            "side": "right"
        },
        "timezones": [
            "UTC-03:00"
        ],
        "continents": [
            "South America"
        ],
        "flags": {
            "png": "https://flagcdn.com/w320/ar.png",
            "svg": "https://flagcdn.com/ar.svg"
        },
        "coatOfArms": {
            "png": "https://mainfacts.com/media/images/coats_of_arms/ar.png",
            "svg": "https://mainfacts.com/media/images/coats_of_arms/ar.svg"
        },
        "startOfWeek": "monday",
        "capitalInfo": {
            "latlng": [
                -34.58,
                -58.67
            ]
        },
        "postalCode": {
            "format": "@####@@@",
            "regex": "^([A-Z]\\d{4}[A-Z]{3})$"
        }
    },
    {
        "name": {
            "common": "Paraguay",
            "official": "Republic of Paraguay",
            "nativeName": {
                "grn": {
                    "official": "Tetã Paraguái",
                    "common": "Paraguái"
                },
                "spa": {
                    "official": "República de Paraguay",
                    "common": "Paraguay"
                }
            }
        },
        "tld": [
            ".py"
        ],
        "cca2": "PY",
        "ccn3": "600",
        "cca3": "PRY",
        "cioc": "PAR",
        "independent": true,
        "status": "officially-assigned",
        "unMember": true,
        "currencies": {
            "PYG": {
                "name": "Paraguayan guaraní",
                "symbol": "₲"
            }
        },
        "idd": {
            "root": "+5",
            "suffixes": [
                "95"
            ]
        },
        "capital": [
            "Asunción"
        ],
        "altSpellings": [
            "PY",
            "Republic of Paraguay",
            "República del Paraguay",
            "Tetã Paraguái"
        ],
        "region": "Americas",
        "subregion": "South America",
        "languages": {
            "grn": "Guaraní",
            "spa": "Spanish"
        },
        "translations": {
            "ara": {
                "official": "جمهورية باراغواي",
                "common": "باراغواي"
            },
            "ces": {
                "official": "Paraguayská republika",
                "common": "Paraguay"
            },
            "cym": {
                "official": "Republic of Paraguay",
                "common": "Paraguay"
            },
            "deu": {
                "official": "Republik Paraguay",
                "common": "Paraguay"
            },
            "est": {
                "official": "Paraguay Vabariik",
                "common": "Paraguay"
            },
            "fin": {
                "official": "Paraguayn tasavalta",
                "common": "Paraguay"
            },
            "fra": {
                "official": "République du Paraguay",
                "common": "Paraguay"
            },
            "hrv": {
                "official": "Republika Paragvaj",
                "common": "Paragvaj"
            },
            "hun": {
                "official": "Paraguayi Köztársaság",
                "common": "Paraguay"
            },
            "ita": {
                "official": "Repubblica del Paraguay",
                "common": "Paraguay"
            },
            "jpn": {
                "official": "パラグアイ共和国",
                "common": "パラグアイ"
            },
            "kor": {
                "official": "파라과이 공화국",
                "common": "파라과이"
            },
            "nld": {
                "official": "Republiek Paraguay",
                "common": "Paraguay"
            },
            "per": {
                "official": "جمهوری پاراگوئه",
                "common": "پاراگوئه"
            },
            "pol": {
                "official": "Republika Paragwaju",
                "common": "Paragwaj"
            },
            "por": {
                "official": "República do Paraguai",
                "common": "Paraguai"
            },
            "rus": {
                "official": "Республика Парагвай",
                "common": "Парагвай"
            },
            "slk": {
                "official": "Paraguajská republika",
                "common": "Paraguaj"
            },
            "spa": {
                "official": "República de Paraguay",
                "common": "Paraguay"
            },
            "swe": {
                "official": "Republiken Paraguay",
                "common": "Paraguay"
            },
            "urd": {
                "official": "جمہوریہ پیراگوئے",
                "common": "پیراگوئے"
            },
            "zho": {
                "official": "巴拉圭共和国",
                "common": "巴拉圭"
            }
        },
        "latlng": [
            -23.0,
            -58.0
        ],
        "landlocked": true,
        "borders": [
            "ARG",
            "BOL",
            "BRA"
        ],
        "area": 406752.0,
        "demonyms": {
            "eng": {
                "f": "Paraguayan",
                "m": "Paraguayan"
            },
            "fra": {
                "f": "Paraguayenne",
                "m": "Paraguayen"
            }
        },
        "flag": "🇵🇾",
        "maps": {
            "googleMaps": "https://goo.gl/maps/JtnqG73WJn1Gx6mz6",
            "openStreetMaps": "https://www.openstreetmap.org/relation/287077"
        },
        "population": 7132530,
        "gini": {
            "2019": 45.7
        },
        "fifa": "PAR",
        "car": {
            "signs": [
                "PY"
            ],
            "side": "right"
        },
        "timezones": [
            "UTC-04:00"
        ],
        "continents": [
            "South America"
        ],
        "flags": {
            "png": "https://flagcdn.com/w320/py.png",
            "svg": "https://flagcdn.com/py.svg"
        },
        "coatOfArms": {
            "png": "https://mainfacts.com/media/images/coats_of_arms/py.png",
            "svg": "https://mainfacts.com/media/images/coats_of_arms/py.svg"
        },
        "startOfWeek": "monday",
        "capitalInfo": {
            "latlng": [
                -25.28,
                -57.57
            ]
        },
        "postalCode": {
            "format": "####",
            "regex": "^(\\d{4})$"
        }
    },
    {
        "name": {
            "common": "El Salvador",
            "official": "Republic of El Salvador",
            "nativeName": {
                "spa": {
                    "official": "República de El Salvador",
                    "common": "El Salvador"
                }
            }
        },
        "tld": [
            ".sv"
        ],
        "cca2": "SV",
        "ccn3": "222",
        "cca3": "SLV",
        "cioc": "ESA",
        "independent": true,
        "status": "officially-assigned",
        "unMember": true,
        "currencies": {
            "USD": {
                "name": "United States dollar",
                "symbol": "$"
            }
        },
        "idd": {
            "root": "+5",
            "suffixes": [
                "03"
            ]
        },
        "capital": [
            "San Salvador"
        ],
        "altSpellings": [
            "SV",
            "Republic of El Salvador",
            "República de El Salvador"
        ],
        "region": "Americas",
        "subregion": "Central America",
        "languages": {
            "spa": "Spanish"
        },
        "translations": {
            "ara": {
                "official": "جمهورية السلفادور",
                "common": "السلفادور"
            },
            "ces": {
                "official": "Salvadorská republika",
                "common": "Salvador"
            },
            "cym": {
                "official": "Gweriniaeth El Salfador",
                "common": "El Salfador"
            },
            "deu": {
                "official": "Republik El Salvador",
                "common": "El Salvador"
            },
            "est": {
                "official": "El Salvadori Vabariik",
                "common": "El Salvador"
            },
            "fin": {
                "official": "El Salvadorin tasavalta",
                "common": "El Salvador"
            },
            "fra": {
                "official": "République du Salvador",
                "common": "Salvador"
            },
            "hrv": {
                "official": "Republika El Salvador",
                "common": "Salvador"
            },
            "hun": {
                "official": "Salvadori Köztársaság",
                "common": "Salvador"
            },
            "ita": {
                "official": "Repubblica di El Salvador",
                "common": "El Salvador"
            },
            "jpn": {
                "official": "エルサルバドル共和国",
                "common": "エルサルバドル"
            },
            "kor": {
                "official": "엘살바도르 공화국",
                "common": "엘살바도르"
            },
            "nld": {
                "official": "Republiek El Salvador",
                "common": "El Salvador"
            },
            "per": {
                "official": "جمهوری السالوادور",
                "common": "السالوادور"
            },
            "pol": {
                "official": "Republika Salwadoru",
                "common": "Salwador"
            },
            "por": {
                "official": "República de El Salvador",
                "common": "El Salvador"
            },
            "rus": {
                "official": "Республика Эль-Сальвадор",
                "common": "Сальвадор"
            },
            "slk": {
                "official": "Salvádorská republika",
                "common": "Salvádor"
            },
            "spa": {
                "official": "República de El Salvador",
                "common": "El Salvador"
            },
            "swe": {
                "official": "Republiken El Salvador",
                "common": "El Salvador"
            },
            "urd": {
                "official": "جمہوریہ ایل سیلواڈور",
                "common": "ایل سیلواڈور"
            },
            "zho": {
                "official": "萨尔瓦多共和国",
                "common": "萨尔瓦多"
            }
        },
        "latlng": [
            13.83333333,
            -88.91666666
        ],
        "landlocked": false,
        "borders": [
            "GTM",
            "HND"
        ],
        "area": 21041.0,
        "demonyms": {
            "eng": {
                "f": "Salvadoran",
                "m": "Salvadoran"
            },
            "fra": {
                "f": "Salvadorienne",
                "m": "Salvadorien"
            }
        },
        "flag": "🇸🇻",
        "maps": {
            "googleMaps": "https://goo.gl/maps/cZnCEi5sEMQtKKcB7",
            "openStreetMaps": "https://www.openstreetmap.org/relation/1520612"
        },
        "population": 6486201,
        "gini": {
            "2019": 38.8
        },
        "fifa": "SLV",
        "car": {
            "signs": [
                "ES"
            ],
            "side": "right"
        },
        "timezones": [
            "UTC-06:00"
        ],
        "continents": [
            "North America"
        ],
        "flags": {
            "png": "https://flagcdn.com/w320/sv.png",
            "svg": "https://flagcdn.com/sv.svg"
        },
        "coatOfArms": {
            "png": "https://mainfacts.com/media/images/coats_of_arms/sv.png",
            "svg": "https://mainfacts.com/media/images/coats_of_arms/sv.svg"
        },
        "startOfWeek": "monday",
        "capitalInfo": {
            "latlng": [
                13.7,
                -89.2
            ]
        },
        "postalCode": {
            "format": "CP ####",
            "regex": "^(?:CP)*(\\d{4})$"
        }
    },
    {
        "name": {
            "common": "Bolivia",
            "official": "Plurinational State of Bolivia",
            "nativeName": {
                "aym": {
                    "official": "Wuliwya Suyu",
                    "common": "Wuliwya"
                },
                "grn": {
                    "official": "Tetã Volívia",
                    "common": "Volívia"
                },
                "que": {
                    "official": "Buliwya Mamallaqta",
                    "common": "Buliwya"
                },
                "spa": {
                    "official": "Estado Plurinacional de Bolivia",
                    "common": "Bolivia"
                }
            }
        },
        "tld": [
            ".bo"
        ],
        "cca2": "BO",
        "ccn3": "068",
        "cca3": "BOL",
        "cioc": "BOL",
        "independent": true,
        "status": "officially-assigned",
        "unMember": true,
        "currencies": {
            "BOB": {
                "name": "Bolivian boliviano",
                "symbol": "Bs."
            }
        },
        "idd": {
            "root": "+5",
            "suffixes": [
                "91"
            ]
        },
        "capital": [
            "Sucre"
        ],
        "altSpellings": [
            "BO",
            "Buliwya",
            "Wuliwya",
            "Bolivia, Plurinational State of",
            "Plurinational State of Bolivia",
            "Estado Plurinacional de Bolivia",
            "Buliwya Mamallaqta",
            "Wuliwya Suyu",
            "Tetã Volívia"
        ],
        "region": "Americas",
        "subregion": "South America",
        "languages": {
            "aym": "Aymara",
            "grn": "Guaraní",
            "que": "Quechua",
            "spa": "Spanish"
        },
        "translations": {
            "ara": {
                "official": "دولة بوليفيا المتعددة القوميات",
                "common": "بوليفيا"
            },
            "ces": {
                "official": "Mnohonárodnostní stát Bolívie",
                "common": "Bolívie"
            },
            "cym": {
                "official": "Gweriniaeth Bolifia",
                "common": "Bolifia"
            },
            "deu": {
                "official": "Plurinationaler Staat Bolivien",
                "common": "Bolivien"
            },
            "est": {
                "official": "Boliivia Paljurahvuseline Riik",
                "common": "Boliivia"
            },
            "fin": {
                "official": "Bolivian monikansainen valtio",
                "common": "Bolivia"
            },
            "fra": {
                "official": "État plurinational de Bolivie",
                "common": "Bolivie"
            },
            "hrv": {
                "official": "Plurinational State of Bolivia",
                "common": "Bolivija"
            },
            "hun": {
                "official": "Bolíviai Többnemzetiségű Állam",
                "common": "Bolívia"
            },
            "ita": {
                "official": "Stato Plurinazionale della Bolivia",
                "common": "Bolivia"
            },
            "jpn": {
                "official": "ボリビアの多民族国",
                "common": "ボリビア多民族国"
            },
            "kor": {
                "official": "볼리비아 다민족국",
                "common": "볼리비아"
            },
            "nld": {
                "official": "Plurinationale Staat van Bolivia",
                "common": "Bolivia"
            },
            "per": {
                "official": "جمهوری بولیوی",
                "common": "بولیوی"
            },
            "pol": {
                "official": "Wielonarodowe Państwo Boliwia",
                "common": "Boliwia"
            },
            "por": {
                "official": "Estado Plurinacional da Bolívia",
                "common": "Bolívia"
            },
            "rus": {
                "official": "Многонациональное Государство Боливия",
                "common": "Боливия"
            },
            "slk": {
                "official": "Bolívijská republika",
                "common": "Bolívia"
            },
            "spa": {
                "official": "Estado Plurinacional de Bolivia",
                "common": "Bolivia"
            },
            "swe": {
                "official": "Mångnationella staten Bolivia",
                "common": "Bolivia"
            },
            "urd": {
                "official": "جمہوریہ بولیویا",
                "common": "بولیویا"
            },
            "zho": {
                "official": "多民族玻利维亚国",
                "common": "玻利维亚"
            }
        },
        "latlng": [
            -17.0,
            -65.0
        ],
        "landlocked": true,
        "borders": [
            "ARG",
            "BRA",
            "CHL",
            "PRY",
            "PER"
        ],
        "area": 1098581.0,
        "demonyms": {
            "eng": {
                "f": "Bolivian",
                "m": "Bolivian"
            },
            "fra": {
                "f": "Bolivienne",
                "m": "Bolivien"
            }
        },
        "flag": "🇧🇴",
        "maps": {
            "googleMaps": "https://goo.gl/maps/9DfnyfbxNM2g5U9b9",
            "openStreetMaps": "https://www.openstreetmap.org/relation/252645"
        },
        "population": 11673029,
        "gini": {
            "2019": 41.6
        },
        "fifa": "BOL",
        "car": {
            "signs": [
                "BOL"
            ],
            "side": "right"
        },
        "timezones": [
            "UTC-04:00"
        ],
        "continents": [
            "South America"
        ],
        "flags": {
            "png": "https://flagcdn.com/w320/bo.png",
            "svg": "https://flagcdn.com/bo.svg"
        },
        "coatOfArms": {
            "png": "https://mainfacts.com/media/images/coats_of_arms/bo.png",
            "svg": "https://mainfacts.com/media/images/coats_of_arms/bo.svg"
        },
        "startOfWeek": "monday",
        "capitalInfo": {
            "latlng": [
                -19.02,
                -65.26
            ]
        }
    },
    {
        "name": {
            "common": "Nicaragua",
            "official": "Republic of Nicaragua",
            "nativeName": {
                "spa": {
                    "official": "República de Nicaragua",
                    "common": "Nicaragua"
                }
            }
        },
        "tld": [
            ".ni"
        ],
        "cca2": "NI",
        "ccn3": "558",
        "cca3": "NIC",
        "cioc": "NCA",
        "independent": true,
        "status": "officially-assigned",
        "unMember": true,
        "currencies": {
            "NIO": {
                "name": "Nicaraguan córdoba",
                "symbol": "C$"
            }
        },
        "idd": {
            "root": "+5",
            "suffixes": [
                "05"
            ]
        },
        "capital": [
            "Managua"
        ],
        "altSpellings": [
            "NI",
            "Republic of Nicaragua",
            "República de Nicaragua"
        ],
        "region": "Americas",
        "subregion": "Central America",
        "languages": {
            "spa": "Spanish"
        },
        "translations": {
            "ara": {
                "official": "جمهورية نيكاراغوا",
                "common": "نيكاراغوا"
            },
            "ces": {
                "official": "Republika Nikaragua",
                "common": "Nikaragua"
            },
            "cym": {
                "official": "Republic of Nicaragua",
                "common": "Nicaragua"
            },
            "deu": {
                "official": "Republik Nicaragua",
                "common": "Nicaragua"
            },
            "est": {
                "official": "Nicaragua Vabariik",
                "common": "Nicaragua"
            },
            "fin": {
                "official": "Nicaraguan tasavalta",
                "common": "Nicaragua"
            },
            "fra": {
                "official": "République du Nicaragua",
                "common": "Nicaragua"
            },
            "hrv": {
                "official": "Republika Nikaragva",
                "common": "Nikaragva"
            },
            "hun": {
                "official": "Nicaraguai Köztársaság",
                "common": "Nicaragua"
            },
            "ita": {
                "official": "Repubblica del Nicaragua",
                "common": "Nicaragua"
            },
            "jpn": {
                "official": "ニカラグア共和国",
                "common": "ニカラグア"
            },
            "kor": {
                "official": "니카라과 공화국",
                "common": "니카라과"
            },
            "nld": {
                "official": "Republiek Nicaragua",
                "common": "Nicaragua"
            },
            "per": {
                "official": "جمهوری نیکاراگوئه",
                "common": "نیکاراگوئه"
            },
            "pol": {
                "official": "Republika Nikaragui",
                "common": "Nikaragua"
            },
            "por": {
                "official": "República da Nicarágua",
                "common": "Nicarágua"
            },
            "rus": {
                "official": "Республика Никарагуа",
                "common": "Никарагуа"
            },
            "slk": {
                "official": "Nikaragujská republika",
                "common": "Nikaragua"
            },
            "spa": {
                "official": "República de Nicaragua",
                "common": "Nicaragua"
            },
            "swe": {
                "official": "Republiken Nicaragua",
                "common": "Nicaragua"
            },
            "urd": {
                "official": "جمہوریہ نکاراگوا",
                "common": "نکاراگوا"
            },
            "zho": {
                "official": "尼加拉瓜共和国",
                "common": "尼加拉瓜"
            }
        },
        "latlng": [
            13.0,
            -85.0
        ],
        "landlocked": false,
        "borders": [
            "CRI",
            "HND"
        ],
        "area": 130373.0,
        "demonyms": {
            "eng": {
                "f": "Nicaraguan",
                "m": "Nicaraguan"
            },
            "fra": {
                "f": "Nicaraguayenne",
                "m": "Nicaraguayen"
            }
        },
        "flag": "🇳🇮",
        "maps": {
            "googleMaps": "https://goo.gl/maps/P77LaEVkKJKXneRC6",
            "openStreetMaps": "https://www.openstreetmap.org/relation/287666"
        },
        "population": 6624554,
        "gini": {
            "2014": 46.2
        },
        "fifa": "NCA",
        "car": {
            "signs": [
                "NIC"
            ],
            "side": "right"
        },
        "timezones": [
            "UTC-06:00"
        ],
        "continents": [
            "North America"
        ],
        "flags": {
            "png": "https://flagcdn.com/w320/ni.png",
            "svg": "https://flagcdn.com/ni.svg"
        },
        "coatOfArms": {
            "png": "https://mainfacts.com/media/images/coats_of_arms/ni.png",
            "svg": "https://mainfacts.com/media/images/coats_of_arms/ni.svg"
        },
        "startOfWeek": "monday",
        "capitalInfo": {
            "latlng": [
                12.13,
                -86.25
            ]
        },
        "postalCode": {
            "format": "###-###-#",
            "regex": "^(\\d{7})$"
        }
    },
    {
        "name": {
            "common": "Belize",
            "official": "Belize",
            "nativeName": {
                "bjz": {
                    "official": "Belize",
                    "common": "Belize"
                },
                "eng": {
                    "official": "Belize",
                    "common": "Belize"
                },
                "spa": {
                    "official": "Belice",
                    "common": "Belice"
                }
            }
        },
        "tld": [
            ".bz"
        ],
        "cca2": "BZ",
        "ccn3": "084",
        "cca3": "BLZ",
        "cioc": "BIZ",
        "independent": true,
        "status": "officially-assigned",
        "unMember": true,
        "currencies": {
            "BZD": {
                "name": "Belize dollar",
                "symbol": "$"
            }
        },
        "idd": {
            "root": "+5",
            "suffixes": [
                "01"
            ]
        },
        "capital": [
            "Belmopan"
        ],
        "altSpellings": [
            "BZ"
        ],
        "region": "Americas",
        "subregion": "Central America",
        "languages": {
            "bjz": "Belizean Creole",
            "eng": "English",
            "spa": "Spanish"
        },
        "translations": {
            "ara": {
                "official": "بليز",
                "common": "بليز"
            },
            "ces": {
                "official": "Belize",
                "common": "Belize"
            },
            "cym": {
                "official": "Belîs",
                "common": "Belîs"
            },
            "deu": {
                "official": "Belize",
                "common": "Belize"
            },
            "est": {
                "official": "Belize",
                "common": "Belize"
            },
            "fin": {
                "official": "Belize",
                "common": "Belize"
            },
            "fra": {
                "official": "Belize",
                "common": "Belize"
            },
            "hrv": {
                "official": "Belize",
                "common": "Belize"
            },
            "hun": {
                "official": "Belize",
                "common": "Belize"
            },
            "ita": {
                "official": "Belize",
                "common": "Belize"
            },
            "jpn": {
                "official": "ベリーズ",
                "common": "ベリーズ"
            },
            "kor": {
                "official": "벨리즈",
                "common": "벨리즈"
            },
            "nld": {
                "official": "Belize",
                "common": "Belize"
            },
            "per": {
                "official": "بلیز",
                "common": "بلیز"
            },
            "pol": {
                "official": "Belize",
                "common": "Belize"
            },
            "por": {
                "official": "Belize",
                "common": "Belize"
            },
            "rus": {
                "official": "Белиз",
                "common": "Белиз"
            },
            "slk": {
                "official": "Belize",
                "common": "Belize"
            },
            "spa": {
                "official": "Belice",
                "common": "Belice"
            },
            "swe": {
                "official": "Belize",
                "common": "Belize"
            },
            "urd": {
                "official": "بیلیز",
                "common": "بیلیز"
            },
            "zho": {
                "official": "伯利兹",
                "common": "伯利兹"
            }
        },
        "latlng": [
            17.25,
            -88.75
        ],
        "landlocked": false,
        "borders": [
            "GTM",
            "MEX"
        ],
        "area": 22966.0,
        "demonyms": {
            "eng": {
                "f": "Belizean",
                "m": "Belizean"
            },
            "fra": {
                "f": "Bélizienne",
                "m": "Bélizien"
            }
        },
        "flag": "🇧🇿",
        "maps": {
            "googleMaps": "https://goo.gl/maps/jdCccpdLodm1uTmo9",
            "openStreetMaps": "https://www.openstreetmap.org/relation/287827"
        },
        "population": 397621,
        "gini": {
            "1999": 53.3
        },
        "fifa": "BLZ",
        "car": {
            "signs": [
                "BH"
            ],
            "side": "right"
        },
        "timezones": [
            "UTC-06:00"
        ],
        "continents": [
            "North America"
        ],
        "flags": {
            "png": "https://flagcdn.com/w320/bz.png",
            "svg": "https://flagcdn.com/bz.svg"
        },
        "coatOfArms": {
            "png": "https://mainfacts.com/media/images/coats_of_arms/bz.png",
            "svg": "https://mainfacts.com/media/images/coats_of_arms/bz.svg"
        },
        "startOfWeek": "monday",
        "capitalInfo": {
            "latlng": [
                17.25,
                -88.77
            ]
        }
    },
    {
        "name": {
            "common": "Panama",
            "official": "Republic of Panama",
            "nativeName": {
                "spa": {
                    "official": "República de Panamá",
                    "common": "Panamá"
                }
            }
        },
        "tld": [
            ".pa"
        ],
        "cca2": "PA",
        "ccn3": "591",
        "cca3": "PAN",
        "cioc": "PAN",
        "independent": true,
        "status": "officially-assigned",
        "unMember": true,
        "currencies": {
            "PAB": {
                "name": "Panamanian balboa",
                "symbol": "B/."
            },
            "USD": {
                "name": "United States dollar",
                "symbol": "$"
            }
        },
        "idd": {
            "root": "+5",
            "suffixes": [
                "07"
            ]
        },
        "capital": [
            "Panama City"
        ],
        "altSpellings": [
            "PA",
            "Republic of Panama",
            "República de Panamá"
        ],
        "region": "Americas",
        "subregion": "Central America",
        "languages": {
            "spa": "Spanish"
        },
        "translations": {
            "ara": {
                "official": "جمهورية بنما",
                "common": "بنما"
            },
            "ces": {
                "official": "Panamská republika",
                "common": "Panama"
            },
            "cym": {
                "official": "Republic of Panama",
                "common": "Panama"
            },
            "deu": {
                "official": "Republik Panama",
                "common": "Panama"
            },
            "est": {
                "official": "Panama Vabariik",
                "common": "Panama"
            },
            "fin": {
                "official": "Panaman tasavalta",
                "common": "Panama"
            },
            "fra": {
                "official": "République du Panama",
                "common": "Panama"
            },
            "hrv": {
                "official": "Republika Panama",
                "common": "Panama"
            },
            "hun": {
                "official": "Panamai Köztársaság",
                "common": "Panama"
            },
            "ita": {
                "official": "Repubblica di Panama",
                "common": "Panama"
            },
            "jpn": {
                "official": "パナマ共和国",
                "common": "パナマ"
            },
            "kor": {
                "official": "파나마 공화국",
                "common": "파나마"
            },
            "nld": {
                "official": "Republiek Panama",
                "common": "Panama"
            },
            "per": {
                "official": "جمهوری پاناما",
                "common": "پاناما"
            },
            "pol": {
                "official": "Republika Panamy",
                "common": "Panama"
            },
            "por": {
                "official": "República do Panamá",
                "common": "Panamá"
            },
            "rus": {
                "official": "Республика Панама",
                "common": "Панама"
            },
            "slk": {
                "official": "Panamská republika",
                "common": "Panama"
            },
            "spa": {
                "official": "República de Panamá",
                "common": "Panamá"
            },
            "swe": {
                "official": "Republiken Panama",
                "common": "Panama"
            },
            "urd": {
                "official": "جمہوریہ پاناما",
                "common": "پاناما"
            },
            "zho": {
                "official": "巴拿马共和国",
                "common": "巴拿马"
            }
        },
        "latlng": [
            9.0,
            -80.0
        ],
        "landlocked": false,
        "borders": [
            "COL",
            "CRI"
        ],
        "area": 75417.0,
        "demonyms": {
            "eng": {
                "f": "Panamanian",
                "m": "Panamanian"
            },
            "fra": {
                "f": "Panaméenne",
                "m": "Panaméen"
            }
        },
        "flag": "🇵🇦",
        "maps": {
            "googleMaps": "https://goo.gl/maps/sEN7sKqeawa5oPNLA",
            "openStreetMaps": "https://www.openstreetmap.org/relation/287668"
        },
        "population": 4314768,
        "gini": {
            "2019": 49.8
        },
        "fifa": "PAN",
        "car": {
            "signs": [
                "PA"
            ],
            "side": "right"
        },
        "timezones": [
            "UTC-05:00"
        ],
        "continents": [
            "North America"
        ],
        "flags": {
            "png": "https://flagcdn.com/w320/pa.png",
            "svg": "https://flagcdn.com/pa.svg"
        },
        "coatOfArms": {
            "png": "https://mainfacts.com/media/images/coats_of_arms/pa.png",
            "svg": "https://mainfacts.com/media/images/coats_of_arms/pa.svg"
        },
        "startOfWeek": "monday",
        "capitalInfo": {
            "latlng": [
                8.97,
                -79.53
            ]
        }
    },
    {
        "name": {
            "common": "Colombia",
            "official": "Republic of Colombia",
            "nativeName": {
                "spa": {
                    "official": "República de Colombia",
                    "common": "Colombia"
                }
            }
        },
        "tld": [
            ".co"
        ],
        "cca2": "CO",
        "ccn3": "170",
        "cca3": "COL",
        "cioc": "COL",
        "independent": true,
        "status": "officially-assigned",
        "unMember": true,
        "currencies": {
            "COP": {
                "name": "Colombian peso",
                "symbol": "$"
            }
        },
        "idd": {
            "root": "+5",
            "suffixes": [
                "7"
            ]
        },
        "capital": [
            "Bogotá"
        ],
        "altSpellings": [
            "CO",
            "Republic of Colombia",
            "República de Colombia"
        ],
        "region": "Americas",
        "subregion": "South America",
        "languages": {
            "spa": "Spanish"
        },
        "translations": {
            "ara": {
                "official": "جمهورية كولومبيا",
                "common": "كولومبيا"
            },
            "ces": {
                "official": "Kolumbijská republika",
                "common": "Kolumbie"
            },
            "cym": {
                "official": "Gweriniaeth Colombia",
                "common": "Colombia"
            },
            "deu": {
                "official": "Republik Kolumbien",
                "common": "Kolumbien"
            },
            "est": {
                "official": "Colombia Vabariik",
                "common": "Colombia"
            },
            "fin": {
                "official": "Kolumbian tasavalta",
                "common": "Kolumbia"
            },
            "fra": {
                "official": "République de Colombie",
                "common": "Colombie"
            },
            "hrv": {
                "official": "Republika Kolumbija",
                "common": "Kolumbija"
            },
            "hun": {
                "official": "Kolumbiai Köztársaság",
                "common": "Kolumbia"
            },
            "ita": {
                "official": "Repubblica di Colombia",
                "common": "Colombia"
            },
            "jpn": {
                "official": "コロンビア共和国",
                "common": "コロンビア"
            },
            "kor": {
                "official": "콜롬비아 공화국",
                "common": "콜롬비아"
            },
            "nld": {
                "official": "Republiek Colombia",
                "common": "Colombia"
            },
            "per": {
                "official": "جمهوری کلمبیا",
                "common": "کلمبیا"
            },
            "pol": {
                "official": "Republika Kolumbii",
                "common": "Kolumbia"
            },
            "por": {
                "official": "República da Colômbia",
                "common": "Colômbia"
            },
            "rus": {
                "official": "Республика Колумбия",
                "common": "Колумбия"
            },
            "slk": {
                "official": "Kolumbijská republika",
                "common": "Kolumbia"
            },
            "spa": {
                "official": "República de Colombia",
                "common": "Colombia"
            },
            "swe": {
                "official": "Republiken Colombia",
                "common": "Colombia"
            },
            "urd": {
                "official": "جمہوریہ کولمبیا",
                "common": "کولمبیا"
            },
            "zho": {
                "official": "哥伦比亚共和国",
                "common": "哥伦比亚"
            }
        },
        "latlng": [
            4.0,
            -72.0
        ],
        "landlocked": false,
        "borders": [
            "BRA",
            "ECU",
            "PAN",
            "PER",
            "VEN"
        ],
        "area": 1141748.0,
        "demonyms": {
            "eng": {
                "f": "Colombian",
                "m": "Colombian"
            },
            "fra": {
                "f": "Colombienne",
                "m": "Colombien"
            }
        },
        "flag": "🇨🇴",
        "maps": {
            "googleMaps": "https://goo.gl/maps/RdwTG8e7gPwS62oR6",
            "openStreetMaps": "https://www.openstreetmap.org/relation/120027"
        },
        "population": 50882884,
        "gini": {
            "2019": 51.3
        },
        "fifa": "COL",
        "car": {
            "signs": [
                "CO"
            ],
            "side": "right"
        },
        "timezones": [
            "UTC-05:00"
        ],
        "continents": [
            "South America"
        ],
        "flags": {
            "png": "https://flagcdn.com/w320/co.png",
            "svg": "https://flagcdn.com/co.svg"
        },
        "coatOfArms": {
            "png": "https://mainfacts.com/media/images/coats_of_arms/co.png",
            "svg": "https://mainfacts.com/media/images/coats_of_arms/co.svg"
        },
        "startOfWeek": "monday",
        "capitalInfo": {
            "latlng": [
                4.71,
                -74.07
            ]
        }
    },
    {
        "name": {
            "common": "Peru",
            "official": "Republic of Peru",
            "nativeName": {
                "aym": {
                    "official": "Piruw Suyu",
                    "common": "Piruw"
                },
                "que": {
                    "official": "Piruw Ripuwlika",
                    "common": "Piruw"
                },
                "spa": {
                    "official": "República del Perú",
                    "common": "Perú"
                }
            }
        },
        "tld": [
            ".pe"
        ],
        "cca2": "PE",
        "ccn3": "604",
        "cca3": "PER",
        "cioc": "PER",
        "independent": true,
        "status": "officially-assigned",
        "unMember": true,
        "currencies": {
            "PEN": {
                "name": "Peruvian sol",
                "symbol": "S/ "
            }
        },
        "idd": {
            "root": "+5",
            "suffixes": [
                "1"
            ]
        },
        "capital": [
            "Lima"
        ],
        "altSpellings": [
            "PE",
            "Republic of Peru",
            "República del Perú"
        ],
        "region": "Americas",
        "subregion": "South America",
        "languages": {
            "aym": "Aymara",
            "que": "Quechua",
            "spa": "Spanish"
        },
        "translations": {
            "ara": {
                "official": "جمهورية بيرو",
                "common": "بيرو"
            },
            "ces": {
                "official": "Peruánská republika",
                "common": "Peru"
            },
            "cym": {
                "official": "Republic of Peru",
                "common": "Peru"
            },
            "deu": {
                "official": "Republik Peru",
                "common": "Peru"
            },
            "est": {
                "official": "Peruu Vabariik",
                "common": "Peruu"
            },
            "fin": {
                "official": "Perun tasavalta",
                "common": "Peru"
            },
            "fra": {
                "official": "République du Pérou",
                "common": "Pérou"
            },
            "hrv": {
                "official": "Republika Peru",
                "common": "Peru"
            },
            "hun": {
                "official": "Perui Köztársaság",
                "common": "Peru"
            },
            "ita": {
                "official": "Repubblica del Perù",
                "common": "Perù"
            },
            "jpn": {
                "official": "ペルー共和国",
                "common": "ペルー"
            },
            "kor": {
                "official": "페루 공화국",
                "common": "페루"
            },
            "nld": {
                "official": "Republiek Peru",
                "common": "Peru"
            },
            "per": {
                "official": "جمهوری پرو",
                "common": "پرو"
            },
            "pol": {
                "official": "Republika Peru",
                "common": "Peru"
            },
            "por": {
                "official": "República do Peru",
                "common": "Perú"
            },
            "rus": {
                "official": "Республика Перу",
                "common": "Перу"
            },
            "slk": {
                "official": "Peruánska republika",
                "common": "Peru"
            },
            "spa": {
                "official": "República de Perú",
                "common": "Perú"
            },
            "swe": {
                "official": "Republiken Peru",
                "common": "Peru"
            },
            "urd": {
                "official": "جمہوریہ پیرو",
                "common": "پیرو"
            },
            "zho": {
                "official": "秘鲁共和国",
                "common": "秘鲁"
            }
        },
        "latlng": [
            -10.0,
            -76.0
        ],
        "landlocked": false,
        "borders": [
            "BOL",
            "BRA",
            "CHL",
            "COL",
            "ECU"
        ],
        "area": 1285216.0,
        "demonyms": {
            "eng": {
                "f": "Peruvian",
                "m": "Peruvian"
            },
            "fra": {
                "f": "Péruvienne",
                "m": "Péruvien"
            }
        },
        "flag": "🇵🇪",
        "maps": {
            "googleMaps": "https://goo.gl/maps/uDWEUaXNcZTng1fP6",
            "openStreetMaps": "https://www.openstreetmap.org/relation/288247"
        },
        "population": 32971846,
        "gini": {
            "2019": 41.5
        },
        "fifa": "PER",
        "car": {
            "signs": [
                "PE"
            ],
            "side": "right"
        },
        "timezones": [
            "UTC-05:00"
        ],
        "continents": [
            "South America"
        ],
        "flags": {
            "png": "https://flagcdn.com/w320/pe.png",
            "svg": "https://flagcdn.com/pe.svg"
        },
        "coatOfArms": {
            "png": "https://mainfacts.com/media/images/coats_of_arms/pe.png",
            "svg": "https://mainfacts.com/media/images/coats_of_arms/pe.svg"
        },
        "startOfWeek": "monday",
        "capitalInfo": {
            "latlng": [
                -12.05,
                -77.05
            ]
        },
        "postalCode": {
            "format": "#####",
            "regex": "^(\\d{5})$"
        }
    },
    {
        "name": {
            "common": "Ecuador",
            "official": "Republic of Ecuador",
            "nativeName": {
                "spa": {
                    "official": "República del Ecuador",
                    "common": "Ecuador"
                }
            }
        },
        "tld": [
            ".ec"
        ],
        "cca2": "EC",
        "ccn3": "218",
        "cca3": "ECU",
        "cioc": "ECU",
        "independent": true,
        "status": "officially-assigned",
        "unMember": true,
        "currencies": {
            "USD": {
                "name": "United States dollar",
                "symbol": "$"
            }
        },
        "idd": {
            "root": "+5",
            "suffixes": [
                "93"
            ]
        },
        "capital": [
            "Quito"
        ],
        "altSpellings": [
            "EC",
            "Republic of Ecuador",
            "República del Ecuador"
        ],
        "region": "Americas",
        "subregion": "South America",
        "languages": {
            "spa": "Spanish"
        },
        "translations": {
            "ara": {
                "official": "جمهورية الإكوادور",
                "common": "الإكوادور"
            },
            "ces": {
                "official": "Ekvádorská republika",
                "common": "Ekvádor"
            },
            "cym": {
                "official": "Gweriniaeth Ecwador",
                "common": "Ecwador"
            },
            "deu": {
                "official": "Republik Ecuador",
                "common": "Ecuador"
            },
            "est": {
                "official": "Ecuadori Vabariik",
                "common": "Ecuador"
            },
            "fin": {
                "official": "Ecuadorin tasavalta",
                "common": "Ecuador"
            },
            "fra": {
                "official": "République de l'Équateur",
                "common": "Équateur"
            },
            "hrv": {
                "official": "Republika Ekvador",
                "common": "Ekvador"
            },
            "hun": {
                "official": "Ecuadori Köztársaság",
                "common": "Ecuador"
            },
            "ita": {
                "official": "Repubblica dell'Ecuador",
                "common": "Ecuador"
            },
            "jpn": {
                "official": "エクアドル共和国",
                "common": "エクアドル"
            },
            "kor": {
                "official": "에콰도르 공화국",
                "common": "에콰도르"
            },
            "nld": {
                "official": "Republiek Ecuador",
                "common": "Ecuador"
            },
            "per": {
                "official": "جمهوری اکوادور",
                "common": "اکوادور"
            },
            "pol": {
                "official": "Ekwador",
                "common": "Ekwador"
            },
            "por": {
                "official": "República do Equador",
                "common": "Equador"
            },
            "rus": {
                "official": "Республика Эквадор",
                "common": "Эквадор"
            },
            "slk": {
                "official": "Ekvádorská republika",
                "common": "Ekvádor"
            },
            "spa": {
                "official": "República del Ecuador",
                "common": "Ecuador"
            },
            "swe": {
                "official": "Republiken Ecuador",
                "common": "Ecuador"
            },
            "urd": {
                "official": "جمہوریہ ایکوڈور",
                "common": "ایکواڈور"
            },
            "zho": {
                "official": "厄瓜多尔共和国",
                "common": "厄瓜多尔"
            }
        },
        "latlng": [
            -2.0,
            -77.5
        ],
        "landlocked": false,
        "borders": [
            "COL",
            "PER"
        ],
        "area": 276841.0,
        "demonyms": {
            "eng": {
                "f": "Ecuadorean",
                "m": "Ecuadorean"
            },
            "fra": {
                "f": "Équatorienne",
                "m": "Équatorien"
            }
        },
        "flag": "🇪🇨",
        "maps": {
            "googleMaps": "https://goo.gl/maps/TbX8hUW4gcbRPZiK7",
            "openStreetMaps": "https://www.openstreetmap.org/relation/108089"
        },
        "population": 17643060,
        "gini": {
            "2019": 45.7
        },
        "fifa": "ECU",
        "car": {
            "signs": [
                "EC"
            ],
            "side": "right"
        },
        "timezones": [
            "UTC-06:00",
            "UTC-05:00"
        ],
        "continents": [
            "South America"
        ],
        "flags": {
            "png": "https://flagcdn.com/w320/ec.png",
            "svg": "https://flagcdn.com/ec.svg"
        },
        "coatOfArms": {
            "png": "https://mainfacts.com/media/images/coats_of_arms/ec.png",
            "svg": "https://mainfacts.com/media/images/coats_of_arms/ec.svg"
        },
        "startOfWeek": "monday",
        "capitalInfo": {
            "latlng": [
                -0.22,
                -78.5
            ]
        },
        "postalCode": {
            "format": "@####@",
            "regex": "^([a-zA-Z]\\d{4}[a-zA-Z])$"
        }
    },
    {
        "name": {
            "common": "Chile",
            "official": "Republic of Chile",
            "nativeName": {
                "spa": {
                    "official": "República de Chile",
                    "common": "Chile"
                }
            }
        },
        "tld": [
            ".cl"
        ],
        "cca2": "CL",
        "ccn3": "152",
        "cca3": "CHL",
        "cioc": "CHI",
        "independent": true,
        "status": "officially-assigned",
        "unMember": true,
        "currencies": {
            "CLP": {
                "name": "Chilean peso",
                "symbol": "$"
            }
        },
        "idd": {
            "root": "+5",
            "suffixes": [
                "6"
            ]
        },
        "capital": [
            "Santiago"
        ],
        "altSpellings": [
            "CL",
            "Republic of Chile",
            "República de Chile"
        ],
        "region": "Americas",
        "subregion": "South America",
        "languages": {
            "spa": "Spanish"
        },
        "translations": {
            "ara": {
                "official": "جمهورية تشيلي",
                "common": "تشيلي"
            },
            "ces": {
                "official": "Chilská republika",
                "common": "Chile"
            },
            "cym": {
                "official": "Gweriniaeth Chile",
                "common": "Chile"
            },
            "deu": {
                "official": "Republik Chile",
                "common": "Chile"
            },
            "est": {
                "official": "Tšiili Vabariik",
                "common": "Tšiili"
            },
            "fin": {
                "official": "Chilen tasavalta",
                "common": "Chile"
            },
            "fra": {
                "official": "République du Chili",
                "common": "Chili"
            },
            "hrv": {
                "official": "Republika Čile",
                "common": "Čile"
            },
            "hun": {
                "official": "Chilei Köztársaság",
                "common": "Chile"
            },
            "ita": {
                "official": "Repubblica del Cile",
                "common": "Cile"
            },
            "jpn": {
                "official": "チリ共和国",
                "common": "チリ"
            },
            "kor": {
                "official": "칠레 공화국",
                "common": "칠레"
            },
            "nld": {
                "official": "Republiek Chili",
                "common": "Chili"
            },
            "per": {
                "official": "جمهوری شیلی",
                "common": "شیلی"
            },
            "pol": {
                "official": "Republika Chile",
                "common": "Chile"
            },
            "por": {
                "official": "República do Chile",
                "common": "Chile"
            },
            "rus": {
                "official": "Республика Чили",
                "common": "Чили"
            },
            "slk": {
                "official": "Čílska republika",
                "common": "Čile"
            },
            "spa": {
                "official": "República de Chile",
                "common": "Chile"
            },
            "swe": {
                "official": "Republiken Chile",
                "common": "Chile"
            },
            "urd": {
                "official": "جمہوریہ چلی",
                "common": "چلی"
            },
            "zho": {
                "official": "智利共和国",
                "common": "智利"
            }
        },
        "latlng": [
            -30.0,
            -71.0
        ],
        "landlocked": false,
        "borders": [
            "ARG",
            "BOL",
            "PER"
        ],
        "area": 756102.0,
        "demonyms": {
            "eng": {
                "f": "Chilean",
                "m": "Chilean"
            },
            "fra": {
                "f": "Chilienne",
                "m": "Chilien"
            }
        },
        "flag": "🇨🇱",
        "maps": {
            "googleMaps": "https://goo.gl/maps/XboxyNHh2fAjCPNn9",
            "openStreetMaps": "https://www.openstreetmap.org/relation/167454"
        },
        "population": 19116209,
        "gini": {
            "2017": 44.4
        },
        "fifa": "CHI",
        "car": {
            "signs": [
                "RCH"
            ],
            "side": "right"
        },
        "timezones": [
            "UTC-06:00",
            "UTC-04:00"
        ],
        "continents": [
            "South America"
        ],
        "flags": {
            "png": "https://flagcdn.com/w320/cl.png",
            "svg": "https://flagcdn.com/cl.svg"
        },
        "coatOfArms": {
            "png": "https://mainfacts.com/media/images/coats_of_arms/cl.png",
            "svg": "https://mainfacts.com/media/images/coats_of_arms/cl.svg"
        },
        "startOfWeek": "monday",
        "capitalInfo": {
            "latlng": [
                -33.45,
                -70.67
            ]
        },
        "postalCode": {
            "format": "#######",
            "regex": "^(\\d{7})$"
        }
    },
    {
        "name": {
            "common": "Guatemala",
            "official": "Republic of Guatemala",
            "nativeName": {
                "spa": {
                    "official": "República de Guatemala",
                    "common": "Guatemala"
                }
            }
        },
        "tld": [
            ".gt"
        ],
        "cca2": "GT",
        "ccn3": "320",
        "cca3": "GTM",
        "cioc": "GUA",
        "independent": true,
        "status": "officially-assigned",
        "unMember": true,
        "currencies": {
            "GTQ": {
                "name": "Guatemalan quetzal",
                "symbol": "Q"
            }
        },
        "idd": {
            "root": "+5",
            "suffixes": [
                "02"
            ]
        },
        "capital": [
            "Guatemala City"
        ],
        "altSpellings": [
            "GT"
        ],
        "region": "Americas",
        "subregion": "Central America",
        "languages": {
            "spa": "Spanish"
        },
        "translations": {
            "ara": {
                "official": "جمهورية غواتيمالا",
                "common": "غواتيمالا"
            },
            "ces": {
                "official": "Republika Guatemala",
                "common": "Guatemala"
            },
            "cym": {
                "official": "Republic of Guatemala",
                "common": "Guatemala"
            },
            "deu": {
                "official": "Republik Guatemala",
                "common": "Guatemala"
            },
            "est": {
                "official": "Guatemala Vabariik",
                "common": "Guatemala"
            },
            "fin": {
                "official": "Guatemalan tasavalta",
                "common": "Guatemala"
            },
            "fra": {
                "official": "République du Guatemala",
                "common": "Guatemala"
            },
            "hrv": {
                "official": "Republika Gvatemala",
                "common": "Gvatemala"
            },
            "hun": {
                "official": "Guatemalai Köztársaság",
                "common": "Guatemala"
            },
            "ita": {
                "official": "Repubblica del Guatemala",
                "common": "Guatemala"
            },
            "jpn": {
                "official": "グアテマラ共和国",
                "common": "グアテマラ"
            },
            "kor": {
                "official": "과테말라 공화국",
                "common": "과테말라"
            },
            "nld": {
                "official": "Republiek Guatemala",
                "common": "Guatemala"
            },
            "per": {
                "official": "جمهوری گواتِمالا",
                "common": "گواتِمالا"
            },
            "pol": {
                "official": "Republika Gwatemali",
                "common": "Gwatemala"
            },
            "por": {
                "official": "República da Guatemala",
                "common": "Guatemala"
            },
            "rus": {
                "official": "Республика Гватемала",
                "common": "Гватемала"
            },
            "slk": {
                "official": "Guatemalská republika",
                "common": "Guatemala"
            },
            "spa": {
                "official": "República de Guatemala",
                "common": "Guatemala"
            },
            "swe": {
                "official": "Republiken Guatemala",
                "common": "Guatemala"
            },
            "urd": {
                "official": "جمہوریہ گواتیمالا",
                "common": "گواتیمالا"
            },
            "zho": {
                "official": "危地马拉共和国",
                "common": "危地马拉"
            }
        },
        "latlng": [
            15.5,
            -90.25
        ],
        "landlocked": false,
        "borders": [
            "BLZ",
            "SLV",
            "HND",
            "MEX"
        ],
        "area": 108889.0,
        "demonyms": {
            "eng": {
                "f": "Guatemalan",
                "m": "Guatemalan"
            },
            "fra": {
                "f": "Guatémaltèque",
                "m": "Guatémaltèque"
            }
        },
        "flag": "🇬🇹",
        "maps": {
            "googleMaps": "https://goo.gl/maps/JoRAbem4Hxb9FYbVA",
            "openStreetMaps": "https://www.openstreetmap.org/relation/1521463"
        },
        "population": 16858333,
        "gini": {
            "2014": 48.3
        },
        "fifa": "GUA",
        "car": {
            "signs": [
                "GCA"
            ],
            "side": "right"
        },
        "timezones": [
            "UTC-06:00"
        ],
        "continents": [
            "North America"
        ],
        "flags": {
            "png": "https://flagcdn.com/w320/gt.png",
            "svg": "https://flagcdn.com/gt.svg"
        },
        "coatOfArms": {
            "png": "https://mainfacts.com/media/images/coats_of_arms/gt.png",
            "svg": "https://mainfacts.com/media/images/coats_of_arms/gt.svg"
        },
        "startOfWeek": "monday",
        "capitalInfo": {
            "latlng": [
                14.62,
                -90.52
            ]
        },
        "postalCode": {
            "format": "#####",
            "regex": "^(\\d{5})$"
        }
    },
    {
        "name": {
            "common": "Puerto Rico",
            "official": "Commonwealth of Puerto Rico",
            "nativeName": {
                "eng": {
                    "official": "Commonwealth of Puerto Rico",
                    "common": "Puerto Rico"
                },
                "spa": {
                    "official": "Estado Libre Asociado de Puerto Rico",
                    "common": "Puerto Rico"
                }
            }
        },
        "tld": [
            ".pr"
        ],
        "cca2": "PR",
        "ccn3": "630",
        "cca3": "PRI",
        "cioc": "PUR",
        "independent": false,
        "status": "officially-assigned",
        "unMember": false,
        "currencies": {
            "USD": {
                "name": "United States dollar",
                "symbol": "$"
            }
        },
        "idd": {
            "root": "+1",
            "suffixes": [
                "787",
                "939"
            ]
        },
        "capital": [
            "San Juan"
        ],
        "altSpellings": [
            "PR",
            "Commonwealth of Puerto Rico",
            "Estado Libre Asociado de Puerto Rico"
        ],
        "region": "Americas",
        "subregion": "Caribbean",
        "languages": {
            "eng": "English",
            "spa": "Spanish"
        },
        "translations": {
            "ara": {
                "official": "كومنولث بويرتوريكو",
                "common": "بويرتوريكو"
            },
            "ces": {
                "official": "Portoriko",
                "common": "Portoriko"
            },
            "cym": {
                "official": "Commonwealth of Puerto Rico",
                "common": "Puerto Rico"
            },
            "deu": {
                "official": "Freistaat Puerto Rico",
                "common": "Puerto Rico"
            },
            "est": {
                "official": "Puerto Rico Ühendus",
                "common": "Puerto Rico"
            },
            "fin": {
                "official": "Puerto Rico",
                "common": "Puerto Rico"
            },
            "fra": {
                "official": "Porto Rico",
                "common": "Porto Rico"
            },
            "hrv": {
                "official": "Zajednica Puerto Rico",
                "common": "Portoriko"
            },
            "hun": {
                "official": "Puerto Rico",
                "common": "Puerto Rico"
            },
            "ita": {
                "official": "Commonwealth di Porto Rico",
                "common": "Porto Rico"
            },
            "jpn": {
                "official": "プエルトリコのコモンウェルス",
                "common": "プエルトリコ"
            },
            "kor": {
                "official": "푸에르토리코",
                "common": "푸에르토리코"
            },
            "nld": {
                "official": "Gemenebest van Puerto Rico",
                "common": "Puerto Rico"
            },
            "per": {
                "official": "قلمرو همسود پورتوریکو",
                "common": "پورتوریکو"
            },
            "pol": {
                "official": "Wolne Stowarzyszone Państwo Portoryko",
                "common": "Portoryko"
            },
            "por": {
                "official": "Commonwealth of Puerto Rico",
                "common": "Porto Rico"
            },
            "rus": {
                "official": "Содружество Пуэрто-Рико",
                "common": "Пуэрто-Рико"
            },
            "slk": {
                "official": "Portorické spoločenstvo",
                "common": "Portoriko"
            },
            "spa": {
                "official": "Asociado de Puerto Rico",
                "common": "Puerto Rico"
            },
            "swe": {
                "official": "Puerto Rico",
                "common": "Puerto Rico"
            },
            "urd": {
                "official": " دولتِ مشترکہ پورٹو ریکو",
                "common": "پورٹو ریکو"
            },
            "zho": {
                "official": "波多黎各联邦",
                "common": "波多黎各"
            }
        },
        "latlng": [
            18.25,
            -66.5
        ],
        "landlocked": false,
        "area": 8870.0,
        "demonyms": {
            "eng": {
                "f": "Puerto Rican",
                "m": "Puerto Rican"
            },
            "fra": {
                "f": "Portoricaine",
                "m": "Portoricain"
            }
        },
        "flag": "🇵🇷",
        "maps": {
            "googleMaps": "https://goo.gl/maps/sygfDbtwn389wu8x5",
            "openStreetMaps": "https://www.openstreetmap.org/relation/4422604"
        },
        "population": 3194034,
        "fifa": "PUR",
        "car": {
            "signs": [
                "USA"
            ],
            "side": "right"
        },
        "timezones": [
            "UTC-04:00"
        ],
        "continents": [
            "North America"
        ],
        "flags": {
            "png": "https://flagcdn.com/w320/pr.png",
            "svg": "https://flagcdn.com/pr.svg"
        },
        "coatOfArms": {},
        "startOfWeek": "monday",
        "capitalInfo": {
            "latlng": [
                18.47,
                -66.12
            ]
        },
        "postalCode": {
            "format": "#####-####",
            "regex": "^(\\d{9})$"
        }
    },
    {
        "name": {
            "common": "Dominican Republic",
            "official": "Dominican Republic",
            "nativeName": {
                "spa": {
                    "official": "República Dominicana",
                    "common": "República Dominicana"
                }
            }
        },
        "tld": [
            ".do"
        ],
        "cca2": "DO",
        "ccn3": "214",
        "cca3": "DOM",
        "cioc": "DOM",
        "independent": true,
        "status": "officially-assigned",
        "unMember": true,
        "currencies": {
            "DOP": {
                "name": "Dominican peso",
                "symbol": "$"
            }
        },
        "idd": {
            "root": "+1",
            "suffixes": [
                "809",
                "829",
                "849"
            ]
        },
        "capital": [
            "Santo Domingo"
        ],
        "altSpellings": [
            "DO"
        ],
        "region": "Americas",
        "subregion": "Caribbean",
        "languages": {
            "spa": "Spanish"
        },
        "translations": {
            "ara": {
                "official": "جمهورية الدومينيكان",
                "common": "جمهورية الدومينيكان"
            },
            "ces": {
                "official": "Dominikánská republika",
                "common": "Dominikánská republika"
            },
            "cym": {
                "official": "Gweriniaeth Dominica",
                "common": "Gweriniaeth Dominica"
            },
            "deu": {
                "official": "Dominikanische Republik",
                "common": "Dominikanische Republik"
            },
            "est": {
                "official": "Dominikaani Vabariik",
                "common": "Dominikaani Vabariik"
            },
            "fin": {
                "official": "Dominikaaninen tasavalta",
                "common": "Dominikaaninen tasavalta"
            },
            "fra": {
                "official": "République Dominicaine",
                "common": "République dominicaine"
            },
            "hrv": {
                "official": "Dominikanska Republika",
                "common": "Dominikanska Republika"
            },
            "hun": {
                "official": "Dominikai Köztársaság",
                "common": "Dominikai Köztársaság"
            },
            "ita": {
                "official": "Repubblica Dominicana",
                "common": "Repubblica Dominicana"
            },
            "jpn": {
                "official": "ドミニカ共和国",
                "common": "ドミニカ共和国"
            },
            "kor": {
                "official": "도미니카 공화국",
                "common": "도미니카 공화국"
            },
            "nld": {
                "official": "Dominicaanse Republiek",
                "common": "Dominicaanse Republiek"
            },
            "per": {
                "official": "جمهوری دومینیکن",
                "common": "جمهوری دومینیکن"
            },
            "pol": {
                "official": "Republika Dominikańska",
                "common": "Dominikana"
            },
            "por": {
                "official": "República Dominicana",
                "common": "República Dominicana"
            },
            "rus": {
                "official": "Доминиканская Республика",
                "common": "Доминиканская Республика"
            },
            "slk": {
                "official": "Dominikánska republika",
                "common": "Dominikánska republika"
            },
            "spa": {
                "official": "República Dominicana",
                "common": "República Dominicana"
            },
            "swe": {
                "official": "Dominikanska republiken",
                "common": "Dominikanska republiken"
            },
            "urd": {
                "official": "جمہوریہ ڈومینیکن",
                "common": "ڈومینیکن"
            },
            "zho": {
                "official": "多明尼加共和国",
                "common": "多明尼加"
            }
        },
        "latlng": [
            19.0,
            -70.66666666
        ],
        "landlocked": false,
        "borders": [
            "HTI"
        ],
        "area": 48671.0,
        "demonyms": {
            "eng": {
                "f": "Dominican",
                "m": "Dominican"
            },
            "fra": {
                "f": "Dominicaine",
                "m": "Dominicain"
            }
        },
        "flag": "🇩🇴",
        "maps": {
            "googleMaps": "https://goo.gl/maps/soxooTHxEeiAbn3UA",
            "openStreetMaps": "https://www.openstreetmap.org/relation/307828"
        },
        "population": 10847904,
        "gini": {
            "2019": 41.9
        },
        "fifa": "DOM",
        "car": {
            "signs": [
                "DOM"
            ],
            "side": "right"
        },
        "timezones": [
            "UTC-04:00"
        ],
        "continents": [
            "North America"
        ],
        "flags": {
            "png": "https://flagcdn.com/w320/do.png",
            "svg": "https://flagcdn.com/do.svg"
        },
        "coatOfArms": {
            "png": "https://mainfacts.com/media/images/coats_of_arms/do.png",
            "svg": "https://mainfacts.com/media/images/coats_of_arms/do.svg"
        },
        "startOfWeek": "monday",
        "capitalInfo": {
            "latlng": [
                18.47,
                -69.9
            ]
        },
        "postalCode": {
            "format": "#####",
            "regex": "^(\\d{5})$"
        }
    },
    {
        "name": {
            "common": "Costa Rica",
            "official": "Republic of Costa Rica",
            "nativeName": {
                "spa": {
                    "official": "República de Costa Rica",
                    "common": "Costa Rica"
                }
            }
        },
        "tld": [
            ".cr"
        ],
        "cca2": "CR",
        "ccn3": "188",
        "cca3": "CRI",
        "cioc": "CRC",
        "independent": true,
        "status": "officially-assigned",
        "unMember": true,
        "currencies": {
            "CRC": {
                "name": "Costa Rican colón",
                "symbol": "₡"
            }
        },
        "idd": {
            "root": "+5",
            "suffixes": [
                "06"
            ]
        },
        "capital": [
            "San José"
        ],
        "altSpellings": [
            "CR",
            "Republic of Costa Rica",
            "República de Costa Rica"
        ],
        "region": "Americas",
        "subregion": "Central America",
        "languages": {
            "spa": "Spanish"
        },
        "translations": {
            "ara": {
                "official": "جمهورية كوستاريكا",
                "common": "كوستاريكا"
            },
            "ces": {
                "official": "Kostarická republika",
                "common": "Kostarika"
            },
            "cym": {
                "official": "Gweriniaeth Costa Rica",
                "common": "Costa Rica"
            },
            "deu": {
                "official": "Republik Costa Rica",
                "common": "Costa Rica"
            },
            "est": {
                "official": "Costa Rica Vabariik",
                "common": "Costa Rica"
            },
            "fin": {
                "official": "Costa Rican tasavalta",
                "common": "Costa Rica"
            },
            "fra": {
                "official": "République du Costa Rica",
                "common": "Costa Rica"
            },
            "hrv": {
                "official": "Republika Kostarika",
                "common": "Kostarika"
            },
            "hun": {
                "official": "Costa Rica-i Köztársaság",
                "common": "Costa Rica"
            },
            "ita": {
                "official": "Repubblica di Costa Rica",
                "common": "Costa Rica"
            },
            "jpn": {
                "official": "コスタリカ共和国",
                "common": "コスタリカ"
            },
            "kor": {
                "official": "코스타리카 공화국",
                "common": "코스타리카"
            },
            "nld": {
                "official": "Republiek Costa Rica",
                "common": "Costa Rica"
            },
            "per": {
                "official": "جمهوری کاستاریکا",
                "common": "کاستاریکا"
            },
            "pol": {
                "official": "Republika Kostaryki",
                "common": "Kostaryka"
            },
            "por": {
                "official": "República da Costa Rica",
                "common": "Costa Rica"
            },
            "rus": {
                "official": "Республика Коста-Рика",
                "common": "Коста-Рика"
            },
            "slk": {
                "official": "Kostarická republika",
                "common": "Kostarika"
            },
            "spa": {
                "official": "República de Costa Rica",
                "common": "Costa Rica"
            },
            "swe": {
                "official": "Republiken Costa Rica",
                "common": "Costa Rica"
            },
            "urd": {
                "official": "جمہوریہ کوسٹاریکا",
                "common": "کوسٹاریکا"
            },
            "zho": {
                "official": "哥斯达黎加共和国",
                "common": "哥斯达黎加"
            }
        },
        "latlng": [
            10.0,
            -84.0
        ],
        "landlocked": false,
        "borders": [
            "NIC",
            "PAN"
        ],
        "area": 51100.0,
        "demonyms": {
            "eng": {
                "f": "Costa Rican",
                "m": "Costa Rican"
            },
            "fra": {
                "f": "Costaricaine",
                "m": "Costaricain"
            }
        },
        "flag": "🇨🇷",
        "maps": {
            "googleMaps": "https://goo.gl/maps/RFiwytjvNrpfKN7k6",
            "openStreetMaps": "https://www.openstreetmap.org/relation/287667"
        },
        "population": 5094114,
        "gini": {
            "2019": 48.2
        },
        "fifa": "CRC",
        "car": {
            "signs": [
                "CR"
            ],
            "side": "right"
        },
        "timezones": [
            "UTC-06:00"
        ],
        "continents": [
            "North America"
        ],
        "flags": {
            "png": "https://flagcdn.com/w320/cr.png",
            "svg": "https://flagcdn.com/cr.svg"
        },
        "coatOfArms": {
            "png": "https://mainfacts.com/media/images/coats_of_arms/cr.png",
            "svg": "https://mainfacts.com/media/images/coats_of_arms/cr.svg"
        },
        "startOfWeek": "monday",
        "capitalInfo": {
            "latlng": [
                9.93,
                -84.09
            ]
        },
        "postalCode": {
            "format": "####",
            "regex": "^(\\d{4})$"
        }
    },
    {
        "name": {
            "common": "Equatorial Guinea",
            "official": "Republic of Equatorial Guinea",
            "nativeName": {
                "fra": {
                    "official": "République de la Guinée Équatoriale",
                    "common": "Guinée équatoriale"
                },
                "por": {
                    "official": "República da Guiné Equatorial",
                    "common": "Guiné Equatorial"
                },
                "spa": {
                    "official": "República de Guinea Ecuatorial",
                    "common": "Guinea Ecuatorial"
                }
            }
        },
        "tld": [
            ".gq"
        ],
        "cca2": "GQ",
        "ccn3": "226",
        "cca3": "GNQ",
        "cioc": "GEQ",
        "independent": true,
        "status": "officially-assigned",
        "unMember": true,
        "currencies": {
            "XAF": {
                "name": "Central African CFA franc",
                "symbol": "Fr"
            }
        },
        "idd": {
            "root": "+2",
            "suffixes": [
                "40"
            ]
        },
        "capital": [
            "Malabo"
        ],
        "altSpellings": [
            "GQ",
            "Republic of Equatorial Guinea",
            "República de Guinea Ecuatorial",
            "République de Guinée équatoriale",
            "República da Guiné Equatorial"
        ],
        "region": "Africa",
        "subregion": "Middle Africa",
        "languages": {
            "fra": "French",
            "por": "Portuguese",
            "spa": "Spanish"
        },
        "translations": {
            "ara": {
                "official": "جمهورية غينيا الاستوائية",
                "common": "غينيا الاستوائية"
            },
            "ces": {
                "official": "Republika Rovníková Guinea",
                "common": "Rovníková Guinea"
            },
            "cym": {
                "official": "Gweriniaeth Gini Gyhydeddol",
                "common": "Gini Gyhydeddol"
            },
            "deu": {
                "official": "Republik Äquatorialguinea",
                "common": "Äquatorialguinea"
            },
            "est": {
                "official": "Ekvatoriaal-Guinea Vabariik",
                "common": "Ekvatoriaal-Guinea"
            },
            "fin": {
                "official": "Päiväntasaajan Guinean tasavalta",
                "common": "Päiväntasaajan Guinea"
            },
            "fra": {
                "official": "République de Guinée équatoriale",
                "common": "Guinée équatoriale"
            },
            "hrv": {
                "official": "Republika Ekvatorska Gvineja",
                "common": "Ekvatorijalna Gvineja"
            },
            "hun": {
                "official": "Egyenlítői-Guinea-i Köztársaság",
                "common": "Egyenlítői-Guinea"
            },
            "ita": {
                "official": "Repubblica della Guinea Equatoriale",
                "common": "Guinea Equatoriale"
            },
            "jpn": {
                "official": "赤道ギニア共和国",
                "common": "赤道ギニア"
            },
            "kor": {
                "official": "적도 기니 공화국",
                "common": "적도 기니"
            },
            "nld": {
                "official": "Republiek Equatoriaal-Guinea",
                "common": "Equatoriaal-Guinea"
            },
            "per": {
                "official": "جمهوری گینه استوایی",
                "common": "گینه استوایی"
            },
            "pol": {
                "official": "Republika Gwinei Równikowej",
                "common": "Gwinea Równikowa"
            },
            "por": {
                "official": "República da Guiné Equatorial",
                "common": "Guiné Equatorial"
            },
            "rus": {
                "official": "Республика Экваториальная Гвинея",
                "common": "Экваториальная Гвинея"
            },
            "slk": {
                "official": "Republika rovníkovej Guiney",
                "common": "Rovníková Guinea"
            },
            "spa": {
                "official": "República de Guinea Ecuatorial",
                "common": "Guinea Ecuatorial"
            },
            "swe": {
                "official": "Republiken Ekvatorialguinea",
                "common": "Ekvatorialguinea"
            },
            "urd": {
                "official": "جمہوریہ استوائی گنی",
                "common": "استوائی گنی"
            },
            "zho": {
                "official": "赤道几内亚共和国",
                "common": "赤道几内亚"
            }
        },
        "latlng": [
            2.0,
            10.0
        ],
        "landlocked": false,
        "borders": [
            "CMR",
            "GAB"
        ],
        "area": 28051.0,
        "demonyms": {
            "eng": {
                "f": "Equatorial Guinean",
                "m": "Equatorial Guinean"
            },
            "fra": {
                "f": "Équato-guinéenne",
                "m": "Équato-guinéen"
            }
        },
        "flag": "🇬🇶",
        "maps": {
            "googleMaps": "https://goo.gl/maps/ucWfFd8aW1FbGMva9",
            "openStreetMaps": "https://www.openstreetmap.org/relation/192791"
        },
        "population": 1402985,
        "fifa": "EQG",
        "car": {
            "signs": [
                "GQ"
            ],
            "side": "right"
        },
        "timezones": [
            "UTC+01:00"
        ],
        "continents": [
            "Africa"
        ],
        "flags": {
            "png": "https://flagcdn.com/w320/gq.png",
            "svg": "https://flagcdn.com/gq.svg"
        },
        "coatOfArms": {
            "png": "https://mainfacts.com/media/images/coats_of_arms/gq.png",
            "svg": "https://mainfacts.com/media/images/coats_of_arms/gq.svg"
        },
        "startOfWeek": "monday",
        "capitalInfo": {
            "latlng": [
                3.75,
                8.78
            ]
        }
    },
    {
        "name": {
            "common": "Cuba",
            "official": "Republic of Cuba",
            "nativeName": {
                "spa": {
                    "official": "República de Cuba",
                    "common": "Cuba"
                }
            }
        },
        "tld": [
            ".cu"
        ],
        "cca2": "CU",
        "ccn3": "192",
        "cca3": "CUB",
        "cioc": "CUB",
        "independent": true,
        "status": "officially-assigned",
        "unMember": true,
        "currencies": {
            "CUC": {
                "name": "Cuban convertible peso",
                "symbol": "$"
            },
            "CUP": {
                "name": "Cuban peso",
                "symbol": "$"
            }
        },
        "idd": {
            "root": "+5",
            "suffixes": [
                "3"
            ]
        },
        "capital": [
            "Havana"
        ],
        "altSpellings": [
            "CU",
            "Republic of Cuba",
            "República de Cuba"
        ],
        "region": "Americas",
        "subregion": "Caribbean",
        "languages": {
            "spa": "Spanish"
        },
        "translations": {
            "ara": {
                "official": "جمهورية كوبا",
                "common": "كوبا"
            },
            "ces": {
                "official": "Kubánská republika",
                "common": "Kuba"
            },
            "cym": {
                "official": "Gweriniaeth Ciwba",
                "common": "Ciwba"
            },
            "deu": {
                "official": "Republik Kuba",
                "common": "Kuba"
            },
            "est": {
                "official": "Kuuba Vabariik",
                "common": "Kuuba"
            },
            "fin": {
                "official": "Kuuban tasavalta",
                "common": "Kuuba"
            },
            "fra": {
                "official": "République de Cuba",
                "common": "Cuba"
            },
            "hrv": {
                "official": "Republika Kuba",
                "common": "Kuba"
            },
            "hun": {
                "official": "Kubai Köztársaság",
                "common": "Kuba"
            },
            "ita": {
                "official": "Repubblica di Cuba",
                "common": "Cuba"
            },
            "jpn": {
                "official": "キューバ共和国",
                "common": "キューバ"
            },
            "kor": {
                "official": "쿠바 공화국",
                "common": "쿠바"
            },
            "nld": {
                "official": "Republiek Cuba",
                "common": "Cuba"
            },
            "per": {
                "official": "جمهوری کوبا",
                "common": "کوبا"
            },
            "pol": {
                "official": "Republika Kuby",
                "common": "Kuba"
            },
            "por": {
                "official": "República de Cuba",
                "common": "Cuba"
            },
            "rus": {
                "official": "Республика Куба",
                "common": "Куба"
            },
            "slk": {
                "official": "Kubánska republika",
                "common": "Kuba"
            },
            "spa": {
                "official": "República de Cuba",
                "common": "Cuba"
            },
            "swe": {
                "official": "Republiken Kuba",
                "common": "Kuba"
            },
            "urd": {
                "official": "جمہوریہ کیوبا",
                "common": "کیوبا"
            },
            "zho": {
                "official": "古巴共和国",
                "common": "古巴"
            }
        },
        "latlng": [
            21.5,
            -80.0
        ],
        "landlocked": false,
        "area": 109884.0,
        "demonyms": {
            "eng": {
                "f": "Cuban",
                "m": "Cuban"
            },
            "fra": {
                "f": "Cubaine",
                "m": "Cubain"
            }
        },
        "flag": "🇨🇺",
        "maps": {
            "googleMaps": "https://goo.gl/maps/1dDw1QfZspfMUTm99",
            "openStreetMaps": "https://www.openstreetmap.org/relation/307833"
        },
        "population": 11326616,
        "fifa": "CUB",
        "car": {
            "signs": [
                "C"
            ],
            "side": "right"
        },
        "timezones": [
            "UTC-05:00"
        ],
        "continents": [
            "North America"
        ],
        "flags": {
            "png": "https://flagcdn.com/w320/cu.png",
            "svg": "https://flagcdn.com/cu.svg"
        },
        "coatOfArms": {
            "png": "https://mainfacts.com/media/images/coats_of_arms/cu.png",
            "svg": "https://mainfacts.com/media/images/coats_of_arms/cu.svg"
        },
        "startOfWeek": "monday",
        "capitalInfo": {
            "latlng": [
                23.12,
                -82.35
            ]
        },
        "postalCode": {
            "format": "CP #####",
            "regex": "^(?:CP)*(\\d{5})$"
        }
    },
    {
        "name": {
            "common": "Western Sahara",
            "official": "Sahrawi Arab Democratic Republic",
            "nativeName": {
                "ber": {
                    "official": "Sahrawi Arab Democratic Republic",
                    "common": "Western Sahara"
                },
                "mey": {
                    "official": "الجمهورية العربية الصحراوية الديمقراطية",
                    "common": "الصحراء الغربية"
                },
                "spa": {
                    "official": "República Árabe Saharaui Democrática",
                    "common": "Sahara Occidental"
                }
            }
        },
        "tld": [
            ".eh"
        ],
        "cca2": "EH",
        "ccn3": "732",
        "cca3": "ESH",
        "independent": false,
        "status": "officially-assigned",
        "unMember": false,
        "currencies": {
            "DZD": {
                "name": "Algerian dinar",
                "symbol": "دج"
            },
            "MAD": {
                "name": "Moroccan dirham",
                "symbol": "DH"
            },
            "MRU": {
                "name": "Mauritanian ouguiya",
                "symbol": "UM"
            }
        },
        "idd": {
            "root": "+2",
            "suffixes": [
                "125288",
                "125289"
            ]
        },
        "capital": [
            "El Aaiún"
        ],
        "altSpellings": [
            "EH",
            "Taneẓroft Tutrimt"
        ],
        "region": "Africa",
        "subregion": "Northern Africa",
        "languages": {
            "ber": "Berber",
            "mey": "Hassaniya",
            "spa": "Spanish"
        },
        "translations": {
            "ara": {
                "official": "الجمهورية العربية الصحراوية الديمقراطية",
                "common": "الصحراء الغربية"
            },
            "ces": {
                "official": "Západní Sahara",
                "common": "Západní Sahara"
            },
            "cym": {
                "official": "Sahrawi Arab Democratic Republic",
                "common": "Western Sahara"
            },
            "deu": {
                "official": "Demokratische Arabische Republik Sahara",
                "common": "Westsahara"
            },
            "est": {
                "official": "Lääne-Sahara",
                "common": "Lääne-Sahara"
            },
            "fin": {
                "official": "Länsi-Sahara",
                "common": "Länsi-Sahara"
            },
            "fra": {
                "official": "République arabe sahraouie démocratique",
                "common": "Sahara Occidental"
            },
            "hrv": {
                "official": "Sahrawi Arab Demokratska Republika",
                "common": "Zapadna Sahara"
            },
            "hun": {
                "official": "Nyugat-Szahara",
                "common": "Nyugat-Szahara"
            },
            "ita": {
                "official": "Repubblica Araba Saharawi Democratica",
                "common": "Sahara Occidentale"
            },
            "jpn": {
                "official": "サハラアラブ民主共和国",
                "common": "西サハラ"
            },
            "kor": {
                "official": "사하라 아랍 민주 공화국",
                "common": "서사하라"
            },
            "nld": {
                "official": "Sahrawi Arabische Democratische Republiek",
                "common": "Westelijke Sahara"
            },
            "per": {
                "official": "صحرای غربی",
                "common": "صحرای غربی"
            },
            "pol": {
                "official": "Saharyjska Arabska Republika Demokratyczna",
                "common": "Sahara Zachodnia"
            },
            "por": {
                "official": "República Árabe Saharaui Democrática",
                "common": "Saara Ocidental"
            },
            "rus": {
                "official": "Sahrawi Арабская Демократическая Республика",
                "common": "Западная Сахара"
            },
            "slk": {
                "official": "Západná Sahara",
                "common": "Západná Sahara"
            },
            "spa": {
                "official": "República Árabe Saharaui Democrática",
                "common": "Sahara Occidental"
            },
            "swe": {
                "official": "Västsahara",
                "common": "Västsahara"
            },
            "urd": {
                "official": "صحراوی عرب عوامی جمہوریہ",
                "common": "مغربی صحارا"
            },
            "zho": {
                "official": "阿拉伯撒哈拉民主共和国",
                "common": "西撒哈拉"
            }
        },
        "latlng": [
            24.5,
            -13.0
        ],
        "landlocked": false,
        "borders": [
            "DZA",
            "MRT",
            "MAR"
        ],
        "area": 266000.0,
        "demonyms": {
            "eng": {
                "f": "Sahrawi",
                "m": "Sahrawi"
            }
        },
        "flag": "🇪🇭",
        "maps": {
            "googleMaps": "https://goo.gl/maps/7nU3mB69vP6zQp7A8",
            "openStreetMaps": "https://www.openstreetmap.org/relation/5441968"
        },
        "population": 510713,
        "car": {
            "signs": [
                ""
            ],
            "side": "right"
        },
        "timezones": [
            "UTC+00:00"
        ],
        "continents": [
            "Africa"
        ],
        "flags": {
            "png": "https://flagcdn.com/w320/eh.png",
            "svg": "https://flagcdn.com/eh.svg"
        },
        "coatOfArms": {},
        "startOfWeek": "monday",
        "capitalInfo": {
            "latlng": [
                -13.28,
                27.14
            ]
        }
    },
    {
        "name": {
            "common": "Spain",
            "official": "Kingdom of Spain",
            "nativeName": {
                "spa": {
                    "official": "Reino de España",
                    "common": "España"
                }
            }
        },
        "tld": [
            ".es"
        ],
        "cca2": "ES",
        "ccn3": "724",
        "cca3": "ESP",
        "cioc": "ESP",
        "independent": true,
        "status": "officially-assigned",
        "unMember": true,
        "currencies": {
            "EUR": {
                "name": "Euro",
                "symbol": "€"
            }
        },
        "idd": {
            "root": "+3",
            "suffixes": [
                "4"
            ]
        },
        "capital": [
            "Madrid"
        ],
        "altSpellings": [
            "ES",
            "Kingdom of Spain",
            "Reino de España"
        ],
        "region": "Europe",
        "subregion": "Southern Europe",
        "languages": {
            "spa": "Spanish"
        },
        "translations": {
            "ara": {
                "official": "مملكة إسبانيا",
                "common": "إسبانيا"
            },
            "ces": {
                "official": "Španělské království",
                "common": "Španělsko"
            },
            "cym": {
                "official": "Kingdom of Spain",
                "common": "Spain"
            },
            "deu": {
                "official": "Königreich Spanien",
                "common": "Spanien"
            },
            "est": {
                "official": "Hispaania Kuningriik",
                "common": "Hispaania"
            },
            "fin": {
                "official": "Espanjan kuningaskunta",
                "common": "Espanja"
            },
            "fra": {
                "official": "Royaume d'Espagne",
                "common": "Espagne"
            },
            "hrv": {
                "official": "Kraljevina Španjolska",
                "common": "Španjolska"
            },
            "hun": {
                "official": "Spanyol Királyság",
                "common": "Spanyolország"
            },
            "ita": {
                "official": "Regno di Spagna",
                "common": "Spagna"
            },
            "jpn": {
                "official": "スペイン王国",
                "common": "スペイン"
            },
            "kor": {
                "official": "에스파냐 왕국",
                "common": "스페인"
            },
            "nld": {
                "official": "Koninkrijk Spanje",
                "common": "Spanje"
            },
            "per": {
                "official": "پادشاهی اسپانیا",
                "common": "اسپانیا"
            },
            "pol": {
                "official": "Królestwo Hiszpanii ",
                "common": "Hiszpania"
            },
            "por": {
                "official": "Reino de Espanha",
                "common": "Espanha"
            },
            "rus": {
                "official": "Королевство Испания",
                "common": "Испания"
            },
            "slk": {
                "official": "Španielske kráľovstvo",
                "common": "Španielsko"
            },
            "spa": {
                "official": "Reino de España",
                "common": "España"
            },
            "swe": {
                "official": "Konungariket Spanien",
                "common": "Spanien"
            },
            "urd": {
                "official": "مملکتِ ہسپانیہ",
                "common": "ہسپانیہ"
            },
            "zho": {
                "official": "西班牙王国",
                "common": "西班牙"
            }
        },
        "latlng": [
            40.0,
            -4.0
        ],
        "landlocked": false,
        "borders": [
            "AND",
            "FRA",
            "GIB",
            "PRT",
            "MAR"
        ],
        "area": 505992.0,
        "demonyms": {
            "eng": {
                "f": "Spanish",
                "m": "Spanish"
            },
            "fra": {
                "f": "Espagnole",
                "m": "Espagnol"
            }
        },
        "flag": "🇪🇸",
        "maps": {
            "googleMaps": "https://goo.gl/maps/138JaXW8EZzRVitY9",
            "openStreetMaps": "https://www.openstreetmap.org/relation/1311341"
        },
        "population": 47351567,
        "gini": {
            "2018": 34.7
        },
        "fifa": "ESP",
        "car": {
            "signs": [
                "E"
            ],
            "side": "right"
        },
        "timezones": [
            "UTC",
            "UTC+01:00"
        ],
        "continents": [
            "Europe"
        ],
        "flags": {
            "png": "https://flagcdn.com/w320/es.png",
            "svg": "https://flagcdn.com/es.svg"
        },
        "coatOfArms": {
            "png": "https://mainfacts.com/media/images/coats_of_arms/es.png",
            "svg": "https://mainfacts.com/media/images/coats_of_arms/es.svg"
        },
        "startOfWeek": "monday",
        "capitalInfo": {
            "latlng": [
                40.4,
                -3.68
            ]
        },
        "postalCode": {
            "format": "#####",
            "regex": "^(\\d{5})$"
        }
    },
    {
        "name": {
            "common": "Guam",
            "official": "Guam",
            "nativeName": {
                "cha": {
                    "official": "Guåhån",
                    "common": "Guåhån"
                },
                "eng": {
                    "official": "Guam",
                    "common": "Guam"
                },
                "spa": {
                    "official": "Guam",
                    "common": "Guam"
                }
            }
        },
        "tld": [
            ".gu"
        ],
        "cca2": "GU",
        "ccn3": "316",
        "cca3": "GUM",
        "cioc": "GUM",
        "independent": false,
        "status": "officially-assigned",
        "unMember": false,
        "currencies": {
            "USD": {
                "name": "United States dollar",
                "symbol": "$"
            }
        },
        "idd": {
            "root": "+1",
            "suffixes": [
                "671"
            ]
        },
        "capital": [
            "Hagåtña"
        ],
        "altSpellings": [
            "GU",
            "Guåhån"
        ],
        "region": "Oceania",
        "subregion": "Micronesia",
        "languages": {
            "cha": "Chamorro",
            "eng": "English",
            "spa": "Spanish"
        },
        "translations": {
            "ara": {
                "official": "غوام",
                "common": "غوام"
            },
            "ces": {
                "official": "Guam",
                "common": "Guam"
            },
            "cym": {
                "official": "Guam",
                "common": "Guam"
            },
            "deu": {
                "official": "Guam",
                "common": "Guam"
            },
            "est": {
                "official": "Guami ala",
                "common": "Guam"
            },
            "fin": {
                "official": "Guam",
                "common": "Guam"
            },
            "fra": {
                "official": "Guam",
                "common": "Guam"
            },
            "hrv": {
                "official": "Guam",
                "common": "Guam"
            },
            "hun": {
                "official": "Guam",
                "common": "Guam"
            },
            "ita": {
                "official": "Guam",
                "common": "Guam"
            },
            "jpn": {
                "official": "グアム",
                "common": "グアム"
            },
            "kor": {
                "official": "괌",
                "common": "괌"
            },
            "nld": {
                "official": "Guam",
                "common": "Guam"
            },
            "per": {
                "official": "گوآم",
                "common": "گوآم"
            },
            "pol": {
                "official": "Terytorium Guamu",
                "common": "Guam"
            },
            "por": {
                "official": "Guam",
                "common": "Guam"
            },
            "rus": {
                "official": "Гуам",
                "common": "Гуам"
            },
            "slk": {
                "official": "Guam",
                "common": "Guam"
            },
            "spa": {
                "official": "Guam",
                "common": "Guam"
            },
            "swe": {
                "official": "Guam",
                "common": "Guam"
            },
            "urd": {
                "official": "گوام",
                "common": "گوام"
            },
            "zho": {
                "official": "关岛",
                "common": "关岛"
            }
        },
        "latlng": [
            13.46666666,
            144.78333333
        ],
        "landlocked": false,
        "area": 549.0,
        "demonyms": {
            "eng": {
                "f": "Guamanian",
                "m": "Guamanian"
            }
        },
        "flag": "🇬🇺",
        "maps": {
            "googleMaps": "https://goo.gl/maps/Xfnq2i279b18cH3C9",
            "openStreetMaps": "https://www.openstreetmap.org/relation/306001"
        },
        "population": 168783,
        "fifa": "GUM",
        "car": {
            "signs": [
                "USA"
            ],
            "side": "right"
        },
        "timezones": [
            "UTC+10:00"
        ],
        "continents": [
            "Oceania"
        ],
        "flags": {
            "png": "https://flagcdn.com/w320/gu.png",
            "svg": "https://flagcdn.com/gu.svg"
        },
        "coatOfArms": {
            "png": "https://mainfacts.com/media/images/coats_of_arms/gu.png",
            "svg": "https://mainfacts.com/media/images/coats_of_arms/gu.svg"
        },
        "startOfWeek": "monday",
        "capitalInfo": {
            "latlng": [
                13.48,
                144.75
            ]
        },
        "postalCode": {
            "format": "969##",
            "regex": "^(969\\d{2})$"
        }
    },
    {
        "name": {
            "common": "Venezuela",
            "official": "Bolivarian Republic of Venezuela",
            "nativeName": {
                "spa": {
                    "official": "República Bolivariana de Venezuela",
                    "common": "Venezuela"
                }
            }
        },
        "tld": [
            ".ve"
        ],
        "cca2": "VE",
        "ccn3": "862",
        "cca3": "VEN",
        "cioc": "VEN",
        "independent": true,
        "status": "officially-assigned",
        "unMember": true,
        "currencies": {
            "VES": {
                "name": "Venezuelan bolívar soberano",
                "symbol": "Bs.S."
            }
        },
        "idd": {
            "root": "+5",
            "suffixes": [
                "8"
            ]
        },
        "capital": [
            "Caracas"
        ],
        "altSpellings": [
            "VE",
            "Bolivarian Republic of Venezuela",
            "Venezuela, Bolivarian Republic of",
            "República Bolivariana de Venezuela"
        ],
        "region": "Americas",
        "subregion": "South America",
        "languages": {
            "spa": "Spanish"
        },
        "translations": {
            "ara": {
                "official": "جمهورية فنزويلا البوليفارية",
                "common": "فنزويلا"
            },
            "ces": {
                "official": "Bolívarská republika Venezuela",
                "common": "Venezuela"
            },
            "cym": {
                "official": "Bolivarian Republic of Venezuela",
                "common": "Venezuela"
            },
            "deu": {
                "official": "Bolivarische Republik Venezuela",
                "common": "Venezuela"
            },
            "est": {
                "official": "Venezuela Bolívari Vabariik",
                "common": "Venezuela"
            },
            "fin": {
                "official": "Venezuelan bolivariaainen tasavalta",
                "common": "Venezuela"
            },
            "fra": {
                "official": "République bolivarienne du Venezuela",
                "common": "Venezuela"
            },
            "hrv": {
                "official": "BOLIVARIJANSKA Republika Venezuela",
                "common": "Venezuela"
            },
            "hun": {
                "official": "Venezuelai Bolivári Köztársaság",
                "common": "Venezuela"
            },
            "ita": {
                "official": "Repubblica Bolivariana del Venezuela",
                "common": "Venezuela"
            },
            "jpn": {
                "official": "ベネズエラ·ボリバル共和国",
                "common": "ベネズエラ・ボリバル共和国"
            },
            "kor": {
                "official": "베네수엘라 볼리바르 공화국",
                "common": "베네수엘라"
            },
            "nld": {
                "official": "Bolivariaanse Republiek Venezuela",
                "common": "Venezuela"
            },
            "per": {
                "official": "جمهوری بولیواری ونزوئلا",
                "common": "ونزوئلا"
            },
            "pol": {
                "official": "Boliwariańska Republika Wenezueli",
                "common": "Wenezuela"
            },
            "por": {
                "official": "República Bolivariana da Venezuela",
                "common": "Venezuela"
            },
            "rus": {
                "official": "Боливарианская Республика Венесуэла",
                "common": "Венесуэла"
            },
            "slk": {
                "official": "Venezuelská bolívarovská republika",
                "common": "Venezuela"
            },
            "spa": {
                "official": "República Bolivariana de Venezuela",
                "common": "Venezuela"
            },
            "swe": {
                "official": "Bolivarianska republiken Venezuela",
                "common": "Venezuela"
            },
            "urd": {
                "official": "جمہوریہ وینیزویلا",
                "common": "وینیزویلا"
            },
            "zho": {
                "official": "委内瑞拉玻利瓦尔共和国",
                "common": "委内瑞拉"
            }
        },
        "latlng": [
            8.0,
            -66.0
        ],
        "landlocked": false,
        "borders": [
            "BRA",
            "COL",
            "GUY"
        ],
        "area": 916445.0,
        "demonyms": {
            "eng": {
                "f": "Venezuelan",
                "m": "Venezuelan"
            },
            "fra": {
                "f": "Vénézuélienne",
                "m": "Vénézuélien"
            }
        },
        "flag": "🇻🇪",
        "maps": {
            "googleMaps": "https://goo.gl/maps/KLCwDN8sec7z2kse9",
            "openStreetMaps": "https://www.openstreetmap.org/relation/272644"
        },
        "population": 28435943,
        "gini": {
            "2006": 44.8
        },
        "fifa": "VEN",
        "car": {
            "signs": [
                "YV"
            ],
            "side": "right"
        },
        "timezones": [
            "UTC-04:00"
        ],
        "continents": [
            "South America"
        ],
        "flags": {
            "png": "https://flagcdn.com/w320/ve.png",
            "svg": "https://flagcdn.com/ve.svg"
        },
        "coatOfArms": {
            "png": "https://mainfacts.com/media/images/coats_of_arms/ve.png",
            "svg": "https://mainfacts.com/media/images/coats_of_arms/ve.svg"
        },
        "startOfWeek": "monday",
        "capitalInfo": {
            "latlng": [
                10.48,
                -66.87
            ]
        },
        "postalCode": {
            "format": "####",
            "regex": "^(\\d{4})$"
        }
    }
]
```


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
