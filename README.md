**1. Methodology**

The TOPSIS (Technique for Order of Preference by Similarity to Ideal Solution) follows a structured mathematical approach:

Data Collection: Input CSV file containing alternatives and criteria.

Data Pre-Processing: Normalization of the decision matrix.

Model Training: Applying weights to the normalized matrix.

Model Testing: Calculating distances from the Ideal Best (+) and Ideal Worst (-) solutions.

Result Analysis: Computing the TOPSIS score and final ranking.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
**2. Description**

This web service automates the ranking of alternatives based on multiple criteria.

Functionality: Users upload a CSV and receive results via email.

Core Library: Built with Python (Flask), using Pandas and NumPy for calculations.

Input Requirements: CSV file with numerical criteria (first column must be the name/ID).

Other Information: Secure email delivery implemented via SMTP.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**3. Input / Output**

<img width="938" height="171" alt="image" src="https://github.com/user-attachments/assets/d4406f93-a413-4132-99d0-1c4002c70691" />

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**4. Live Link**
The application is live at: https://namansingh.pythonanywhere.com/

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
**5. Screenshot of the Interface**

<img width="500" height="302" alt="Screenshot 2026-01-20 at 10 45 06 PM" src="https://github.com/user-attachments/assets/13786d62-a6af-45a4-9bc3-5613896dced5" />
