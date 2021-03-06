# Enigma Coding Challenge

Two part challenge when trying to interview for Enigma, a big data analytics company.
At this time, Feburary 2017, I had no clue how to code in Python and the recuiter wanted me to take a stab at it.
So I tried it because I hardly knew another programming language other than C++ straight from college. 
I thought if I just attempted it, I could persuade the hiring manager that I was eager to learn.
If I failed, I atleast dived into another potential language.
I managed to get this working but during the interview with the hiring manager, he was very displeased with my code and I could sense it in his voice.
I knew I was reinventing the wheel in many ways but I only had two days to work on it. I had to learn Python from scratch and Beautiful Soup. I even tacked on multithreading to try it out for fun.
I didn't get the job but I continued to learn to Python. Its now October 2017 and I've nearly learned tons of things about Python. Wish they could see me now. ;)

# Part 1 - CSV Test

TODO Write a script to transform input CSV to desired output CSV. 

You will find a CSV file available for download here: test.csv. There are two steps (plus an optional bonus) to this part of the test. Each step concerns manipulating the values for a single field according to the step's requirements. The steps are as follows:

String cleaning - The bio field contains text with arbitrary padding, spacing and line breaks. Normalize these values to a space-delimited string.
Code swap - There is a supplementary CSV file for download here: state_abbreviations.csv. This "data dictionary" contains state abbreviations alongside state names. For the state field of the input CSV, replace each state abbreviation with its associated state name from the data dictionary.
Date offset (bonus) - The start_date field contains data in a variety of formats. These may include e.g., "June 23, 1912" or "5/11/1930" (month, day, year). But not all values are valid dates. Invalid dates may include e.g., "June 2018", "3/06" (incomplete dates) or even arbitrary natural language. Add a start_date_description field adjacent to the start_date column to filter invalid date values into. Normalize all valid date values in start_date to ISO 8601 (i.e., YYYY-MM-DD).
Your script should take "test.csv" as input and produce a cleansed "solution.csv" file according to the step requirements above. Please attach your "solution.csv" file along with your solution code in your reply!

Recommended libraries:

Python's csv module is standard for dealing with CSV data.

# Part 2 - Web Scrape

TODO Write a script to scrape a sample site and output its data in JSON.

edgar is a company listings site containing ten pages of company links. Each link endpoint holds company-specific data such as name, description and address. The sole requirement of this part of the test is to produce JSON of all of the company listings data for the site.

Please attach a "solution.json" file of the parsed company listings data along with your solution code in your reply!

Recommended libraries: 

Beautiful Soup contains a robust HTML parser.
Python's json module is convenient for JSON format. 
Submission Guidelines

We ask that your solutions be implemented in Python (2.x), as this is our choice for internal data ingestion code. If you are coming from a different language or if your Python is rusty, we've linked to a few Python reference resources (in order of length/detail) below to help!

LPTHW - slow-build introduction to basic programming in Python.
Google's Python Class - crash course on Python syntax and data types.
learn x in y minutes - quick Python reference and run-through.
That was a lot, so let's recap on what we expect* from you in your reply:

The CSV test solution script.
A "solution.csv" file of the cleansed "test.csv" data.
The web scrape test solution script.
A "solution.json" file of the scraped company listings data.
*Anything specified as "optional" or "bonus" is just that, and you will not be penalized for its exclusion. 

We suggest submission of these materials in 3-5 business days. You will not be penalized for taking longer. Please do not hesitate to contact us if any of the above instructions are unclear, or if you'd like to discuss any of the test components in greater detail. We are here to help!

Assessment Criteria

The code test is meant to mirror the actual work that you will be called upon to perform in the capacity of a Data Engineer. Our goal is not to fool you. On the contrary, we would like to see you in your best light! We value clean, DRY and documented code; and in the interest of full disclosure, our assessment criteria is outlined below (in order of significance):

Your ability to effectively solve the problems posed.
Your ability to solve these problems in a clear and logical manner, with tasteful design.
Your ability to appropriately document and comment your code. 
When in doubt, import this.

We hope that you enjoy completing our test as much as we do tackling the real-world challenge of data wrangling daily, and eagerly await your reply!

Thank you,
carla
