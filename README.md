# PBHLTH_142_Group Project 1 Due on February 28, 2022
### Questions:

1. [2 marks] What is the problem your are addressing with these data? State the question you are trying
to answer and let us know what type of question this is in terms of the PPDAC framework.


2. [2 marks] What is the target population for your project? Why was this target chosen i.e., what was
your rationale for wanting to answer this question in this specific population?


3. [2 marks] What is the sampling frame used to collect the data you are using? Describe why you think
this sampling strategy is appropriate for your question. To what group(s) would you feel comfortable
generalizing the findings of your study and why.


4. [2 marks] Write a brief description (1-4 sentences) of the source and contents of your dataset. Provide a
URL to the original data source if applicable. If not (e.g., the data came from your internship), provide
1-2 sentences saying where the data came from. If you completed a web form to access the data and
selected a subset, describe these steps (including any options you selected) and the date you accessed
the data.


5. [1 mark] Write code below to import your data into R. Assign your dataset to an object.


6. [3 marks] Use code in R to answer the following questions:

i) What are the dimensions of the dataset?

ii) Provide a list of variable names.

iii) Print the first six rows of the dataset.


7. [4 marks] Use the data to demonstrate a statistical concept from Part I of the course. Describe the
concept that you are demonstrating and interpret the findings. This should be a combination of code
and written explanation.

Tips
We anticipate that importing the data into R may be a challenging task for many datasets.
The frustration is part of the challenge and a common occurrence if you work with data from the real world.
To make this easier on yourself, choose data that has a “rectangle” format with no merged headings.
For example, it should contain variable headings where each variable has its own row of data. There
should be no summary information at the end of the data, or any information outside the “rectangle”
that makes up your dataset.
The data will be easiest to use in R if the variable names do not contain spaces or unusual characters.
If you need to, you can rename variables in Excel to be of the format: “my_variable_name” rather
than “my variable” or “my variable * 100”, as examples.
If you are having trouble importing the data, try making a much smaller data set and import it first.
This can help you isolate the problem. Some datasets you find will be thousands or even millions of
rows. Given that this may be your first time importing data, we recommend you choose something
smaller!
To make your report look presentable, check out this cheat sheet style guide on .rmd.


### Integrate Github and Git with RStudio
##### Github
1) Create an account on Github
2) Find our group by clicking on this link https://github.com/phtseng/PBHLTH_142_Group.git
3) On the top left corn, you can "pin" (like a bookmark), "watch" (or follow), or "fork" (creates a copy) of this in your own page
4) If you pin, the group will show up in your profile, Then navigate to the PBHLTH_142_Group's master page simply by clicking the PBHLTH_142_Group hyperlink.

##### Git
1) Download Git https://git-scm.com/downloads, select all the recommended or default steps to install Git
2) After it downloaded, open the command prompt then set your global username and email address by typing in
  |git config --global user.name "Your Name"
  |git config --global user.email

##### RStudio
1) Click on "Tools" > "Global Options" > Git/SVN to make sure your git is set up properly
2) In your environment console, you should now see a "Git" tab
3) Click on "Git" and clone this master/default main page to retreive the full repository
    
    |git clone https://github.com/phtseng/PBHLTH_142_Group.git
    
4) Under the master/default main page, you can create a new branch or go to Terminal in RStudio and type in 
    
    |git branch [branch name]
    
5) Check the status and that the branch is created

    |git branch
    |git status
    
6) In Rstudio environment console, check that you're on the right branch and it's pointing to it locally.
Git cheat sheet: chrome-extension://efaidnbmnnnibpcajpcglclefindmkaj/viewer.html?pdfurl=https%3A%2F%2Feducation.github.com%2Fgit-cheat-sheet-education.pdf&clen=100194&chunk=true
 
 7) Then you want to add a file to this branch. Create a new test file like "hello_world.R" and in the code insert 
   print("Hello World!")
 
 8) Save then go to the Terminal in RStudio, make sure you add then push and finally commit the file
  
   |git add .
   
   |git push origin head
   
   |git commit -m "my hello_world.R test file"
 
 9) Go back to Github to check for your new file, push, and commit

