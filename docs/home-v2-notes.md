# Home v2: changelog, open items, assets

## Page height (measured)

| View | Height | Target |
|---|---|---|
| Mobile, 390px wide | **6,985px** (about 8.3 phone screens) | under ~7,000px |
| Desktop, 1440px wide | **7,717px** | n/a |

Before this pass: about 20,000px on mobile and 11,500px on desktop.

## Changelog

1. **New 9-part structure**, in your order: hero, results, case studies, how I run social, everything I make, production, experience, tools, let's talk. The five equal sections (Social, Content, Design, Camera, Writing) are gone. The story is now "I run social" first, then "I make it too."
2. **Hero:** filled the "Open to" line. Swapped the photo slot for a 9:16 phone frame with the video loop placeholder. Kept the headline, intro, and both CTAs. Moved "Interim Social Media Director, Soccer Post" into the line above the headline so the title is the first thing read.
3. **Results band:** replaced scope stats with four outcomes, including +19.4% Austin follower growth. The [MISSING] stat is gone. Blue and red blocks sit on the first and last.
4. **Case studies:** three cards on one template (Goal, What I did, Result, What I'd do next). Tony now has its baseline: about 240x the ~29K followers. On mobile the three cards swipe sideways, which saved about 1,100px.
5. **How I run social:** National and Austin accounts with links. Austin copy now says "Where I test ideas and build community" with the 5M+ stat. The "data to decision" Metricool example sits in its own red block. Four systems in one row, three artifact slots, and the blog and analytics line.
6. **Everything I make:** one section, 7 pieces, with All / Video / Design / Photo / Writing filters. The filters are pure CSS. Browsers without support show All. Instagram and TikTok embeds are replaced with media slots and "View original" links, so nothing third-party loads.
7. **Production:** Charly and the jumbotron commercial only, with the portfolio link. These also swipe on mobile.
8. **Experience:** timeline cut to 6 lines. 2022 to 2025 is one line, Imagine That Sports moved to Aug 2026, plus one testimonial slot.
9. **Tools:** split into Platforms, Analytics, and Creative, with the brand line kept.
10. **Nav:** Work / Social / Content / About / Resume, with Get In Touch as the button.
11. **Motion:** kept the headline intro and the play-once reveals, retuned for the new sections. Hover lift on the content tiles.

**Two calls I made against the brief:**
- **Away Jerseys reel left out.** You told me that account was deleted, so there's no original to link to. I used your launch carousel (@soccerpost) instead. That keeps the pick at 7 pieces with no [MISSING] slot.
- **Gael Meza Media start date** is set to Feb 2025, from your message on Oct 3, instead of a [VERIFY] tag. Confirm it matches LinkedIn.

## Every [MISSING] and [VERIFY] still on the page

1. Tony case study: What I'd do next [MISSING]
2. YouTube case study: What I did [MISSING: my role and formats]
3. YouTube case study: What I'd do next [MISSING]
4. World Cup case study: What I'd do next [MISSING]
5. Data to decision: Result [MISSING]
6. Charly Heritage Collection: Results [MISSING]
7. How I run social: [VERIFY: 3 or 4 accounts] (national IG, TikTok, YouTube, Austin IG = 4. The F50 TikTok is on @soccerpostaustin, which may make 5)
8. Experience: [VERIFY: titles match LinkedIn]
9. Portfolio link: [PORTFOLIO URL]
10. Testimonial: [QUOTE], [NAME], [TITLE], [COMPANY]

**Links still pointing nowhere (#):** case study pages (3), Resume (3 places), SP Stats carousel original, Future Hero Card original, Austin FC photo original, blog post URL, portfolio.

## Assets I need from you

| Slot | Format | Size / ratio | Notes |
|---|---|---|---|
| Hero reel loop | MP4 (H.264) + poster JPG | 9:16, 720x1280 | 6 to 8s, muted, under 3MB, seamless loop |
| YouTube Studio graph | PNG | 16:9, 1600x900 | Recreated or cropped so only the views line shows |
| F50 reel loop | MP4 + poster | 4:5, 720x900 (crop from 9:16) | Muted, 5 to 8s, under 2MB |
| SP Stats carousel cover | JPG or WebP | 4:5, 1080x1350 | First slide |
| Future Hero Card | done | 3:4, 1080x1440 | Already in the repo |
| Launch carousel cover | JPG or WebP | 4:5, 1080x1350 | First slide of the @soccerpost post |
| Austin FC matchday photo | JPG or WebP | 4:5, 1600x2000 | Your strongest action shot |
| Nike Scorpion soleplate photo | JPG or WebP | 4:5, 1600x2000 | Studio shot |
| Blog post header | JPG or WebP | 4:5, 1080x1350 | Or a clean screenshot of the published post |
| Monthly social report | PNG | 16:10, 1600x1000 | Recreated with sanitized data, never internal screenshots |
| Content calendar snapshot | PNG | 16:10, 1600x1000 | Recreated sample week |
| Caption template + voice guide | PNG | 16:10, 1600x1000 | Side by side |
| Charly Heritage hero | JPG or WebP | 16:9, 2400x1350 | Wide street shot |
| Jumbotron commercial | MP4 + poster, or YouTube/Vimeo link | 16:9, 1920x1080 | Host video off-site |
| Resume | PDF | Letter | One page, titles matching LinkedIn |
| Social share image | JPG | 1200x630 | For link previews on LinkedIn and iMessage |

Lightroom export for photos: long edge 2000px (1600 is fine for 4:5), sRGB, quality 80, sharpen for screen (standard). I'll make WebP and AVIF versions in the build.
