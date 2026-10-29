# Equity in Transport: Use cases

**An interactive showcase of 15 real-world use cases on understanding and tackling transport poverty.**
Search by keyword, spin the globe, and open any case to read it with its sources.

[![Live demo](https://img.shields.io/badge/live%20demo-open%20the%20site-181D70?style=for-the-badge)](https://francescad99.github.io/Transport-Poverty/)

![Preview of the Equity in Transport use cases website](social-preview.png)

## What it is

The use cases are part of the **Equity in Transport: Understanding and Tackling Transport Poverty** course. This site turns them into something you can explore instead of a long document: from gender-sensitive planning in Vienna and cable cars in Medellín, to fare-free transport in Luxembourg, bus rapid transit in Ahmedabad and low-emission zones in London.

## Features

- **Dashboard of cases:** every use case is a card with a photo, title, subtitle and keywords.
- **Search and filters:** free-text search across the full text of every case (it understands everyday words, so "women" finds the gender cases), plus filters by focus area, region and keyword. Counts update as you filter.
- **Interactive globe:** drag it to turn it, select a numbered pin to open that case. Pins fade when a case is filtered out, and the globe turns to the matching cases.
- **Case pages that follow the course text:** context, challenge, intervention, impact, equity gaps, key takeaways and **sources**, in the same order as the source document.
- **Related use cases:** each case links to the cases that share the most keywords with it.
- **Works on phones** and respects light and dark mode.
- **Follows the Equity in Transport brand:** colours, graphic language and typography.

## Use it

Open the live demo above, or run it locally by opening `index.html` in a browser. There is nothing to install or build.

### Link straight to a case

Add `#/case/N` to the address, where `N` is the use case number:

```
https://francescad99.github.io/Transport-Poverty/#/case/1
```

### Embed it in another page

```html
<iframe
  src="https://francescad99.github.io/Transport-Poverty)/"
  title="Equity in Transport use cases"
  style="width:100%; height:900px; border:0;"
  loading="lazy"
  allowfullscreen>
</iframe>
```

The page is laid out like an app, so give the frame at least 800 px of height.

## How it is built

One self-contained `index.html`: plain HTML, CSS and JavaScript, with the photos, logos and case texts embedded in the file. The only things it loads from outside are the [d3](https://d3js.org/) library (for the globe) and Google Fonts, which is used as a fallback font. The map outlines come from [Natural Earth](https://www.naturalearthdata.com/) via the `world-atlas` package.

## Credits and funding

- **Equity in Transport: Understanding and Tackling Transport Poverty** course.
- Developed with the support of **EIT Urban Mobility**, co-funded by the European Union.
- Partners: **UCL** and **Factual**.

## Content, images and logos

The use case texts, photographs, illustrations, logos and the Equity in Transport brand belong to their respective owners and are **not** covered by an open-source licence. Please contact the course team before reusing or republishing them. *(Add photo credits here once confirmed.)*

## Contact

Francesca D'Alessandro - Project Mobility COnsultant and Data SPecialist at FACTUAL Consulting
