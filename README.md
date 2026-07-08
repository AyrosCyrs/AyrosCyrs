# ¡Hola! Soy Claudia (Ayros)

Soy estudiante de Ciencias de la Computación en la Facultad de Ciencias, UNAM (graduación estimada: 2027), y parte activa del club de Ciberseguridad de la Facultad de Ingeniería, UNAM — ahí no solo aprendo, también doy clases: he impartido temas como introducción a redes, reconocimiento activo, OWASP Top 10, análisis de correos maliciosos y análisis de binarios/malware.

Me gusta entender las cosas de punta a punta, no solo que funcionen. Por eso este perfil no es solo una lista de proyectos — es más bien el mapa de cómo he ido construyendo criterio propio: desde estructuras de datos, pasando por compiladores hechos desde cero, hasta pentesting real bajo NDA.

## Lo que me apasiona

- **Ciberseguridad ofensiva y defensiva** — análisis de malware con ingeniería inversa (Ghidra, VirusTotal), metodologías de pentesting, análisis de correos de phishing
- **Diseño de software con criterio, no solo código que funcione** — patrones de diseño, arquitectura de compiladores, buenas prácticas
- **RF y hardware hacking** — empecé este año en Pwnterrey 2026 y me atrapó por completo: WiFi scanning, BLE, GPS wardriving
- **Idiomas** — voy por mi JLPT N3 en diciembre 2026, después de 7 niveles de japonés en la ENALLT; inglés fluido; ruso y chino como meta a futuro
- **Enseñar lo que aprendo** — creo que explicar algo a alguien más es la mejor forma de comprobar que de verdad lo entendiste

## Con qué trabajo

**Lenguajes:** `Java` `Python` `Kotlin` `C` `Solidity` `Haskell` (ocasional)
**Frameworks/Herramientas:** `Django` `Flask` `Flex/Bison` `Kali Linux` `Ghidra`
**Ahora mismo aprendiendo a profundidad:** pandas, scikit-learn y fundamentos de ML/LLMs

---

## Ciberseguridad

### [cyber-dojo](https://github.com/AyrosCyrs/cyber-dojo)
Bitácora de writeups de CTFs y laboratorios (HackTheBox, echoCTF). Documento la metodología completa: desde el reconocimiento inicial hasta el análisis con Ghidra de binarios maliciosos reales, como en mi writeup de **Lupin**, donde rastreo el comportamiento de un clipper de criptomonedas (familia Phorpiex) paso a paso.

---

## Compiladores y Lenguajes de Programación

Esta es probablemente el área donde más me gusta meterme a fondo — construir un lenguaje desde cero te obliga a entender realmente cómo funciona todo lo demás por debajo.

### [ProyectoCompilador](https://github.com/AyrosCyrs/ProyectoCompilador)
Compilador construido de cero en Java a lo largo de un semestre completo: expresiones regulares → autómatas (NFA/DFA) → parsers LL(1) y LALR(1). Fue mi introducción real a cómo una computadora "entiende" código.

### [PigmentaCompiler](https://github.com/AyrosCyrs/PigmentaCompiler)
Mi proyecto más ambicioso y personal: un lenguaje experimental donde el código se representa mediante colores — literalmente puedes "pintar" un programa. Conservo dos versiones que muestran mi evolución de diseño: la primera traduce colores directamente a instrucciones; la segunda sigue la arquitectura clásica de un compilador real (Lexer → Parser → AST → Análisis semántico). Sigo trabajando en él — la meta a futuro es ocultar código real dentro de imágenes que se vean como arte genuino, usando esteganografía.

### [Analizador-Yacc-Bison](https://github.com/AyrosCyrs/Analizador-Yacc-Bison)
Analizador léxico y sintáctico construido con Flex y Bison en C — mi primer acercamiento a estas herramientas clásicas de construcción de compiladores.

---

## Patrones de Diseño y Algoritmos

### [Practicas-Patrones-Diseno](https://github.com/AyrosCyrs/Practicas-Patrones-Diseno)
Repositorio vivo donde practico patrones de diseño en Java resolviendo problemas reales (por ahora, Decorator y Adapter con un sistema de restaurante). Lo sigo alimentando por mi cuenta, más allá de lo que pide cualquier clase — quiero dominar esto a fondo.

### [Analisis-de-Algoritmos](https://github.com/AyrosCyrs/Analisis-de-Algoritmos)
Algoritmos de ordenamiento (Insertion, Selection, Bubble, Counting, Merge, Quick Sort) y teoría de gráficas, implementados en Java **y** Python en paralelo, para comparar cómo cambia el mismo razonamiento entre lenguajes.

---

## Aplicaciones

### [Fodify](https://github.com/AyrosCyrs/Fodify)
Mi primera app de Android completa con Android Studio: un menú digital para restaurante, con login funcional y navegación por categorías. Kotlin de principio a fin.

### [nubesDeAlgodon](https://github.com/AyrosCyrs/nubesDeAlgodon)
Tienda en línea con Django, hecha por mi cuenta para practicar backend más allá de lo que pedía la clase.

### [Karen-Luis_Wedding](https://github.com/AyrosCyrs/Karen-Luis_Wedding)
La invitación digital de la boda de mi hermana — pero le metí seguridad real: tokens únicos por invitado, contraseñas con SHA-256, mitigaciones XSS y tracking de confirmaciones vía Google Sheets/Apps Script. Un proyecto personal donde uní cariño familiar con mis habilidades de seguridad.

---

## Proyectos en Equipo Destacados

### [Nyx Valley (Equipo Ada)](https://github.com/AyrosCyrs/Ada)
_(fork del [repo original](https://github.com/AlanKevinCT/Ada))_

Proyecto de la materia de Ingeniería de Software donde simulamos ser una empresa de software real, usando Trello para gestión ágil de tareas — de principio a fin, no solo el código.

**Mi rol (Backend):**
- Diseñé y construí toda la estructura del backend en Django
- Implementé completamente el mapa interactivo con Leaflet.js
- Creé un sistema de 6 temas visuales (claros y oscuros) en CSS puro
- Adapté los estilos de todas las páginas del sitio para que coincidieran correctamente con el tema activo en cada momento

### [TrustID & WavyLend](https://github.com/AyrosCyrs/oracle-wavylend-trustid)
_(fork del [repo original](https://github.com/EstradaRubi/oracle-wavylend-trustid))_

Construido en el Hackathon Avalanche LatAm sin experiencia previa en blockchain — diseñé e implementé los contratos inteligentes en Solidity y el flujo completo (RFC → score → blockchain), junto con mi compañera Rubí Estrada, en menos de 40 horas.

### [MusicApp](https://github.com/AyrosCyrs/MusicApp)
Gestor de colecciones musicales en Java con persistencia de datos binaria y validaciones robustas. Trabajado junto a dos compañeros de mi materia de Modelado y Programación.

---

## Redes de Computadoras
Prácticas de la materia, cubriendo desde servidores Flask en la capa de aplicación hasta infraestructura real (servidores propios con OMV, Samba/NFS, VPN con ZeroTier) y criptografía aplicada con OpenSSL. *Subiendo pronto.*

---

## Hacia dónde voy

A mediano plazo quiero profundizar en desarrollo full-stack (Django, Spring Boot), seguir compitiendo y aprendiendo en el mundo de RF/hardware hacking, y eventualmente hospedar mi propio homelab.

## Contacto
- LinkedIn: [Claudia Osorio](https://www.linkedin.com/in/claudia-osorio-803b97318/)

---
*Este perfil está en construcción — voy subiendo proyectos poco a poco* 🚧
