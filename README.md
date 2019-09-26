# csc436_Fall2019_Ravi

#github URL
https://github.com/rsharm18/csc436_Fall2019_Ravi_HW1.git

#Features Implemented
1. Reverse
	when user clicks on the reverse button, the system shows a new div with reversed content. I wrote a JS method with the logic to reverse the list of startup names
2. Add Toggle Button
	I wrote JS method to generate the Toggle button when the page loads.
3. Print the anonymous method content on console
	added () at the end of the method to invoke the anonymous method and print its content on the console.
4. Cleanup and Count 
	added the logic to clean up/remove the special characters and trim the startup names and display the # of characters against each startup name. I have considered a single space between two words as  a valid character i.e if there are multiple spaces between two words then I replace the multiple spaces with a single space.
	
#Additional Features
1. used the custom CSS provided in the HTML file.
2. used the Bootstrap CSS for styling.
3. I used a JSON Object object to count the number of occurrences of each character accross all      startup names and style and display the results as part of the                        "cleanAndCountCharacters" function.
4. added a functionality to 'undo clean and count words'
		when user clicks on th 'Clean and Count words' button, the UI respects the functionality but updates the button text as 'Undo Clean and Count words' and chages the button backgroung to red. When user clicks the 'Undo Clean and count words' the system shows the original startup names (with all special chars) and button property and text changes to its oiginal form.