# Group & Profile Caption Generator

A simple web application that generates captions for group posts and profiles, allowing users to customize their captions with placeholders for names, ages, and locations. This application dynamically pulls data from text files, providing an enjoyable and unique way to create captions for social media.

![fb-group](https://github.com/user-attachments/assets/55d41bdb-e292-41af-a2c8-0bafed69365f)
 <!-- This line adds your favicon as an image preview -->

## Features

- **Dynamic Caption Generation**: Generates captions by randomly selecting from a list and replacing placeholders with random values.
- **Clipboard Copying**: Allows users to copy the generated caption to the clipboard with one click.
- **Reset Functionality**: Resets the used captions and reloads new captions from the text files.
- **Responsive Design**: The application is designed to work well on various screen sizes.
- **User-friendly Interface**: Easy to navigate and use for generating captions.

## Technologies Used

- HTML
- CSS
- JavaScript

## File Structure

/Group-Profile-Caption-Generator │ ├── index.html # Main HTML file ├── captions.txt # Text file containing the captions ├── names.txt # Text file containing the names ├── ages.txt # Text file containing the ages ├── locations.txt # Text file containing the locations └── favicon.png # Favicon for the web application

## How Placeholders Work

The application supports the following placeholders in the captions:

- {name}: This will be replaced with a random name from the names.txt file.
- {age}: This will be replaced with a random age from the ages.txt file.
- {location}: This will be replaced with a random location from the locations.txt file.

## Example of Caption Format

Adding Captions: You can add more captions to the captions.txt file by following the format:

Your caption here {name}, {age}, {location} ----
Another caption here {name}, {age}, {location} ----

Adding Names, Ages, and Locations: Similarly, you can add more entries to the names.txt, ages.txt, and locations.txt files, one per line.

## Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to fork the repository and submit a pull request.
