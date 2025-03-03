# VC Exit Calculator

## Overview
The **VC Exit Calculator** is an interactive tool designed to help NYU students in the BTE Capstone class understand how venture capital return multiples work. By manipulating different variables, students can see the impact of valuation, investment size, ownership dilution, and industry revenue multiples on exit outcomes. 

## Purpose
This project aims to provide a hands-on way for students to grasp key concepts in venture capital, including:
- **Post-Money Valuation**: The total valuation of a startup **after** an investment round, including the newly invested capital.
- **Check Size**: The amount of money the investor is contributing in a given funding round.
- **Ownership at Entry**: The percentage of the company the investor receives based on the check size and post-money valuation.
- **Dilution**: The assumption that the investor will be diluted by 20% in each of the following **three** rounds if they do not invest further - a simplification for the purposes of this class.
- **Fund Returner**: A startup is considered a “fund returner” if the investor’s ownership at exit generates enough proceeds to return their entire fund.
- **Revenue Multiple (EV/R)**: A common valuation method in VC that determines the exit value based on revenue and an industry-specific multiple.

## How It Works
The calculator allows users to input:
1. **Check Size ($)** – The amount the investor is putting into the company.
2. **Valuation (Post-Money, $)** – The valuation of the company immediately after the round.
3. **Fund Size of the Investor ($)** – The total size of the venture capital fund making the investment.
4. **Industry Multiple** – A multiplier (5x, 7x, 10x) used to estimate the company’s exit valuation based on revenue.

### Calculations
- **Ownership at Entry (%)** = Check Size / Post-Money Valuation
- **Final Ownership at Exit (%)** = Ownership at Entry × (0.8 × 0.8 × 0.8) [assuming no follow-on investments]
- **Exit Valuation Needed ($)** = Fund Size / Final Ownership
- **Revenue Target for Exit ($)** = Exit Valuation Needed / Industry Multiple

## How to Use
1. **Open the calculator** 
2. **Enter investment details** (check size, valuation, fund size, and industry multiple).
3. **Review the calculated outputs**:
   - Final ownership at exit
   - Exit valuation needed
   - Revenue target for exit
4. **Experiment with different values** to understand how assumptions impact VC returns.

## License
This project is open-source and intended for educational purposes only.
