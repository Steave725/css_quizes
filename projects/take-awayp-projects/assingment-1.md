

# Take-Home Assignment: Styled Profile Page

## Assignment Title:

**“My Favorite Things – CSS Mastery Project”**

---

# Instructions for Students

Create a webpage about your favorite things (movie, food, hobby, place, etc.) and style it using the CSS concepts we’ve learned.

You must demonstrate:

* External CSS
* Internal CSS
* Inline CSS
* Multiple selectors
* Proper syntax
* Understanding of cascading

---

# Project Structure

```
favorite-things/
│
├── index.html
└── style.css
```

---

# Part 1: HTML Requirements (index.html)

Your page must include:

1. A main heading (`h1`) – “My Favorite Things”

2. At least 2 subheadings (`h2`)

3. At least 4 paragraphs

4. One ordered list (`ol`) with at least 3 items

5. One image (`img`)

6. One `div` container wrapping a section of content

7. The following attributes:

   * One element with an id
   * Two different elements using the same class
   * One element with two classes

8. A correct link to your external CSS file inside the `<head>`

---

# Part 2: CSS Requirements (style.css)

Your CSS file must include:

1. Universal Selector
   Add padding or margin to all elements.

2. Element Selector
   Style all `h2` elements.

3. Class Selector
   Style at least two elements using the same class.

4. ID Selector
   Style one unique section differently.

5. Descendant Selector
   Example: `div p`
   Style paragraphs inside a div differently.

6. Grouping Selector
   Style `h1, h2` together with one rule.

---

# Part 3: CSS Application Rules

## External CSS

Most of your styling must be inside `style.css`.

## Internal CSS

Inside a `<style>` tag in the `<head>`:

* Change the background color of the page
  OR
* Change the color of one specific heading

## Inline CSS

Use inline styling on ONE element only.

Example:

```html
<p style="color: red;">This text uses inline CSS.</p>
```

---

# Part 4: Comments

You must include:

* At least 3 CSS comments
* At least 1 HTML comment

Example:

```css
/* This styles the favorite section */
```

---

# Part 5: Avoid These Errors

Be careful:

* End each declaration with `;`
* Close every `{ }`
* Do not misspell property names
* Do not write values like `10 px`
* Make sure class and id names match exactly

---

# Bonus (Extra Credit)

Choose at least ONE:

* Add a hover effect on links or list items
* Add a border and padding to create a “card” design
* Change a style using cascading (override a rule)
* Add text alignment styling
* Use `font-family`

---

# Grading Rubric

| Requirement                          | Points |
| ------------------------------------ | ------ |
| Correct HTML structure               | 10     |
| External CSS linked properly         | 15     |
| Required selectors implemented       | 20     |
| Internal + Inline CSS used correctly | 15     |
| Comments included                    | 10     |
| No syntax errors                     | 15     |
| Clean formatting & organization      | 15     |
| Total                                | 100    |

---

# Submission Instructions

* Submit:

  * `index.html`
  * `style.css`
* Test your page in a browser before submitting
* Make sure all styles appear correctly
* Check for syntax errors carefully


