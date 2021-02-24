# Shopping Cart Project

A program that allows a customer to checkout their grocery items and get the total payment (+tax) they owe for their items.

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

In in the root directory of your local repository, create a new file called ".env", and update the contents of the ".env" file to store information required to access the Products Database. Additionally, specify the tax rate:

    GOOGLE_SHEET_ID = "1_hisQ9kNjmc-cafIasMue6IQG-ql_6TcqFGpVNOkUSE"
    SHEET_NAME = "Products-2021" 
    TAX_RATE="0.0875"


> NOTE: the ".env" file is usually the place for passing configuration options and secret credentials, so as a best practice we don't upload this file to version control (which is accomplished via a corresponding entry in the [.gitignore](/.gitignore) file)

## Usage

Run the program:

```py
python shopping_cart.py
```
