# Crypto Tracker

Application for tracking historical and live cryptocoin values and select diffrerent cryptocoins to add to watchlist.

## Problem statement

When owning certain cryptocoins it's nice to see quickly what your coins are doing. This app will provide you with personalized information about the crypto coins you have. 

## Solution description

By adding coin to your wathclist via the select menu they will autmatically be added to you watchlist. 
Via an API it will get the current and historic value of your coins and will display the current value in euro's. In the dropdown menu it will show a chart so the user can see where the course has been.

## How to run

1. download zip file
2. Download via terminal:
- axios:          npm install axios
- chartjs:        npm install chart.js
- chartjs react:  npm install --save react-chartjs-2 chart.js
- download node to run the application(https://nodejs.org/en/download/)

3. Clone this repository via terminal: git clone https://github.com/uva-webapps/final-BonoLardinois.git

4. Open in texteditor

5. Change directory: cd CRYPTO_TRACKER

6. In terminal type: npm start
   to run the project

## Details and example

- The application makes use of the following API: https://www.coingecko.com/en/api
- User can add coins to their watchlist
- When coin is added you can see it appear on the page via an list
- User can click the expand button with a coin a see a chart for the historical data and current value

![Schermafbeelding 2021-05-27 om 14 18 24](https://user-images.githubusercontent.com/78788799/119863632-0f333080-bf1a-11eb-9d6e-e45a20889b09.png)

## Video

For a explanation video: https://video.uva.nl/media/0_12ldojry (In Dutch)

Timestamps:
- 0:00 - 0:48:    Intro
- 0:48 - 1:09:    Starting page
- 1:09 - 1:38:    Adding of a coin
- 1:38 - 2:35:    Coin details
- 2:35 - Einde:   Delete coins
