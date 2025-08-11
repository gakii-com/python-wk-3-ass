# Function to calculate the final price after applying a discount
def calculate_discount(price, discount_percent):
    """
    Calculate the final price after applying a discount if it's 20% or more.

    Parameters:
        price (float): The original price of the item.
        discount_percent (float): The discount percentage to apply.

    Returns:
        float: The final price after discount (if applicable).
    """
    # Check if discount is 20% or more
    if discount_percent >= 20:
        # Calculate the discount amount
        discount_amount = price * (discount_percent / 100)
        # Subtract discount from original price
        final_price = price - discount_amount
        return final_price
    else:
        # Return original price if discount is less than 20%
        return price

# Prompt the user to enter the original price
price = float(input("Enter the original price of the item: "))

# Prompt the user to enter the discount percentage
discount_percent = float(input("Enter the discount percentage: "))

# Call the function to calculate the final price
final_price = calculate_discount(price, discount_percent)

# Display the result
if discount_percent >= 20:
    # Discount applied
    print(f"Final price after {discount_percent}% discount: {final_price}")
else:
    # No discount applied
    print(f"No discount applied. Price remains: {price}")
