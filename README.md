# crypto_app

A Flutter project which uses Bloc and an external API to show the current prices for the top 25 crypto coins.This app fetches data from afrom https://min-api.cryptocompare.com/.

Basically it's only contains one page called homepage which contains the UI and shows the latest prices.  This application only has two models for data_error and currency and one service called data_repo. 

Bloc was used to tell the UI the state and build a listview. Also pull to refresh was implemented.
