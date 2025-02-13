# web-dev-starter

This is a starter project for web development with no frameworks and minimal
dependencies. It is intended to be a starting point for web development projects
that are written in plain HTML, CSS, and JavaScript.

## Getting Started

To get started, clone this repository and run the following commands:

```bash
npm install
```
This will install the necessary dependencies for the project.

## Development

It is recommended to use the VSCode Live Server extension to run the project
locally. This will allow you to see changes in real-time as you make them. There
is no need to run a build process or refresh the page manually. Additionally,
you do not need to setup a local server to run the project.

Personally, I like to use a local browser to view my progress. 

## Testing

To run the tests for the project, run the following command:

```bash
npm test
```

## Accessibility Lab Answers

# Color
The background color started as green, which made the text difficult to read. I changed it to white in order to fix this.

According to WebAIM, the foreground of #000000 with the background of #008000 fails most of the tests (3/5). This scored 4.08:1. Changing the background to #FFFFFF changed the scoring to passing (5/5) and had a contrast score of 21.0:1

# Semantic HTML
For me, nothing really happened when trying to navigate with the keyboard. Using the arrow keys, I was able to scroll through the site. 

I did update the article text to use p headers instead of br headers. I also updated the table to use table headers / table datapoints more appropriately. I also replaced certain areas that used the font header with css headers (h1, h2, h3).

For the navigation, I added english as the language and references to adjust for different screen sizes / devices.

# The Images
Added alt text to images, so those who cannot see them are able to tell what images are present.



