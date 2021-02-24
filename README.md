# Shopping Cart Project

A program that allows a customer to checkout their grocery items and get a receipt including the total payment (+tax) they owe for their items.

## Installation

Clone or download from [Github source][https://github.com/NikoRestifo/shopping-cart-project.git], then navigate to the project repository

```sh
cd ~/Desktop/shopping-cart-project

```

Use Anaconda to create and activate a new virtual environment, perhaps called "shopping-env":

```sh
# Create a new virtual enviromnent and install the packages from reqiurements.txt:
conda create -n shopping-env python=3.8 
conda activate shopping-env
pip install -r requirements.txt
```

## Setup

In the root directory of your local repository, create a new file called ".env", and update the contents of the ".env" file to store information required to access the Products Database. Additionally, specify the tax rate:

    GOOGLE_SHEET_ID = "1ItN7Cc2Yn4K90cMIsxi2P045Gzw0y2JHB_EkV4mXXpI"
    SHEET_NAME = "products" 
    TAX_RATE="0.0875"

## Usage

Run the program:

```py
python shopping_cart.py
```

Enter the Product ID for each item in your shopping cart. Type 'DONE' when you are finished entering each product. The program will then output the receipt.