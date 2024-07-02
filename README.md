# Practo Automation Test with Robot Framework

This project contains a Robot Framework test to search for a dentist on Practo and book the first available slot.

## Prerequisites

1. **Python**: Make sure Python is installed on your system. You can download it from [python.org](https://www.python.org/).

2. **pip**: Ensure you have `pip` installed. It usually comes with Python. You can check by running:
   ```bash
   pip --version

3. **Robot Framework:**: Install Robot Framework using pip:
```
 pip install robotframework
```

4. **SeleniumLibrary:** Install the SeleniumLibrary for Robot Framework:
```

pip install robotframework-seleniumlibrary
```

5. **WebDriver:** : Ensure you have the appropriate WebDriver for your browser installed and available in your system PATH.

## Setting Up the Project

1. **Create a virtual environment (optional but recommended):**
```
python -m venv myenv
```
2. Activate the virtual environment: 
   -On macOS and Linux:
```
source myenv/bin/activate
```
 -On windows
```
myenv\Scripts\activate
```
3. ***Install required libraries:***
```
   pip install robotframework
pip install robotframework-seleniumlibrary
```
## Running the Test
1. Navigate to the directory containing the practo_test.robot file.

2. Run the test using the following command:
```
robot login_test.robot
```


