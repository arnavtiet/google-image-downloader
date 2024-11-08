Image Downloader and Email Sender
This project is a web application built with Streamlit that allows users to download images from Google based on a search keyword. The downloaded images are compressed into a zip file and sent directly to the user's email.

Features
Keyword-based Image Search: Users can specify a keyword and the desired number of images to download from Google.
Image Compression: Images are automatically compressed into a zip file.
Email Delivery: The zip file is sent directly to the provided email address.
Prerequisites
To run this application, you’ll need:

Python (3.6 or higher)
Streamlit: For building the frontend interface
icrawler: To enable image crawling from Google
smtplib and email libraries: For handling the email process

Clone the repository:
bash
Copy code
git clone https://github.com/yourusername/your-repo-name.git
Navigate to the project folder:
bash
Copy code
cd your-repo-name
Install the dependencies:
bash
Copy code
pip install -r requirements.txt
