<p align="center"><img src="https://i.imgur.com/DNxpZGG.png"></p>

<br>

This project offers a unique collection of 100 D&D 5e books, each teaching a distinct skill, proficiency, or spell. The HTML table provides a ready-made d100 list to enrich your D&D campaigns by introducing books with meaningful gameplay benefits.

## Table Features

- **100 Unique Books**: Each book in the list provides a unique skill, proficiency, or spell upon reading.
- **Randomized Selection**: Entries are numbered 1 to 100, allowing for easy random selection using a d100 roll.
- **Styled Table**: Alternate row colors and the Verdana font enhance readability.

## Player Rules for Reading the Books

1. **Reading Duration**: Requires **8 hours** of dedicated reading (can be broken up into sessions).
2. **Requirements**: A minimum Intelligence score of 10 is needed to comprehend any book.
3. **Skill Check**: After reading, characters must succeed on an **Intelligence check** to learn from the book.
4. **Book Exhaustion**: Books can only be used once per character.
5. **Trade and Value**: Books are valuable trade items and can be bought or sold based on their listed prices.

## Usage Instructions

1. **Download the HTML file** and open it in your browser.
2. **Use the d100 system** by clicking "Roll a d100" to display a random book entry.
3. **Follow the rules** listed in this README for characters to gain benefits from reading the books.

## Code Example

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <!-- Additional HTML structure here -->
</head>
<body>
    <button onclick="rollD100()">Roll a d100</button>
    <p id="result"></p>
    <table id="bookTable">
        <!-- Table data with 100 unique books goes here -->
    </table>
</body>
</html>
```

## Future Plans

- Implement tooltip descriptions for each skill, proficiency, or spell.
- Include a “lore” field to each book, detailing its background or origin.
- Expand the reading rules for different book rarities or campaign settings.

---

Feel free to fork this repository or submit pull requests to add additional features or books!
