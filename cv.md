# CV
***

1. Name
**Ekaterina Lapitskaya**


2. Contacts
*mob.: +375 29 123 45 67*
*e-mail: yourmail@gmail.com*


3. Summary
I started learning JS because:
* JavaScript Runs Everywhere;
* JavaScript Developers Are in High Demand;
* Vibrant and Active Community;
* Building Block for Other Programming Languages.


4. Skills 
* _HTML/CSS_
* _JavaScript_
* _React JS_
* _Vue_


5. Code example
```html>
<head>
  <title>Multiplication Table</title>
  <script type="text/javascript">
    var rows = prompt("How many rows for your multiplication table?");
    var cols = prompt("How many columns for your multiplication table?");
    if(rows == "" || rows == null)
   		 rows = 10;
    if(cols== "" || cols== null)
   		 cols = 10;
    createTable(rows, cols);
    function createTable(rows, cols)
    {
      var j=1;
      var output = "<table border='1' width='500' cellspacing='0'cellpadding='5'>";
      for(i=1;i<=rows;i++)
      {
    	output = output + "<tr>";
        while(j<=cols)
        {
  		  output = output + "<td>" + i*j + "</td>";
   		  j = j+1;
   		}
   		 output = output + "</tr>";
   		 j = 1;
    }
    output = output + "</table>";
    document.write(output);
    }
  </script>
</head>
<body>
</body>
</html>
```


6. Work experience
* _2013-2015 HR Manager in "IBM Group"_
* _2015-2016 Waitress in "Pekin Hotel"_
* _2017-2018 Economist in "ITransition"_


7. Education
* BSEU, Accounting & Economics (2009-2012)
* RSSchool (2019)


8. Languages
* English B1 (Streamline 2013-2014)
* Spanish C1 (Streamline 2016-2018)