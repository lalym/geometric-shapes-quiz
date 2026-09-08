# Replit project notes

## Run

This is a static HTML application with no dependencies or build step.

- Start the **Start application** workflow.
- The workflow runs `python3 -m http.server 5000 --bind 0.0.0.0`.
- Open the Replit web preview to use the quiz.

## Known upstream issue

`index.html` references 18 files under `shapes/*.png`, but the `shapes/` directory is not present in the imported GitHub repository. The app shell runs, but quiz illustrations will remain missing until those source images or replacements are added.