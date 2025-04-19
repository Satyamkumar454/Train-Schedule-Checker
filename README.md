# IRCTC Train Schedule Checker

A simple Python CLI tool that fetches and displays train schedules using the IndianRailAPI.

## Features

- Input a train number and fetch full route details
- Displays station name, arrival time, departure time, and distance
- Error handling for invalid train numbers and API responses

## Prerequisites

- Python 3.6+
- `requests` library

## Installation

1. Clone this repository:
   ```bash
   https://github.com/Satyamkumar454/Train-Schedule-Checker.git
   ```
2. (Optional) Create and activate a virtual environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

Run the script:

```bash
python train_schedule.py
```

Then follow the prompts:

1. Choose option 3 to check train schedule.
2. Enter the train number.
3. View the list of stops with timings.

## Future Improvements

- Live train status feature
- PNR status checking
- GUI using Tkinter or a web interface with Flask

## Contributing

Contributions are welcome! Please open issues or pull requests.

##

