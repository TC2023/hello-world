# **GitHub Markdown Lesson 1**
For lesson 1, the goal is to learn how to format text using github flavor of markdown, creative lists (**numbered and bulletted**), create tables and add links and images to the document.

# **Simple Text**
Simple text is easy. Start with a new line and add your text.

## Second Level Header
You can add different levels of headers easily.

### **Third Level**

#### **Fourth Level**

##### **Fifth Level**

For creating **Bold** simply add ** before and after the characters.  
For creating ~~Strikethrough~~ add ~~ around text. Make sure not to leave **any spaces between text and these special characters**  
For creating *italics* simply use * or _ around text  
These can be combined around text \_\*\*text**_ to create _**italic bold**_

## **Lists**
The text in the previous section can be turned into list with bullets or numbers

### **As bulleted list**
* For creating **Bold** simply add ** before and after the characters.
* For creating ~~Strikethrough~~ add ~~ around text. Make sure not to leave **any spaces between text and these special characters**
* For creating *italics* simply use * or _ around text
* These can be combined to create _**italic bold**_

### **As numbered list**
1. For creating **Bold** simply add ** before and after the characters.
2. For creating ~~Strikethrough~~ add ~~ around text. Make sure not to leave **any spaces between text and these special characters**
3. For creating *italics* simply use * or _ around text
4. These can be combined to create _**italic bold**_

### **Task Lists**
- [x] Task 1
- [x] Task 2
- [x] Task 3
- [ ] Task 4 is not complete

## **Quotes**
Remember:
> **Markdown** has many flavors. For GitHub readme files, remember to use the related syntax.

## **Tables**
**c1** | **c2** | **c3**
-- | -- |--
a1 | b1 | c1
a2 | b2 | c2
a3 | b3 | c4

## **Python Code Example**

```python
import unittest

class TestSum(unittest.TestCase): 
  def test_list_int(self):
    """
    Test that it can sum a list of integers 
    """
    data = [1, 2, 3]
    result = sum(data) 
    self.assertEqual(result, 6)
    
 if __name__ == '__main__': 
  unittest.main()
```

## **Adding Links**
This link to [GitHub Markdown Reference](https://guides.github.com/features/mastering-markdown/) was created using the following syntax  

\[text](link)

## **Adding an Image from web**

![](https://www.conncoll.edu/media/website-media/visualidentity/images/Seal-Color.jpg)  

!\[Alt Text](url)
