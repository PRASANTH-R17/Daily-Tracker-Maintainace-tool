# Daily-Tracker-Maintainace-tool
Spreadsheet Link : https://docs.google.com/spreadsheets/d/1uAV7_kBEIzkuUfjtF7JRptILz7mD0OUpa_uzwXMRamQ/edit?usp=sharing

Please make a copy of this spreadsheet for your use.

Many organizations and educational institutions maintain a record of each member's activities in a spreadsheet. This tool simplifies the process and helps to track daily activities (only planned meetings and other activities filled manually) and time management.

Working 
  - The tool retrieves meeting details from Google Calendar.
  - It fills in the daily tracker spreadsheet for each member.
  - The tool includes meeting titles and dates for each day.

This tool handles the entire team tracker separately, with each team member having their own time tracker spreadsheet.

Initially, we intended to build this tool to automatically fill in meeting details at 8:00 am every morning. However, if we made it fully automated, we would need master permission for each team member's calendar, which could compromise each member's data privacy.

Thus, we created a semi-automated tool that requires team members to check a custom button or menu visible on their own sheet. If a team member checks the custom menu, the script will automatically retrieve the meeting data from that team member's calendar and fill in the details on their individual sheet.

This tool also automatically filters the meetings based on status, only retrieving those with a "yes" status (i.e., meetings created by another person that we have accepted an invitation to attend) and Owner Meeting (i.e., those that we have created ourselves ).
