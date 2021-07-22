# Zen-Task 
Tasks - July 20, 2021
List 5 difference between Browser JS(console) v Nodejs
1) Javascript is a programming language that is used for writing scripts on the website / NodeJS is a Javascript runtime environment.  
2) Javascript can only be run in the browsers /	NodeJS code can be run outside the browser.
3) It is basically used on the client-side / It is mostly used on the server-side.
4) Javascript is capable enough to add HTML and play with the DOM / Nodejs does not have capability to add HTML tags.
5) Javascript can run in any browser engine as like JS core in safari and Spidermonkey in Firefox / Nodejs can only run in V8 engine of google chrome.

watch & summary 5 points - https://www.youtube.com/watch?v=SmE4OwHztCc&ab_channel=JSConf
1) Parsing of Html into DOM tree and parsing of css into CSSOM.
2) Rendering both the DOM tree and CSSOM into rendering tree. The rendering will be slowed by the halt and speculative parsing.
3) Rendering tree has Multiple trees namely Rendering Objects, styles, Layers and Line boxes.
4) Layout places the node on the screen.
5) Painting computes bitmap and composite to screen.

To read - https://stackoverflow.com/questions/5641997/is-it-necessary-to-write-head-body-and-html-tags

Execute the bellow code and write your description in txt file
        typeof(1)    -  "number"
        typeof(1.1)  -  "number" 
        typeof('1.1') - "string"
        typeof(true) - "boolean"
        typeof(null) - "object"
        typeof(undefined) - "undefined"
        typeof([])   -   "object"
        typeof({})   -   "object"
        typeof(NaN)  -   "number"        
Tasks - July 21, 2021
   var obj = [ 
   { person: "Name 1", age: "2", company: "GUVI" },
    { person: "Name 2", age: "5", company: "GUVI geek" },
    { person: "Name 3", age: "8", company: "GUVI geek network" },
  ];
   //for loop
  for(var i = 0; i < obj.length; i++){
         console.log(obj[i].person + " " + obj[i].age + " " + obj[i].company );       
  }
  //for in
  for (let x in obj){
      console.log(obj[x].person + " " + obj[x].age + " " + obj[x].company);    
  }
  //for of
  for (let x of obj){
      console.log(x.person, x.age, x.company);
  }
  // for each
  obj.forEach(key => console.log(key.person, key.age, key.company));

