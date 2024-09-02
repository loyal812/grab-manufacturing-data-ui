# Web Scraping Project: FastAPI + Next.js

Welcome to the Web Scraping Project! This repository contains code for a web scraping API built with FastAPI and a frontend UI using Next.js, TypeScript, and TailwindCSS.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Scraped Companies](#scraped-companies)
- [Frontend UI](#frontend-ui)

## Overview
This project allows users to scrape data from various companies' websites and display it through a modern UI. The backend is powered by FastAPI while the frontend is built with Next.js, TypeScript, and TailwindCSS.

## Features
✨ Fast and efficient web scraping using FastAPI  
💅 Modern, responsive UI with Next.js and TailwindCSS  
🛠 Easy setup and deployment  

## Installation
### Backend
1. Clone the repository:
   ```shell
   git clone https://github.com/your_username/your_repository.git
   cd your_repository/backend
   ```

2. Install the required dependencies:
   ```shell
   pip install -r requirements.txt
   ```

3. Run the FastAPI server:
   ```shell
   uvicorn main:app --reload
   ```

### Frontend
1. Navigate to the frontend directory:
   ```shell
   cd ../frontend
   ```

2. Install the required dependencies:
   ```shell
   npm install
   ```

3. Run the Next.js development server:
   ```shell
   npm run dev
   ```

## Usage
1. Start the FastAPI server.
2. Start the Next.js development server.
3. Open your web browser and visit `http://localhost:3000` to interact with the UI.

## Scraped Companies
The following companies are included in the scraping list:
- [onsemi](https://www.onsemi.com/PowerSolutions/MaterialComposition.do)
- [Maxim Integrated](https://www.maximintegrated.com)
- [Molex](https://www.molex.com/)
- [Phoenix Contact](https://www.phoenixcontact.com)
- [RS Delivers](https://export.rsdelivers.com)
- [TE Connectivity](https://www.te.com)
- [WAGO](https://smartdata.wago.com)
- [Omron](https://industrial.omron.eu)
- [Arrow](http://api.arrow.com/itemservice/v4)

## Frontend UI
The frontend is developed using Next.js with TypeScript and styled using TailwindCSS. It provides a sleek, modern interface for interacting with the scraping API.
