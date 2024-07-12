README
Project Overview
This project demonstrates how to fetch data from the Faker API and display it on a webpage. Specifically, it fetches person data from the https://fakerapi.it/api/v1/persons endpoint and displays it in a formatted JSON string within a container element on the page.

How to Use
Download or Clone the Project:

1.Download the project as a ZIP file or clone it using Git.
2.Extract the ZIP file to your desired location (if downloaded).
3.Open the HTML File:
4.Open the index.html file in your preferred web browser.
5.Fetch and Display Data:
6.Click the "Get Person Data" button.
The application will fetch data from the API and display it in the div container below the button.


Code Explanation

Button: The button element with onclick="getAnimal()" triggers the getAnimal() function when clicked.

Container: The div element with the ID container is where the fetched data will be displayed.

JavaScript Function:
The getAnimal() function uses the Fetch API to get data from https://fakerapi.it/api/v1/persons.
It parses the JSON response and updates the inner HTML of the container element with the JSON data, formatted for readability.
Any errors encountered during the fetch operation are logged to the console.


Dependencies
There are no external dependencies required for this project.


Additional Notes
Ensure you have an active internet connection when running the project, as it fetches data from an online API.
You can modify the API endpoint URL in the fetch function to retrieve different types of data if needed.


Author
Shashank Awasthi
Feel free to reach out if you have any questions or need further assistance. Enjoy using the project!