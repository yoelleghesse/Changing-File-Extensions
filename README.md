The CSV to TXT File Converter is a Python script that recursively iterates through a directory tree and converts all CSV files to TXT files. It utilizes the pathlib module to work with file paths and directories.

Clone the repo:

``git clone https://github.com/your-username/csv-to-txt-converter.git``

Run the script:

``python csv_to_txt_converter.py``

Features:

- Recursively iterates through a directory and its subdirectories.
- Identifies CSV files based on their file extension (*.csv).
- Converts CSV files to TXT files by renaming them with a .txt file extension.

Config:

- Modify the root_dir variable to specify the directory where the CSV files are located.
- Ensure that the directory structure contains the CSV files that you want to convert to TXT format.

Ex., Suppose you have the following directory structure:

``files/
    ├── data1.csv
    ├── folder1/
    │   ├── data2.csv
    │   └── data3.csv
    └── folder2/
        ├── data4.csv
        └── data5.csv
``

After running the script, the CSV files will be converted to TXT format:

``files/
    ├── data1.txt
    ├── folder1/
    │   ├── data2.txt
    │   └── data3.txt
    └── folder2/
        ├── data4.txt
        └── data5.txt
``
