# 🐍 Basi Application development using Python

---

## class-1
programminng python
```py
import tkinter as tk
from tkinter import messagebox, ttk

# সাবমিট বাটনের কাজ
def Ratul():
    name = entry_name.get()
    father = entry_father.get()
    mother = entry_mother.get()
    gender = gender_var.get()
    phone = entry_phone.get()
    email = entry_email.get()
    
    if not name or not phone:
        messagebox.showerror("দয়া করে অন্তত নাম এবং মোবাইল নম্বর লিখুন!")
    else:
        messagebox.showinfo(f"ধন্যবাদ {name} ")

# উইন্ডো তৈরি
root = tk.Tk()
root.title("Class 1")
root.geometry("650x650")
root.config(bg="#007afc")


root.mainloop()
```
