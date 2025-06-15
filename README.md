# Cookies-extractor
Simple tool for getting Cookies of Facebook multiple Ids at Once, Coded By GYRO

## Requirements
- Python 3.x
- Dependencies listed in `requirements.txt` (requests, pyrua, cookiesparser)

## Installation

### 1. Clone the repository
```bash
git clone
https://github.com/GYRO-XD/Cookies-extractor.git
cd Cookies-extractor
```

### 2. Install dependencies
Make sure you have Python and `pip` installed, then run:
```bash
pip install -r requirements.txt
```

### 3. Run the script
To start the tool:
```bash
python cookies.py
```

### 4. Enter file containing Facebook IDs
The tool will ask you to enter the name of the file containing the Facebook IDs. The format for each line in the file should be:
```
<email|uid>|<password>
```

The tool will then attempt to log in to each Facebook account and save the cookies in `Cookies.txt`.

## Run in Termux (Android)
1. Install `git` and `python`:
   ```bash
   pkg install git
   pkg install python
   ```

2. Follow the steps above to clone the repository and run the script.

## Screenshot
![Screenshot](https://raw.githubusercontent.com/GYRO-XD/Cookies-extractor/refs/heads/main/Screenshot_20250614-192252_Termux.jpg)


## Version
Version 1.0
