<p align="center">
  <img width="270" height="270" src="https://github.com/GooglyBlox/wizard-quotes/blob/main/images/logo/wizard-logo.png?raw=true">
</p>

# Wizard Quotes API
Welcome to the Wizard Quotes API! This is a simple and free JSON API for accessing a curated list of humorous and whimsical wizard-related quotes. Perfect for any fantasy enthusiast, D&D player, or aspiring sorcerer!

## How to Use
Make a request to the JSON URL: https://raw.githubusercontent.com/GooglyBlox/wizard-quotes/main/quotes.json  
You will receive a JSON response with an array of quotes.  

You can fetch these quotes from any client that can make HTTP requests. For example, here is how you can fetch the quotes using JavaScript's Fetch API:
```javascript
fetch('https://raw.githubusercontent.com/GooglyBlox/wizard-quotes/main/quotes.json')
  .then(response => response.json())
  .then(data => {
    const quotes = data.quotes;
    // Use the quotes here...
  });
```

# Wizard Quotes Meme Maker
The Wizard Quotes Meme Maker is a web application that utilizes the Wizard Quotes API to generate top text/bottom text style wizard memes. Users can simply refresh the page to generate a new meme each time, with ~15,000 (as of writing) unique possibilities.  

Visit the website [here](https://wizard-quotes.googlyblox.repl.co).

## Contributing
Contributions are welcome! If you have a wizard quote or image you'd like to add, feel free to make a pull request.
