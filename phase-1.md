# gaelmeza.com, Phase 1

Mockup: `home-mockup.html` (open it in a browser; the "Palette A / B" switch in the corner swaps palettes).

## 1. Repo read

- github.com/gaelameza/gaelmeza is empty: no commits, no branches, no files.
- This folder (E:\gmm\Website\gaelmezadotcom) was also empty.
- Nothing to keep or migrate. We start clean, which makes the data-file setup easy.
- The studio site (gaelmezamedia.netlify.app) is not in this repo, so the future redirect is a later Netlify step, not a code change.

## 2. Sitemap

```
/                         Home
/social-media             Social Media
/content                  Content Creation (social-first)
/production               Professional Content Creation (brand-level)
  /production/photography Photography
  /production/video       Video & Editing
/work                     Case studies index
  /work/tonymakesvlogs
  /work/charly-heritage
  /work/youtube-revival
  /work/blog-program
/about                    About
/contact                  Contact
/404
```

Nav (desktop, always visible): Social Media, Content, Production, Work, About, plus two buttons: Resume (outline) and Get In Touch (solid).

Changes I recommend, and why:
1. **Nav mirrors the three Home blocks.** Social Media, Content, Production map one to one to Blocks 1, 2, 3, so a hiring manager learns the structure once.
2. **Photography and Video & Editing sit under Production** instead of top level. Nine top-level links won't fit an open nav. Both still get their own URL, so you can send them as direct links.
3. **Add a /work index** for case studies, with a "Case Study 01 to 04" grid. Gives you one link that says "here's the proof."
4. **Resume is a nav button on every page**, not only on About.
5. **Sam Kerr x Nike concept goes on /production as a text-only "Concept work" card.** It shows your thinking without needing any media.
6. **"Other work" one-liners go at the bottom of /content** (Queens Soccer Festival, NYC TikTok launch support, Panini trading activation, Bootspotting).

## 3. Text wireframes

Every page ends with the same CTA band (Get In Touch + Download Resume) and footer, so each one works as a standalone pitch.

**Home** (round 2: minimal brutalism, Paper palette, color only as accents)
1. Nav: GMM logo, open links, Resume link, Get In Touch button.
2. Hero: name and title line, giant headline, positioning line, "Open to" line, two CTAs, candid working photo.
3. Stat row: 4 big numbers between rules (6.9M, 5M+, ~80K, 3).
4. The short version: "What I own" scope list and a career timeline.
5. Block 1, Social media professional: TonyMakesVlogs, the three-account system, YouTube revival, blog program. Each opens with a one-line situation.
6. Block 2, Social-first content: 5 vertical tiles, then the World Cup window numbers.
7. Block 3, Camera work: Charly feature, then Noche de Barrio, Club América giveaway, jumbotron spot, product/studio.
8. Quote placeholder.
9. Tools and the brand line.
10. CTA (the one black block), footer.

**Social Media**
1. Hero: "I run social like a business" style headline, your title, 3 stats.
2. What I do: strategy, multi-account management, scheduling, analytics, reporting (5 bordered cells).
3. Systems I built: the six systems from your section 6, one card each.
4. Proof: TonyMakesVlogs, YouTube revival, Blog program cards linking to case studies.
5. Numbers wall: Austin 5M+, World Cup window, 3 accounts.
6. CTA.

**Content Creation**
1. Hero: "Platform-native, built to perform."
2. Range grid: trends, humor, education, product hype, 9:16 tiles with numbers.
3. World Cup content program: formats, verify-before-publish, carousel examples.
4. Meanwhile Brewing popup series: content you can draw a line to people walking in the door.
5. Graphics and carousels: design system examples (corner labels, numbered steps, stat cards).
6. Other work one-liners.
7. CTA.

**Professional Content Creation**
1. Hero: "Brand-level production, one person."
2. My production role: concepting, shot lists, drone plans, directing talent and studios, shooting, editing (as a horizontal step strip).
3. Charly Heritage Collection feature.
4. Noche de Barrio, Club América giveaway, Inter Miami jumbotron spot (one card each, role first).
5. Product and studio: Nike Scorpion Pack soleplate work, Predator, F50 Messi.
6. Concept work: Sam Kerr x Nike Player Edition, text only.
7. Links to Photography and Video. CTA.

**Photography**
1. Hero: short intro, button to full portfolio.
2. Category tabs or stacked sections: Editorial/Street Style, Events, Matchday, Product.
3. Grid with lightbox (the one place JS is needed).
4. Full portfolio button again. CTA.

