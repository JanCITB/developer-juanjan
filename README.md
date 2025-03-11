Developer Docker Image
Aquest repositori conté un Dockerfile per crear una imatge Docker d'un entorn de desenvolupament amb VNC, Visual Studio Code i Python.

📌 Característiques
✅ Ubuntu 24.04 amb entorn XFCE4
✅ Servidor VNC per accedir a l'escriptori remot
✅ Visual Studio Code preinstal·lat
✅ Python & Flask per a desenvolupament
✅ Client psql per connectar-se a PostgreSQL
✅ Servidor SSH per accedir al contenidor

🚀 Com utilitzar-lo
1️⃣ Clonar el repositori
bash
Copiar
Editar
git clone https://github.com/your_user/developer-docker-image.git
cd developer-docker-image
2️⃣ Construir la imatge
bash
Copiar
Editar
docker build -t your_user/developer-env .
3️⃣ Executar el contenidor
bash
Copiar
Editar
docker run -d --name dev-container -p 5900:5900 -p 2223:22 your_user/developer-env
4️⃣ Accedir a l'entorn
📌 Via VNC Viewer: Connecta't a localhost:5900 amb la contrasenya definida al Dockerfile.
📌 Via SSH:

bash
Copiar
Editar
ssh developer@localhost -p 2223
