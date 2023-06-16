# chucknorrisAPI
This Java application demonstrates how to call the Chuck Norris API and fetch data in JSON format. 
It retrieves a random Chuck Norris joke from the API and prints various fields from the JSON response.

## Prerequisites

- Java Development Kit (JDK) installed on your machine
- Internet connectivity to make API calls

## Usage

1. Open the `Main.java` file located in the `org.geekster` package.

2. Run the `main` method in the `Main` class to execute the program.

Upon running the program, it will make a GET request to the Chuck Norris API and retrieve a random joke in JSON format. The program will print the following fields from the JSON response:

- `icon_url`: URL of the Chuck Norris icon
- `updated_at`: Last updated timestamp
- `created_at`: Created timestamp
- `id`: Unique ID of the joke
- `value`: The joke itself
- `url`: URL of the joke
- `categories`: Categories associated with the joke

If the API call is successful (response code 200), the program will print the JSON response and the extracted fields. Otherwise, an error message will be displayed.

## Acknowledgments

- The Chuck Norris API for providing random jokes.
