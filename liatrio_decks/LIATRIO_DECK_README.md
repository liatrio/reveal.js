# Liatrio Reveal.js Deck Template

This directory contains a template for Liatrio presentations using Reveal.js. It includes all of the styling and assets from the [Liatrio brand guide](https://www.liatrio.com/brand).

Use this template to quickly create new, branded Liatrio presentations with consistent style and best practices.

## How to Use the Template

### Prerequisites

1. Clone this repository

    ```bash
    git clone git@github.com:liatrio/reveal.js.git
    cd reveal.js
    ```

2. Install dependencies

    ```bash
    npm install
    ```

3. Start the development server

    ```bash
    npm start
    ```

4. Open <http://localhost:8000/liatrio_decks> in your browser to view the template and any decks you create.

### Making a New Deck

1. **Copy the Template File**
   - Duplicate `liatrio_deck_template.html` and rename it for your presentation (e.g., `my_presentation.html`).

2. **Customize Your Deck**
   - Update the title, subtitle, and presenter fields.
   - Replace example slides and content with your own material.
   - Add or remove slides as needed.
   - Replace images/screenshots where indicated.
   - Use the provided code block and callout examples as a starting point for technical content.

3. **Speaker Notes**
   - Add your talking points using `<aside class="notes">...</aside>` blocks under each slide.
   - Press `S` during your presentation to open the speaker notes window.

4. **Preview Your Deck**
   - Open your HTML file in a web browser to view and present your slides.
   - For best results, use a modern browser (Chrome, Firefox, Edge).

5. **Styling & Branding**
   - The template uses Liatrio's custom theme and code highlighting for a consistent look.
   - You can further customize styles in `static/liatrio.css` if needed.

## Using AI to Generate a Deck

1. Open this directory in your IDE along with the code you're working on.
2. Add the [liatrio_decks](liatrio_decks) directory to your AI context
3. Add git logs, PR descriptions, and other relevant references to the AI context
4. Instruct the AI to generate a new deck from the template based on the context
5. Review the generated deck for accuracy and completeness
6. Make any necessary adjustments to the deck

## Additional Tips

- Review the template for example slides, code, callouts, and speaker notes.
- Keep slides focused and concise.
- Use callouts sparingly for maximum impact.
- Reach out to the DevOps Enablement team if you need help or want to contribute improvements.

---

For more details on Reveal.js features, see the [Reveal.js documentation](https://revealjs.com/).
