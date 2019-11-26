## Data Processing in Python: MIDTERM EXAM
You have 80 minutes. "Open browser" but NO COMMUNICATION between students.

Using following [Wikipedia page](https://en.wikipedia.org/wiki/20th_Century%27s_Greatest_Hits:_100_English-Language_Books_of_Fiction):

1. Scrape urls linking to the (individual wikipedia pages of) books which are common between the Modern Library list and the Greatest Hits list of books.
2. Then, for each book get DataFrame with 2-column MultiIndex and one column with values (long data format). MultiIndex levels should be: 
    * Name of the book
    * Attribute of table scraped from wiki (e.g. Author, Country, etc.) 
(Hint: Be aware that some of the books might not have table associated with their wiki page. 
Let User know and skip that page.)
3. Answer following questions:
    1. For how many books could number of pages be scraped from wiki tables associated with webpage?
    2. What is the maximum number of books, single author has in this list? Who she/he is?
    3. Which book was published first?
    
### Evaluation criteria
1. Submit as GitHub repository (last commit timestamp at 19.55) with Jupyter Notebook with description (5pts)
    * send link to vit.machacek@cerge-ei.cz and martin.hronec@fsv.cuni.cz with subject 'PythonDataIES Midterm - {}'.format(your_name)
2. An independent class for `downloader` with appropriate functions and attributes (5pts)
3. class representing scraped object with appropriate functions and attributes (5pts)
4. `Pandas dataframe` with results saved as an attribute in the `downloader` object (5pts)
5. Answer to asked questions (5pts)
6. Appropriate comments including a very simple `docstring` of all functions and classes (5pts)
