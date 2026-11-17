# BMI Calculator (Python)

## Why I Built This
I wanted to build something that goes beyond simply proving a technical skill. I designed it with a clear purpose: health tools often feel overly cold and purely machine like, spitting out a raw number without context.

Because health is something that affects all of us—and weight and wellness can be sensitive topics—I wanted this calculator to greet the user by name and deliver clinically grounded responses (based on CDC guidelines) that still feel approachable and grounded. Rather than leaving users with a cold statistic, each result reminds them what the calculation is based on—ensuring it doesn´t feel personal or ill-aimed, whatever their circumstances may be—and encourages them to save the number and consult a health specialist.

## How It Works
1. **Personalized Input:** Prompts the user for their name, weight (in pounds), and height (in inches).
2. **Standard CDC Formula:** Calculates Body Mass Index using the standard imperial formula: `(weight / height²) × 703`.
3. **Clinical Classification & Guidance:** Evaluates the result against CDC adult BMI categories—from Underweight to Class 1, 2, and 3 Obesity—and returns a personalized message along with a recommendation to consult a health professional.

## Tech Stack & Data Sources
* **Language:** Python 3 (Jupyter Notebook `.ipynb`)
* **Clinical Reference:** [CDC Adult BMI Calculator & Categories](https://cdc.gov)
