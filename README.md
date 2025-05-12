# pythonweek3Assignmentquestion1
def calculate_discount(price, discount_percent):
if discount_percent >= 20:
 discounted_price = price * (1 - discount_percent / 100)
  return discounted_price
else:
  return price

#Prompt the user for inputquestion2
original_price = float(input("Enter the original price: "))
discount_percent = float(input("Enter the discount percentage: "))
#calculate the final price
final_price = calculate_discount(original_price, discount_percent)
if discount_price >= 20:
     print(f"The final price after a {discount_percent}% discount is: Kshs{final_price:.2f}")
 else:
     print(f"No discount applied. original price is: Kshs{original_price:.2f}")
  

