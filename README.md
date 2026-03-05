# Telegram Bot con Spring Boot 🤖

Este proyecto implementa un **bot de Telegram utilizando Spring Boot** y la librería de Telegram Bots para Java.  
El bot permite recibir mensajes desde Telegram y responder a los usuarios automáticamente.

## 🚀 Tecnologías utilizadas
- Java 21
- Spring Boot
- Maven
- Telegram Bots API
- Git & GitHub

## 📂 Estructura del proyecto

TelegramBot
│
├── src
│   ├── main
│   │   ├── java
│   │   └── resources
│   │       └── application.properties
│   │
│   └── test
│
├── pom.xml
├── mvnw
├── mvnw.cmd
└── README.md

## ⚙️ Configuración

Para ejecutar el bot es necesario obtener un **Token de Telegram**.

### Crear un bot en Telegram
1. Abrir Telegram
2. Buscar **@BotFather**
3. Ejecutar el comando:

/newbot

4. Asignar un nombre y username al bot
5. BotFather entregará un **TOKEN**

## 🔐 Seguridad

El token del bot **NO debe subirse al repositorio**.

Ejemplo de variables de entorno:

TELEGRAM_BOT_TOKEN=TU_TOKEN_AQUI  
TELEGRAM_BOT_USERNAME=TU_USERNAME

## ▶️ Ejecutar el proyecto

Clonar el repositorio:

git clone https://github.com/tu-usuario/TelegramBot.git

Entrar al proyecto:

cd TelegramBot

Ejecutar la aplicación:

mvn spring-boot:run

## 🧪 Prueba del bot

1. Abrir Telegram
2. Buscar el bot
3. Presionar **Start**
4. Enviar mensajes al bot

## 📸 Evidencias

El repositorio incluye capturas de:
- Implementación del bot
- Ejecución del proyecto
- Interacción en Telegram

## 👨‍💻 Autor

Proyecto desarrollado como práctica de integración entre **Spring Boot y Telegram Bot API**.