**Video & Editing**
1. Hero: short intro.
2. Inter Miami jumbotron spot (16:9 feature).
3. Recaps (Noche de Barrio and others).
4. Short-form vertical reels in a 9:16 row, tap to play, no autoplay with sound.
5. CTA.

**Work (index)**
1. Hero: "Case studies."
2. 4 big cards: label, title, headline number, one line.
3. CTA.

**Case study template** (TonyMakesVlogs, Charly, YouTube, Blog)
1. Label + title + one-line summary + headline number.
2. The Situation.
3. What I Did (role list).
4. The Result (big numbers, colored blocks).
5. Media.
6. Next case study link. CTA.

**About**
1. Hero: portrait placeholder + "Sales floor to national social."
2. Story: 3 short paragraphs, Soccer Corner 2022 through Interim Social Media Director.
3. Timeline: roles with dates, plus Gael Meza Media, Imagine That Sports, ACC.
4. Tools.
5. Influences: SoccerBible, COPA90, Aimé Leon Dore.
6. Resume download. CTA.

**Contact**
1. Headline + one line on what you're open to.
2. Netlify form: name, email, organization, inquiry type dropdown, message, honeypot.
3. Email, Instagram, LinkedIn. No phone.

## 4. Hero headline options

1. **SOCIAL THAT MOVES THE NUMBERS.**
   I'm Gael Meza, a social media professional in Austin, TX. I run strategy, systems, and content for a national soccer retailer, and I shoot and edit it myself.
2. **6.9M VIEWS. ONE PAIR OF BOOTS.**
   Social media professional and social-first creative. I find the idea, build the system, and get the result, often with no budget.
3. **I RUN THE ACCOUNT AND SHOOT THE CONTENT.**
   Strategy, analytics, and brand-level photo and video from one social media professional. Soccer culture is my specialty. The playbook works for any brand.

The mockup uses option 1. My pick is 1 for the headline with 2 as the first case study's title, since it's the strongest hook but needs context a cold reader doesn't have yet.

## 5. Palettes (WCAG contrast checked)

**A. Night Shift (black leads)**. Recommended. Photos and video pop on black, and it reads "founder" not "template."

| Role | Hex | Check |
|---|---|---|
| Base | `#0A0A0A` | |
| Text / light sections | `#F4F1EA` | 17.6:1 on base |
| Blue | `#2B44FF` | white text on blue 6.2:1. Blue text on black only 3.2:1, so blue is fill only |
| Red | `#FF4433` | black text on red 5.8:1, red text on black 5.8:1 |
| Muted text | `#9A9A9A` | 7.0:1 on base |

**B. Paper (off-white leads)**. Calmer, more "editorial," easier for long reads.

| Role | Hex | Check |
|---|---|---|
| Base | `#F2F0EA` | |
| Ink | `#111111` | 16.6:1 on base |
| Blue | `#0033CC` | 7.9:1 as text on base, white on blue 9.0:1 |
| Red | `#D7261E` | white on red 5.0:1. Red text on base 4.4:1, so large text only |
| Muted text | `#555555` | 6.5:1 on base |

Either way, full case study pages flip to the light base for long reading, so the brutalism stays in the blocks and body text stays easy.

**Type.** I'm assuming "Adineu Pro" is adineue PRO, adidas's corporate typeface. Honest take: the shape fits (geometric, wide, heavy in Bold, great in all caps), but two problems. First, licensing: it's usually not sold for public web use, so we need to confirm you have a webfont license. Second, positioning: your copy rules require neutrality across Nike, adidas, and Puma, and setting your whole site in adidas's brand font quietly undercuts that for anyone who recognizes it. My recommendation is a similar wide grotesk for headlines (the mockup uses **Archivo** at its widest, free on Google Fonts) and **JetBrains Mono** for labels and tags, with Archivo at normal width for body. If you have the license and still want it, it drops in as the headline font with one line of CSS.

## 6. Questions before the full build

1. Which headline (1, 2, 3) and which palette (A, B)?
2. Your portfolio URL.
3. Missing results: Charly Heritage numbers, Club América giveaway numbers, your exact role and the formats on the YouTube revival, and the World Cup program's name and scope.
4. Block 2 needs a trendy/fast post, a funny post, and an educational post with their numbers. Which posts?
5. Do you have a current resume PDF, and does it match the titles and dates above?
6. Adineu Pro: do you own a webfont license, and do you still want it after the note above?
7. Stack: I recommend Eleventy. It outputs plain HTML, keeps all projects and numbers in simple data files, and Netlify builds it automatically. OK to use it?
8. Is this repo already connected to a Netlify site, or should I set one up when we build?
