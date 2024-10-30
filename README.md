# README: Beamer Presentation Template for UT Austin Econ

## How to Use This Template

Follow these steps to customize the template:

### 1. Change the Paper Title and Author Name
Modify the Paper Title and Author Name in the title page and footline for each page in the slides.

- **Location** : '%TITLE HERE%' and '% NAME HERE%'
- \newcommand{\myname}{Author Name}
- \newcommand{\papertitle}{Paper Title}
- **What to Edit**: Replace "Paper Title"
and "Author Name" with your paper title and the authors' names.

### 2. Change the Content
Modify or add new sections and frames to fit your presentation's needs.

- **Location**: `% CONTENT HERE %`
- **What to Edit**: Replace bullet points with your content, add new sections like `\section{New Section}` and corresponding slides.
- **Note**: Each page of each section will show up automatically on the navigation bar on the top each slide.

### Optional: Change Theme and Colors
Adjust the theme or color scheme to match your style.

- **Location**: `% THEME AND COLOR SETTINGS HERE %`
- **What to Edit**: Replace `"Madrid"` with a different theme (e.g., `Boadilla`). Change RGB values for a new color.
