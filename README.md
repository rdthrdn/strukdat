### E1: Show the keys with which each of the following targets will be compared in a search of the preceding binary search tree.

1. \(c\):
   - k, c

2. \(s\):
   - k, n, s

3. \(k\):
   - k

4. \(a\):
   - k, c, a

5. \(d\):
   - k, c, e, d

6. \(m\):
   - k, n

7. \(f\):
   - k, c, e, h

8. \(b\):
   - k, c, a

9. \(t\):
   - k, n, s

### E2: Insert each of the following keys into the preceding binary search tree.

1. \(m\):
   - k, n, m

2. \(f\):
   - k, c, e, h, f

3. \(b\):
   - k, c, a, b

4. \(t\):
   - k, n, s, t

5. \(c\):
   - Already in the tree (no insertion needed)

6. \(s\):
   - Already in the tree (no insertion needed)

### E3: Delete each of the following keys from the preceding binary search tree.

1. \(a\):
   - k, c (delete a)

2. \(p\):
   - k, n, s (delete p)

3. \(n\):
   - k (delete n)

4. \(s\):
   - k, n (delete s)

5. \(e\):
   - k, c (delete e)

6. \(k\):
   - delete k

### E4: Draw the binary search trees that function insert will construct for the list of 14 names presented in each of the following orders and inserted into a previously empty binary search tree.

1. **a**
   - Jan, Guy, Jon, Ann, Jim, Eva, Amy, Tim, Ron, Kim, Tom, Roy, Kay, Dot

2. **b**
   - Amy, Tom, Tim, Ann, Roy, Dot, Eva, Ron, Kim, Kay, Guy, Jon, Jan, Jim

3. **c**
   - Jan, Jon, Tim, Ron, Guy, Ann, Jim, Tom, Amy, Eva, Roy, Kim, Dot, Kay

4. **d**
   - Jon, Roy, Tom, Eva, Tim, Kim, Ann, Ron, Jan, Amy, Dot, Guy, Jim, Kay

### E5: Consider building two binary search trees containing the integer keys 1 to 63, inclusive, received in the orders

1. **a**
   - All the odd integers in order \(1, 3, 5, \ldots, 63\), then \(32, 16, 48\), then the remaining even integers in order \(2, 4, 6, \ldots\).

2. **b**
   - \(32, 16, 48\), then all the odd integers in order \(1, 3, 5, \ldots, 63\), then the remaining even integers in order \(2, 4, 6, \ldots\).

**Which of these trees will be quicker to build? Explain why.**
- Tree (b) will likely be quicker to build because inserting \(32\), \(16\), and \(48\) first will balance the tree early on, reducing the height and maintaining balance as more nodes are inserted.

### E6: All parts of this exercise refer to the binary search trees shown in Figure 10.8 and concern the different orders in which the keys \(a, b, \ldots, g\) can be inserted into an initially empty binary search tree.

1. **a**
   - Four different orders for inserting the keys:
     - \(a, b, c, d, e, f, g\)
     - \(g, f, e, d, c, b, a\)
     - \(d, b, a, c, f, e, g\)
     - \(d, b, a, c, f, g, e\)

2. **b**
   - Four different orders for inserting the keys:
     - \(b, a, d, c, g, f, e\)
     - \(e, f, g, d, c, b, a\)
     - \(d, a, b, c, f, e, g\)
     - \(c, b, a, d, e, f, g\)

3. **c**
   - Four different orders for inserting the keys:
     - \(c, a, b, e, d, g, f\)
     - \(f, e, d, g, a, b, c\)
     - \(e, c, a, b, d, g, f\)
     - \(d, b, a, c, e, g, f\)

4. **d**
   - There is only one order for inserting the keys that will produce a binary search tree that reduces to a given chain. This is because in a strictly increasing or decreasing order, each new key is either always greater or always smaller than all previously inserted keys, resulting in a straight-line structure (linked list). For example:
     - \(a, b, c, d, e, f, g\) (increasing order) or
     - \(g, f, e, d, c, b, a\) (decreasing order).
