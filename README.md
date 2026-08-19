# CUSTOMER INFORMATION
name = input("Name: ")
contact = input("Contact #: ")
address = input("Address: ")
print("")

# PRODUCT 1
product1 = input("Product Name: ")
price1 = int(input("Price: "))
quantity1 = int(input("Quantity: "))
amount1 = price1 * quantity1

# PRODUCT 2
print("")
product2 = input("Product Name: ")
price2 = int(input("Price: "))
quantity2 = int(input("Quantity: "))
amount2 = price2 * quantity2

# PRODUCT 3
print("")
product3 = input("Product Name: ")
price3 = int(input("Price: "))
quantity3 = int(input("Quantity: "))
amount3 = price3 * quantity3

print("")

# TOTAL AMOUNT
discount = float(input("Enter Discount: "))

subtotal = amount1 + amount2 + amount3
discount_amount = subtotal * (discount / 100)
total = subtotal - discount_amount

# RECEIPT
print("")

print("========================================")
print("           STORE RECEIPT                ")
print("========================================")
print("Name: ", name)
print("Contact#:", contact)
print("Address: ", address)
print("")
print("----------------------------------------")
print("Product  ", "Price  ", "Quantity  ", "Total  ")
print("----------------------------------------")
print("")
print(product1, ":", "", price1, "", quantity1, "", amount1)
print(product2, ":", "", price2, "", quantity2, "", amount2)
print(product3, ":", "", price3, "", quantity3, "", amount3)
print("")
print("----------------------------------------")
print("")
print("Subtotal: ", subtotal)
print("Discount: ", discount)
print("")
print("----------------------------------------")
print("")
print("Total Price: ", total)
print("")
print("========================================")
