
<center>

# <u>**Arbitage Betting**</u>



</center>

Arbitrage Betting is a sophisticated strategy designed to leverage differences in odds across various bookmakers, ensuring a guaranteed profit for the bettor. This repository presents an algorithm that meticulously calculates arbitrage opportunities, focusing on two distinct betting games: Over/Under (Totals) and Head-to-Head (H2H) betting.

## Overview

### Strategy

Arbitrage betting involves strategically placing bets on all potential outcomes of an event, exploiting pricing disparities among bookmakers. This results in a positive return, irrespective of the actual event outcome. The algorithm employed in this project provides a quick, precise, and risk-free approach to capitalize on these opportunities.

### Betting Games

1. **Over/Under (Totals) Betting:** Predicts whether a game's final score will surpass (Over) or fall below (Under) a predetermined score set by the bookmaker. This requires forecasting the total points or goals in a game.

2. **Head-to-Head (H2H) Betting:** Individuals place bets on the anticipated victory of either the home or away team, with the option to bet on a draw if applicable.

## Data Source

The algorithm utilizes live data sourced from the [ODDS API](https://the-odds-api.com/), specifically collecting information on the upcoming/live games to ensure accurate and current calculations.

## Getting Started

To run the Arbitrage Betting algorithm:

1. **Get API Key:** Obtain a free API key from [ODDS API](https://the-odds-api.com/#get-access).
2. **Configure .env:** Place your API key in the `.env` file.
3. **Run the Algorithm:** Execute the entire `arbitage_betting.ipynb` notebook by selecting the **Run All** option.
4. **View Results:** Navigate to the [Run Section](https://github.com/StamTheo28/arbitage-betting/blob/main/arbitage_betting.ipynb) to analyze the final results.

**Note:** Exercise caution as there are limited API requests available per month.

## Results

The algorithm generates two pandas dataframes, presenting arbitrage opportunities in a ranked order based on the highest Return On Investment (ROI%).

## License

This project is licensed under the [MIT License](LICENSE).

---

**Disclaimer:** This project is for educational purposes only. Ensure compliance with relevant gambling laws and regulations in your jurisdiction.

