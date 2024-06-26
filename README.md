![image](https://github.com/oracio-tech/LinkxDoxer/assets/78463847/0d8d13bd-0e54-4fcd-ab32-5b1d813c2b56)

)

# LinkxDoxer

LinkxDoxer is a Python script designed to efficiently retrieve all links found directly under the webpage of a given URL. It is ideal for web developers, bug bounty hunters, and OSINT (Open-Source Intelligence) enthusiasts seeking to analyze links under a webpage and uncover valuable information(Expected In Ideal Cases)
## Features

- Retrieves all links found directly under the webpage of a given URL.
- Supports HTTP and HTTPS URLs.
- Customizable number of retries and delay between retries to handle network issues gracefully(Code Edit).
- Provides detailed error messages for better troubleshooting.

## New Features | Version LinkxDoxer 1.2:
- Enhanced Link Extraction: Version 1.2 improves the accuracy and reliability of extracting all links from a webpage, ensuring no relevant links are missed.
- Retry Mechanism: Includes a robust retry mechanism for handling network issues, making the tool more reliable even in unstable network conditions.
- User-Friendly Save Option: Adds a convenient feature to save extracted links to a file with user confirmation and file existence check, preventing accidental overwrites.
  

### Getting Started

1. **Installation:**
    - Clone this repository to your local machine.
    ```
    git clone https://github.com/oracio-tech/LinkxDoxer.git
    ```
2. **Prerequisites:**
    - Python 3
    - Install required dependencies using pip:
    ```
    pip install -r requirements.txt
    ```
3. **Usage:**
    - Run the script using Python:
    ```
    python LinkxDoxer_v1.2.py
    ```
    - Enter the website URL when prompted and press Enter.
4. **Output:**
    - The script will display all the links found directly under the provided URL.

## Customization

You can customize the behavior of the script by modifying the following parameters in the script:
- `retries`: The number of times the script will retry retrieving the webpage in case of failures.
- `delay`: The delay (in seconds) between retry attempts.

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvement, please open an issue

## License

This project is licensed under the CC BY-NC 4.0 LEGAL CODE Attribution-NonCommercial 4.0 International License - see the LICENSE.txt file for details.


