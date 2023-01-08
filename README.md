# MTG 10k Most Popular Cards Dataset

Magic: The Gathering is a popular trading card game created by Wizard's of the Coast.

This repository contains two files:
1. `MTG_Cards.csv`
2. `scrape.ipynb`

## MTG_Cards.csv
This is the resulting dataset created by `scrape.ipynb` as of 12/23/2022.

It is the product of scraping the 10,000 most popular cards from [Card Kingdom](https://www.cardkingdom.com/).

Information for `MTG_Cards.csv` can be found [here](https://github.com/Agustin-Mor/MTG-10k-Most-Popular-Cards-Dataset/tree/main/MTG_Cards).

## scrape.ipynb
A jupyter notebook file for scraping the 10,000 most popular cards on [Card Kingdom](https://www.cardkingdom.com/).

Can be rerun in order to create an updated dataset.

If you have a faster computer you may need to introduce some artificial wait time to avoid HTML Status Code 429 (Too Many Requests).
