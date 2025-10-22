# ADP Shares Outstanding

This web application fetches and displays the minimum and maximum shares outstanding for Automatic Data Processing (ADP) from the SEC Edgar database.

## Functionality

- Fetches data from the SEC API for the specified CIK.
- Parses the data to extract the entity name and shares outstanding information.
- Identifies the minimum and maximum shares outstanding after 2020.
- Dynamically updates the HTML page to display the fetched data.
- Supports CIK parameter to dynamically load data for other companies.

## Usage

1.  Clone the repository.
2.  Open `index.html` in your browser.
3.  To view data for a different company, append `?CIK=<CIK>` to the URL, where `<CIK>` is the 10-digit Central Index Key.

## Files

- `index.html`: The main HTML file that displays the data.
- `data.json`: The JSON file containing the processed shares outstanding data.
- `uid.txt`: A unique identifier.
- `README.md`: This file.
- `LICENSE`: Contains the MIT license.

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.