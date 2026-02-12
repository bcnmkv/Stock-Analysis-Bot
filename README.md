# Stock-Analysis-Bot

## About
This is a Power Automate Desktop flow that automatically retrieves stock tickers from an Excel file, scrapes the latest news headlines for each stock, and saves the data back into Excel.

## Features
- **Excel Integration:** Reads tickers dynamically from `Stocks.xlsx`.
- **Smart Scraping:** Extracts stock movements and relevant news headlines.
- **Dynamic Routing:** Determines if a stock is "UP" or "DOWN" and adjusts search queries accordingly.

## Prerequisites
- Windows 10/11
- Power Automate Desktop
- Microsoft Excel
- Mozilla Firefox
- (Optional) Power BI Desktop

## Installation & Setup
1. **Download the Repository:** Clone or download this project.
2. **Prepare Excel:** Move `data/Stocks.xlsx` to your `Downloads` folder (or update the path in the flow). Fill out the `Ticker` and `Name` columns according to your investments.
3. **Import Flow:**
   - Open the `bot_flow.txt` file.
   - Copy the entire text.
   - Create a new Flow in Power Automate Desktop.
   - Paste the text into the designer workspace.
4. **Run:** Click the "Run" button.

## Project Structure
- `/src` - Contains the raw PAD source code.
- `/data` - Example Excel files and templates.

## Notes
- Ensure your browser extensions for Power Automate are installed and enabled.
