ASSIGNMENT: LAB 9 - MESSAGES 2
ELIA RODRIGUEZ LOPEZ

INSTRUCTIONS PART 2:
	Q: TURN OFF PYTHON'S SIMPLE HTTP SERVER. INSTEAD, OPEN THE INDEX.HTML ON A FEW WEB BROWSERS VIA DOUBLE-CLICKING ON THE FILE OR DO A FILE>OPEN. DOES IT REALLY WORK? SHOULD IT WORK?
	A: THE MESSAGES ONLY DISPLAYED ON FIREFOX. THEY DID NOT DISPLAY IN GOOGLE CHROME OR SAFARI. I THINK IT SHOULDN'T WORK, BECAUSE ALTHOUGH THE JSON FILE IS LOCATED IN THE SAME DIRECTORY AS THE HTML, JAVASCRIPT, AND CSS FILES, IT IS NOT REFERENCED IN THE HTML FILE SO IT IS NOT CONSIDERED TO HAVE THE SAME DOMAIN AS THE HTML/JS/CSS FILES. 

INSTRUCTIONS PART 3:
	Q: INSTEAD OF LOADING THE DATA FROM THE DATA.JSON FILE, TRY LOADING THE JSON DATA FROM A URI. REPLACE DATA.JSON IN YOUR LAB.JS TO HTTPS://MESSAGEHUB.HEROKUAPP.COM/MESSAGES.JSON. THE JSON LOOKS VERY SIMILAR WITH THE SAME IMPORTANT FIELDS. YOU DO NOT NEED TO MODIFY ANY OTHER CODE IN YOUR JAVASCRIPT. DOES IT WORK?
	A: YES, IT WORKS. THE MESSAGES DISPLAYED ON ALL THREE BROWSERS IT THAT WERE TESTED: CHROME, FIREFOX, AND SAFARI. 

IMPORTANT QUESTION: IS IT POSSIBLE TO REQUEST THE DATA FROM A DIFFERENT ORIGIN (E.G., HTTP://MESSAGEHUB.HEROKUAPP.COM/) OR FROM YOUR LOCAL MACHINE (FROM FILE://) FROM USING XMLHTTPREQUEST? WHY OR WHY NOT?
A: YOU SHOULDN'T BE ABLE TO REQUEST DATA FROM A DIFFERENT ORIGIN (SUCH AS HTTP://MESSAGEHUB.HEROKUAPP.COM/) OR FROM THE LOCAL MACHINE (EVEN IF IT IS IN THE SAME DIRECTORY) BECAUSE OF THE JAVASCRIPT SAME ORIGIN POLICY. WE WERE ABLE TO ACCESS THE DATA IN INSTRUCTIONS PART 3 BECAUSE CORS (CROSS-ORIGIN RESOURCE SHARING) WAS ENABLED. 

1. THIS LAB FOCUSED ON USING THE XMLHTTPREQUEST OBJECT, WHICH IS FINALLY IMPLEMENTED CORRECTLY. I TRIED TO ADD AN ICON IN THE HEADING, BUT THE ALIGNMENT IS DIFFERENT IN DIFFERENT BROWSERS. I TRIED TO FIX THIS, BUT WASN'T COMPLETELY SUCCESSFUL. 

2. I DSICUSSED THIS ASSIGNMENT WITH RAMTIN, WHO HELPED ME FIGURE OUT THE STRUCTURE OF AN XMLHTTPREQUEST AND HOW TO STRUCTURE A LOOP TO GO THOUGH THE ARRAY, AND PROFESSOR MING CHOW, WHO CAUGHT THAT ANNOYING TYPO AND GAVE ME REFERENCES ON HOW THE XMLHTTPREQUEST WORKS.I ALSO LOOKED AT THE PIAZZA FORUMS, AND CONSULTED PULKIT TO UNDERSTAND THE QUESTIONS ASKED IN INSTRUCTIONS PART 2 AND 3. ADDITIONAL REFERENCES ARE LISTED BELOW:
	- https://en.wikipedia.org/wiki/XMLHttpRequest
	- https://developer.mozilla.org/en-US/docs/Same-origin_policy_for_file:_URIs
	- https://security.stackexchange.com/questions/8264/why-is-the-same-origin-policy-so-important
	- https://stackoverflow.com/questions/22545325/how-to-vertically-align-text-with-icon-font
	- https://www.w3schools.com/cssref/pr_padding-bottom.asp
	- https://stackoverflow.com/questions/735394/add-image-to-left-of-text-via-css
	- http://www.freeiconspng.com/images/message-icon-png

3. I SPENT APPROXIMATELY A WEEK WORKING ON THIS ASSIGNMENT INTERMITTENTLY WHILE ALSO WORKING ON OTHER LABS, BUT I WOULD ESTIMATE THAT I SPENT ABOUT 10 HOURS ON THIS ASSIGNMENT?

