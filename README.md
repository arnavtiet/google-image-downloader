Image Downloader and Email Sender
This project is a web application built with Streamlit that allows users to download multiple images from Google based on a keyword search. Once downloaded, the images are compressed into a zip file and sent to the user's email address.

Features
Keyword-based Image Search: Search and download a specified number of images from Google using the provided keyword.
Image Compression: Downloaded images are automatically compressed into a zip file.
Email Functionality: The compressed file is sent directly to the user’s email.
Prerequisites
To run this application, make sure you have the following:

Python (version 3.6 or higher)
Streamlit: For the frontend
icrawler: For image crawling from Google
smtplib: For handling the email functionality
zipfile: For file compression
