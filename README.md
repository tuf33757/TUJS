
#TUJS

Temple University IS&amp;T Capstone JavaScript Library

 OVERVIEW:
 This Library is a compilation of functions and features that are helpful with Temple IS&T Capstone Client side features.  You are free to use it and modify it as needed.  
 
 SOME FEATURES USE JQUERY version 2.2.0 (the latest version at the time of build) which is included in the zip file. You can use that which is referenced in the library, or if you are using a newer version you can remove it and use .

To use this Library: 
1) Download the zip file, extract it, and place the TUJS folder inside the root folder of your application (where your main pages are stored). Make sure that both JQuery.js and TUJS.js are inside the folder.

2) place the following code on any page that you want to use the Library. NOTE that you may need to reassign the folders based on if you put the library inside another folder:

\<script src="TUJS/TUJS.js">\</script>

3) To call any of the following funcitons from the library you to call the Library itself followed by the functions with any parameters that it may take.  For example, the following code will display the version function in the console when the button is clicked:

\<button onclick"TUJS.ver()">Click for Version\</button>

## Usable Functions
### Below is a list of all functions in the Library:
[Calculations](#calculations)<br/>
[Hide and Show Content](#hide-and-show-content)<br/>
[Get Size of Page](#get-size-of-page)<br/>
[Date Difference](#date-difference)<br/>
[Contains](#contains)<br/>

####Calculations:
######Notes: 
This function takes in 3 OR 4 arguments.
4 arguments:( First Textbox ID, Second Textbox ID, Operator as string, ID of Output Element).  Based on the Operator that you input (ie: '+'), the function will get the integer value of the two textbox inputs and perform the calculation returning the caclulated value.
3 arguments:( First Textbox ID, Second Textbox ID, Operator as string).  Does the same calculation as with 4 arguements, but the function is now assignable. (ie: var ans = TUJS.Calc('txtbx1', 'txtbx2', '*'); )
######INPUT: 
4 Arguments (String, String, String, String) OR 3 Arguments (String, String, String)
######OUTPUT:
can be returned as an float to perform more calculations or returns nothing and can be used to assign the value of the 4th element passed in


####Hide and Show Content:
######Notes:
######INPUT:
######OUTPUT:


####Get Size of Page:
######Notes:
######INPUT:
######OUTPUT:


####Date Difference:
######Notes:
######INPUT:
######OUTPUT:


####Contains:
######Notes:
######INPUT:
######OUTPUT:


[Back to top](#usable-functions)

