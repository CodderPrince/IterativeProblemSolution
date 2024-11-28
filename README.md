# Iterative Linear Search Algorithm

## ✨ **Overview**

Welcome to the **Iterative Linear Search** implementation! This is a simple and effective algorithm used to find an element in an array. In this readme, you'll find a detailed explanation, as well as a colorful and animated design to make learning fun! 🚀

---

## 📚 **What is Linear Search?**

**Linear Search** is a searching algorithm that checks each element of a list sequentially until the desired item is found or the list ends. It works on both sorted and unsorted arrays, making it a versatile option.

### **Time Complexity:**
- Worst-case: O(n)
- Best-case: O(1)

---

## ⚙️ **How It Works**

1. Start from the first element of the array.
2. Compare the current element with the search item.
3. If they match, return the index where the element is found.
4. If no match is found, continue searching through the list.
5. If the list ends and no match is found, return -1.

---

## 📝 **Code Implementation** 

```python
def linearSearch(arr, searchItem):
    for i in range(len(arr)):  # Loop through each element
        if arr[i] == searchItem:
            print(f"Item found at index: {i}")  # Item found, return the index
            return i  # Return the index of the found item

    print("Item not found!")  # Item is not found
    return -1  # Return -1 if item is not found

# Main function to test the algorithm
arr = [3, 4, 5, 6, 7, 8, 9]  
searchItem = 7

linearSearch(arr, searchItem)
