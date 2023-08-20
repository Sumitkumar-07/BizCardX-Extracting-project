# BizCardX-Extracting_Business_Card_Data_with_OCR

# What is EasyOCR?

   EasyOCR, as the name suggests, is a Python package that allows computer vision developers to effortlessly perform Optical Character Recognition.It is a Python library for Optical Character Recognition (OCR) that allows you to easily extract text from images and scanned documents. In my project I am using easyOCR to extract text from **business cards.**
   
   When it comes to OCR, EasyOCR is by far the most straightforward way to apply Optical Character Recognition:

   - The EasyOCR package can be installed with a single pip command.
   - The dependencies on the EasyOCR package are minimal, making it easy to configure your OCR development environment.
   - Once EasyOCR is installed, only one import statement is required to import the package into your project.
   - From there, all you need is two lines of code to perform OCR — one to initialize the Reader class and then another to OCR the image via the readtext function.

# Project Overview
 
   BizCardX is a user-friendly tool for extracting information from business cards. The tool uses OCR technology to recognize text on business cards and extracts the data into a SQL database after classification using regular expressions. Users can access the extracted information using a GUI built using streamlit.
   The BizCardX application is a simple and intuitive user interface that guides users through the process of uploading the business card image and extracting its information. The extracted information would be displayed in a clean and organized manner, and users would be able to easily add it to the database with the click of a button. Further the data stored in database can be easily Read, updated and deleted by user as per the requirement.

# Technologies Used
   - Python
   - EasyOCR
   - Streamlit
   - MySQL
   - Pandas
   
# Libraries/Modules used for the project!

   - Pandas - (To Create a DataFrame with the scraped data)
   - mysql.connector - (To store and retrieve the data)
   - Streamlit - (To Create Graphical user Interface)
   - EasyOCR - (To extract text from images)
   
   
# Workflow

   To get started with BizCardX Data Extraction, follow the steps below:

   - Install the required libraries using the pip install command. Streamlit, mysql.connector, pandas, easyocr.

# Usage & Pages
  ## Home
   - The Home section provides an introduction to the application and its purpose. It also includes a visual representation of the application.
  ## Upload & Extract
   - In the Upload & Extract section, users can upload an image of a business card. The app processes the image using OCR and extracts relevant information, which 
     is displayed to the user. Users have the option to upload this data to the MySQL database.
  ## Modify
   - The Modify section allows users to update or delete business card data stored in the database. Users can select a cardholder's name, make changes to the data, 
     and commit those changes to the database.

# Database
   - The application uses a MySQL database named bizcardx_db to store business card data. The database schema includes fields such as company name, cardholder 
     name, designation, contact information, and an image of the uploaded business card.

