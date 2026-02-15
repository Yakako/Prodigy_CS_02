# 🖼 Simple Image Encryption Tool

## 📌 Task-02

A Python-based image encryption tool that encrypts and decrypts images using pixel manipulation techniques.

---

## 🎯 Objective

Develop a program that:

- Encrypts an image using pixel-level operations
- Decrypts the image back to its original form
- Uses a mathematical key-based transformation
- Saves encrypted and decrypted outputs

---

## 🛠 Technologies Used

- Python 3
- NumPy
- Pillow (PIL)
- Modular arithmetic


---

## 🧠 How It Works

### 🔐 Encryption

Each pixel value is modified using:

```
Encrypted Pixel = (Original Pixel + Key) % 256
```

### 🔓 Decryption

```
Decrypted Pixel = (Encrypted Pixel - Key) % 256
```

Because of modular arithmetic, the operation is reversible.

---

## 📸 Example

Input Image → `sample.jpg`  
Encrypted Output → `encrypted.png`  
Decrypted Output → `decrypted.png`

---

## 📈 Skills Demonstrated

✔ Image processing  
✔ Pixel manipulation  
✔ Encryption logic  
✔ Modular arithmetic  
✔ NumPy operations  
✔ File handling  


---

## 👩‍💻 Author

- Name: Pruonh Kimliya
- Email: kimliyapruonh@gmail.com
