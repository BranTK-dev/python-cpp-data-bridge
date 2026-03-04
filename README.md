# Python-C++ Data Bridge
**Status:** 🚧 Python script is live; working on the C++ CSV reader.

## The Problem
Python is great for grabbing data from the web, but UNISA taught me C++ for the heavy lifting. I wanted to see if I could make them work together.

## How it works (The Plan)
1. **Python:** I wrote a script that pings a free API to get the current ZAR/USD exchange rate.
2. **The Bridge:** Python saves that to a `.csv` file.
3. **C++:** My Qt app reads that file and calculates moving averages to see where the Rand is heading.

## Tech Stack
- **Python (Requests):** For the web stuff.
- **C++:** For the math and the desktop dashboard.

## To-Do
- [ ] Automate the Python script to run every hour.
- [ ] Fix the C++ bug where it crashes if the CSV is empty.
