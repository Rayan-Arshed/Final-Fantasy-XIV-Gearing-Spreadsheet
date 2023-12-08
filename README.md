# Final-Fantasy-XIV-Gearing-Spreadsheet

##Overview
A personal project of mine to create a spreadsheet in Google Sheets that allows me to keep track of my gear and weapons, and automatically updates sheet-wide, calculating other resources, when I update a class' gear pieces.

## Project Goals
As I like to gear up every class I can in this game, I needed my spreadsheet to be able to keep track of the 8 typical gearsets that can be built for each role, so I set that as a goal. Also, I wanted the spreadsheet to automatically update whenever I input that I got a new piece of gear, so by using cross-sheet referencing, updating a value in the best in slot columns in the related role sheet (the columns who's headers are purple), it automatically fills in the larger sheet which helps me to keep track of my overall progress. This page is then also calculated upon, and worked into manipulating the title page, which gives me a quick overview of my progress, what's left to get, and my relic weapon progress per class. I also aimed to use conditional formatting to colour code the whole sheet, to make it easily digestible, and straightforward to understand.

## Tools and Technologies Used, as well as Strong Points
### Google Sheets
- Cross-sheet referencing to aid in automated updating across the workbook
- Conditional formatting used to make the spreadsheet look aesthetically appealing
- Complex formulas such as multiple length IFS statements and others seen below:
![image](https://github.com/Rayan-Arshed/Final-Fantasy-XIV-Gearing-Spreadsheet/assets/95011650/daf8f5ff-0ab6-466d-bbbf-e551520392d1)
![image](https://github.com/Rayan-Arshed/Final-Fantasy-XIV-Gearing-Spreadsheet/assets/95011650/e104fd9a-d037-42df-8add-e2f37be7cf64)

## Link to the spreadsheet:

https://docs.google.com/spreadsheets/d/e/2PACX-1vSZbGF3u9nodD5QuckZIIwsvWU92qPfDJMCBwkduWy0KatfEq_rEjpTU4IcR4rTLzpdM0vXWV6AeCZZ/pubhtml

## Screenshots and Explanations of Spreadsheet:

### Title Page

![image](https://github.com/Rayan-Arshed/Final-Fantasy-XIV-Gearing-Spreadsheet/assets/95011650/9f2c693c-b9e9-4198-90f0-555fffe3e420)

### Gear Overview Sheet

![image](https://github.com/Rayan-Arshed/Final-Fantasy-XIV-Gearing-Spreadsheet/assets/95011650/48f497a2-b212-4b90-9b4c-6bbd54ffdf54)

### Individual Class sheet

![image](https://github.com/Rayan-Arshed/Final-Fantasy-XIV-Gearing-Spreadsheet/assets/95011650/0fb3fdbb-de9d-4606-bcec-df4e32dd757b)

### Spreadsheet can be collapsed at the top of the page via the groupings in order to filter date. In this example, I have collapsed the data so only the 3rd raid tier of data is visible, as the 3rd raid tier was selected on the title page

![image](https://github.com/Rayan-Arshed/Final-Fantasy-XIV-Gearing-Spreadsheet/assets/95011650/5f5a582c-7729-4ba6-ae71-2fd4e9717de2)

### The raid tier can be adjusted, which changes the values that will be loaded into the overview and title pages

![image](https://github.com/Rayan-Arshed/Final-Fantasy-XIV-Gearing-Spreadsheet/assets/95011650/975c6522-4a75-4d1c-aeb3-925113f32e34)

### Depending on which raid tier is selected, the best in slot item level is automatically adjusted too, these are all calculated from a fixed item level listed in the overview sheet, which can be updated every expansion which is every 2 years to keep the sheet up to date, as the intervals between artifact gear and the other gear pieces are consistent 

![image](https://github.com/Rayan-Arshed/Final-Fantasy-XIV-Gearing-Spreadsheet/assets/95011650/4a5bf820-7950-4f4e-a09d-db6459bad39c)
![image](https://github.com/Rayan-Arshed/Final-Fantasy-XIV-Gearing-Spreadsheet/assets/95011650/4f4d88c1-ba1d-43a6-b0a1-2a39b239c75f)
![image](https://github.com/Rayan-Arshed/Final-Fantasy-XIV-Gearing-Spreadsheet/assets/95011650/79b2de5d-f282-4f95-a07d-6203d496359d)
![image](https://github.com/Rayan-Arshed/Final-Fantasy-XIV-Gearing-Spreadsheet/assets/95011650/23137960-f6c3-4cfc-b7b1-5fb2850bb77b)

### Changing the artifact level automatically updates the ilevels in the class spreadsheets, which in turn mean the spreadsheet will never go out of date; only the columns need to be renamed each expansion and filtered if a raid tier is not released yet

![image](https://github.com/Rayan-Arshed/Final-Fantasy-XIV-Gearing-Spreadsheet/assets/95011650/ef8b6fe2-6ddf-4781-a0e4-23f3b59f150f)
#### Average Item Level is a stat in game, so that will need to be manually updated by users too, but the sheet keeps track of that on the title page automatically whenever it is changed


### This all means that users only need to highlight the pieces they wish to obtain for each class in the individual work sheets, and can select the current raid tier that they are gearing for, and the spreadsheet will automatically handle the rest of the processing and labelling of data.
