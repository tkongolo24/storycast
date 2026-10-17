# StoryCast: Every Voice Carries a Story

## Project Overview

StoryCast is an editorial media microsite concept designed to share thoughtful human stories through accessible storytelling. The website presents stories about people, places, and experiences in an engaging and reader-friendly format.

The project focuses on editorial design, responsive layouts, semantic HTML, modular Sass styling, and accessibility.

## Website Pages

### 1. Home Page
**File:** `index.html`

The homepage introduces StoryCast, presents its editorial vision, highlights the featured story *The Keepers of the Tide*, and directs visitors to the full story and accessibility information.

### 2. Story Page
**File:** `story/index.html`

The story page contains the full article *The Keepers of the Tide*, story information, an audio-player placeholder, and a written transcript to support visitors who cannot or prefer not to listen to audio.

### 3. About & Access Page
**File:** `about.html`

This page explains the purpose of StoryCast and describes its approach to accessible and inclusive storytelling.

## Technologies Used

- HTML5 for semantic page structure.
- Sass (SCSS) for modular and maintainable styling.
- CSS for layout, visual presentation, and responsive design.
- JavaScript is not currently required for the core page navigation.

## Project Structure

```text
storycast/
├── index.html
├── about.html
├── README.md
├── package.json
├── story/
│   └── index.html
├── sass/
│   ├── main.scss
│   ├── _colours.scss
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

## Design Approach

StoryCast uses an editorial visual identity intended to feel calm, welcoming, and readable.

### Colour Palette

- Navy: `#18243A`
- Cream: `#F7F1E7`
- Terracotta: `#B84F32`
- Charcoal: `#20242B`
- Slate: `#5D6470`
- Warm border: `#D9D0C3`

### Typography

The intended typography combines DM Serif Display for expressive headlines with DM Sans for body text and interface elements.

### Visual Style

The design uses generous spacing, clear content hierarchy, coastal-inspired illustrations, and consistent navigation across the three pages.

## Accessibility Features

The project incorporates the following accessibility considerations:

- Semantic HTML landmarks, including `header`, `nav`, `main`, `article`, and `footer`.
- A skip link that allows keyboard users to jump to the main content.
- Descriptive page titles and metadata.
- Consistent navigation between pages.
- An active-page indicator using `aria-current`.
- Text alternatives for meaningful illustrations.
- Native audio controls and a written transcript section.
- Responsive layout and keyboard-focus styling.
- Reduced-motion support where specified in the stylesheet.

## Running the Project Locally

1. Install Node.js.
2. Open the project folder in Visual Studio Code.
3. Install dependencies if needed:

   ```bash
   npm install
   ```

4. Start the Sass compiler:

   ```bash
   npm run sass
   ```

5. Use the Live Server extension in Visual Studio Code to open `index.html` in a browser.

The Sass watcher compiles `sass/main.scss` into `css/main.css`. Keep the watcher running while editing Sass files so that changes are compiled automatically.

## Content and Prototype Limitations

The featured story, *The Keepers of the Tide*, currently uses demonstration copy. It should be replaced with researched material and credible sources before being presented as verified reporting.

The audio player is a placeholder until an audio recording is added.

## Testing Checklist

Before submission, verify that:

- All three pages load correctly.
- Navigation links lead to the correct pages.
- The website works at desktop and mobile widths.
- Keyboard navigation and visible focus states work.
- Sass compiles without errors.
- The transcript is available on the story page.
- The deployed website works through its public URL.

## Project Status

StoryCast is a course-project prototype demonstrating editorial website design, structured HTML, modular Sass, and accessibility-focused content presentation.
