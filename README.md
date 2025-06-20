# Search Suggestion System

This is a simple JavaScript implementation of a product suggestion system.  
It shows up to 3 product suggestions as the user types, based on matching prefixes.

## Features

- Lexicographically sorted suggestions
- Shows suggestions for each typed character
- Returns up to 3 matching products

## Example

```javascript
const products = ["mobile", "mouse", "moneypot", "monitor", "mousepad"];
const system = new SearchSuggestionSystem(products);
console.log(system.getSuggestions("mouse"));

[
  ["mobile", "moneypot", "monitor"],
  ["mobile", "moneypot", "monitor"],
  ["mouse", "mousepad"],
  ["mouse", "mousepad"],
  ["mouse", "mousepad"]
]
