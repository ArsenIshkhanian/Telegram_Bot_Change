# Currency Exchange Rate Telegram Bot

A Telegram bot that provides up-to-date currency exchange rates using web scraping and Selenium.

## Project Description

This bot fetches current currency exchange rates from the web using Selenium, processes the data, and sends the information to users on Telegram via an interactive bot built with the `telebot` library.

## Technologies Used

- Python  
- [pyTelegramBotAPI (telebot)](https://github.com/eternnoir/pyTelegramBotAPI) for Telegram bot framework  
- Selenium WebDriver for automated web scraping  
- ChromeDriver (headless mode) for browser automation  

## Features

- Fetches live currency exchange rates dynamically  
- Supports inline keyboard buttons for easy user interaction  
- Runs in headless Chrome for efficient scraping without GUI  

## How It Works

1. **Rate grabbing:** Uses Selenium with ChromeDriver in headless mode to scrape currency rates from the target website.  
2. **Telegram bot:** Utilizes `telebot` to receive commands and send currency information to users.  
3. **Interactive UI:** Inline keyboard buttons allow users to select currencies and receive rates quickly.
