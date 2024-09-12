# Motivational_line_maker
# Motivational Line Maker

## Description

The **Motivational Line Maker** is a simple web application that fetches and displays motivational quotes along with their authors. It displays a "Quote of the Day" when the page loads and allows users to generate new quotes by clicking the "New Quote" button. The quotes are fetched dynamically from the [Quotable API](https://quotable.io).

## Features

- **Display Motivational Quotes**: Shows a motivational quote and the author's name.
- **Fetch New Quotes**: Users can click a button to fetch and display a new quote.
- **Clean, Responsive Design**: Styled with CSS to ensure a visually appealing and responsive layout.

## Project Structure

The project consists of three main files:

1. **HTML (`index.html`)**  
   Provides the structure of the webpage with sections for displaying the quote and its author, and a button to generate a new quote.
   
2. **CSS (`style.css`)**  
   Defines the styling for the page, including fonts, layout, button effects, and general aesthetics.

3. **JavaScript (`script.js`)**  
   Handles the dynamic fetching of quotes from an external API and updates the quote and author displayed on the page.

## How It Works

1. When the page loads, a quote is fetched from the Quotable API and displayed on the page inside the `<p>` tag.
2. The user can click the **New Quote** button, which triggers an API call to get a fresh quote.
3. The fetched quote and its author replace the current displayed content dynamically.

## How to Run

1. Clone or download the project files.
2. Open `index.html` in any web browser.
3. A motivational quote will be displayed on page load.
4. Click the "New Quote" button to fetch a new random quote.

## Dependencies

- Font Awesome (for quote icons)  
  Included via CDN in the `<head>` of the HTML file.

- [Quotable API](https://quotable.io)  
  Provides the random quotes used in the application.


