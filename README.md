<!-- HTML code to add icon in the title bar -->
<!DOCTYPE html>
<html>
	<head>
		<meta charset = "utf-8" />
		
		
		<!-- add icon link -->
        <link rel = "icon" href =
        
        "https://upload.wikimedia.org/wikipedia/en/thumb/8/81/Titanic_Brewery_logo.svg/1200px-Titanic_Brewery_logo.svg.png"

		type = "image/x-icon">
		
	</head>
	
	
		
		
		
	</body>
</html>	
<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body {
  font-family: Arial, Helvetica, sans-serif;
  font-size: 20px;
}

#myBtn {
  display: none;
  position: fixed;
  bottom: 20px;
  right: 30px;
  z-index: 99;
  font-size: 18px;
  border: none;
  outline: none;
  background-color: #04AA6D;
  color: white;
  cursor: pointer;
  padding: 15px;
  border-radius: 4px;
}

#myBtn:hover {
  background-color: #555;
}
</style>
</head>
<body>

<button onclick="topFunction()" id="myBtn" title="Go To Top">⬆</button>



<script>
//Get the button
var mybutton = document.getElementById("myBtn");

// When the user scrolls down 20px from the top of the document, show the button
window.onscroll = function() {scrollFunction()};

function scrollFunction() {
  if (document.body.scrollTop > 20 || document.documentElement.scrollTop > 20) {
    mybutton.style.display = "block";
  } else {
    mybutton.style.display = "none";
  }
}

// When the user clicks on the button, scroll to the top of the document
function topFunction() {
  document.body.scrollTop = 0;
  document.documentElement.scrollTop = 0;
}
</script>

</body>
</html>

<!DOCTYPE html>
<html>
	
<head>
	 

	
	<!-- Style to create button -->
	<style>
		.GFG {
			background-color: white;
			border: 2px solid black;
			color: #04AA6D;
			padding: 5px 10px;
			text-align: center;
			display: inline-block;
			font-size: 20px;
			margin: 10px 30px;
			cursor: pointer;
      height: 50px;
  position: relative;
  margin: 0;
  position: absolute;
  background-color: #04AA6D;
  color: white
		}



    .GMT {
			background-color: white;
			border: 2px solid black;
			color: #04AA6D;
			padding: 5px 10px;
			text-align: center;
			display: inline-block;
			font-size: 20px;
			margin: 10px 30px;
			cursor: pointer;
      height: 50px;
  position: relative;
  margin: 0;
  position: absolute;
  left: 150px;
  
  
		}

    .GRT {
			background-color: white;
			border: 2px solid black;
			color: #04AA6D;
			padding: 5px 10px;
			text-align: center;
			display: inline-block;
			font-size: 20px;
			margin: 10px 30px;
			cursor: pointer;
      height: 50px;
  position: relative;
  margin: 0;
  position: absolute;
  left: 80px;
  

 
		}

    .GRT:hover{
      background-color: #555;
      color:white;
    }

    .GMT:hover{
      background-color: #555;
      color:white;
    }


	</style>
</head>

<body>

    
   
	
	<!-- Adding link to the button on the onclick event -->
  <button class="GFG"
	onclick="window.location.href = 'file:///C:/Users/balaj/OneDrive/Desktop/Titanic/Titanic.html';">
Home		
	</button>

   <!-- Adding link to the button on the onclick event -->
   <button class="GRT"
   onclick="window.location.href = 'file:///C:/Users/balaj/OneDrive/Desktop/Titanic/About(titanic).html';">
     About
   </button>

  <!-- Adding link to the button on the onclick event -->
  <button class="GMT"
  onclick="window.location.href = 'file:///C:/Users/balaj/OneDrive/Desktop/Titanic/Contacts(titanic).html';">
    Contacts
  </button>


  <br>
  <br>
  <br>
</body>

				

