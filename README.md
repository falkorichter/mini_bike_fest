# MINI BIKE FEST

Simple website for the MINI BIKE FEST event on May 30th, 2026 in Berlin.

## Event Details
- **Date:** May 30th, 2026
- **Location:** craftwerk.berlin, Berlin
- **Time:** 12:00 - 20:00
- **Entry:** FREE

## Website Features
- Clean, simple design with background image
- Event information display
- Blog section for updates
- Instagram link
- Vendor list (to be updated)

## Logo Switching

The website includes three different logo variations that can be selected using a URL parameter:

- **Logo 1:** `?logo=1` - Default logo
- **Logo 2:** `?logo=2` - Alternative logo variant
- **Logo 3:** `?logo=3` - Alternative logo variant

### White Logo Option

You can make the logo display in white by adding the `white` parameter:

- **White logo:** `?white=1` or `?white=true` - Makes the logo white

### Examples:

| Logo | Default Color | White |
|------|---------------|-------|
| Logo 1 | [View](https://falkorichter.github.io/mini_bike_fest/) | [View](https://falkorichter.github.io/mini_bike_fest/?white=1) |
| Logo 2 | [View](https://falkorichter.github.io/mini_bike_fest/?logo=2) | [View](https://falkorichter.github.io/mini_bike_fest/?logo=2&white=1) |
| Logo 3 | [View](https://falkorichter.github.io/mini_bike_fest/?logo=3) | [View](https://falkorichter.github.io/mini_bike_fest/?logo=3&white=1) |

## Local Development

To run the website locally:

```bash
bundle install
bundle exec jekyll serve
```

Then visit `http://localhost:4000` in your browser.

## GitHub Pages

This site is configured to work with GitHub Pages. Simply enable GitHub Pages in the repository settings and select the main branch as the source.

## Adding Blog Posts

Create new blog posts in the `_posts` directory following the naming convention:
`YYYY-MM-DD-title.md`

Example:
```
_posts/2026-02-15-welcome.md
```