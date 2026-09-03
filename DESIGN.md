# Savory Scope — DESIGN.md

## 1. Brand Overview

**Brand Name:** Savory Scope

**Website Type:** Food Editorial / Food Magazine / Recipe & Culinary Information Website

**Primary Content Categories:**

* Recipes
* Cooking Tips
* Food & Ingredients
* Food Culture

**Brand Positioning:**

Savory Scope should feel like a modern independent food magazine rather than a generic recipe blog.

The design should combine:

* editorial magazine layouts
* warm natural colors
* strong food photography
* clean typography
* generous whitespace
* simple navigation
* comfortable long-form reading

The website should feel trustworthy, calm, useful, and visually appetizing.

Avoid making the site feel like:

* a SaaS website
* a technology product
* an AI-generated template
* an overly commercial recipe website
* a highly animated lifestyle landing page

---

# 2. Design Direction

Use a **Warm Editorial Food Magazine** visual direction.

Key characteristics:

* Warm off-white backgrounds
* Dark charcoal text
* Olive green as the primary brand color
* Terracotta / warm brown as secondary accents
* Serif typography for major headlines
* Clean sans-serif typography for navigation and body content
* Large editorial food photography
* Thin dividers instead of heavy borders
* Minimal shadows
* Small or no border radius
* Spacious layouts

The design should resemble a modern food publication or print magazine adapted for the web.

---

# 3. Color Palette

## Primary Background

```css
--color-background: #F7F4EC;
```

Warm cream / paper-like background.

Use for:

* main site background
* article pages
* large editorial sections

---

## Secondary Background

```css
--color-background-alt: #EFEADF;
```

Use for:

* category sections
* newsletter sections
* highlighted content blocks
* footer transitions

---

## Primary Text

```css
--color-text: #24251F;
```

Use for:

* headings
* body text
* navigation
* primary UI

Avoid pure black unless necessary.

---

## Secondary Text

```css
--color-text-muted: #6C6B63;
```

Use for:

* dates
* author information
* excerpts
* metadata
* captions

---

## Primary Brand Color

```css
--color-primary: #46583E;
```

Deep olive green.

Use for:

* logo accents
* navigation hover states
* category labels
* buttons
* links
* decorative elements

---

## Primary Hover

```css
--color-primary-hover: #35442F;
```

---

## Accent Color

```css
--color-accent: #B96848;
```

Warm terracotta.

Use sparingly for:

* featured tags
* special category labels
* small icons
* decorative accents

Do not use this as the dominant website color.

---

## Border Color

```css
--color-border: #D8D2C5;
```

Use thin subtle borders.

---

# 4. Typography

Typography should create a clear distinction between editorial headlines and readable content.

## Headings

Use an elegant serif font.

Recommended fonts:

1. Libre Baskerville
2. Lora
3. DM Serif Display
4. Playfair Display

Preferred:

```text
Libre Baskerville
```

Use for:

* H1
* H2
* feature article titles
* category feature titles
* editorial quotes

Headings should feel refined but not luxurious or fashion-oriented.

---

## Body & UI

Use a neutral sans-serif font.

Recommended:

1. Inter
2. Source Sans 3
3. Manrope
4. DM Sans

Preferred:

```text
Inter
```

Use for:

* body text
* navigation
* metadata
* buttons
* category labels
* footer

---

# 5. Typography Scale

Desktop guideline:

```text
Hero H1: 52–64px
Article H1: 44–56px
Section H2: 34–42px
Card H3: 22–28px
Small Card Title: 18–22px
Body: 17–19px
Metadata: 13–14px
Navigation: 14–15px
Category Label: 12–13px
```

Mobile:

```text
Hero H1: 36–42px
Article H1: 34–40px
Section H2: 28–32px
Card H3: 20–24px
Body: 16–18px
```

Body line height:

```css
line-height: 1.7;
```

Long-form articles must prioritize readability.

---

# 6. Layout

## Maximum Width

Main page container:

```css
max-width: 1280px;
```

Article content:

```css
max-width: 760px;
```

Wide editorial content:

```css
max-width: 1100px;
```

Use centered containers.

---

## Page Padding

Desktop:

```text
32–48px
```

Tablet:

```text
24–32px
```

Mobile:

```text
18–20px
```

---

## Section Spacing

Desktop sections should normally have:

```text
72–100px vertical spacing
```

Mobile:

```text
48–64px
```

Avoid overcrowding the homepage.

---

# 7. Header

The header should be simple and editorial.

Desktop structure:

```text
Logo
Home
Recipes
Cooking Tips
Food & Ingredients
Food Culture
About
Search
```

Recommended layout:

```text
[ SAVORY SCOPE ]

Home   Recipes   Cooking Tips   Food & Ingredients   Food Culture   About        Search
```