<!DOCTYPE html>
<html>
    <head>
    
        <title>Titanic</title
            <meta name="viewport" content="width=device-width, initial-scale=1">

    </head>
    <body>
        <style>
.btn {
    font-size: 20px;
    font-style: italic;
    font-weight: bold;
    
}

.GFGF:hover{
  background-color: #555;
      color:white;
}




#p {
    font-size: 25px;
   
    color: black;
}

h1 {
    color: black;
}

h2 {
    color: black;
}

.GFGF {
			background-color: white;
			border: 2px solid black;
			color: #04AA6D;
			padding: 5px 10px;
			text-align: center;
			display: inline-block;
			font-size: 20px;
			margin: 10px 30px;
			cursor: pointer;
      height: 35px;
  position: relative;
  margin: 0;
  position: absolute;

  
  
		}

    
hr {
            border-top: 5px dashed #04AA6D;
            
        }
        

        </style>

   <br>
   <br>

  

 <h2>What is <strong><em>Titanic</em></strong>?</h2>
        <p id=p><strong>Titanic</strong> was a British passenger liner operated by the White Star
            Line that sank in the North Atlantic Ocean on 15 April 1912, after
            striking an iceberg during her maiden voyage from Southampton to
            New York City. Of the estimated 2,224 passengers and crew aboard,
            more than 1,500 died, making the sinking at the time one of the
            deadliest of a single ship and the deadliest peacetime sinking
            of a superliner or cruise ship to date. With much public attention
             in the aftermath, the disaster has since been the material of many
             artistic works and a founding material of the disaster film genre.</p>
             <button class="GFGF"
             onclick="window.location.href = 'file:///C:/Users/balaj/OneDrive/Desktop/Titanic/Titanic%20(More%20Information).html';">
                 Read more
             </button>
            

             <br>
             <br>
             <br>
