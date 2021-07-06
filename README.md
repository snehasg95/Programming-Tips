# Programming-Tips
Tips I learnt for writing efficient code


Examples for edge cases to look out for
Source: https://medium.com/swlh/taking-the-edge-off-of-edge-cases-7b3008d83a57

String: null, empty string, length 1, spaces, upper/lower cases, all same character, long string, Unicode string (special characters), odd/even length string
Numbers: 0, dividing by zero, leading 0s, Min/MaxInt, negative/positive
Sort algorithm: empty input, null input, 1 element, very long input, duplicate elements (sort on a second condition?), odd/even length input
Linked List/Tree: null values for head/root
Stack/Queue: removing elements from empty stack/queue
Loops: while loops running forever (properly incre./decre. pointers)


Example 2: If a number is palindrome
  # edge cases to think of -- negative numbers? never a palindrome
  # those with zeros how do we handle
  # empty input
