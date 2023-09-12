# donedeal_scraper
  This repo contains two jupyter notbooks that are made to scrape donedeal.ie website for car ilstings and store them in a CSV file

  # Donedeal Car Listings Scraper
  # Overview
  This repository contains two Jupyter notebooks designed to scrape car listings from "donedeal.ie":

  donedeal3_best.ipynb: Extracts general car listings.
  donedeal3_filtered.ipynb: Targets listings based on filtered queries, specifically those within a certain price range.
  Prerequisites
  Ensure you have the necessary libraries installed:

  pip install -r requirements.txt
  # Usage
  For General Listings (donedeal3_best.ipynb):

  Open the notebook in Jupyter.
  Within the code, locate the loop for i in range(800):. The number 800 determines the number of query pages to be scraped. Adjust this value as needed.
  Execute the cells sequentially.
  Data is written to "car_listing_buy.csv".
  For Filtered Queries (donedeal3_filtered.ipynb):

  Open the notebook in Jupyter.
  Within the code, find the loop for i in range(64):. The number 64 specifies the number of query pages to scrape for the filtered results. Modify this value based on your requirements.
  Execute the cells sequentially.
  Data, specifically for cars within a price range, is written to "car_listing_lowprice.csv".
  Both notebooks extract the following attributes:

  # Price
  # Year
  # Make
  # Model
  # Mileage
  # Transmission
  # Fuel Type
  # Body Type
  # Color
  # Engine Size
  # NCT Expiry
  # Road Tax
  # URL (only in the filtered notebook)
  # Tips
  The number in the loop (for i in range(...)) in each notebook defines how many pages of listings will be scraped. For instance, if set to 10, ten pages will be scraped. Adjust this   based on how many pages of listings you want to cover.
  # Disclaimer
  Ensure you're in compliance with the "donedeal.ie" terms of service when scraping. If the website's structure changes, the scraper might need updates.

