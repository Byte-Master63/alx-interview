# 0x04. UTF-8 Validation

## 📚 Description

This project is part of the **ALX Software Engineering curriculum**, under the **Interview Preparation** track. The goal is to implement a method that validates whether a given list of integers correctly represents a valid UTF-8 encoding.

UTF-8 is a variable-length character encoding for Unicode, and this project helps you understand how multi-byte characters are encoded and decoded in a byte stream.

---

## 📌 Learning Objectives

By the end of this project, you should be able to:

- Understand the basics of **UTF-8 encoding**.
- Parse and validate multi-byte character sequences.
- Use **bitwise operations** effectively in Python.
- Handle edge cases in encoding schemes.

---

## 🧠 Background Context

UTF-8 is the most common encoding for the web and supports all Unicode characters. It uses 1 to 4 bytes to encode characters:

- **1-byte** character: `0xxxxxxx`
- **2-byte** character: `110xxxxx 10xxxxxx`
- **3-byte** character: `1110xxxx 10xxxxxx 10xxxxxx`
- **4-byte** character: `11110xxx 10xxxxxx 10xxxxxx 10xxxxxx`

The goal is to verify if a given list of integers (0-255), where each integer represents a byte, conforms to the UTF-8 encoding rules.

---

## 🛠️ Project Requirements

- Language: **Python 3**
- No use of external libraries unless specified.
- Your code should pass all test cases provided.
- Must follow **PEP8** style guidelines.

---

## 🚀 Usage

### Function Prototype

```python
def validUTF8(data: List[int]) -> bool:
    """
    Determines if a given list of integers represents a valid UTF-8 encoding.

    Args:
        data (List[int]): A list of integers representing bytes (0 <= val <= 255)

    Returns:
        bool: True if data is a valid UTF-8 encoding, else False
    """

