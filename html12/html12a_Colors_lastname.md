**Before you start:** rename this file to `html12a_Colors_lastname.md`, using your own last name. Watch videos 1–3 and use **Part 1** of `html12_ColorsSeoProtocols_StudyGuide.md` (in this folder) to answer. Put the file in an `html12` folder in your `htmlCssJavaScript` repo. Commit and push when you're done.

**Name:**

---

# Task 12a — Web Colors (RGB and Hex)

Type your answers on the blank line under each **Answer:**. Don't just copy the study guide. Explain in your own words where a question asks why.

## 1. How screens make color

**a.** A screen turns its red and blue lights all the way up and leaves green off. What color do you see? Why is mixing light called **additive** color?

**Answer:** Red. Because you add light to make color


**b.** A classmate says, "Hex has fewer colors than RGB because hex codes use fewer digits." Are they right? Explain using the number of choices for each color.

**Answer:** No, they both have the same exact capabilities when it comes to what colors you can use.


## 2. Reading hex codes

**c.** Name the color for each hex code. For the last two, say whether it is a light or dark gray and how you can tell.

| Hex | Color |
|---|---|
| `#FF00FF` | Pink |
| `#00FFFF` | Blue |
| `#FFFF00` | Yellow |
| `#CCCCCC` | Light Gray (more white) |
| `#1A1A1A` | Dark Gray (more black) |

**d.** In `#3C9F12`, which pair is the strongest? What color family will this be?

**Answer:** 9f, Green


**e.** The CSS color name `lime` and the CSS color name `green` are not the same color. Give the hex code for each.

**Answer:** Lime: #00FF00 / Green: #008000


## 3. Converting between hex and RGB

**f.** Write each color the other way.

| Given | Write it as |
|---|---|
| `rgb(255, 255, 0)` | hex: #ffff00|
| `#0000FF` | rgb: rgb(0, 0, 255)|
| `rgb(0, 0, 0)` | hex: #000000|
| `#FFFFFF` | rgb: rgb(255, 255, 255)|

**g.** Convert the hex pair `C0` to a normal number. Show your work using the rule in section 1.4 (first digit × 16, plus the second digit). Remember C = 12.

**Answer:** 12 * 16 + 0 = 192


**h.** `#F80` is short hex. Write it out as a full 6-digit hex code.

**Answer:** #FF8800


## 4. Colors in CSS

**i.** Write CSS that does both of these. Use **hex** for one and **rgb** for the other.
- Makes `h1` text red
- Makes the page (`body`) background white

```css
h1 {
  color: #FF0000;
}

body {
  background-color: rgb(255, 255, 255);
}
```

**j.** Write a CSS rule for a class called `.overlay` that makes its background **black and half see-through**. Which number controls the see-through part?

```css
.overlay {
  background: rgba(0, 0, 0, 0.5);
}
```

**Answer:** 0.5


**k.** Why is yellow text (`#FFFF00`) on a white background (`#FFFFFF`) a bad choice? What would you change?

**Answer:** It's hard to see. I would maybe make the text `#000000` (black)


## 5. Your own site

**l.** Open the `styles.css` for your DIY website. Pick one color you used (or choose a new one you like). Write it as a hex code, then explain what the red, green, and blue pairs tell you about the color.

**Answer:** How much red, green, and blue are added to make that color.


## Closing 12a — Vocabulary

| Term | Your definition |
|---|---|
| RGB | Red, Green, Blue |
| Hex code | Numbers and letters to make a color using RGB |
| Hexadecimal | A base-16 number system|
| Additive color | Adding light to make color |
| rgba | Red, Green, Blue, Alpha (transparency )|