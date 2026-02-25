# Friends with Allergies

Hi, we are *Friends with Allergies* team!
<br>
This is a repository for the group project assignment in the *Building Natural Language Processing Applications* course (Spring 2026).

Here are the group memebers:
  1. Yi Li
  2. Ricky
  3. Iuliia
  4. Qing

## What this app does

FWA is an application targeted at people with allergies or dietary restrictions to find suitable and allergy-free restaurants across Helsinki, Finland. We scraped the location, menu and reviews from the website Quandoo. There it is impossible to find suitable restaurants based on allergies or dietary preferences, or get close-to-heart daily food recommendations. Our application fills this gap and offers even more! 
Find foods and places that suit your gastronomical wishes and concerns using three types of search engines, explore maps and visualisations and do not worry about safety – our algorithm takes allergies seriously!

## How to run (from terminal)

To run the website locally, clone this repository to your computer.

1. It is recommended to first activate a virtual environment (inside the repo directory):
```bash
python3.11 -m venv .venv
source .venv/bin/activate
```

2. Then, install the dependencies:
```bash
pip install -r requirements.txt
```

3. Start the app:
```bash
python3 app.py
```

4. Open the *localhost* address specified by Flask (e.g. http://127.0.0.1:5001) in your browser to access the app interface. NB: the initial loading of the main page may take a while – be patient :)

