# CarryCARI
![Frame 1](https://user-images.githubusercontent.com/54930877/151214445-027c87e3-d8c5-4cbc-aac9-7cec41e1e20d.jpg)
![151363026-4966f45c-4758-496f-bc26-aac1af291a63](https://user-images.githubusercontent.com/54930877/177606805-bb6f6c1d-e127-4cff-a776-492ab6085c5c.gif)

## Index
- [Lego2me](#lego2me)
  - [1. Prerequisites](#1-prerequisites)
  - [2. Installation Process](#2-installation-process)
  - [3. Getting Started](#3-getting-started)
  - [4. File Manifest](#4-file-manifest)
  - [5. Copyrights / End User Licesnse](#5-copyrights--end-user-licesnse)
  - [6. Contact Information](#6-contact-information)

## 1. Architecture
- https://flagly.org/
### **Architecture**
![image](https://user-images.githubusercontent.com/54930877/151213519-4f122273-bca5-47b4-99e2-2f0aeb5b05f5.png)

## 2. Installation Process
- Requires a computer with an nvidia GPU.
```
$ git clone https://github.com/sung1san3/Lego2me
$ docker-compose up --build
```
## 3. Getting Started
- If you are running in a local environment, type localhost in the Internet browser address.
- Click the 'get started' button at the top and upload a picture of yourself you want to make into a LEGO character. After editing the top and bottom, save and check the result.
![image](https://user-images.githubusercontent.com/54930877/151208137-9c34e377-4610-4d8c-b839-d198c4f57447.png)
- Check out the results and try customizing your character!
- Please leave a review for the results
![image](https://user-images.githubusercontent.com/54930877/151210758-16a7822d-d600-4cdd-abd8-1bb283b2606b.png)
![image](https://user-images.githubusercontent.com/54930877/151211337-11d81eed-b686-44a6-96b9-16c7bb6d9935.png)


## 4. File Structure
```
📦CarryCARI
 ┣ 📂_media
 ┃ ┣ 📂result_images
 ┃ ┗ 📂user_images
 ┣ 📂assets
 ┃ ┣ 📂user_image_latent
 ┃ ┗ 📂result_image_clip
 ┣ 📂cari
 ┃ ┣ 📂migration
 ┃ ┣ 📜admin.py
 ┃ ┣ 📜apps.py
 ┃ ┣ 📜models.py
 ┃ ┣ 📜serializers.py
 ┃ ┣ 📜tests.py
 ┃ ┣ 📜urls.py
 ┃ ┣ 📜views.py
 ┃ ┗ 📜__init__.py
 ┣ 📂CarryCARI_prj
 ┃ ┣ 📜asgi.py
 ┃ ┣ 📜settings.py
 ┃ ┣ 📜urls.py
 ┃ ┣ 📜wsgi.py
 ┃ ┗ 📜__init__.py
 ┣ 📂ml
 ┃ ┣ 📂StyleCLIP-pytorch
 ┃ ┣ 📂StyleCariGAN
 ┃ ┗ 📜ai.py
 ┣ 📂venv
 ┣ 📜db.sqlite3
 ┣ 📜manage.py
 ┗ 📜README.md
```

## 5. Contact Information

| Name    | 김소민                                         |김유진                                | 이진경                                         | 이주현                                  | 임연우                                    |
| ------- | --------------------------------------------- | ------------------------------------ | --------------------------------------------- | --------------------------------------- |--------------------------------------- |
| role    | <br>Backend Developer                | Backend Developer                         | AI, Backend Developer                                 | Frontend Developer |AI
| Github  | [@thals1214](https://github.com/thals1214) | [@Yujin-nKim](https://github.com/Yujin-nKim) | [@dooli1971039](https://github.com/dooli1971039) | [@JulieOnIsland](https://github.com/JulieOnIsland) |[@Lim-YeonWoo](https://github.com/Lim-YeonWoo) |
