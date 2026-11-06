# How to add a blog article

This file is just for you. It is not published on the website.

Each article is one text file in the `_posts` folder. When you save it to GitHub, the site
rebuilds itself in about a minute. The blog page, the article page, the "Keep reading"
links, the sitemap, the RSS feed and `llms.txt` (for AI assistants) all update on their own.

## Steps (in the browser, no software needed)

1. Go to github.com/jacobinbeta/ai-ops-website and open the `_posts` folder.
2. Click **Add file > Create new file**.
3. Name the file with today's date and a short web address for the article, all lowercase,
   words separated by dashes, ending in `.md`. For example:
   `2026-12-01-how-to-price-fractional-cfo-services.md`
   The part after the date becomes the article's web address:
   aioperationspartners.com/blog/how-to-price-fractional-cfo-services/
4. Paste the template below, fill it in, and write the article underneath.
5. Click **Commit changes**. Check the live blog page a minute or two later.

Or just ask Claude: "Add this as a new blog article" and paste your draft.

## Template

```
---
title: "Your Headline Here"
description: "One or two sentences on what the reader will learn. Shows in Google and on the blog page. Aim for 140 to 160 characters."
category: Finding clients
takeaways:
  - First key point, in one sentence.
  - Second key point.
  - Third key point.
---

Opening paragraph. Get to the point in the first two or three sentences.

## A section heading

Normal paragraphs are just text. Leave a blank line between paragraphs.

- A bullet point
- **Bold text** goes between double asterisks
- [A link](/signal-scan/) is the words in square brackets, then the address in round brackets

> A quote or sample message starts with a greater-than sign.
```

Everything between the two `---` lines must stay in that exact format. Keep the quote marks
around the title and description.

## Optional settings

Add any of these lines between the `---` lines if you need them:

- `updated: 2027-01-15` shows an "Updated" date when you revise an article.
- `published: false` saves the article without showing it on the site.
- `image: /assets/your-image.png` sets the picture shown when the article is shared on
  LinkedIn. Upload the image to the `assets` folder first.

## Tips that get articles read and found

- **Headline:** say exactly what the reader gets. Use the words a Fractional CFO would type
  into Google, e.g. "How to price fractional CFO services".
- **Key takeaways:** three or four one-line points. Skimmers read these first, and AI
  assistants often quote them.
- **Answer early:** give the main answer in the first few paragraphs, then the detail.
- **Use `##` headings** every few paragraphs so the article is easy to scan.
- **Link to one or two related pages**, like the Signal Scan or another article.
- **Use real examples only.** Your own experience is what makes an article worth citing.
