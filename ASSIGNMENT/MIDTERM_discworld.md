## Data Processing in Python: MIDTERM EXAM
You have 80 minutes. "Open browser" but NO COMMUNICATION between students.

Using following [Discworld Wikipedia page](http://wiki.lspace.org/mediawiki/List_of_Pratchett_characters):

1. Scrape urls linking to the (individual wikipedia pages of) Major Discworld characters that are related to `Ankh-Morpork` and `The Watch`.

2. Then, get DataFrame linking the particular character with the book he is appearing in. DataFrame should contain two columns: 
    * Name of the book (`book`)
    * Name of the character (`character_name`)
    
(Hint: The list of books of each characters are stored in the table in upper-right corner of the page and its link always contain string Book:)

3. Answer following questions:

    a. How many characters is reported in the book `Men at Arms`?
    
    b. In how many books appear both `Visit-The-Infidel-With-Explanatory-Pamphlets` and `Evadne Cake`?
    
    
### Evaluation criteria
1. Submit as GitHub repository (last commit timestamp at 19.55) with Jupyter Notebook with description (5pts)
    * send link to vit.machacek@cerge-ei.cz and martin.hronec@fsv.cuni.cz with subject 'PythonDataIES Midterm - {}'.format(your_name)
2. An independent class for `downloader` with appropriate functions and attributes (5pts)
3. class representing scraped object with appropriate functions and attributes (5pts)
4. `Pandas dataframe` with results saved as an attribute in the `downloader` object (5pts)
5. Answer to asked questions (5pts)
6. Appropriate comments including a very simple `docstring` of all functions and classes (5pts)
