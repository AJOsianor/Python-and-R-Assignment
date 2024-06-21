# Policyholder Management System

This Python program demonstrates a simple policyholder management system where policyholders can purchase products and display their account details.

## Classes

### Policyholder
- Attributes:
    - name: Name of the policyholder
    - address: Address of the policyholder
    - products: List of products purchased by the policyholder
- Methods:
    - `add_product(product)`: Adds a purchased product to the policyholder's account
    - `display_account_details()`: Displays the policyholder's account details including name, address, and purchased products

### Product
- Attributes:
    - name: Name of the product
    - description: Description of the product
    - price: Price of the product

## Usage

1. Create instances of policyholders and products.
2. Have policyholders purchase products using the `add_product()` method.
3. Display the account details of each policyholder using the `display_account_details()` method.

Sample code snippet:

```python
# Create policyholders
policyholder1 = Policyholder("Jasiel Ikhianosimhe", "123 Main St")
policyholder2 = Policyholder("Abu Osianor", "456 Elm St")

# Create products
product1 = Product("Insurance Plan A", "Comprehensive coverage for healthcare", 100)
product2 = Product("Insurance Plan B", "Basic coverage for emergencies", 50)

# Policyholder 1 purchases product 1
policyholder1.add_product(product1)

# Policyholder 2 purchases product 2
policyholder2.add_product(product2)

# Display account details for both policyholders
policyholder1.display_account_details()
policyholder2.display_account_details()