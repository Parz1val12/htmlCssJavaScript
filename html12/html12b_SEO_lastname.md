**Before you start:** rename this file to `html12b_SEO_lastname.md`, using your own last name. Watch videos 4–6 and use **Part 2** of `html12_ColorsSeoProtocols_StudyGuide.md` (in this folder) to answer. Put the file in an `html12` folder in your `htmlCssJavaScript` repo. Commit and push when you're done.

**Name:**

---

# Task 12b — Search Engine Optimization (SEO)

Type your answers on the blank line under each **Answer:**, or fix the code inside the code boxes. Explain in your own words where a question asks why.

## 1. How a search engine works

**a.** Put the three steps a search engine uses in order, and describe each one in one sentence of your own.

| Step | Name | What happens |
|---|---|---|
| 1 | Crawling | Automated bots or spiders explore the web by following links and sitemaps to discover new and updated web pages |
| 2 | Indexing | : The discovered pages are analyzed, cataloged, and stored in a massive database (the index) so they can be quickly retrieved later |
| 3 | Ranking | : When a user types a query, the search engine sorts and orders the indexed pages based on relevance, quality, location, and other algorithmic factors to display the best results on the Search Engine Results Page (SERP) |

**b.** You just built a new page, but **no other page links to it**. Why might a search engine have trouble finding it? (Hint: think about how crawlers find pages.)

**Answer:** It may never find it unless it is submitted to the search engine.


## 2. Organic vs. paid

**c.** You search for "pizza Medina Ohio." The first two results say **Sponsored**. The next ones do not. Which results are organic and which are paid? Which kind can SEO help with?

**Answer:** The first two results labeled **Sponsored** are the paid ads. The results below them are the organic search results. SEO can help with the organic results because it improves a site's ranking in the unpaid listings.

**d.** A business owner asks, "Why would I spend time on SEO when I could just pay for ads?" Give one reason SEO is still worth it.

**Answer:** SEO is worth it because it can bring long-term, free traffic over time without paying for every click, while ads stop delivering traffic as soon as the ad budget runs out.


## 3. Fix the head

This is the `<head>` of a bakery's home page. It works, but it is weak for SEO.

```html
<head>
  <meta charset="UTF-8">
  <title>Home</title>
</head>
```

**e.** Rewrite it below. Add a strong `<title>`, a meta description, and the viewport meta tag. Make up a name and town for the bakery.

```html
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Sweet Crumb Bakery in Medina, Ohio, bakes fresh artisan bread, pastries, custom cakes, and seasonal treats for every occasion.">
  <title>Sweet Crumb Bakery | Fresh Bread, Pastries & Cakes in Medina, Ohio</title>
</head>
```

**f.** Where does the text in your `<title>` show up? Where does the meta description usually show up?

**Answer:** The text in the `<title>` shows up in the browser tab and is often used as the clickable headline in search engine results. The meta description usually shows up underneath the page title in the search results snippet.

## 4. Fix the page

**g.** Rewrite this code to be better for SEO and accessibility. Fix the alt text, the link text, and the file name.

```html
<img src="IMG_4471.jpg" alt="picture">
<a href="page3.html">Click here</a> to see our menu.
```

Your fixed version:

```html
<img src="bakery-cinnamon-rolls.jpg" alt="Fresh cinnamon rolls and pastries on a tray at Sweet Crumb Bakery">
<a href="menu.html">See our menu</a> to browse our bakery selection.
```

**h.** A page has three `<h1>` tags: one for the logo, one for the page title, and one for the footer. What is wrong, and how should the headings be set up?

**Answer:** There should usually be only one main `<h1>` for the page's primary topic. The logo is not the main heading, and the footer should not be another `<h1>`. A better structure is to use one `<h1>` for the page title, then use `<h2>` and `<h3>` for section headings below it, while the footer can just be plain text or a smaller heading if needed.

## 5. Spot the problem

**i.** Here is a meta description someone wrote:

`content="cheap shoes cheap shoes best cheap shoes buy cheap shoes cheap shoes near me"`

What is this called? What will a search engine do about it? Rewrite it as a good description.

**Answer:** This is called keyword stuffing. A search engine will usually treat it as spammy or low-quality because the same keyword is repeated unnaturally, and it may ignore the text or lower the page's ranking. A better description would be: `content="Browse affordable shoes for everyday wear, running, and casual styles in Medina, Ohio. Find comfortable, stylish options for men and women."`

**j.** Name **two** SEO choices that also help people who use screen readers. Explain how each one helps both.

**Answer:** Two good examples are descriptive alt text and clear heading structure. Descriptive alt text helps screen readers explain what an image shows and also gives search engines more context about the page content. Clear headings like one main `<h1>` and meaningful `<h2>` and `<h3>` sections help screen reader users navigate the page and also help search engines understand the page structure and main topics.

## 6. Your own site

**k.** Write a `<title>` and a meta description for the `index.html` of your DIY website. Then add them to your real `index.html` and push it.

Example for a DIY website:

```html
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>IC Web Design | Creative Ideas and Handmade Inspiration</title>
  <meta name="description" content="Explore creative DIY projects, step-by-step tutorials, handmade inspiration, and practical ideas for home, gifts, and everyday life.">
</head>
```

## Closing 12b — Vocabulary

| Term | Your definition |
|---|---|
| SEO | Search engine optimization, which means improving a website so it ranks higher in unpaid search results. |
| Crawler (spider) | A search engine bot that visits pages, follows links, and collects information to add to the search index. |
| Organic results | The unpaid listings on a search results page that appear because they match the query and are ranked by relevance. |
| Meta description | A short summary of a page’s content written in the HTML head that can appear under the title in search results. |
| Keyword stuffing | Repeating the same keyword too many times in a page or description in an unnatural way, which can hurt SEO. |
| SERP | Search Engine Results Page, the page that shows the list of results after a user searches. |
