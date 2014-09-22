# Python Web Fuzzer
### Project Specification
http://www.se.rit.edu/~swen-331/projects/fuzzer/

## Contributors
* Danielle Gonzalez 
* Zack Downs
* Stephan Wlodarczyk

## Installation & Setup


1. Download all files
* or clone the Github repository
2. Install the following depenencies using pip 
    * Python (at least 2.4)
    * BeautifulSoup (pip install beautifulsoup4)
    * Requests (pip install requests)


## Usage


## Discover


1. Navigate your terminal/command prompt to the fuzzy directory
2. Type the command:
	
    ``` python
    python fuzz.py discover [Link] [Options] --common-words=[CommonWords]
    ```

	[Link] 	= link you want to use the fuzzier on (ex. http://www.pythonforbeginners.com)
	
    [CommonWords] 	= Newline-delimited file of common words to be used in page guessing and input guessing
	
    [Options] 	= —-custom-auth=dvwa or —-custom-auth=bodgeit to use our hard-coded authentication for the related website
	

### No Authorization
 Omit the --custom-auth parameter 

### Authorization
 include the --custom-auth parameter and specify either dvwa or bodgeit
