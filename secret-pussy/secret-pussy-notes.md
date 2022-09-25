

# Notes for Secret Pussy

## Style
* Put a caption with 2 hashes above the image
	* Caption should be pleasant and romantic
* Images should be no bigger than 600 wide or 600 tall
	* use: mogrify -resize '600x600>' *.jpg 
		* mogrify re-writes the image file, convert creates a new file
		* the > makes it only affect files bigger than 600x600
		* it will only scale to one factor, width OR height whichever is bigger
* Add tooltip to image
	* tooltip should be super dirty 
* Add 2 spaces at the end of the image for a carriage return
* Add a date after the image
* Add two spaces before the next entry


## An entry looks like this in markdown
![Markdown pic name](./filename.jpg "dirty tooltip")  
2022-09-16