<hr>
            <H2>When did <strong><em>Titanic</em></strong> sank?</H2>

             <p id=p>The <strong>RMS Titanic</strong> sank in the early morning hours of 15 April 1912
                  in the North Atlantic Ocean, four days into her maiden voyage
                   from Southampton to New York City. The largest ocean liner in 
                   service at the time, <strong>Titanic</strong> had an estimated 2,224 people on 
                   board when she struck an iceberg at around 23:40 (ship's time)
                    on Sunday, 14 April 1912. Her sinking two hours and forty
                     minutes later at 02:20 (ship's time; 05:18 GMT) on Monday,
                      15 April, resulted in the deaths of more than 1,500 people,
                       making it one of the deadliest peacetime maritime disasters
                        in history.</p>

                        <button class="GFGF"
	onclick="window.location.href = 'file:///C:/Users/balaj/Titanic%20(More%20Information1).html';">
		Read more
	</button>
    <br>
    <br>
    <br>
<hr>
    <h2>Passengers of <strong><em>Titanic</em></strong></h2>

    <p id=p>A total of 2,208 people sailed on the maiden voyage
         of the <strong>RMS Titanic</strong>, the second of the White Star 
         Line's Olympic-class ocean liners, from Southampton, England, to New
          York City. Partway through the voyage, the ship struck an iceberg
           and sank in the early morning of 15 April 1912, resulting in the
            deaths of 1,503 people. The ship's passengers were divided into 
            three separate classes determined by the price of their ticket: 
            those travelling in first class, most of them the wealthiest 
            passengers on board, included prominent members of the upper 
            class, businessmen, politicians, high-ranking military personnel,
             industrialists, bankers, entertainers, socialites, and professional
              athletes. Second-class passengers were predominantly middle-class
               travellers and included professors, authors, clergymen, and tourists.
                Third-class or steerage passengers were primarily immigrants moving
                 to the United States and Canada</p>

                 <button class="GFGF"
	onclick="window.location.href = 'file:///C:/Users/balaj/OneDrive/Desktop/Titanic/Titanic%20(More%20Information1).html';">
		Read more
	</button>

  <br>
  <br>
  <br>
<hr>
  <h2>Power of <em>Titanic</em></h2>
  <p id=p><strong>Titanic</strong> was equipped with three main engines—two reciprocating
     four-cylinder, triple-expansion steam engines and one centrally placed low-pressure
     Parsons turbine—each driving a propeller. The two reciprocating engines had a combined
      output of 30,000 horsepower (22,000 kW). The output of the steam turbine was 16,000 
      horsepower (12,000 kW). The White Star Line had used the same combination of engines
       on an earlier liner, the SS Laurentic, where it had been a great success. It provided 
       a good combination of performance and speed; reciprocating engines by themselves were
        not powerful enough to propel an Olympic-class liner at the desired speeds, while
         turbines were sufficiently powerful but caused uncomfortable vibrations, a problem
          that affected the all-turbine Cunard liners Lusitania and Mauretania. By combining 
          reciprocating engines with a turbine, fuel usage could be reduced and motive power
           increased, while using the same amount of steam.</p>

               <button class="GFGF"
onclick="window.location.href = 'file:///C:/Users/balaj/OneDrive/Desktop/Titanic/Titanic%20(More%20Information6).html';">
  Read more
</button>
    <br>
    <br>
    <br>
    <hr>
    <h2>Crews in <strong><em>Titanic</em></strong></h2>

    <p id=p>The crew of the <strong>RMS Titanic</strong>  were among the estimated 2,208 people who sailed on the
        maiden voyage of the second of the White Star Line's Olympic class ocean sea liners, 
        from Southampton, England to New York City in the United States. Halfway through 
        the voyage, the ship struck an iceberg and sank in the early morning of 15 April
         1912, resulting in the deaths of over 1,500 people, including approximately 688
          crew members.</p>

          <button class="GFGF"
	onclick="window.location.href = 'file:///C:/Users/balaj/OneDrive/Desktop/Titanic/Titanic%20(More%20Information3).html';">
		Read more
	</button>
<br>
<br>
<br>
<hr>
  <h2>Building <strong><em>Titanic</em></strong></h2>

  <p id=p>The sheer size of <strong>Titanic</strong> and her sister ships posed
     a major engineering challenge for Harland and Wolff;
      no shipbuilder had ever before attempted to construct
       vessels this size. The ships were constructed on Queen's 
       Island, now known as the <strong>Titanic</strong> Quarter, in Belfast Harbour.
        Harland and Wolff had to demolish three existing slipways and
         build two new ones, the largest ever constructed up to that 
         time, to accommodate both ships. Their construction was 
         facilitated by an enormous gantry built by Sir William Arrol & Co.,
          a Scottish firm responsible for the building of the Forth Bridge 
          and London's Tower Bridge. The Arrol Gantry stood 228 feet (69 m)
           high, was 270 feet (82 m) wide and 840 feet (260 m) long, and weighed
            more than 6,000 tons. It accommodated a number of mobile cranes.
             A separate floating crane, capable of lifting 200 tons, was
              brought in from Germany.</p>

              <button class="GFGF"
	onclick="window.location.href = 'file:///C:/Users/balaj/OneDrive/Desktop/Titanic/Titanic%20(More%20Information4).html';">
		Read more
	</button>
  <br>
<br>
<br>
<hr>
  <h2>Wreck of <strong><em>Titanic</em></strong></h2>

  <p id=p>Within days of the <strong>Titanic's</strong> strong sinking, talk
    began of finding the wreck. Given the limits of 
    technology, however, serious attempts were not 
    undertaken until the second half of the 20th 
    century. In August 1985 Robert Ballard led an
     American-French expedition from aboard the U.S.
      Navy research ship Knorr.</p>

              <button class="GFGF"
	onclick="window.location.href = 'file:///C:/Users/balaj/OneDrive/Desktop/Titanic/Titanic%20(More%20Information5).html';">
		Read more
	</button>


    </body>
</html>




