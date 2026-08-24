# Distance Calculator

A lightweight Python tool that calculate the straight-line and travel distance between coordinates or cities.

## Features

- Computes distance using latitude and longitude (Haversine formula).

## Installation

### Prerequisites

Make sure you have **Python 3.8 or higher** installed on your system.

### Steps

1. Clone my repository to your local machine:
   ```bash
   git clone https://github.com
   ```

2. Navigate into the project directory:
   ```bash
   cd distance-calculator
   ```

3. Install the required dependencies that I used for this project:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

### Command Line Interface (CLI)

You can run my main script directly from your terminal:

```bash
python calculator.py --origin "New York" --destination "Los Angeles"
```

### Python Module Example

You can also import my module into your own Python scripts like this:

```python
from calculator import DistanceCalculator

# Initialize my calculator class
calc = DistanceCalculator()

# Calculate distance between two coordinate points
miles = calc.between_coordinates((40.7128, -74.0060), (34.0522, -118.2437))
print(f"Distance: {miles} miles")
```

