# Mine ændringer

I dette repo, har jeg ændret på nogen koder, som jeg har forked fra github.com/simmoe , som hedder "api bored". I Index filen har jeg arbejdet lidt med Jquery og at tilføje "cards", der viser forskellige aktiviteter, fra et api. Jeg har Lavet 2 ekstra kort og herunder har jeg arbejdet med en funktion der får et af kortene til at fade ud, når man klikker et sted på "Klik her for at få kort til at forsvinde" og kommer igen, når man klikker på "klik her for at få kort tilbage". Jeg har også prøvet at få nogen gemte informationer omkring kortet op, men det er stadig work in progress. Selve funktionen med fade in og ud, virker ikke helt optimalt, da jeg har problemer med det sted man skal trykke. Har dog set at det virkede et par gange. Til videre arbejde skal jeg nok fin pudse fade in/ud funktionerne og få kortet til at vise flere informationer, når der klikkes på den. Vil også gerne prøve at arbejde med, at nogen dropdown menuer senere. 



## api_bored
  This is an example of a very simple app using an API. Namely we use pure javascript embedded directly in an HTML file, to get results from an API called <a href="https://www.boredapi.com/documentation">the "bored" API</a>.
  
  The structure of the page is made up of a small jQuery menu - when you click menu items, the page toggles visibility on respective div sections. This is a neat and quick way to build a one-page html app, that is superquick and still easy to overview code wise.  
  
  The API calls are made with the jQuery ajax function. Ajax is short for "asynchronous javascript and xml". In fact the xml part doesn't really apply to many modern applications, since what we see in our response objects is instead JSON. To work with this pice of code, all you need to know is that the $.ajax() parts in the code, means we are requesting data from an external source - here, the bored api - and when we get something in return (.done()), we can use data in the app.
  
  <a href="https://www.w3schools.com/js/js_json_xml.asp">W3C on the difference between JSON an XML</a><br>
  <a href="">Eloquent Javascript on asynchronous programming in.. well, javascript</a>
  
### Handlebars
  We also use a js framework called <a href="https://handlebarsjs.com/">handlebars</a>, to ease json formatting. 
  
  
  Lastly - and really the reason we use handlebars - we use a rather complex css boilerplate, <a href="https://materializecss.com/cards.html"> called materialize</a>, which gives us some rather cool layouts. 
  
  Hence the total project presents a set of meaningful skills and architecture in frontend web-programming. 


  
