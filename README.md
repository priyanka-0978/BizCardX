**BizCardX: Extracting Business Card Data with OCR**

The Bizcardx project enables users to upload a picture of a business card and extract pertinent data from it. Additionally, the application can save the extracted data into a database along with the provided business card image, and it also gives users access to read, update, and remove data through a streamlined user interface.

**TOOLS AND LIBRARIES USED:**

**EasyOCR:**
Easyocr is a python module for extracting text from image. It is a general OCR that can read both natural scene text and dense text in document.

**STREAMLIT:**
Streamlit library was used to create a user-friendly UI that enables users to interact with the programme and carry out data retrieval and analysis operations.

**PYTHON:**
Python is a powerful programming language renowned for being easy to learn and understand. Python is the primary language employed in this project for the development of the complete application, including data retrieval, processing, analysis, and visualisation.

**MySQL:**
MySQL is a relational database management system based on SQL – Structured Query Language. The application is used for a wide range of purposes, including data warehousing, e-commerce, and logging applications.It provides a platform for storing and managing structured data, offering support for various data types and advanced SQL capabilities.

**REQUIRED LIBRARIES:**

1. easyocr

2. streamlit

3. PIL

4. numpy

5. pandas

6. mysql.connector

7. cv2

8. time

9. RegEx or Regular Expression(re)

  **Approach:**
  
  Begin by using Streamlit to create a basic and intuitive user interface that walks users through the process of uploading the business card image and retrieving its information.
  
  To extract the required information from the provided business card image, use easyOCR.Once the information has been extracted, display it in the Streamlit GUI in a well-organised and structured manner.
  
  In order to maintain the extracted information alongside the submitted business card image, use a database management system such as SQLite or MySQL.
  
  To obtain data from a database, utilise SQL queries.Create an easy-to-use user interface for the application so that data may be updated and deleted.
  
   **FEATURES:**
  
   The following functions are available in the BizCardx application:
  
  * Card Information can be extracted from uploaded business card images by users.
  
  * Users can add extracted data to a database with the press of a button.
  
  * Based on the chosen name designation and other criteria, users can simply update, delete, and retrieve images from database.



