#Mugsi Grade Calculator


###Background
I know they're shutting down MUGSI this year, but I was getting frustrated with my GPA constantly appearing and disappearing in Grade Report. I also don't want to sit and calculate my GPA by hand using degree audit because they only give letter grades (what year is it?)

###Along came Mechanize
[Mecahnize](https://github.com/jjlee/mechanize) is a wonderful Python module for programmatic web browsing. This allowed me to easily surpass MUGSI's sad attempt at securing the page from bots and scripts. 

###How to use it
To use the grade calculator, simply checkout the repository or download the .zip from GitHub. Once you've got it, open `gradescalculator.py` and modify the following lines with correct information.   
  
I've bundled Mechanize, but you can choose to download and install it for the latest version (though it may not work).

Then, simply run the program

```
$ python gradescalculator.py
```
After you run the program it will prompt you for the username and password
###Future Updates
I might clean this up a bit, but since Mosaic is coming soon, the process would be vastly different. Once Mosaic is integrated, I will look for a way to continue this. Hopefully we don't need it, and Mosaic is reliable enough to meet the needs of the students.
