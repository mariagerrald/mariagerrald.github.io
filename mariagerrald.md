---
layout: page
title: Maria Gerrald
permalink: /about/
weight: 1
---

Jag är en ny utvecklare med fokus på geografiska informationssystem (GIS), Microsoft .NET och Javascript. Jag flyttade till Sverige från USA i slutet av 2013.  Sedan dess har jag förutom svenska studerat GIS och programmering genom olika kurser och självständiga studier. Jag tycker om att lösa programmering problem och att lära mig ny teknik.  När jag läste biologi på universitetet som ledde till en BS examen tog jag flera kurser i programmering och matematik.  Jag har också alltid varit intresserad av kartor och geospatiala data.  Det har varit givande att kunna kombinera och fördjupa mig i dessa ämnen.

<!--I am a junior developer with focus and training in GIS, Microsoft .Net framework and Javascript.   I moved to Sweden from the United States in late 2013.   While learning Swedish, I have had the opportunity to study GIS and programming through formal coursework as well as independent learning.  I enjoy solving coding problems and learning new technologies.  Years ago while completing my Bachelors of Science in Biology, I had enjoyed taking courses in programming and math.  I have also always liked maps and geospatial information.   It is rewarding to be able to combine these two interests and return to study and work in these areas again.    -->

# Projekt inklusiv webbprojekt, kartor

- <a href="https://skyddsvarda-trad-jkpg.surge.sh/" target="_blank">Skyddsvärda träd</a>  
<!--(provide link to site and to github code)  -->
Sökbar, interaktiv kartapplikation som visar skyddsvärda träd i Jönköpings län.  Web-sida skapad med Leaflet kartbibliotek och Javascript /jQuery.  Hämtar data om träd genom REST API query från Länsstyrelsens ArcGIS WMS server,
- <a href="https://github.com/marigerr/TreesWebAPI/tree/master/BigTrees" target="_blank">Web API Skyddvärda Träd</a>  
Fullstack version av Skyddsvärda träd app.  För detta exporterade jag träd shapefile till en SQL databas med verktyget ogr2ogr.  Sedan byggde jag API med Asp.Net WebApi2.  Kartappen är ännu inte online men koden finns åtkomlig för granskning på github.   
- <a href="http://chicken-stats-2005-2016-se.surge.sh/" target="_blank">Chickens Stats in Sweden 2005-2016</a>  
Enkel webb-karta för att visualisera regionala förändringar i hönsproduktionen i Sverige baserad på statistik från SCB.  Använde <a href="http://www.qgis.org/en/site/ " target="_blank">Qgis</a> för att förena shapefil innehållande regioner med data om hönsproduktion och exporterade resultatet till GeoJson.  Webbplatsen är en modifierad version av Leaflets handledning för choropleth kartor.    
- <a href="https://github.com/marigerr/forum" target="_blank">Forum</a>   
Forum app inklusive sida för händelser/nyheter, privata meddelanden och roller för moderator/administratör.  Byggd med Asp.Net MVC, AngularJS, SQL-databas.  Inte live ännu, men koden finns åtkomlig för granskning på github.  
- [Map - Gothenburg Sweden ]({{ site.url }}/assets/images/GothenburgSE.PNG) - Karta med infällda kartramar, skapad med ArcGIS
- [Map - Cities in Countries with Population over 10 Million ]({{ site.url }}/assets/images/CitiesCountiesOver10Million.PNG) - map created with ArcGIS 
- [Map - Potential Dumpsite Areas Larger than 5 Hectares]({{ site.url }}/assets/images/PotentialDumpsiteAreasLargerThan5Hectares.PNG)  
Exempel på att skapa en karta med buffertkriterier kring features i ArcGIS. (Kartan är tyvärr en lågkvalitativ kopia av en bild)  
- [Writing Excerpt - Implementation of GIS in EIA]({% post_url 2014-11-15-GIS-EIA %})  
Utdrag ur ett papper skrivet för GIS A21 (Lund Univ). Papper diskuterar utmaningar med att använda GIS för miljöbedömningar. Hur EU Inspire är relevant.
   

# Praktik

Cube Corner AB - Huskvarna juni 2016- dec 2016  
- Arbetade med att förbättra webbplattform för logistik / hantering av leveranser.  Bidrog till förändringar i både front end i Javscript och jQuery samt back end kodning i C# och PostgreSQL stored procedures    
- Andra projekt omfattade programmering i Visual Basic for Applications (VBA) för att exportera data till Excelfiler från affärssystemet Jeeves. Kodade SQL stored procedures för att exportera  data och design rapporter med Crystal Reports.   
  

# Open Source contributions
<!--- [Humanitarian Tool Box](http://www.htbox.org/)-->
- <a href="https://github.com/HTBox/allReady/pull/2000/files" target="_blank">Unit test to the HTbox Allready Project</a>   
Humanitarian Tool Box är ett öppen källkod projekt som startats av Microsoft för att tillhandahålla gratis open source-lösningar för humanitära organisationer. Det är ett tillfälle att börja bidra till öppen källkod, lära känna den senaste Microsoft. Net Core framework och arbeta ideellt för en humanitär organisation. Jag har haft ett commit merged och två andra pågående pull requests.     
- <a href="https://www.openstreetmap.org/user/marigerr/history#map=9/58.0917/14.6338" target="_blank">Open Street Map edits</a>   
Jag har bidragit med 338 ändringar till Open Street Map (OSM) som är en öppenkällkod karta som alla kan bidra till och använda. OSM används av flera baskarta tile leverantörer som [Mapbox](https://www.mapbox.com/) 

# Kompetens

- GIS - ArcGIS Desktop, ArcGIS Pro, ArcGIS Online, QGis
- Web GIS - Leaflet, Google Maps Api, ArcGIS JS API, OpenStreetMap, JOSM Editor 
- .Net - C#, Web API, MVC, Visual Studio, Visual Studio Code
- SQL, T-SQL, SQL Server Management Studio, PostgreSQL, pgAdmin
- Visual Basic for Applications (VBA), Crystal Reports
- Javascript, jQuery, AngularJS
- Version Control - Git, Team Foundation Server
- Front End Build Tools - Webpack, Npm
- Unit Testing, Agile Development

<!--Projects I'm working on can be viewed on github at 
{% include icon-github.html username="marigerr" %} -->
<!--[marigerr](https://github.com/marigerr)-->

<!--# Recent Formal Programming Coursework

- Asp.Net development - Lexicon  Jönköping  
Coursework covered both front and back-end languages and frameworks including:  
C#, Asp.Net MVC, SQL, javascript, jquery, angularJS, bootstrap, unit testing, agile development
- GIS A21 - Lund University    
Analys av geografiska data i raster och vektor form samt kartografisk och grafisk presentation av digitalt kartmaterial och tillämpningarna.  
    Coursework examples:  
    - [Excerpt from final paper]({% post_url 2014-11-15-GIS-EIA %})      
    [Sri Lanka Monthly Income by District]({{ site.url }}/assets/images/SriLankaAvgMonthlyIncomeDistrict.PNG)
     <!--[Potential Dumpsite Areas]({{ site.url }}/assets/images/PotentialDumpsiteAreas.PNG)
    - [Potential Dumpsite Areas Larger than 5 Hectares]({{ site.url }}/assets/images/PotentialDumpsiteAreasLargerThan5Hectares.PNG)
    - [Gothenburg Sweden ]({{ site.url }}/assets/images/GothenburgSE.PNG) 
*<span style="font-size: 12px">map image quality is low due being old pdf copy of map and no current ArcGIS subscription.  I plan to recreate soon with QGis</span>  -->
