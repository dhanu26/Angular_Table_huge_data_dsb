# Angular_Table_huge_data_dsb
Its an angular based application which is User friendly display of  huge  data which is fetched from a json file of "WALKWEL Organization"


AnGular and express based application which can display 50000 of data with a good interface




1. install Node and express
2. Install angular ( ng i -g @angular/cli)


	a) copy the "src" folder of frontend and backend from the these files and 
			REPLACE in your respective frontend src folder


3. install bootstrap (ng i bootstrap --save)

4. update angular.json ==> find "styles"  in array add below line

  "node_modules/bootstrap/dist/css/bootstrap.min.css",

5. start frontend by following command in terminal

ng serve -o 

 

6. if your browser doesn't support Cross origin stuff

or it give error like 
			Access to XMLHttpRequest at 'https://walkwel.herokuapp.com/' from origin 'http://localhost:4200' 
			has been blocked by CORS policy: No 'Access-Control-Allow-Origin' header
			 is present on the requested resource.

				use this browser to access the page

				a)window+r (RUN) 
				b) type 
						chrome.exe --user-data-dir="C://Chrome dev session" --disable-web-security
				c) ok
*Note this is unsafe browser you should not use it for anything else
        
Made for WALKWEL assignment
link for source code :https://walkwel.herokuapp.com/
Now enjoy the interface of table with such a huge data.

To get more stuff like this 
contact: Dhanushant 
	dhanushantp@gmail.com
