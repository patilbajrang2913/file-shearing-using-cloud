
# ⚡ Quantum File Share

**Quantum File Share** is a futuristic, stylish, and secure web-based file sharing application. It allows users to upload files, generate a unique share code, and download the files later using the code. It supports multiple files, password protection, expiration settings, and QR code sharing.



---

## 🚀 Features

- 🎯 Drag-and-drop file uploads
- 🔒 Optional password protection
- ⏳ Auto-expiring download links (e.g., 24h)
- 📦 Multiple file support with individual or batch download
- 🔗 Share code generation & copy button
- 📱 QR code generation for easy mobile sharing
- 🧠 Web Share API support (if available)
- 💡 Fully responsive, animated futuristic UI
- 🎵 Sound effects for actions (can be muted)
- 🌙 Dark theme with glowing neon gradients
- 🧪 Built with [Appwrite](https://appwrite.io/) as the backend

---

## 🧰 Tech Stack

- **Frontend**: HTML, CSS (custom), JavaScript
- **Backend**: [Appwrite](https://appwrite.io/) – File storage & permission management
- **QR Codes**: [QRCode.js](https://github.com/davidshimjs/qrcodejs)
- **Icons**: Font Awesome 6

---

## 📦 Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/quantum-file-share.git
cd quantum-file-share
````

### 2. Configure Appwrite

1. Set up a free Appwrite instance (or use [Appwrite Cloud](https://cloud.appwrite.io)).
2. Create a project and get:

   * **Project ID**
   * **API Endpoint**
   * **Bucket ID** (for file storage)
3. Enable **read permissions** on your bucket.

### 3. Update Appwrite settings

Edit your `share.html` or project config:

```js
.setEndpoint("https://<your-endpoint>/v1")    // ← Replace with your endpoint
.setProject("<your-project-id>");             // ← Replace with your project ID
const BUCKET_ID = "<your-bucket-id>";         // ← Replace with your bucket ID
```

---

## 🧪 Testing

Open `share.html` in your browser. Test:

* File drag-drop & upload
* Generating and using share code
* Download via link or QR
* Expired file logic
* Password protection toggle
* Multi-file upload behavior

---



## 🛡️ Security Notes

* Files are publicly accessible if shared (via read permission).
* Always use password protection for sensitive files.
* Consider adding user login in future updates.

---

## 📜 License

MIT © [Bajrang patil](https://github.com/patilbajrang2913)

---

## 💬 Feedback & Contributions

Feel free to open issues or submit pull requests if you’d like to contribute!

> Built with 💙 using futuristic design + Appwrite + QR Codes + secure cloud storage.

```


