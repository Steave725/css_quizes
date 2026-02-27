
# Final Project: Roblox Fan Website (Multi-Page)

## Assignment Title:

**“Roblox Game Showcase – Multi-Page Website”**

---

# Objective

Create a multi-page website about Roblox.
Your site can focus on:

* Your favorite Roblox game
* Your Roblox character
* Game strategies
* A made-up Roblox game you designed

This project tests:

* Semantic HTML
* Forms
* Tables
* Embedded video
* Multi-page navigation
* CSS selectors
* Cascading and specificity
* External, internal, and inline CSS

---

# Project Structure

```
roblox-website/
│
├── index.html
├── games.html
├── gallery.html
├── contact.html
└── styles.css
```

You must create all four HTML pages.

---

# General Requirements (All Pages)

Each page must include:

* Proper HTML structure (`<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`)
* Link to `styles.css`
* Semantic tags:

  * `<header>`
  * `<nav>`
  * `<main>`
  * `<section>`
  * `<footer>`
* A navigation menu that links to ALL pages
* At least one HTML comment per page

Navigation must work correctly on every page.

---

# Page 1: Home (index.html)

Must include:

* One `h1` (Example: “My Roblox World”)
* Introduction paragraph about Roblox
* One `<article>` section
* One embedded video:

  * YouTube gameplay video (iframe) OR
  * `<video>` element
* One element with an id
* One element with a class

---

# Page 2: Games (games.html)

Must include:

* At least two `h2`
* At least three paragraphs
* One table that shows:

  * Game name
  * Genre
  * Rating (out of 10)

Table must include:

* `<caption>`
* `<th>`
* `<td>`
* Minimum 3 rows

---

# Page 3: Gallery (gallery.html)

Must include:

* At least 3 images (Roblox characters or gameplay)
* Proper `alt` attributes
* A section wrapping the images
* Two elements using the same class
* One element with two classes

---

# Page 4: Contact (contact.html)

Create a “Join My Roblox Team” form.

Form must include:

* `<form>`
* Text input (Username)
* Email input
* Password input
* Radio buttons (Skill Level: Beginner / Intermediate / Pro)
* Checkbox (I agree to the rules)
* Dropdown (`<select>`) for favorite game type
* Textarea (Why should we accept you?)
* Submit button
* Proper `<label>` elements

---

# CSS Requirements (styles.css)

All major styling must be in the external stylesheet.

You must include:

## 1. Universal Selector

Reset margin or padding.

## 2. Element Selectors

Style:

* `body`
* `p`
* `table`
* `nav`

## 3. Class Selector

Used on multiple elements (example: `.card`)

## 4. ID Selector

Style one special section differently.

## 5. Grouping Selector

Example:

```
h1, h2, h3
```

## 6. Descendant Selector

Example:

```
section p
```

## 7. Attribute Selector

Example:

```
input[type="text"]
```

## 8. Hover Effect

Add hover effect to navigation links.

## 9. Table Styling

Add:

* Borders
* Padding
* Background color for header row

## 10. Form Styling

Style:

* Input fields
* Labels
* Submit button
* Add spacing

---

# CSS Application Rules

You must demonstrate:

## External CSS

Main styling in `styles.css`.

## Internal CSS

On ONE page only:

* Add a `<style>` section
* Override or add one style

## Inline CSS

Use inline CSS on ONE element only in the entire project.

---

# Cascading Demonstration

You must:

1. Style all paragraphs using:

   ```
   p { }
   ```
2. Override one paragraph using a class
3. Override another using an id
4. Show clear understanding of specificity

---

# Comments

Include:

* At least 5 CSS comments
* At least 1 HTML comment per page

---

# Avoid These Errors

* Missing semicolons
* Unclosed braces
* Misspelled CSS properties
* Incorrect values like `20 px`
* Broken navigation links
* Missing closing tags

---

# Bonus (Optional)

* Create a “game card” design with padding and border
* Add box-shadow
* Use flexbox for layout
* Add smooth hover transitions
* Use consistent Roblox-inspired colors

---

# Grading Rubric

| Requirement                         | Points |
| ----------------------------------- | ------ |
| All pages created correctly         | 15     |
| Navigation works on all pages       | 10     |
| Semantic HTML structure             | 15     |
| Table implemented correctly         | 10     |
| Form implemented correctly          | 15     |
| Required CSS selectors used         | 15     |
| Cascading demonstrated clearly      | 10     |
| Internal + Inline CSS included      | 5      |
| Comments included                   | 5      |
| Clean formatting / no syntax errors | 10     |
| Total                               | 100    |

