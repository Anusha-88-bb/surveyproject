# Django Survey Project

**Status: Work in progress — HTML/Django templates uploaded**

A learning project for collecting technology survey responses and presenting results using Django.

## Files Currently Available

- `base.html` — shared layout and navigation
- `home.html` — survey form page
- `login.html` — user login page
- `results.html` — survey results and summary cards

These files use **Django template syntax** and Bootstrap styling.

## Important Project Status

The current GitHub repository contains the templates, but **not yet the complete Django application**. Files such as `manage.py`, project settings, URLs, views, forms, models, and dependencies are still needed to run it.

The templates currently sit at the repository root; when integrated into a Django app, they should be placed in the appropriate templates directory (for example, `templates/survey/`) and wired to the app's routes and views.

## Planned Next Steps

1. Upload the Django project and application source files.
2. Connect the survey form to models and views.
3. Configure login, response submission, and results.
4. Add a `.gitignore` and dependency file.
5. Test the application locally before documenting run instructions.

This repository documents my ongoing Django learning journey.
