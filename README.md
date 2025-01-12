# Network Vulnerability Scanner

This project is a comprehensive network vulnerability scanner built using Python and Flask. It provides an interactive web application that allows users to perform vulnerability scans on their networks and view the results in a user-friendly format.

## Features

- **User-Friendly Interface**: An intuitive web interface built with Flask that allows users to easily input parameters for scanning.
- **Vulnerability Scanning**: The core functionality of the scanner analyzes network vulnerabilities and provides detailed results.
- **Interactive Visuals**: Engaging animations and styles to enhance user experience.
- **Modular Design**: The project is structured into modules for easy maintenance and scalability.

## Project Structure

```
network-vulnerability-scanner
├── src
│   ├── app.py                # Entry point of the Flask application
│   ├── scanner
│   │   ├── __init__.py       # Initializes the scanner module
│   │   ├── scanner.py         # Main logic for the network vulnerability scanner
│   ├── templates
│   │   ├── base.html          # Base template for the web application
│   │   ├── index.html         # Landing page for user input
│   │   └── results.html       # Displays scan results
│   ├── static
│   │   ├── css
│   │   │   └── styles.css     # CSS styles for the web application
│   │   ├── js
│   │   │   └── scripts.js     # JavaScript for interactive features
│   │   └── images             # Directory for images used in the application
│   └── utils
│       └── helpers.py         # Utility functions for the application
├── requirements.txt           # Python libraries required for the project
├── config.py                  # Configuration settings for the Flask application
└── README.md                  # Documentation for the project
```

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/network-vulnerability-scanner.git
   cd network-vulnerability-scanner
   ```

2. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

3. Run the application:
   ```
   python src/app.py
   ```

4. Open your web browser and navigate to `http://127.0.0.1:5000` to access the application.

5.Login page credentials:
Username:admin
Password:Password

## Screenshots
![Screenshot (362)](https://github.com/user-attachments/assets/3a8a552c-fba0-4edd-a7dc-940869a4424e)

![Screenshot (363)](https://github.com/user-attachments/assets/924edc84-1e5a-41dc-976f-51418f0008cc)

![Screenshot (364)](https://github.com/user-attachments/assets/a14535cb-9e6b-4bfa-b673-c01311a775fd)

![Screenshot (367)](https://github.com/user-attachments/assets/e9cbdbe4-d65a-41d0-9a78-16f6f0cf61d7)

![Screenshot (366)](https://github.com/user-attachments/assets/8a7545e1-959b-44bc-84d6-376b7f795b6a)

![Screenshot (365)](https://github.com/user-attachments/assets/303d9dfe-043e-46b2-8344-2118464e5f34)


## Usage

- Input the necessary parameters for the vulnerability scan on the landing page.
- Click the "Scan" button to initiate the scanning process.
- View the results on the results page, which will display the findings in a clear and organized manner.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any suggestions or improvements.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.
