# TaxSavvy

## Overview

TaxSavvy is a simple web application that allows users to input their income and estimate the tax they need to pay based on predefined tax slabs. The application supports different tax regimes for various age categories and provides a straightforward way to calculate taxes according to the Indian tax system.

## Features

- Input fields for income and estimated tax.
- Supports tax calculations for:
  - General Category (Less than 60 years)
  - Senior Citizens (60 years and above but below 80 years)
  - Very Senior Citizens (80 years and above)
- Displays the calculated tax and compares it with the estimated tax.
- Alerts the user if the estimated tax does not match the calculated tax.

## Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/09amish/TaxSavvy.git
    ```

2. Navigate to the project directory:

    ```sh
    cd TaxSavvy
    ```

3. Open `index.html` in your preferred web browser.

## Usage

1. Enter your income in the "What's your income (USD)?" field.
2. Enter your estimated tax in the "Estimated Tax to be Paid (USD)" field.
3. Click on the "Calculate" button.
4. The application will display the calculated tax and compare it with your estimated tax. If they do not match, an alert will notify you.

## Tax Calculation Criteria

### General Category (Less than 60 years)
| Income Slab                       | Existing Tax Regime                        | New Tax Regime                            |
|-----------------------------------|--------------------------------------------|-------------------------------------------|
| Up to Rs. 2,50,000                | Nil                                        | 0 – Rs. 3,00,000: Nil                     |
| Rs. 2,50,001 – Rs.  5,00,000      | 5% above Rs. 2,50,000                      | Rs. 3,00,000 – Rs.  6,00,000: 5%          |
| Rs. 5,00,001 – Rs. 10,00,000      | Rs. 12,500 + 20% above Rs. 5,00,000        | Rs. 6,00,000 - Rs. 9,00,000: 10%          |
| Above Rs. 10,00,000               | Rs. 1,12,500 + 30% above Rs. 10,00,000     | Rs. 9,00,000 – Rs. 12,00,000: 15%         |
|                                   |                                            | Rs. 12,00,000 – Rs. 15,00,000: 20%        |
|                                   |                                            | Above Rs. 15,00,000: 30%                  |

### Senior Citizens (60 years and above but below 80 years)
| Income Slab                       | Existing Tax Regime                        | New Tax Regime                            |
|-----------------------------------|--------------------------------------------|-------------------------------------------|
| Up to Rs. 3,00,000                | Nil                                        | 0 – Rs. 3,00,000: Nil                     |
| Rs. 3,00,001 – Rs.  5,00,000      | 5% above Rs. 3,00,000                      | Rs. 3,00,000 – Rs.  6,00,000: 5%          |
| Rs. 5,00,001 – Rs. 10,00,000      | Rs. 10,000 + 20% above Rs. 5,00,000        | Rs. 6,00,000 - Rs. 9,00,000: 10%          |
| Above Rs. 10,00,000               | Rs. 1,10,000 + 30% above Rs. 10,00,000     | Rs. 9,00,000 – Rs. 12,00,000: 15%         |
|                                   |                                            | Rs. 12,00,000 – Rs. 15,00,000: 20%        |
|                                   |                                            | Above Rs. 15,00,000: 30%                  |

### Very Senior Citizens (80 years and above)
| Income Slab                       | Existing Tax Regime                        | New Tax Regime                            |
|-----------------------------------|--------------------------------------------|-------------------------------------------|
| Up to Rs. 5,00,000                | Nil                                        | 0 – Rs. 3,00,000: Nil                     |
| Rs. 5,00,001 – Rs. 10,00,000      | 20% above Rs. 5,00,000                     | Rs. 3,00,000 – Rs. 6,00,000: 5%           |
| Above Rs. 10,00,000               | Rs. 1,00,000 + 30% above Rs. 10,00,000     | Rs. 6,00,000 - Rs. 9,00,000: 10%          |
|                                   |                                            | Rs. 9,00,000 – Rs. 12,00,000: 15%         |
|                                   |                                            | Rs. 12,00,000 – Rs. 15,00,000: 20%        |
|                                   |                                            | Above Rs. 15,00,000: 30%                  |

## Contributing

1. Fork the repository.
2. Create a new branch:

    ```sh
    git checkout -b feature-branch
    ```

3. Make your changes.
4. Commit your changes:

    ```sh
    git commit -m "Add some feature"
    ```

5. Push to the branch:

    ```sh
    git push origin feature-branch
    ```

6. Create a pull request.


## Contact

If you have any questions or suggestions, feel free to reach out at 09amish@gmail.com.
