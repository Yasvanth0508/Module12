# 📚 Stack using Linked List: Stack Implementation (Top Element Display)

## 🎯 Aim

To write a Python program that implements a **stack**.  
The program allows inserting 3 elements from the user and then prints the **top element** of the stack.

---

## 🧠 Algorithm

1. **Start the program.**
2. **Initialize** an empty list called `stack` to simulate the stack.
3. **Repeat 3 times**:
   - Prompt the user to **input a value**.
   - Use `stack.append(value)` to **push** the value onto the stack.
4. After inserting 3 elements:
   - Access the **top element** using `stack[-1]`.
5. **Print** the top element.
6. **End the program.**

---

## 💻 Program
```
  stack = []
  
  for i in range(3):
      value = input(f"Enter value {i + 1}: ")
      stack.append(value) 
  
  top_element = stack[-1]
  print("Top element of the stack is:", top_element)
```

## Output
![447323614-3453a038-da7e-4998-bc49-ef45b1374fab](https://github.com/user-attachments/assets/6139f292-a653-4b49-af01-b7c816576df8)

## Result
Thus, the program is executed successfully
