#!/usr/bin/env python
# coding: utf-8

# In[1]:


#1) Calculate factorial of a number
num = int(input("Enter the number: "))
factorial_result = 1

while num != 0:
    factorial_result = factorial_result * num
    num = num - 1

print("Factorial of your number is:", factorial_result)


# In[2]:


#2) Reverse a word
input_word = input("Enter the word: ")
reversed_result = input_word[::-1]
print("Reversed word:", reversed_result)


# In[7]:


#3) Reverse a number
input_number = int(input("Enter a number: "))
result_reversed = int(str(input_number)[::-1])
print("Reversed number:", result_reversed)


# In[8]:


#4) Count down from a given number
user_input = int(input("Enter the number: "))

while user_input >= 0:
    print(user_input)
    user_input -= 1


# In[9]:


#5) Display the first 7 multiples of 7 using a while loop
i = 1
while i <= 7:
    result = 7 * i
    print(result)
    i += 1


# In[20]:


#6) Append the squares of multiple numbers to a list using a while loop with a stop condition
result_list = []

while True:
    user_input = int(input("Enter a number (-1 to stop): "))
    
    if user_input == -1:
        break
    
    squared_result = user_input ** 2
    result_list.append(squared_result)

print("Updated list:", result_list)


# In[ ]:


#7) Separate positive and negative numbers from a list
original_list = [5, 8, -1, 7, -2, -7]
positive_numbers = []
negative_numbers = []
for num in original_list:
    if num > 0:
        positive_numbers.append(num)
    else:
        negative_numbers.append(num)
print("Positive numbers:", positive_numbers)
print("Negative numbers:", negative_numbers)


# In[22]:


#8) Append the types of elements from a list to a new list
original_list = [1, -5, 'khushi', True, 3.14]
types_list = []

for item in original_list:
    types_list.append(type(item))

print("Types of elements:", types_list)


# In[24]:


#9) Filter even and odd numbers from a list
original_list = [67,98,23,67,43]
even_numbers_list = []
odd_numbers_list = []

for num in original_list:
    if num % 2 == 0:
        even_numbers_list.append(num)
    else:
        odd_numbers_list.append(num)

print("Even numbers:", even_numbers_list)
print("Odd numbers:", odd_numbers_list)


# In[25]:


#10) Fetch even values from a dictionary
my_dict = {'a': 10, 'b': 15, 'c': 24, 'd': 31, 'e': 42}
even_values_dict = {}

for key, value in my_dict.items():
    if value % 2 == 0:
        even_values_dict[key] = value

print("Dictionary with even values:", even_values_dict)


# In[ ]:




