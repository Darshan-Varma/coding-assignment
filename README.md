# Marketing Coding Test #
## The Challenge: Modify a Web-based Search App ##

This .NET Core demo app uses [Lucene.NET](https://lucenenet.apache.org/) to index data from the included FilmsInfo.csv file into a search engine. When you run the app, press the reload button to load the data into the search engine. After that, you can enter search terms and press the search button to search for matching movie results. 

## Features Implemented ##
### Basic Features ###
1. **Display Voting Average:** The application now displays the voting average in the returned search results.
2. **Voting Average Filter:** Connected the Voting Average (Minimum) so that it filters the results that are above the minimum selected values. 
3. **Release Date in Index**: Added release date to the index and display it in the returned search results.
4. **Date Range Filter:** Added a way to filter the search by date range for the release date using **flatpickr**.
5. **CSS Improvements:** Enhanced the styling and layout of the page and search results to provide a better user experience.

### Advanced Features :mortar_board: ###
1. **Stemming:** Implemented stemming using **EnglishAnalyzer** to return results for different forms of a word *(e.g., "engineer" will also return results for "engineering", "engineers", and "engineered").*

## Deployment Steps ##
1. Open the Git Bash terminal and run the following commands in sequence.
2. git clone https://github.com/Darshan-Varma/coding-assignment.git
3. cd coding-assignment/MarketingCodingAssignment
4. dotnet restore
5. dotnet build
6. cd MarketingCodingAssignment
7. dotnet run
8. Open your browser and navigate to the URL displayed in the terminal (e.g., http://localhost:5123/) to access the application.
9. Click on the 'Rebuild Search Index' link to load all the indexes.

## Approach ##
### Tools Used: ###
  - Visual Studio 2022
  - GitHub Desktop
### Repository Setup: ###
  - Forked the original repository and cloned it into my local machine.
  - Created a new branch 'coding-assignment-darshan' to start working on the assignment.
### Development Practices: ###
  - Maintained naming conventions and added appropriate comments.
  - Committed each task separately with detailed commit messages.
  - Tested all changes, self-reviewed the code, and then merged it into the main branch.
### Task 4: Date Range Filter ###
  - Used flatpickr to add a date range filter.
  - Added a function to filter the results only when both dates are selected.
### Task 5: CSS Improvements ###
  - Implemented hover effects on the search results.
### Advanced Task 1: Stemming ###
  - Implemented stemming using EnglishAnalyzer to handle different forms of words.
  - Reference: https://lucenenet.apache.org/quick-start/tutorial.html

## Feedback ##
- This coding task was great for learning and all the tasks were clearly mentioned.
