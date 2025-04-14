### **substrReplace**  
Write a function `substrReplace` to replace a portion of the string starting from a specified position and length with another given string.

Don't use in-built function that works same as `substrReplace` function.

**Example:**  
```
Input: "I love sunny days", replacement="rainy", position=7, length=5  
Output: "I love rainy days"
```

---

### **replaceArray**  
Write a function `replaceArray` to sequentially replace each occurrence of the placeholder `"?"` in a string with multiple values provided in an array.

Don't use in-built function that works same as `replaceArray` function.

**Example:**  
```
Input: "I saw ? and ? today.", replacements=["Alice","Bob"]  
Output: "I saw Alice and Bob today."
```

---

### **inlineMarkdown**  
Write a function `inlineMarkdown` to convert basic markdown syntax (**bold**, *italic*) in the string into HTML tags.

Don't use in-built function that directly converts markdown to HTML.

**Example:**  
```
Input: "Make *this* word italic and **this** bold."  
Output: "Make <em>this</em> word italic and <strong>this</strong> bold."
```

---

### **password**  
Write a `password` function to securely generate a random password string containing at least one uppercase letter, one lowercase letter, one digit, and one special character.

Don't use in-built function that works same as `password` function.

**Example:** (Possible)  
```
Length: 8  
Output: "h6G#t2M!"
```

---

### **slug**  
Write a function `slug` to convert the provided string into an SEO-friendly URL "slug": lowercase with words separated by dashes, removing special characters.

Don't use in-built function that works same as `slug` function.

**Example:**  
```
Input: "Easy & Secure Payments!"  
Output: "easy-secure-payments"
```

---

### **ucsplit**  
Write a function `ucsplit` to split a camelCase or PascalCase input string into separate words at uppercase-letter boundaries.

Don't use in-built function that works same as `ucsplit` function.

**Example:**  
```
Input: "helloWorldToday"  
Output: ["hello", "World", "Today"]
```

---

### **mask**  
Write a function `mask` to mask all characters of a given string except a specified number of characters from the start and end with a masking symbol.

Don't use in-built function that works same as `mask` function.

**Example:**  
```
Input: "1234567890", unmaskedStart=2, unmaskedEnd=2, maskWith="#"  
Output: "12######90"
```

---

### **wrap**  
Write a function `wrap` to wrap the provided content within specified opening and closing strings, but only add wrappers if the string doesn't already begin and end with them.

Don't use in-built function that works same as `wrap` function.

**Example:**  
```
Input: "welcome", start="<p>", end="</p>"  
Output: "<p>welcome</p>"  

Input (already wrapped): "<p>welcome</p>"  
Output: "<p>welcome</p>"
```

---

### **headline**  
Write a function `headline` to convert input text into proper headline
formatting: Capitalize all words, and remove redundant spaces.

Don't use in-built function that works same as `headline` function.

**Example:**  
```
Input: "exciting news:hello,superUser!"  
Output: "Exciting News: Hello, SuperUser!"
```

---

### **betweenFirst**  
Write a function `betweenFirst` to obtain the substring appearing immediately after the first occurrence of given "start" string up to the next occurrence of provided "end" string. Return empty if boundaries not present.

Don't use in-built function that works same as `betweenFirst` function.

**Example:**  
```
Input: "[Click Here] for detail.", start="[", end="]"  
Output: "Click Here"
```

---

### **replaceEnd**  
Write a function `replaceEnd` to replace substring at the end of the input string with given replacement substring, but only if the target substring is exactly at the end.

Don't use in-built function that works same as `replaceEnd` function.


**Example:**  
```
Input: "project_draft", from="_draft", to="_final"  
Output: "project_final"
```

---

### **title**  
Write a function `title` to capitalize the first letter of each word correctly, properly handling special characters such as apostrophes and dashes.

Don't use in-built function that works same as `title` function.

**Example:**  
```
Input: "let's work-out together"  
Output: "Let's Work-Out Together"
```

---

### **swap**  
Write a function `swap` to replace multiple distinct substrings simultaneously within the input using a pair-wise mapping provided.

Don't use in-built function that works same as `swap` function.


**Example:**  
```
Input: "blue ocean deep sky", replacements={"blue":"green","sky":"forest"}  
Output: "green ocean deep forest"
```

---

### **substrCount**  
Write a function `substrCount` to count how many times a substring occurs within
a larger string.

Don't use in-built function that works same as `substrCount` function.


**Example:**  
```
Input: "one two one three one", substring="one"  
Output: 3
```

---

### **reverseWords**  
Write a function `reverseWords` to reverse the entire word sequence in the provided sentence without reversing individual letters.

Don't use in-built function that works same as `reverseWords` function.


**Example:**  
```
Input: "Hello there general"  
Output: "general there Hello"
```

---

### **wordWrap**  
Write a function `wordWrap` to format the input string so each line contains no more than the specified maximum width, breaking at word boundaries.

Don't use in-built function that works same as `wordWrap` function.

**Example:**  
```
Input: "Wrap it nicely please", maxLength=9  
Output:
"Wrap it
nicely
please"
```

---

### **remove**  
Write a function `remove` to eliminate every instance of specified substrings from the provided input string.

Don't use in-built function that works same as `remove` function.

**Example:**  
```
Input: "apple orange apple grape", remove=["apple", "grape"]  
Output: " orange  "
```

---

### **padBoth**  
Write a function `padBoth` to pad the input string equally on both sides with a provided padding string until the specified length is achieved. If uneven, extra padding should go at the end.

Don't use in-built function that works same as `padBoth` function.

**Example:**  
```
Input: "50", length=7, padding="XY"  
Output: "XY50XYX"
```

---

### **afterLast** 
Write a function `afterLast` that returns the substring occurring after the last occurrence of a specified substring. Return empty if substring is not found.

Don't use in-built function that works same as `afterLast` function.

**Example:**  
```
Input: "Folder/SubFolder/File.txt", substring="/"  
Output: "File.txt"
```

---

### **beforeLast**
Write a function `beforeLast` that returns the substring that appears before the last occurrence of a specified substring.

Don't use in-built function that works same as `beforeLast` function.

**Example:**  
```
Input: "User/Profile/Settings", substring="/"  
Output: "User/Profile"
```
