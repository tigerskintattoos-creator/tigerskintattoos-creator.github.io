# Tiger Skin Website — Guide

Your site is now a full multi-page website. Here's the structure and how to maintain it.

## PAGES
- index.html ............ Homepage (brief sections, each links to a detail page)
- portfolio.html ........ Full portfolio with category filter
- faq.html .............. All FAQs
- blog.html ............. Blog index (the "Journal")
- blog-tattoo-cost-thane.html ... Post 1
- blog-first-tattoo-prep.html ... Post 2
- blog-aftercare.html ........... Post 3
- style.css ............. Shared design for ALL pages (edit once, changes everywhere)
- images/ ............... Logo, footer logo, texture, and your photos go here

## ADDING PORTFOLIO PHOTOS
1. Name your photo by category + number: realism-1.jpg, colour-1.jpg, pet-1.jpg,
   religious-1.jpg, blackgrey-1.jpg, fineline-1.jpg
   (Homepage feature photos: feature-1.jpg through feature-4.jpg)
2. Upload it to the images/ folder on GitHub.
3. In portfolio.html (or index.html for features), use Ctrl+F to find the slot,
   e.g. search: realism-1.jpg
4. Replace the line:
     <div class="ph">...<span>Realism · add photo</span></div>
   with:
     <img src="images/realism-1.jpg" alt="Realism tattoo in Thane by Tiger Skin">
5. Commit. Done.

## ADDING A NEW BLOG POST
- Easiest: ask Claude or Cowork to "write a new blog post about X" and it'll
  generate a ready-to-upload .html file matching the others.
- Then add a matching card to blog.html (copy an existing card block, change the
  href, tag, title and description).
- Keep posts Thane-anchored and genuinely useful — that's what ranks.

## WHAT'S SET
- Phone (Call + WhatsApp): +91 96196 10912
- Instagram: @tigerskintattoos
- Location shown: Naupada, Thane West (exact address after booking)
- Styles: Realism, Black & Grey, Colour, Pet Portraits, Religious & Deity, Fine Line
- Payment: Cash · UPI
- No cover-up mentions (intentional, protects premium positioning)

## TIPS
- Compress photos at tinypng.com (keep under ~500KB) so pages load fast.
- Always write alt="[style] tattoo in Thane" on images — helps Google.
- The blog is your ranking edge. One good post every week or two via Cowork
  will outrank competitors who post generic filler.
