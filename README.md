# Image Search App

This is a simple web application that allows users to search for images using the Unsplash API. Users can enter a search query in the input field, and the app will display a list of image results from Unsplash. Users can also click the "Show More" button to load additional image results.

## Prerequisites

Before you get started, you will need the following:

- [Unsplash API Access Key](https://unsplash.com/developers)
  - You need to sign up for an Unsplash developer account and obtain an API access key. Replace `accessKey` in the code with your own access key.

## Installation

1. Clone or download this repository to your local machine.

2. Open the `index.html` file in a web browser.

## Usage

1. Enter a search query in the input field.

2. Press the "Enter" key or click the "Search" button to perform the image search.

3. The search results will be displayed below the input field. You can click on an image to view it on Unsplash.

4. If there are multiple pages of results, the "Show More" button will appear. Clicking this button will load additional image results.

## Code Explanation

- The JavaScript code in `script.js` sets up event listeners for the form submission and the "Show More" button click.

- When the form is submitted, the `searchImages` function is called. This function fetches image data from Unsplash based on the user's search query and displays the results on the web page.

- The Unsplash API access key is required for making API requests. Ensure that you have replaced `accessKey` in the code with your own access key.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- This project uses the Unsplash API to retrieve image data. Thanks to Unsplash for providing this service.

Feel free to customize and expand upon this code to create your own image search application!
