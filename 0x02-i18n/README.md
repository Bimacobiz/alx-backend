# 0x02-i18n (Internationalization)

---

## Resources

Before diving into this project, it's recommended to familiarize yourself with the following resources:

- [Flask-Babel](https://pythonhosted.org/Flask-Babel/)
- [Flask i18n tutorial](https://flask.palletsprojects.com/en/2.0.x/patterns/i18n/)
- [pytz](https://pypi.org/project/pytz/)

## Learning Objectives

In this project, you'll accomplish the following:

- Learn how to parametrize Flask templates to display different languages.
- Understand how to infer the correct locale based on URL parameters, user settings, or request headers.
- Localize timestamps in your application.

## Requirements

Before proceeding, ensure that your environment meets the following requirements:

- Ubuntu 18.04 LTS
- Python 3 (version 3.7)
- `pycodestyle` style (version 2.5)
- All Python files should use `#!/usr/bin/env python3` as the first line.
- All Python files should be executable.
- All modules, classes, functions, and methods should be properly documented.
- Type annotations should be provided for all functions and coroutines.

## Tasks Overview

Here's a brief overview of the tasks you'll tackle in this project:

1. **Basic Flask app**: Set up a basic Flask app with a single route and a simple HTML template.
2. **Basic Babel setup**: Install and configure Flask-Babel extension to support multiple languages.
3. **Get locale from request**: Create a function to determine the user's preferred locale based on request headers or URL parameters.
4. **Parametrize templates**: Use translation functions to parametrize templates and support multiple languages.
5. **Force locale with URL parameter**: Implement a mechanism to force a particular locale by passing a parameter in the URL.
6. **Mock logging in**: Emulate user login system and display personalized messages based on the logged-in user's locale.
7. **Use user locale**: Prioritize user's preferred locale over other sources for language selection.
8. **Infer appropriate time zone**: Determine the appropriate time zone based on user preferences or request parameters.

## Directory Structure

- `0x02-i18n`
  - `0-app.py`, `1-app.py`, ..., `7-app.py`: Flask application files for each task.
  - `templates`: Directory containing HTML templates for different tasks.
  - `babel.cfg`: Configuration file for Babel.
  - `translations`: Directory containing translation files for different languages.

## Getting Started

1. Clone the GitHub repository: `git clone https://github.com/yourusername/0x02-i18n.git`
2. Navigate to the project directory: `cd 0x02-i18n`
3. Start with Task 1 and proceed sequentially through each task.

## Support and Contact

For any assistance or inquiries, feel free to reach out to us at [email@example.com](mailto:email@example.com) or open an issue in the repository.

Happy internationalizing your Flask applications! 🌍🚀

