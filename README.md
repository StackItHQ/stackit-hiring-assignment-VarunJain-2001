
# StackIt Hiring Assignment

### Welcome to StackIt's hiring assignment! 🚀

**If you didn't get here through github classroom, are you sure you're supposed to be here? 🤨**


We are glad to have you here, but before you read what you're going to beat your head over for the next few hours (maybe days?), let's get a few things straight:
- We really appreciate honesty. Don't copy anyone else's assignment, it'll only sabotage your chances :P
- You're free to use any stack, and library of your choice. Use whatever you can get your hands on, on the internet!
- We love out of the box solutions. We prefer to call it *Jugaad* 
- This might be just the first round, but carries the most importance of all. Give your best, and we hope you have a fun time solving this problem.

## ✨ **Problem Statement: Crafting a CSV Importer for Google Sheets** ✨

**Context**:
Data analysts around the world 🌍, handle massive amounts of data to derive meaningful insights for their organization 📊. Among the tools they use, Google Sheets 📈 stands out due to its ease of use, accessibility, and collaborative features. However, many analysts have identified a recurring pain point: the cumbersome process of importing CSV files into Google Sheets repeatedly.

A typical week of an analyst in an e-commerce company 🛒 involves receiving multiple CSV files 📁 containing sales, inventory, customer feedback, and more. The data from these files needs to be meticulously analyzed and presented in the company’s weekly meetings. However, instead of diving directly into analysis, most analysts need to spend an inordinate amount of time just importing and structuring these CSV files into Google Sheets ⏳. This repetitive, time-consuming task reduces the efficiency of these professionals and delays the extraction of crucial insights 😫.

**Today, you are going to make their lives better.**

**Problem Statement**:
Make a CSV Importer for Google Sheets that lets users drag and drop CSV files onto the Google Sheet. The moment they drop the CSV file, allow them to select which columns to import 🗂️.

You get brownie points 🍪 if you can make it even easier by allowing them to filter the data as well before importing it into Google Sheets 🔍.

**Other pointers**:
- Import to Sheet – After validation and mapping, devise a method to populate the data into a chosen Google Sheet, either appending to existing data or creating a new sheet 📥📋.
- Optimize for Large Files – Large datasets are common in analytics. Your solution should effectively handle large CSV files (~15MB CSV file) without causing performance issues or prolonged waiting times 📈📦.

## Submission ⏰
The timeline for this submission is: **9AM, 30th Sept, 2023 - 12PM, 2nd Oct, 2023**

Some things you might want to take care of:
- Make use of git and commit your steps!
- Use good coding practices.
- Write beautiful and readable code. Well-written code is nothing less than a work of art.
- Use semantic variable naming.
- Your code should be organized well in files and folders which is easy to figure out.
- If there is something happening in your code that is not very intuitive, add some comments.
- Add to this README at the bottom explaining your approach (brownie points 😋)

Make sure you finish the assignment a little earlier than this so you have time to make any final changes.

Once you're done, make sure you **record a video** showing your project working. The video should **NOT** be longer than 120 seconds. While you record the video, tell us about your biggest blocker, and how you overcame it! Don't be shy, talk us through, we'd love that.

We have a checklist at the bottom of this README file, which you should update as your progress with your assignment. It will help us evaluate your project.

- [x]  My code's working just fine! 🥳
- [x]  I have recorded a video showing it working and embedded it in the README ▶️
- [x]  I have tested all the normal working cases 😎
- [x]  I have even solved some edge cases (brownie points) 💪
- [x]  I added my very planned-out approach to the problem at the end of this README 📜

## Got Questions❓
Feel free to check the discussions tab, you might get something of help there. Check out that tab before reaching out to us. Also, did you know, the internet is a great place to explore 😛

## Developer's Section

### Project Name
    CSVConnect
    
### Video Link -
    https://drive.google.com/file/d/1Hrb-zsaUukzvyDqHsSPGrk5dF0ZUPjok/view?usp=sharing






https://github.com/StackItHQ/stackit-hiring-assignment-VarunJain-2001/assets/80705703/38a7ab82-c63d-4a86-9cc4-cf47622728cf



### Approach
- **Upload CSV File:** 
   - Users are prompted to upload a CSV file using a file input field.
   - The uploaded CSV file is stored temporarily on the server.

- **Display Options:**
   - After uploading, users are presented with two main options:
       - **Show CSV**: Displays the entire CSV file in an HTML table.
       - **Apply Filters**: Allows users to apply filters to the data.

- **Show CSV Option:**
   - Clicking on this option opens the complete CSV file in an HTML table.
   - Provides a button to "Go to Spreadsheet," which redirects the user to the Google Spreadsheet where the file is imported.

- **Apply Filters Option:**
   - Users can select the columns they want to filter based on.
   - Once columns are selected, users can apply filtering criteria, such as filtering rows containing specific characters or words.

- **Filter Data:**
   - Implement filtering logic to process the selected columns and filtering criteria.
   - Display the filtered data in an HTML table.

- **Save Filtered Data to Google Sheets:**
   - Provide an option to upload/save the filtered data to Google Sheets.
   - Users can click an "Upload" button to send the filtered data to a designated Google Sheet.

- **Show Filtered CSV Option:**
   - After saving the filtered data, user will have the choice to see the filtered CSV data in a clear and organized HTML table.
   - Moreover, user will find a button named "Open in Google Sheets" that he can click to seamlessly access the filtered data in a Google Spreadsheet.


### Features
- **CSV File Handling:**
  - Upload and process CSV files with ease.

- **Data Display:**
  - View uploaded and filtered CSV data in HTML tables.
  - Quick access to Google Sheets for further analysis.

- **Filtering Capability:**
  - Select specific columns for filtering.
  - Versatile row-level and column-level filtering options.

- **Integration with Google Sheets:**
  - Save filtered data directly to Google Sheets.
  - Conveniently open the Google Sheet for further editing.

- **User-Friendly UI:**
  - Intuitive and user-friendly interface for a seamless user experience.
  - Clear buttons and labels for each action.

- **Data Validation:**
  - Implement data validation and error handling for robust performance.
