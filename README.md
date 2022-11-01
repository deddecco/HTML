This is where HTML projects are stored:

 * I did Dave Gray's HTML for Beginners Tutorial, and the code from that is stored here 
	* index.html is the code for the homepage of the Little Taco Shop
   * hours.html defines the LTS's hours
   * contact.html allows customers to place LTS orders or give feedback 

 * And so is the code for a Java application that generates HTML code, which I use to generate a word cloud containing the most frequently used words in a text file 
    * frequency analysis is done on wholebible.txt through Hash.java found in the coding-challenges repository
    * those results get put into BibleFrequencyResults.txtHT
    * the information in that file then gets converted to HTML by GenerateHTML.java
    * test.html generates a table with 2 columns
       * left column: word
        * right column: frequency 
    * testcloud.html generates the word cloud of the 150 most frequent words in test.html
