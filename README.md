# 🌌 DataGalaxy – Star Wars API Explorer

🚀 A Python-based data explorer that fetches, structures, and presents real-time data from the **Star Wars API (SWAPI)**.  
Whether you're a developer learning external API integration or a fan of the galaxy far, far away, this project combines **automation**, **JSON manipulation**, and **multi-endpoint logic** — crafted by a student in AI & Informatics Engineering.

---

## 💡 Project Overview

**DataGalaxy** is a Star Wars data explorer built to:

- Reinforce API handling and HTTP requests
- Structure and present raw JSON into clean, readable formats
- Automate retrieval of character, planet, and starship data from multiple endpoints
- Build a reusable, modular API client architecture in Python

---

## 🧠 Features

| Feature                          | Description                                                   |
|----------------------------------|---------------------------------------------------------------|
| 🌐 Real-time API Fetching        | Connects to SWAPI (https://swapi.dev)                         |
| 📦 JSON Handling                 | Parses deeply nested responses cleanly                        |
| 📄 Structured Output             | Displays tabular or formatted summaries (via `PrettyTable`, `tabulate` or `pandas`)  
| 🧑‍🤖 Multi-endpoint Support       | Characters, Planets, Starships, Films, etc.                   |
| ♻️ Pagination Support            | Automatically handles paginated responses                     |
| 🧰 Modular Code Structure         | Organized Python scripts by functionality                     |
| 🧪 Unit Test Ready               | Easy to test functions using `unittest` or `pytest`           |
| 🛰️ CLI Tool *(Planned)*         | A command-line interface to interact with the API             |

---

## 📁 Project Structure

DataGalaxy-StarWarsAPI/ ├── src/ │   ├── fetcher.py           # Handles API requests and error handling │   ├── parser.py            # Parses and formats JSON response │   ├── explorer.py          # Main program logic (or CLI entry) │   └── utils.py             # Helpers: URL builders, pagination, etc. ├── tests/                   # (Planned) Unit tests ├── assets/                  # Screenshots, output samples ├── requirements.txt └── README.md

---

## 🧪 Example Usage

```python
from src.explorer import StarWarsExplorer

sw = StarWarsExplorer()

sw.get_character("Luke Skywalker")
# => Name: Luke Skywalker | Height: 172 | Starships: X-wing, Imperial shuttle

sw.get_planet("Tatooine")
# => Planet: Tatooine | Population: 200000 | Climate: arid

sw.search_starships("Millennium")
# => Millennium Falcon | Hyperdrive Rating: 0.5 | Crew: 4

---


## 🌠 Sample Output

==================== Starship: Millennium Falcon ====================
Model: YT-1300 light freighter
Hyperdrive Rating: 0.5
Crew: 4
Passengers: 6
Films: A New Hope, Empire Strikes Back, Return of the Jedi
=====================================================================


---

## 🌐 Roadmap

[x] Core API connection and data extraction

[x] Parser for characters, planets, starships

[x] Pagination logic

[ ] CLI interface

[ ] Export results to CSV / JSON

[ ] Web version (with Flask or Streamlit)

[ ] Star Wars data visualization charts (matplotlib / seaborn)



---

## 🧑‍💻 Author

Ayman Bouaziz
🎓 AI & Software Engineering Student – Faculty of Science and Technology Al Hoceima
📍 Morocco | 🧠 Python • APIs • Data Engineering

🔗 LinkedIn: https://www.linkedin.com/in/ayman-bouaziz-7ab181349
✉️ projects.aymanbouaziz@gmail.com


---

## 📜 License

MIT — For educational and personal projects.
© 2025 Ayman Bouaziz


---

## 🌌 Final Thought

> “In a galaxy full of data, DataGalaxy is your light saber for exploration.”
Built with Python. Driven by curiosity. Inspired by Star Wars.