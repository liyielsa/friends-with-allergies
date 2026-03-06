## Tech stack: Python, Flask, NLP (NLTK, Sentence Transformers), Scikit-learn, Pandas, NumPy, HTML

# Friends with Allergies

Hi, we are *Friends with Allergies* team!
<br>
This is a repository for our group project assignment in the *Building Natural Language Processing Applications* course (Spring 2026).

Here are the group members:
  1. Yi Li
  2. Dat, Luu (Ricky)
  3. Iuliia Nesterenko
  4. Qing Li

## Overview

FWA is an application designed for people with allergies or dietary restrictions find suitable restaurants in Helsinki, Finland. We scraped restaurants' information and their reviews from Quandoo, a popular restaurant reservation platform. It is difficult to find suitable restaurants based on allergies or dietary preferences, or get close-to-heart daily food recommendations. Our application fills this gap and offers even more! 
Find foods and places that suit your gastronomical wishes and concerns using three types of search engines, explore maps and visualisations and do not worry about safety – our algorithm takes allergies seriously!

**Tech stack:** Python • Flask • NLTK • Sentence Transformers • Scikit-learn • Pandas • NumPy • HTML

## Installation

To run the website locally, clone this repository and install the required dependencies.

1. Clone the repository:
 ```bash
git clone https://github.com/nesterenkojul/friends-with-allergies
cd friends-with-allergy
```

2. Create and activate a virtual environment (recommended):
```bash
python3.11 -m venv .venv
source .venv/bin/activate
```


3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Start the application:
```bash
python3 app.py
```

5. Open the *localhost* address specified by Flask (e.g. http://127.0.0.1:5001) in your browser to access the app interface. NB: the initial loading of the main page may take a while – be patient :)

