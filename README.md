# api_bored
  This is an example of a very simple app using an API. Namely we use pure javascript embedded directly in an HTML file, to get results from an API called <a href="https://www.boredapi.com/documentation">the "bored" API</a>.
  
  The structure of the page is made up of a small jQuery menu - when you click menu items, the page toggles visibility on respective div sections. This is a neat and quick way to build a one-page html app, that is superquick and still easy to overview code wise.  
  
  The API calls are made with the jQuery ajax function. Ajax is short for "asynchronous javascript and xml". In fact the xml part doesn't really apply to many modern applications, since what we see in our response objects is instead JSON. To work with this pice of code, all you need to know is that the $.ajax() parts in the code, means we are requesting data from an external source - here, the bored api - and when we get something in return (.done()), we can use data in the app.
  
  <a href="https://www.w3schools.com/js/js_json_xml.asp">W3C on the difference between JSON an XML</a><br>
  <a href="">Eloquent Javascript on asynchronous programming in.. well, javascript</a>
  
## Handlebars
  We also use a js framework called <a href="https://handlebarsjs.com/">handlebars</a>, to ease json formatt ing. 
  
  
  Lastly - and really the reason we use handlebars - we use a rather complex css boilerplate, <a href="https://materializecss.com/cards.html"> called materialize</a>, which gives us some rather cool layouts. 
  
  Hence the total project presents a set of meaningful skills and architecture in frontend web-programming. 

  # Mit ekstra
    Keder du dig nogensinde?
    Har du lyst til noget sjovt at lave?
    Så klik ind her
    Med denne hjemme side kan du se hvad du skal lave med 1,2,3,4,5,6,7 eller 8 personer. 
    I toppen klikker du enten på random, 1 -, 2 -, 3 -, 4 -, 5 -, 6 -, 7 - eller 8 personer. Hvis du klikker på random først, vil den altid     ligge i toppen af bunkerne. Hvis du der efter klikker på en af de andre kommer de nedunder. Hvis man klikker Home genstarter siden og       den er blank
