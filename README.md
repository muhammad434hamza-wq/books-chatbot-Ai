# Marginalia — Books, Secondhand & New

A themed, single-page bookstore website built with HTML, CSS, and vanilla JavaScript.

## Features

- 📚 Book browsing by category (fiction, poetry, nonfiction, mystery, sci-fi, children's)
- 🛒 Cart and ❤️ wishlist functionality
- 🔍 Search by title or author
- 📖 Book detail views with condition grading (New, Like New, Good, Well-Read)
- 🤖 Built-in local sales-assistant chatbot:
  - Recommends books by genre, price, or condition
  - Suggests related/similar titles
  - Cross-sells complementary books from related categories
  - Lets customers add items to cart or open checkout directly from chat
- 🎨 Fully customizable theme via CSS variables (colors, fonts)
- 📱 Responsive design

## Tech Stack

- HTML5
- CSS3 (custom properties / CSS variables for theming)
- Vanilla JavaScript (no frameworks or dependencies)
- Google Fonts: Fraunces, Literata, IBM Plex Mono

## Getting Started

1. Clone or download this repository
2. Open `index.html` in any modern web browser
3. No build step or server required — it's a static single-file site

## Customization

The color theme can be changed by editing the CSS variables at the top of the `<style>` block:

```css
:root{
  --ink: ...;
  --ink-soft: ...;
  --parchment: ...;
  --parchment-deep: ...;
  --rust: ...;
  --rust-deep: ...;
  --brass: ...;
  --cream: ...;
}
```

## Chatbot

The chatbot runs entirely in the browser (no API key or backend needed). It can:

- Recommend books by category, price limit, or condition
- Suggest similar/related books for a named title
- Recommend a complementary cross-sell pick alongside any recommendation
- Add books to the cart when the user types things like "add it" or "add the first one"
- Open the cart drawer when the user says "checkout" or "ready to buy"
- Answer FAQs about hours, trade-ins, special orders, and the wishlist

## License

This project is open for personal and educational use.# books-chatbot-Ai
Upgraded the chatbot into a light sales assistant — it now suggests related books, cross-sells complementary titles, and lets customers add items to cart or check out directly through chat.
