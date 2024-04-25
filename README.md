# FinalYearProject User Manual

## Project Setup Guide

### Cloning the Repository
`git clone https://github.com/shivnathtathe/FinalYearProject.git

### Setting Up the Environment
cd FinalYearProject
python3 -m venv venv
source venv/bin/activate  # For Unix/Linux
venv\Scripts\activate      # For Windows

### Installing Dependencies
pip install -r requirements.txt

### Database Configuration
- Ensure MySQL is installed and running.
- Update database configuration in `app.py`.

### Running the Flask Application
python app.py

### Accessing the Application
Open http://localhost:8000 in your web browser.

## Troubleshooting
Refer to documentation or seek assistance if issues arise.

## Project Uninstallation Guide

### Removing the Project Directory
rm -rf FinalYearProject

### Deactivating and Removing the Virtual Environment
deactivate  # For Unix/Linux
deactivate.bat  # For Windows
rm -rf venv  # For Unix/Linux
rmdir /s venv  # For Windows

### Removing Project Dependencies
pip uninstall -r requirements.txt

### Database Cleanup (if necessary)
Manually clean up databases as needed.

### Additional Cleanup
Remove any leftover configuration files, logs, or project-related files.

## Note:
- Exercise caution during uninstallation.
- Backup important data before uninstalling.
