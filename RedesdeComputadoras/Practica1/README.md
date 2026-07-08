# Práctica 01 - Explorando la capa de aplicación

Práctica de la materia de Redes de Computadoras (Facultad de Ciencias, UNAM), donde un equipo de 4 integrantes crea una red de 4 servidores Flask que se comunican entre sí en forma de ciclo (cada servidor le pasa el mensaje al siguiente).

**Este repositorio contiene el servidor que desarrollé individualmente** dentro de la práctica en equipo. Créditos a mis compañeros de equipo por el trabajo conjunto de diseño y pruebas:
- Blancas Peralta Alejandro
- Dromundo Escobedo Antonio Sebastian
- Giron Jimenez Emmanuel

## ¿Qué hace?

Cada servidor de la red:
1. Participa en una elección de "líder" (el servidor que inicia el proceso), usando un identificador único (UUID) para decidir quién empieza
2. Una vez elegido el líder, se envía un valor inicial (0) al siguiente servidor del ciclo
3. Cada servidor recibe el valor, le suma 1, y lo reenvía al siguiente
4. Cuando el valor llega a 50, el proceso se detiene y se notifica a todos los servidores del ciclo que el proceso terminó

## Tecnologías utilizadas

- **Python** y **Flask** — para crear el servidor web
- **python-decouple** — para separar la configuración (usuario, URL) del código
- **requests** — para que cada servidor le hable al siguiente
- **VS Code Tunnels / ngrok** — para exponer el servidor local a internet y conectarlo con los de mis compañeros

## Cómo ejecutarlo

1. Clona este repositorio
2. Crea un entorno virtual e instala las dependencias:
```bash
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
```
3. Copia `settings.ini.example` a `settings.ini` y ajusta los valores (tu nombre, y la URL de tu compañero siguiente en el ciclo)
4. Ejecuta el servidor:
```bash
python app.py
```
5. Expón tu servidor a internet con [ngrok](https://ngrok.com/) o un túnel de VS Code, para que tus compañeros puedan conectarse a él

## Contexto

Práctica realizada en equipo de 4, donde cada integrante desarrolló y ejecutó su propio servidor de forma independiente, coordinándose para formar la red en ciclo.