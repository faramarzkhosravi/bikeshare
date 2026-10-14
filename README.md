# Bikeshare Data Analysis Project

This project analyzes bikeshare trip data for major U.S. cities and generates summary statistics about travel patterns. It is a Python-based command-line application that lets users filter by city, month, and day and then reports information such as the most popular travel times, stations, trip durations, and user demographics.

## Functional Description

The script in `bikeshare.py`:

- Prompts the user to choose a city (`chicago`, `new york city`, or `washington`)
- Allows filtering data by month and weekday
- Loads and processes the relevant bikeshare dataset
- Calculates and prints statistics including:
  - Most common month, weekday, and start hour
  - Most popular start and end stations
  - Most frequent station-to-station trip combinations
  - Total and average trip duration
  - User type, gender and birth year distributions
- Asks whether the user wants to restart the analysis (with new filters)

## Project structure

- `bikeshare.py` — main application logic
- `README.md` — project overview and usage instructions

## Requirements

This project uses:

- Python 3
- pandas
- numpy

Install dependencies with:

```bash
pip install pandas numpy
```

## How to run

* Add CSV files in the project's root directory and ensure they are included in `CITY_DATA` in the script.
* From the project root, run:

```bash
python bikeshare.py
```

Follow the prompts to select a city, month, and day. The script will display the requested statistics and then ask if you want to run the analysis again.

## Contribution guidelines

Contributions are welcome to improve the project, fix bugs, or add new features. To contribute:

1. Fork the repository and create a feature branch from `main`.
2. Keep your changes focused and relevant to the project.
3. Follow the existing code style and keep the project easy to read and maintain.
4. Test your changes locally before submitting a pull request.
5. Include a clear description of what was changed and why in your pull request.

Please open an issue before starting significant work so that the maintainers can align on scope and avoid duplicate effort.

If you find a bug or have an idea for an enhancement, feel free to open an issue with a clear title and description.

## Credits

This project is forked from the Udacity project template repository and uses the starter code and sample bikeshare data provided by Udacity. 

## Date created

14.10.2026