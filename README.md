# 📟 Tarea #5 - Agenda Multicapas con Node.js y Express

¡Hola! Soy **Christian Gil** 👋

📌 **Matrícula:** 2012-1036  
📚 **Materia:** Programación Web  
👨‍🏫 **Profesor:** Raydelto Hernández Perera  
🏫 **Institución:** ITLA  

## 📲 Descripción

Esta tarea consiste en el desarrollo de un servicio Web utilizando Node.js y la librería Express. Decidí crear un frontend para consumir este backend en cual permite a los usuarios almacenar y visualizar contactos de manera organizada y eficiente. El backend se conecta con una API externa para obtener y registrar contactos en tiempo real, facilitando la gestión de la información.

La web app cuenta con una interfaz sencilla y funcional, optimizada para brindar una experiencia fluida en la navegación y la manipulación de los datos.

✨ Características:

- ✅ **Gestión de Contactos** 📋 – Permite registrar nuevos contactos almacenando nombre, apellido y número de teléfono.
- ✅ **Conexión con API** 🌐 – Utiliza la API de [raydelto.org](http://www.raydelto.org/agenda.php) para obtener y enviar datos mediante los métodos GET y POST.
- ✅ **Interfaz Amigable** 🎨 – HTML + CSS + JS vanilla, simple y directa al punto.
- ✅ **Servidor Express** 🚀 – Backend en Node.js con rutas bien definidas para listar y agregar contactos.
- ✅ **Manejo de Errores** ⚠️ – Si hay fallos en la API o problemas de conexión, se muestran mensajes de error amigables para informar al usuario.

Es la quineta y última tarea de la materia de Programación Web impartida por el profesor **Raydelto Hernández**.

---

## 📸 Capturas de Pantalla

A continuación, se muestran capturas de pantalla de las evidencias al realizar esta asignación:

1. ![Captura 1](/public/img/img1.png)
2. ![Captura 2](/public/img/img2.png)
3. ![Captura 3](/public/img/img3.png)
4. ![Captura 4](/public/img/img4-1.png)
5. ![Captura 4](/public/img/img5.png)
6. ![Captura 4](/public/img/img6.png)
7. ![Captura 4](/public/img/img7.png)

---

## 🚀 Instrucciones de Uso

1. 🛠️ Cloná este repositorio:

```bash
git clone https://github.com/chrisfelixgil/Tarea5-servicio-web.git
```

2. Instalá las dependencias:

```bash
npm install
```

3. Iniciá el servidor:

```bash
node index.js
```

4. Abrí tu navegador en:

```
http://localhost:3000
```

---

## 📡 Endpoints del backend

- `GET /contactos` → Lista los contactos obtenidos desde el servicio de Raydelto.
- `POST /contactos` → Agrega un nuevo contacto (nombre, apellido, teléfono).

---

## 🧱 Estructura del Proyecto

```
tarea5-servicio-web/
├── node_modules/
├── public/
│   ├── index.html
│   ├── style.css
│   ├── agenda/
│   │   ├── agenda.html
│   │   ├── agendaStyle.css
│   │   └── agendajs.js
│   └── img/
├── index.js
├── package.json
├── .gitignore
└── README.md
```

---

# 🚀 Tecnologías Utilizadas

A continuación, las principales tecnologías usadas en el desarrollo del proyecto, junto con sus respectivos logos para que no queden dudas:


![Node.js](https://commons.wikimedia.org/wiki/File:Node.js_logo.svg)

!Express.js

![Axios](https://commons.wikimedia.org/wiki/File:Axios_logo_%282020%29.svg)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)

![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

---

## 🙏 Créditos

Esta tarea fue desarrollada como parte de la materia de Programación Web impartida por el profesor **Raydelto Hernández** para el Instituto Tecnológico de Las Américas (ITLA).

---

## 📄 Licencia

Esta tarea se distribuye bajo la licencia MIT, lo que significa que podés utilizarlo, modificarlo y distribuirlo libremente.





