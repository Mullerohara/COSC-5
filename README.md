# COSC-5
Sorry for the late notice more technical difficulties
>>> def main():
...         # Initialize an empty list to store the numbers
...                     numbers = []
...
>>>     print("Please enter a series of 20 numbers:")
  File "<python-input-1>", line 1
    print("Please enter a series of 20 numbers:")
IndentationError: unexpected indent
>>>
>>>     # Loop 20 times to get user input
>>>     for i in range(1, 21):
  File "<python-input-4>", line 1
    for i in range(1, 21):
IndentationError: unexpected indent
>>>         while True:
  File "<python-input-5>", line 1
    while True:
IndentationError: unexpected indent
>>>             try:
  File "<python-input-6>", line 1
    try:
IndentationError: unexpected indent
>>>                 user_input = float(input(f"Enter number {i}: "))
  File "<python-input-7>", line 1
    user_input = float(input(f"Enter number {i}: "))
IndentationError: unexpected indent
>>>                 numbers.append(user_input)
  File "<python-input-8>", line 1
    numbers.append(user_input)
IndentationError: unexpected indent
>>>                 break  # Exit the input validation loop if successful
  File "<python-input-9>", line 1
    break  # Exit the input validation loop if successful
IndentationError: unexpected indent
>>>             except ValueError:
  File "<python-input-10>", line 1
    except ValueError:
IndentationError: unexpected indent
>>>                 print("Invalid input. Please enter a valid number.")
  File "<python-input-11>", line 1
    print("Invalid input. Please enter a valid number.")
IndentationError: unexpected indent
>>>
>>>     # Perform the calculations
>>>     lowest = min(numbers)
  File "<python-input-14>", line 1
    lowest = min(numbers)
IndentationError: unexpected indent
>>>     highest = max(numbers)
  File "<python-input-15>", line 1
    highest = max(numbers)
IndentationError: unexpected indent
>>>     total = sum(numbers)
  File "<python-input-16>", line 1
    total = sum(numbers)
IndentationError: unexpected indent
>>>     average = total / len(numbers)
  File "<python-input-17>", line 1
    average = total / len(numbers)
IndentationError: unexpected indent
>>>
>>>     # Display the analyzed data
>>>     print("\n--- Number Analysis Results ---")
  File "<python-input-20>", line 1
    print("\n--- Number Analysis Results ---")
IndentationError: unexpected indent
>>>     print(f"The lowest number in the list: {lowest}")
  File "<python-input-21>", line 1
    print(f"The lowest number in the list: {lowest}")
IndentationError: unexpected indent
>>>     print(f"The highest number in the list: {highest}")
  File "<python-input-22>", line 1
    print(f"The highest number in the list: {highest}")
IndentationError: unexpected indent
>>>     print(f"The total of the numbers in the list: {total}")
  File "<python-input-23>", line 1
    print(f"The total of the numbers in the list: {total}")
IndentationError: unexpected indent
>>>     print(f"The average of the numbers in the list: {average:.2f}")
  File "<python-input-24>", line 1
    print(f"The average of the numbers in the list: {average:.2f}")
IndentationError: unexpected indent
>>>
>>> if __name__ == "__main__":
...             main()
