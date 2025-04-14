### crossJoin  
Implement a function `crossJoin` that returns the Cartesian product of two arrays, combining each element from the first array with each element from the second array.

Don't use in-built function that works same as `crossJoin` function.

**Example:**  
```
Input: [1, 2] and ["a", "b"]  
Output: [[1,"a"], [1,"b"], [2,"a"], [2,"b"]]
```

---

### dot  
Implement a function called `dot` that takes a nested associative array and converts it into a flat associative array.  
You must combine keys using the "dot notation"—joining nested keys into a single
key separated by dot (".").

Don't use in-built function that works same as `dot` function.

**Example (Dot Notation Explained):**  
```
Input:
{
  "user": { "name": "John", "email": "john@example.com" },
  "country": "US"
}

Output:
{
  "user.name": "John",
  "user.email": "john@example.com",
  "country": "US"
}
```

---

### undot  
Implement a function called `undot`, the opposite of question #2. This expands a flat associative array with keys containing dots (".") into a nested associative structure.

Don't use in-built function that works same as `undot` function.

**Example:**  
```
Input:
{"user.name":"John","user.email":"john@example.com","country":"US"}

Output:
{"user":{"name":"John","email":"john@example.com"},"country":"US"}
```

---

### flatten  
Implement a function `flatten` to convert a multidimensional array to a single-level array.

Don't use in-built function that works same as `flatten` function.

**Example:**  
```
Input: [1, [2, [3, 4]], 5]  
Output: [1, 2, 3, 4, 5]
```

---

### partition  
Implement a function `partition` to split an array into two groups based on a provided testing (condition) function predicate.

Don't use in-built function that works same as `partition` function.

**Example:**  
```
Input: [1, 2, 3, 4, 5], predicate (x => x > 3)  
Output: [[4,5], [1,2,3]]
```

---

### pluck  
Implement the `pluck` function to extract all values of a specified key from an array containing associative arrays.

Don't use in-built function that works same as `pluck` function.

**Example:**  
```
Input:
[{"name":"Alice"},{"name":"Tom"},{"name":"Kate"}], key="name"
Output: ["Alice","Tom","Kate"]
```

---

### keyBy  
Implement a function `keyBy` that converts an array of associative arrays into a single associative array, re-indexing them by the specified associative key.

Don't use in-built function that works same as `keyBy` function.

**Example:**  
```
Input:
[{"id":1,"name":"John"},{"id":2,"name":"Anna"}], key="id"
Output:
{ "1":{"id":1,"name":"John"}, "2":{"id":2,"name":"Anna"} }
```

---

### query  
Implement a function `query` that converts an associative array to a URL query string.

Don't use in-built function that works same as `query` function.

**Example:**  
```
Input: {"page":2,"search":"test"}  
Output: "page=2&search=test"
```

---

### sortRecursive  
Implement a function named `sortRecursive` sorting associative arrays by keys, recursively sorting sub-arrays as well.

Don't use in-built function that works same as `sortRecursive` function.

**Example:**  
```
Input: {"b":2,"a":{"d":4,"c":3}}  
Output: {"a":{"c":3,"d":4},"b":2}
```

---

### shuffle  
Implement a function `shuffle` randomly rearranging elements of an input array.  

Don't use in-built function that works same as `shuffle` function.

**Example (Possible Output):**  
```
Input: [1,2,3,4,5]
Output (Possible): [3,1,4,5,2]
```

---

### random  
Implement the function `random`, which selects and returns one or more random elements from an array.

Don't use in-built function that works same as `random` function.

**Example:**  
```
Input: [1,2,3], count=2  
Possible Output: [2,3]
```

---

### data_fill  
Implement a function called `data_fill` to set values in nested associative arrays using "dot notation".  
(**Dot notation means writing nested keys separated by dots, e.g., "user.address.street"**).  
It sets value only if the key doesn't exist yet.

Don't use in-built function that works same as `data_fill` function.

**Example:**  
```
Input: {}, key="person.name", value="Alex"  
Output: {"person":{"name":"Alex"}}
```

---

### data_get  
Implement a function called `data_get` to retrieve value from a nested associative array, using "dot notation".

Don't use in-built function that works same as `data_get` function.

**Example:**  
```
Input: {"person":{"name":"Alex","age":25}}, key="person.age"  
Output: 25
```

---

### data_set  
Implement `data_set`, similar to Question #12, to set a value using the "dot notation". It overwrites existing values.

Don't use in-built function that works same as `data_set` function.

**Example:**  
```
Input: {}, key="person.address.street", value="Main"  
Output: {"person":{"address":{"street":"Main"}}}
```

---

### data_forget  
Implement a function `data_forget` that removes value from nested associative array, using "dot notation".

Don't use in-built function that works same as `data_forget` function.

**Example:**  
```
Input: {"user":{"name":"Alex","age":25}}, key="user.age"  
Output: {"user":{"name":"Alex"}}
```

---

### prependKeysWith  
Implement `prependKeysWith` adding a given prefix to all keys of associative array.

Don't use in-built function that works same as `prependKeysWith` function.

**Example:**  
```
Input: {"name":"Sam","city":"NY"}, prefix="user_"  
Output: {"user_name":"Sam","user_city":"NY"}
```

---

### collapse  
Implement `collapse` which merges multiple arrays into a single array.

Don't use in-built function that works same as `collapse` function.

**Example:**  
```
Input: [[1,2], [3,4], [5]]  
Output: [1,2,3,4,5]
```

---

### isAssoc  
Implement a function `isAssoc` that determines if an array has associative (named/string) keys.

Don't use in-built function that works same as `isAssoc` function.

**Example:**  
```
Input: {"a":1, "b":2}, Output: true  
Input: [1,2,3], Output: false
```

---

### except  
Implement `except` function that returns an associative array excluding specified keys.

Don't use in-built function that works same as `except` function.

**Example:**  
```
Input: {"a":1,"b":2,"c":3}, remove=["a","c"]  
Output: {"b":2}
```

---

### set  
Implement `set` function setting a value within nested associative arrays based on provided key using dot notation. If the nested structure doesn't exist, it should create it.

Don't use in-built function that works same as `set` function.

**Example:**  
```
Input: {}, key="address.city", value="Boston"  
Output: {"address":{"city":"Boston"}}
```
