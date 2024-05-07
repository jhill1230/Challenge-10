# Challenge-10 Logo Maker

## Task

Your task is to build a Node.js command-line application that takes in user input to generate a logo and save it as an SVG fileLinks to an external site.. The application prompts the user to select a color and shape, provide text for the logo, and save the generated SVG to a .svg file.



### User Story

```md
AS a freelance web developer
I WANT to generate a simple logo for my projects
SO THAT I don't have to pay a graphic designer
```

## Acceptance Criteria

```md
GIVEN a command-line application that accepts user input
WHEN I am prompted for text
THEN I can enter up to three characters
WHEN I am prompted for the text color
THEN I can enter a color keyword (OR a hexadecimal number)
WHEN I am prompted for a shape
THEN I am presented with a list of shapes to choose from: circle, triangle, and square
WHEN I am prompted for the shape's color
THEN I can enter a color keyword (OR a hexadecimal number)
WHEN I have entered input for all the prompts
THEN an SVG file is created named `logo.svg`
AND the output text "Generated logo.svg" is printed in the command line
WHEN I open the `logo.svg` file in a browser
THEN I am shown a 300x200 pixel image that matches the criteria I entered
```

## Mock-Up

![Square](/Examples/logo.svg)


## Usage

As a freelance web developer, you can use this command-line application to generate a simple logo for your projects without having to pay a graphic designer. Follow the steps below to create your logo:

Run the command-line application.
You will be prompted to enter the text for your logo. You can enter up to three characters.
Next, you will be prompted to choose the text color. You can enter a color keyword (e.g., "red", "blue", "green") or a hexadecimal number (e.g., "#FF0000").
After selecting the text color, you will be presented with a list of shapes to choose from: circle, triangle, and square.
Choose the shape you want to include in your logo.
Once you've selected the shape, you will be prompted to choose the shape's color. Similar to the text color, you can enter a color keyword or a hexadecimal number.
After entering input for all the prompts, an SVG file named logo.svg will be created in the current directory.
You will see the message "Generated logo.svg" printed in the command line, indicating that the logo file has been created successfully.
Open the logo.svg file in a browser to view your logo. The image will be displayed as a 300x200 pixel image that matches the text and shape criteria you entered.

