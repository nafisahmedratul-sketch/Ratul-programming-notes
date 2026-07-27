# 🐍 পাইথন ফান্ডামেন্টালস চিট শিট (Python Fundamentals Cheat Sheet)

গিটহাব (GitHub) রেপোজিটোরির জন্য সম্পূর্ণ বাংলায় সাজানো পাইথনের বেসিক চিট শিট।

---

## 📌 সূচিপত্র (Table of Contents)
1. ইনভাইরনমেন্ট ও প্রথম প্রোগ্রাম
2. ভ্যারিয়েবল ও ডাটা টাইপ
3. টাইপ কাস্টিং
4. ইনপুট ও আউটপুট
5. অপারেটরস
6. কন্ডিশনাল স্টেটমেন্ট
7. লুপ (Loops)
8. ডাটা স্ট্রাকচার
9. ফাংশন (Functions)

---
২. ভ্যারিয়েবল ও ডাটা টাইপ <br>
পাইথনে ডাটা সংরক্ষণ করার প্রধান টাইপসমূহ:<br>
String (লেখা/টেক্সট): ---name = "Ratul"<br>
Integer (পূর্ণসংখ্যা): ---age = 20<br>
Float (দশমিক সংখ্যা):--- gpa = 3.85<br>
Boolean (সত্য/মিথ্যা): ---is_active = True<br>
**example**
```python
1. x = "10"              # স্ট্রিং (String)<br>
2. y = int(x)            #ইন্টিজার (Integer): 10<br>
3. z = float(x)          # ফ্লোট (Float): 10.0<br>
4. str_val = str(100)    #স্ট্রিং (String): "100"<br>
```
৫. অপারেটরস🔹 
গাণিতিক অপারেটর (Arithmetic Operators):<br>
*(যোগ): 10 + 3 $\rightarrow$ 13 <br>
*(বিয়োগ): 10 - 3 $\rightarrow$ 7<br>
*(গুণ): 10 * 3 $\rightarrow$ 30<br>
*(ভাগ): 10 / 3 $\rightarrow$ 3.333...<br>
*(ফ্লোর ডিভিশন - পূর্ণসংখ্যা): 10 // 3 $\rightarrow$ 3<br>
*(ভাগশেষ/মডুলাস): 10 % 3 $\rightarrow$ 1<br>
*(পাওয়ার/ঘাত): 10 ** 3 $\rightarrow$ 1000<br><br>
**example**<br>
```python
marks = int(input("মার্কস লিখুন: "))

if marks >= 80:
    print("গ্রেড: A+")
elif marks >= 70:
    print("গ্রেড: A")
elif marks >= 40:
    print("গ্রেড: Pass")
else:
    print("গ্রেড: Fail")
```
