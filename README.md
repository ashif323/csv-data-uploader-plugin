# CSV Data Uploader Plugin

A custom WordPress plugin that allows users to **upload CSV files** and insert their data directly into a custom database table.  

## 📌 Features
- Upload CSV files via shortcode `[csv-data-uploader]`.
- Automatically creates a custom database table `wp_students_data` on plugin activation.
- AJAX-powered upload for smooth user experience (works for logged-in and logged-out users).
- Saves student information:
  - Name  
  - Email  
  - Age  
  - Phone  
  - Photo  

## 🚀 Installation
1. Download or clone this repository into your WordPress plugins directory:  
2. Activate the plugin from **WordPress Admin > Plugins**.
3. Add the shortcode below to any post or page:



## ⚙️ Usage
1. Prepare a CSV file with the following columns (in order):  

- Example:
  ```csv
  name,email,age,phone,photo
  John Doe,john@example.com,25,1234567890,john.jpg
  Jane Smith,jane@example.com,30,9876543210,jane.png
  ```
2. Visit the page where you added `[csv-data-uploader]`.
3. Upload the CSV file and submit.
4. The data will be inserted into the custom table (`wp_students_data`).

## 📂 File Structure


## 🛠️ Requirements
- WordPress 5.0+
- PHP 7.4+
- MySQL/MariaDB

## 📝 Notes
- Table is created as `wp_students_data` (prefix depends on your installation).  
- CSV **first row is treated as header** and skipped during insertion.  

## 👨‍💻 Author
**Mohammad Ashif Iqbal**  
- [Website](https://ashifiqbal.com)  
- [GitHub](https://github.com/ashif323)

---

