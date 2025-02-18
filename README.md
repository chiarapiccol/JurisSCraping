# Juris Scraping
This repository contains a project for scraping legal documents from the Juris database and analyse their content. The project was conducted as research assistant by professor Prof. Dr. Gerald Schneider (AG Internationale Politik, Universität Konstanz) for the Project „Administrative Inequality: The Case of Foreign Nationals in Germany“.


## Introduction
This project involves scraping legal documents from the Juris database. The scraping process is automated using Selenium, and the data is processed and saved for further analysis.

## Installation
To run this project, you need to install the following packages:
selenium
requests
PyPDF2
pickle
Additionally, you need to download and install the ChromeDriver from here.

## Before Starting
Make sure to:

- Be connected to the Uni-WLAN or the Uni-VPN.
- Have all necessary packages installed.
- Ensure a strong and stable internet connection.

## Scraping Process
The scraping process involves the following steps:

- Importing Packages
- Opening the Web and Selecting Filters
- Open the web, select relevant filters, and save cookies.
- Save the cookies
- Downloading PDFs
- Collect the links of the PDFs for each of the elements and download them.

