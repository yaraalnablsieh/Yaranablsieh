

/* Global Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Open Sans', sans-serif;
    font-size: 14px;
    background-color: hsl(218, 28%, 13%);
    color: hsl(0, 0%, 100%);
    text-align: center;
    padding: 20px;
}

/* Header */
.header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px;
    max-width: 1100px;
    margin: auto;
}

.logo {
    font-family: 'Raleway', sans-serif;
    font-weight: 700;
    font-size: 24px;
}

.nav a {
    color: hsl(0, 0%, 100%);
    text-decoration: none;
    margin-left: 20px;
    font-family: 'Raleway', sans-serif;
    font-weight: 400;
}

.nav a:hover {
    text-decoration: underline;
}

/* Hero Section */
.hero {
    max-width: 700px;
    margin: 50px auto;
}

.hero-img {
    max-width: 100%;
    height: auto;
}

.hero h1 {
    font-family: 'Raleway', sans-serif;
    font-weight: 700;
    font-size: 28px;
    margin-top: 20px;
}

.hero p {
    margin: 20px 0;
}

.btn {
    background: linear-gradient(90deg, hsl(176, 68%, 64%), hsl(198, 60%, 50%));
    padding: 12px 24px;
    border-radius: 30px;
    color: hsl(0, 0%, 100%);
    text-decoration: none;
    font-weight: 700;
    font-family: 'Raleway', sans-serif;
}

.btn:hover {
    opacity: 0.8;
}

/* Features Section */
.features {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
    max-width: 1100px;
    margin: 50px auto;
    padding: 20px;
}

.feature {
    background-color: hsl(219, 30%, 18%);
    padding: 20px;
    border-radius: 10px;
}

.feature img {
    width: 50px;
    margin-bottom: 10px;
}
# Front-end Style Guide
/* Import Fonts */
@import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;700&family=Raleway:wght@400;700&display=swap');
## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

> 💡 These are just the design sizes. Ensure content is responsive and meets WCAG requirements by testing the full range of screen sizes from 320px to large screens.

## Colors

### Primary

- Dark Blue (intro and email sign up background): hsl(217, 28%, 15%)
- Dark Blue (main background): hsl(218, 28%, 13%)
- Dark Blue (footer background): hsl(216, 53%, 9%)
- Dark Blue (testimonials background): hsl(219, 30%, 18%)

### Accent

- Cyan (inside call-to-action gradient): hsl(176, 68%, 64%)
- Blue (inside call-to-action gradient): hsl(198, 60%, 50%)
- Light Red (error): hsl(0, 100%, 63%)

### Neutral

- White: hsl(0, 0%, 100%)

## Typography

### Body Copy

- Font size: 14px

### Headings, Call-to-actions, Header Navigation

- Family: [Raleway](https://fonts.google.com/specimen/Raleway)
- Weights: 400, 700

### Body

- Family: [Open Sans](https://fonts.google.com/specimen/Open+Sans)
- Weights: 400, 700

## Icons

For the social icons, you can use a font icon library. Some suggestions can be found below:

- [Font Awesome](https://fontawesome.com/)
- [IcoMoon](https://icomoon.io/)
- [Ionicons](https://ionicons.com/)

> 💎 [Upgrade to Pro](https://www.frontendmentor.io/pro?ref=style-guide) for design file access to see all design details and get hands-on experience using a professional workflow with tools like Figma.
