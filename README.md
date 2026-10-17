# StoryCast

**An editorial media experience exploring stories, communities, and the people connected to the coast.**

StoryCast is a responsive, three-page editorial microsite designed to present a feature story through visual design, accessible content, and audio narration.

## Live Website

- **Homepage:** https://tkongolo24.github.io/storycast/
- **Feature Story:** https://tkongolo24.github.io/storycast/story/
- **About & Accessibility:** https://tkongolo24.github.io/storycast/about.html

## Project Pages

### Home
Introduces StoryCast, highlights the featured story, and presents the project's editorial values.

### Feature Story — The Keepers of the Tide
Presents the featured editorial story with an audio narration player and a text transcript.

### About & Accessibility
Provides information about the project and its accessibility approach.

## Features

- Responsive layouts for different screen sizes.
- Semantic HTML structure.
- Sass stylesheets organized into partials.
- CSS Grid and Flexbox layouts.
- CSS container queries for component responsiveness.
- Keyboard focus styling and a skip-to-main-content link.
- Audio narration with a text transcript.
- A visual design system using a consistent color palette and typography.

## Technologies

- HTML5
- Sass (SCSS)
- CSS Grid
- Flexbox
- CSS container queries
- Git and GitHub Pages

## Project Structure

```text
storycast/
├── index.html
├── about.html
├── story/
│   └── index.html
├── sass/
│   ├── main.scss
│   ├── _colors.scss
│   ├── _typography.scss
│   ├── _spacing.scss
│   ├── _reset.scss
│   ├── _layout.scss
│   ├── _components.scss
│   └── _accessibility.scss
├── css/
│   └── main.css
├── assets/
│   ├── images/
│   ├── audio/
│   ├── video/
│   ├── captions/
│   └── transcripts/
└── docs/
    └── StoryCast-Research-and-Design.pdf
```

*The structure above describes the expected organization. Adjust it if any filenames or folders differ in the repository.*

## Running Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/tkongolo24/storycast.git
   ```

2. Enter the project directory:

   ```bash
   cd storycast
   ```

3. Install Sass if it is not already installed:

   ```bash
   npm install --global sass
   ```

4. Compile the Sass stylesheet:

   ```bash
   sass sass/main.scss css/main.css
   ```

5. To automatically compile changes while editing:

   ```bash
   sass --watch sass/main.scss:css/main.css
   ```

6. Open `index.html` in a browser, or use a local development server.

## Accessibility Checklist

- [x] Semantic HTML5 structure: `header`, `nav`, `main`, `section`
- [x] `lang="en"` set on every page
- [x] One `h1` per page with a logical heading order
- [x] "Skip to main content" link on every page
- [x] Visible keyboard focus using `:focus-visible`
- [x] Labelled navigation (`aria-label`) with `aria-current="page"` on the active link
- [x] Audio player has an accessible name (`aria-label`) and a full text transcript
- [x] Decorative graphics hidden with `aria-hidden="true"`; the main illustration has an `aria-label`
- [x] `prefers-reduced-motion` respected
- [x] Text colors meet WCAG AA contrast (4.5:1 or higher)
- [x] Responsive layout, with a container query on the featured card

## Research and Design

The project is supported by research and design materials prepared during development.

See the research and design PDF in the `docs/` directory and the associated design mockups and wireframes.

## Deployment

The website is published using GitHub Pages from the `main` branch.

Repository: https://github.com/tkongolo24/storycast

## Content Note

“The Keepers of the Tide” is demonstration editorial content created for this project. It should not be interpreted as verified journalism or a report of independently confirmed events.

## License

This project was created for an academic assignment. No open-source license is specified unless one is added to the repository.