Header guidelines:

* cream background
* no large shadow
* thin bottom border
* approximately 72–88px height
* logo should be prominent
* navigation should remain clean
* avoid large CTA buttons

---

# 8. Logo Style

Use a simple text-based logo initially.

Example:

```text
SAVORY SCOPE
```

Logo typography:

* serif
* uppercase or title case
* medium letter spacing

Optional small tagline:

```text
Recipes, Cooking Tips & Food Stories
```

Do not create a complicated icon-heavy logo.

Possible small graphic element:

* simple leaf
* small fork
* small herb illustration

But text should remain the primary branding element.

---

# 9. Homepage Structure

## Hero Section

The hero should immediately feel like a food magazine.

Recommended layout:

```text
----------------------------------------
|                                      |
|          LARGE FOOD IMAGE            |
|                                      |
----------------------------------------

FOOD CULTURE

Why Breakfast Looks So Different
Around the World

Short article introduction goes here.

Read Story →
```

Alternative desktop layout:

```text
60% image | 40% article content
```

Hero rules:

* one primary article only
* large image
* large editorial headline
* short excerpt
* category label
* Read Story link

Avoid sliders and carousels.

---

# 10. Homepage Sections

Recommended homepage order:

## Featured Story

One large story.

---

## Latest Recipes

4 article cards.

Desktop:

```text
4-column grid
```

Tablet:

```text
2-column grid
```

Mobile:

```text
1-column or horizontal image + text
```

---

## Cooking Tips

Use an editorial split layout.

Example:

```text
Large Feature Article

-------------------------

Tip Article
Tip Article
Tip Article
```

---

## Food & Ingredients

Use a clean 3-column editorial grid.

---

## Food Culture

This section can use a darker olive background or alternate cream background.

Large destination-style food imagery is encouraged.

---

## Latest Stories

Simple chronological article list.

Example:

```text
IMAGE | CATEGORY
      | ARTICLE TITLE
      | DESCRIPTION
      | DATE
```

This helps the homepage feel like an active publication.

---

# 11. Article Cards

Cards should remain minimal.

Card structure:

```text
IMAGE

CATEGORY

Article Title

Short description

DATE
```

Card guidelines:

* no heavy card container
* no large drop shadow
* background usually transparent
* image should be dominant
* thin separators if necessary

Recommended image ratio:

```text
4:3
```

Also acceptable:

```text
3:2
```

Avoid overly tall portrait images.

---

# 12. Images

Food photography is one of the most important parts of the design.

Image style:

* natural lighting
* warm color temperature
* realistic food
* real kitchens and dining settings
* ingredient close-ups
* overhead food photography
* editorial photography

Avoid:

* excessive saturation
* artificial-looking AI imagery
* glossy commercial advertising photography
* images with text embedded inside them

Use consistent image aspect ratios.

Images should use:

```css
object-fit: cover;
```

---

# 13. Category Labels

Examples:

```text
RECIPES
COOKING TIPS
FOOD & INGREDIENTS
FOOD CULTURE
```

Style:

* uppercase
* small font
* medium letter spacing
* olive green
* bold or medium weight

Example:

```css
font-size: 12px;
letter-spacing: 0.08em;
text-transform: uppercase;
```

---

# 14. Buttons

Avoid oversized modern SaaS-style buttons.

Preferred button:

```text
Read More →
```

or

```text
View All Recipes →
```

Primary filled button:

* olive green background
* cream text
* small border radius

Example:

```css
border-radius: 3px;
```

Do not use pill-shaped buttons everywhere.

---

# 15. Article Page

Article pages should prioritize reading.

Recommended structure:

```text
CATEGORY

Article Title

Article introduction

By Author Name
Published Date

Featured Image

Article Content
```

Article body:

```text
H2
Paragraphs

Image

H2
Paragraphs

H3
Paragraphs
```

Avoid excessive widgets between paragraphs.

---

# 16. Article Body Styling

Body:

```css
font-size: 18px;
line-height: 1.75;
```

Paragraph spacing:

```text
20–26px
```

H2:

```text
32–36px
```

H3:

```text
24–28px
```

Lists:

* generous spacing
* simple bullets
* no overly decorative icons

Links:

* olive green
* underline on hover

---

# 17. Recipe Content Blocks

Recipes can use structured information blocks.

Example:

```text
Prep Time: 15 minutes
Cook Time: 30 minutes
Servings: 4
```

Ingredients section:

```text
Ingredients

• 2 tbsp olive oil
• 3 cloves garlic
• 400g tomatoes
```

Instructions:

```text
1. Prepare the ingredients.
2. Heat the pan.
3. Add the vegetables.
```

Recipe blocks should remain visually consistent with the editorial design.

