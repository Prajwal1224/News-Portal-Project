# 📰 News Portal Project

A simple and responsive web-based News Portal that allows admin users to post and manage news articles. Users can view news based on categories and search for trending topics.

## 📁 Project Setup Guide (Using XAMPP)

Follow the steps below to set up and run the project on your local machine using XAMPP.

### ✅ Step 1: Install XAMPP

1. Download XAMPP from the official site: https://www.apachefriends.org/index.html  
2. Install it on your system.  
3. Launch **XAMPP Control Panel** and start the following services:  
   - ✅ Apache  
   - ✅ MySQL  

### ✅ Step 2: Add Project to `htdocs` Folder

1. Navigate to the XAMPP installation directory:  
   - Example: `C:\xampp\htdocs`  
2. Paste your **news portal project folder** into this directory.  
   - Example: `C:\xampp\htdocs\News-Portal-Project`  

### ✅ Step 3: Import the Database

1. Open your browser and visit:  
2. Click **New** and create a database named:  
3. Click **Import** in the top menu.  
4. Select the file `newsportal.sql` from your project folder.  
5. Click **Go** to import the database.  

### ✅ Step 4: Configure Database Connection

1. Open the file named `config.php` (or similar).  
2. Update the database connection details like this:


$servername = "localhost";
$username = "root";
$password = "";
$database = "newsportal";

### ✅ Step 5:Run the Project

http://localhost/News-Portal-Project/
