# Heredity

This project is part of the CS50 AI course and explores probabilistic reasoning in genetics. It models how genes and traits are passed down through generations using Bayesian networks.

## Features

- Calculates gene and trait probabilities for family members.
- Handles inheritance and mutation probabilities.
- Supports input from CSV files describing family relationships.

## Setup

1. Clone the repository.
2. (Optional) Create and activate a virtual environment:
   ```
   python3 -m venv venv
   source venv/bin/activate
   ```
3. Install dependencies (if any):
   ```
   pip install -r requirements.txt
   ```

## Usage

Run the main heredity script with a CSV file describing the family:

```
python heredity.py data/family.csv
```

## Files

- `heredity.py`: Main program logic.
- `data/`: Example CSV files.
- `.gitignore`: Git ignore rules.
- `README.md`: Project documentation.

## License

This project is for educational purposes as part of the CS50 AI course.
