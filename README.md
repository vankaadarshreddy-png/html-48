numbers = [i**2 if i % 2 == 0 else i**3 for i in range(1, 11)]
print("Squares (even) & Cubes (odd):", numbers)
2️⃣ Multiplication Table (1–3 × 1–3)
python
table = [[i * j for j in range(1, 4)] for i in range(1, 4)]
print("Multiplication Table (1–3):", table)
3️⃣ Extract Vowels from "Python"
python
vowels = [ch for ch in "Python" if ch.lower() in "aeiou"]
print("Vowels in 'Python':", vowels)
4️⃣ ASCII Values for "ABC"
python
ascii_values = [ord(ch) for ch in "ABC"]
print("ASCII values of 'ABC':", ascii_values)
5️⃣ Uppercase Alphabets A–Z
python
alphabets = [chr(i) for i in range(65, 91)]
print("Uppercase A–Z:", alphabets)
6️⃣ Capitalize Every Word in "hello world python"
python
words = [word.capitalize() for word in "hello world python".split()]
print("Capitalized words:", words)
7️⃣ Print "Even" or "Odd" for Numbers 1–10
python
labels = ["Even" if i % 2 == 0 else "Odd" for i in range(1, 11)]
print("Even/Odd labels:", labels)
