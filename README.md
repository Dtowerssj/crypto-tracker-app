# Crypto Tracker

A mobile app, built with React Native and Expo, that shows the top 100 cryptocurrencies by market capitalisation with live prices from the [CoinGecko API](https://www.coingecko.com/en/api).

## Features

- **Markets list** with the top 100 coins: logo, name, symbol and current price in USD.
- **24-hour change** for each coin, with a green up arrow or a red down arrow.
- **Bottom tab navigation** between the coins list and a watch list screen.
- A search bar component in the header.

### Work in progress

- The search bar is not connected to the list yet, so it does not filter results.
- The Watch List tab is a placeholder screen.

## Tech stack

- React Native with Expo (SDK 42)
- React Navigation (stack and bottom tabs)
- NativeBase and styled-components
- CoinGecko REST API

## Getting started

```bash
git clone https://github.com/Dtowerssj/crypto-tracker-app.git
cd crypto-tracker-app
npm install
npm start
```

> This project targets Expo SDK 42, released in 2021. Current versions of the Expo Go app only open projects built with recent SDKs, so you may need to upgrade the Expo SDK before running it on a device.

The prices come from CoinGecko's public endpoint, which has rate limits. No API key is needed.

## Project structure

```
App.js             App entry point
src/screens/       CoinsList and WatchList screens
src/components/    CoinItem and SearchBar
src/navigation/    Tab and stack navigators
src/constants/     Colors, fonts and icons
assets/            Fonts and app icons
```
