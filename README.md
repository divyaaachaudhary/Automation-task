# Automation-task(C#)
This project is a C# Selenium automation script that opens the CloudQA Automation Practice Form and automatically fills out all available fields — including text inputs, dropdowns, checkboxes, nested iframes, and even the WYSIWYG description editor.

# How to Run This Project

Clone the repository

git clone https://github.com/your-username/your-repo-name.git


Navigate into the project folder:

cd your-repo-name


Make sure you have installed:

.NET SDK

Selenium.WebDriver (NuGet)

Selenium.Support

ChromeDriver (NuGet)

Run the project from terminal:

dotnet run


A Chrome window will open automatically and the script will fill the entire form.

📝 Project Description

This project uses Selenium WebDriver in C# to automate the CloudQA Automation Practice Form.
It auto-fills:

All input fields

Dropdown selections (Country, State, etc.)

Checkboxes + radio buttons

File uploads

Nested iframes (including frames without IDs)

WYSIWYG “Description” editor using JavaScript injection

The script is written to be adaptive, so it works even if HTML structure changes.
