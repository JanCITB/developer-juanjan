# **Developer Docker Image**
---

## **🚀 Com utilitzar-lo**

### **1️⃣ Clonar el repositori**
```bash
git clone https://github.com/your_user/developer-docker-image.git
cd developer-docker-image
```

### **2️⃣ Construir la imatge**
```bash
docker build -t your_user/developer .
```

### **3️⃣ Executar el contenidor**
```bash
docker run -d --name dev-container -p 5900:5900 -p 2223:22 your_user/developer
```

### **4️⃣ Accedir a l'entorn**

📌 **Via VNC Viewer**: Connecta't a `localhost:5900` amb la contrasenya definida al Dockerfile.  
📌 **Via SSH**:  
```bash
ssh developer@localhost -p 2223
```

### 📌 Archivos:
He añadido al git-hub developer-juanjan los archivos que he utilizado.

---
