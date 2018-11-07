# Responsive and Adaptive Web

## Preparing for this class

- bring a phone/tablet!

## New concepts for today

### Developer mode on your devices

- [iOS devices](https://medium.com/@mattcroak718/debugging-your-iphone-mobile-web-app-using-safari-development-tools-71240657c487)
- [Android devices](https://developers.google.com/web/tools/chrome-devtools/remote-debugging)

### Serving a folder
- command line: `python -m SimpleHTTPServer 8000` [article](https://lifehacker.com/start-a-simple-web-server-from-any-directory-on-your-ma-496425450)
- [app](https://itunes.apple.com/us/app/simple-http-server/id441002840?mt=12)

### Viewport meta tag

`<meta name="viewport" content="width=device-width, initial-scale=1">`

## Today's exercise

### Fluid layouts

- Create fluid layouts! The designs might look familiar: https://app.zeplin.io/project/5b980960f8d0cb9de317da5f?seid=5be1bb65ac2d70619d6f6939
- Create a responsive grid with `autofit` and `minmax` following [this article](https://medium.freecodecamp.org/how-to-make-your-html-responsive-by-adding-a-single-line-of-css-2a62de81e431)

### Media queries

[MDN article](https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries/Using_media_queries)

```css
@media (max-width: 600px) {
  /* ... */
}
```

- Change font sizes for smaller screens! Designs: https://app.zeplin.io/project/5b980960f8d0cb9de317da5f/dashboard?seid=5be2c7ca2790467ebf106558
- Change content for smaller screens! Merge these two previous designs:
    - for mobile: https://app.zeplin.io/project/5b980960f8d0cb9de317da5f/screen/5bbce04ffbe15b18ca0f0cfa
    - for desktop: https://app.zeplin.io/project/5b980960f8d0cb9de317da5f/screen/5bbce04f6d78130a55dca412

## Project work

- Check mobile designs, see where to use fluid layouts and where to switch styles with media queries
- Apply responsive text styles
- Change navigation where it won't fit any more
- Change layouts

## Optional homework

- read the [article where Ethan Marcotte coined the expression Responsive Web Design](https://alistapart.com/article/responsive-web-design/)
