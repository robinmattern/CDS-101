# CDS-101 Homework Assignment Templates

Create a new Project, `CDS-01`, in RStudio on your computer for the files in this respoitory: `https://github.com/robinmattern/CDS-101.git`.  After the files have been downloaded or "cloned", there will be two homework assignment folders.  The  `HW02` folder, for Homework Assignment No. 2, will contain three `.Rmd` files:
  
  * The original text from the textbook, `transform.rmd`.  
  * A clean document with just the questions,`2HW_Transform-Exercises-v01.Rmd`. It uses the Word template, `CDS_HW_Template-wBox.docm`. 
  * A sample with a few questions answered, `2HW_Transform-Exercises-v02.Rmd`. It uses the Word template, `CDS_HW_Template.docm`. 
  
I suggest that you do the following: 

  1. Open the original text for the homework assignment, i.e. `transform.rmd`, into one tab.
  2. Open `2HW_Transform-Exercises-v02.Rmd` into a second tab and save it as `2HW_Transform-Exercises-v03.Rmd`
  3. Answer the questions by copying R code chunks from the original text into your version in the second tab. 
     + Note that indention is important.  The item numbers must be in the 1st or 5th character position and the text for the item should begin in the 5th and 9th character positions  The three ticks for the code chunks, ` ``` `, should also start on the 5th or 9th character position.
     + I found a function `n_distinct()` that just prints out the number of returned records.  Counts are very important to keep track of.   They are much better than seeing the first ten rows of the data and give you a reasonable idea that the result of a filter is what you'd expect. 
     + This line of code, `<div class="Pagebreak">&#160; &#160;&#160;</div> \pagebreak` produces a page break in HTML pages (only when printed), PDF files, and Word files (only after pressing CTRL-U).
  4. Review your work by "kniting" a HTML version.  You won't see the page breaks until you "pop-out" the page to your browser and do a Print Preview.  
  5. When you are done asnwering the questions, "knit"" a Word document.  It will use the Word template, `CDS_HW_Template.docm`, without a box frame around the page, but if your want the frame, edit the line at the top of the `.Rmd` file to be: `reference_docx: CDS_HW_Template-wBox.docm`
  6. To tell Word to paginate the document, press CTRL-U.
  7. Do a Save-As to save the Word document as `2HW_Mattern_Transform.docx`.
  
If you commit and push your changes back to GitHub, they will be saved in my repository at https://github.com/robinmattern/CDS-101.  I'd like to see how you are doing if you are willing to upload your work every once in a while.  

When you are all done, you will need to copy the file `2HW_Transform-Exercises-v03.Rmd` to `2HW_Mattern_Transform.Rmd`.  Then copy both the `.docx` and `.Rmd` files to your class Project folder, commit them and push them up to your GitHub respository for your teach to grade.  

For the next 3rd homework assignment, you will need to do the following: 

  * Create a new homework folder, `HW03`, in the CDS-01 project folder. 
  * Clone the Hadley Wickham's repository for the entire `R for Data Analysis` book into a new Project folder named `r4ds`.  It is located at https://github.com/hadley/r4ds. 
  * Copy these three `.Rmd` files with the original text, `import.Rmd`, `tidy.Rmd` and `EDA.Rmd` from the main `r4ds` folder into the new `HW03` folder. I believe they contain the questions for the 3rd homework assignment.  
  * In the `HW03` folder, create a clean `.Rmd` file, named, `3HW_Cleansing-Exercises-v01.Rmd`, and copy out of the original text files, the questions for the homework assignment and/or any new questions your professor assigns for the class.  
  * Copy whichever Word template that you want to use from the `HW02` foldler into the `HW03` folder. 
  * Begin again with Step 1. above. 
  