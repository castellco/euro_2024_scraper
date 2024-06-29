# Getting the game statistics of EURO 2024 ⚽ players with Python 🐍 and Selenium

This is a scraper that extracts the game statistics of EURO 2024 players from the official UEFA website (https://www.uefa.com/european-qualifiers/statistics/players/). The scraper uses Python and Selenium to extract the data and loads it to the environment as a pandas DataFrame. It does not export the data to a file, but you can easily do that with the pandas `to_csv()` method.

It was created as part of the local challenge "UEFA EURO 2024 - Leveraging Machine Learning and Open Data Sets for Advanced Sports Analytics", promoted by [Omdena](https://omdena.com/)'s Tunisia Local Chapter. The project's official repo can be found in [DagsHub](https://dagshub.com/Omdena/TunisiaLocalChapter_UEFAEURO2024).

## Requirements
- Selenium: `pip install selenium` and the code installs the webdriver itself.
- Pandas: `pip install pandas`
- Time and re modules are also used in the code. They are built-in modules in Python.
- Chrome web browser: be sure to update it to the latest version.

![image](https://github.com/castellco/euro_2024_scraper/blob/main/showcase.gif)


