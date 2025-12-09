# AetherDragon-Grafika-Komputer

## 👤 Team
- Rafif Fawwaz Kartika ( RKA 009)
- Dimas Ahmad Satrio Wicaksono ( RKA 015)
- Naufal Humam Maulana ( RKA 022)



https://github.com/user-attachments/assets/c9f26f40-30bb-4504-9f93-6c15213cad5a



# 🐉 Little Dragon AR
Little Dragon AR adalah aplikasi Augmented Reality yang menampilkan naga 3D interaktif menggunakan EasyAR. Pengguna dapat memunculkan telur naga di dunia nyata, melihat proses penetasan, serta menikmati animasi naga lengkap dengan serangan fireball dan kontrol kamera.

### 🧠 Penerapan AI
Inti dari pengalaman Augmented Reality (AR) pada **AetherDragon** dibangun menggunakan teknologi *Computer Vision* tingkat lanjut untuk memastikan interaksi yang *seamless* antara objek virtual dan dunia nyata:

* **Environmental Understanding (SLAM):** Menggunakan algoritma *Simultaneous Localization and Mapping* untuk memetakan lingkungan fisik secara *real-time*. Sistem memproses *feed* kamera untuk melacak posisi perangkat (6DoF tracking) relatif terhadap lingkungan.
* **Plane Detection:** Algoritma AI mendeteksi kluster titik fitur (*feature points*) pada permukaan horizontal (seperti meja atau lantai) untuk menghasilkan *anchor* yang stabil. Ini memungkinkan karakter Naga untuk ditempatkan dan "berdiri" di atas permukaan nyata tanpa bergeser.
* **Real-time Pose Estimation:** Memastikan orientasi dan skala objek virtual tetap konsisten mengikuti pergerakan kamera pengguna.


## ✨ Fitur Utama

### 🔹 1. AR Tracking (EasyAR)
- Deteksi permukaan (plane detection)  
- Penempatan telur dan naga secara akurat di dunia nyata  
- Tracking stabil mengikuti pergerakan kamera  

### 🔹 2. Dragon Lifecycle
- Telur muncul di permukaan yang terdeteksi  
- Animasi telur pecah  
- Naga keluar dan langsung masuk pose idle  

### 🔹 3. Animasi Naga Lengkap
Menggunakan Malbers Animations:
- Idle  
- Walk  
- Roar  
- Attack  
- Hit Reaction  
- Wings Flap  

### 🔹 4. Fireball Attack
- Naga menembakkan fireball dari mulut  
- Efek partikel & suara  
- Arah fireball mengikuti arah kepala naga  

### 🔹 5. Kontrol UI & Kamera
- Tombol Zoom In / Zoom Out  
- Tombol Start / Stop  
- Rotate dragon menggunakan gesture (LeanTouch)  
- UI responsif untuk mobile  

### 🔹 6. Audio Effects
- Suara sayap  
- Roar naga  
- Efek ledakan api  
- Footsteps dan ambience  

### 🔹 7. Build Mobile (Android)
- Dibangun dengan Unity 2022.3 LTS  
- Kompatibel Android menggunakan EasyAR & ARCore  

## 📦 Struktur Project (Ringkas)
Assets/
│── EasyAR/
│── LeanTouch/
│── Malbers Animations/
│── Prefabs/
│── Resources/
│── Scenes/
│── Scripts/
│── UI/
│── Virtual Joystick Pack/

## 🚀 Cara Menjalankan Project
1. Install Unity 2022.3 LTS  
2. Import EasyAR Sense SDK   
3. Buka scene: AR Scene  
4. Build ke Android  
5. Arahkan kamera → telur muncul → naga menetas  

## 🎥 Demo Singkat
- Telur muncul di AR  
- Telur retak dan naga keluar  
- Animasi idle, roar, attack  
- Fireball dengan efek  
- Kontrol zoom & rotasi kamera  

## 🛠 Teknologi yang Digunakan
- Unity 2022.3 LTS  
- EasyAR Sense  
- ARCore  
- LeanTouch  
- Unity UI  
- Particle System  