Avoid highly colorful recipe widgets.

---

# 18. Related Articles

At the end of each article:

```text
You May Also Like
```

Display:

```text
3 related article cards
```

Use image + category + title.

---

# 19. Author Information

Simple author block:

```text
Written by
Emma Collins

Short author bio.
```

Optional small circular avatar.

Do not make author boxes overly prominent.

---

# 20. Category Pages

Each category page should include:

```text
CATEGORY NAME

Short description

Featured Article

Latest Articles Grid
```

Example:

```text
RECIPES

Simple and approachable recipes for everyday cooking.
```

Use approximately:

```text
3-column desktop grid
2-column tablet
1-column mobile
```

---

# 21. Footer

Footer background:

```css
#293027
```

or similar deep olive.

Text:

```css
#F7F4EC
```

Suggested footer layout:

```text
SAVORY SCOPE

Recipes
Cooking Tips
Food & Ingredients
Food Culture

About Us
Contact
Privacy Policy
Terms of Use

Recipes, Cooking Tips & Food Stories

© Savory Scope
```

Footer should be spacious and simple.

---

# 22. Responsive Design

The website must work well on:

* desktop
* tablet
* mobile

Mobile priorities:

* readable typography
* no horizontal overflow
* large tap targets
* stacked article cards
* simplified navigation
* fast page loading
* images should not exceed viewport width

Mobile menu should use a simple hamburger navigation.

---

# 23. Motion & Interaction

Keep animations subtle.

Allowed:

* small image zoom on hover
* underline transitions
* opacity transitions
* subtle button hover
* navigation hover

Example:

```css
transition: 0.2s ease;
```

Avoid:

* parallax
* large scrolling animations
* animated text entrances
* excessive fade-ins
* autoplay video backgrounds
* complex loading animations

---

# 24. Borders & Shadows

Prefer:

```css
border: 1px solid #D8D2C5;
```

Shadows should be rare.

If required:

```css
box-shadow: 0 4px 18px rgba(0,0,0,0.05);
```

Avoid floating card-heavy UI.

---

# 25. Border Radius

Preferred:

```text
0–6px
```

Food images may use:

```css
border-radius: 4px;
```

Avoid:

```text
20px+
```

Do not make the website look like a mobile app interface.

---

# 26. SEO & Content UX

Design should support SEO-friendly editorial content.

Requirements:

* one H1 per page
* clear H2/H3 hierarchy
* visible article title
* category breadcrumb where appropriate
* readable URLs
* image alt text
* visible publish dates
* visible author names
* internal related article links
* strong mobile readability

Do not hide important content behind JavaScript interactions.

---

# 27. Advertising Compatibility

The design should allow advertising to be added later without damaging the layout.

Potential placements:

## Homepage

Between major homepage sections.

Example:

```text
Latest Recipes

[ Advertisement ]

Cooking Tips
```

---

## Article Page

Potential placements:

```text
After introduction

After approximately 3–5 paragraphs

Between major article sections

Near the bottom of the article
```

Ads should not be embedded inside navigation or interfere with buttons.

Do not design fake advertising blocks during the initial version.

Simply keep enough whitespace for future placements.

---

# 28. Accessibility

Requirements:

* sufficient text contrast
* meaningful image alt text
* visible keyboard focus states
* semantic HTML
* buttons must use correct button elements
* navigation must use nav elements
* avoid tiny text
* links must be visually distinguishable

---

# 29. Content Tone

The visual design should match content that feels:

* useful
* friendly
* knowledgeable
* practical
* editorial
* approachable

Avoid overly corporate or technical language in visual presentation.

---

# 30. Design Keywords

When making design decisions, use these keywords:

```text
Warm
Editorial
Food Magazine
Natural
Timeless
Readable
Calm
Inviting
Authentic
Simple
Premium but Accessible
```

Avoid:

```text
SaaS
Tech
Neon
Futuristic
Dashboard
Glassmorphism
Heavy Gradient
Cyberpunk
Overly Rounded
Corporate
```

---

# 31. Reference Direction

The visual style should loosely draw inspiration from:

* modern independent food magazines
* editorial lifestyle publications
* printed culinary magazines
* warm European editorial websites
* recipe publications with strong photography

Do not directly copy any single website.

Use these references only for:

* typography hierarchy
* whitespace
* photography
* editorial grids
* visual pacing

---

# 32. Final Design Goal

Savory Scope should look like a real food publication that could naturally publish hundreds of articles over time.

The design should remain:

* easy to maintain
* easy to expand
* SEO friendly
* advertising friendly
* mobile friendly
* visually consistent

When uncertain, choose the simpler and more editorial solution.

Prioritize:

```text
Content > Photography > Typography > Decoration
```

The food and editorial content should always remain the focus.
