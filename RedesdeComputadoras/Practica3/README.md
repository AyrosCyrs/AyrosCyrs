# Práctica 03 - Certificados Digitales con OpenSSL

Materia: Redes de Computadoras — Facultad de Ciencias, UNAM

**Práctica realizada en equipo.** Créditos a mis compañeros de equipo: 
- Blancas Peralta Alejandro
- Dromundo Escobedo Antonio Sebastian
- Giron Jimenez Emmanuel

## Objetivo

Comprender cómo funcionan los certificados digitales y las firmas digitales, y crear un certificado digital propio usando OpenSSL, incluyendo una Autoridad Certificadora (CA) autofirmada.

## Qué se hizo

1. **Cifrado simétrico:** cifrado y descifrado de un archivo usando Triple DES (3DES) con derivación de llave mediante PBKDF2
2. **Autoridad Certificadora (CA):** creación de una CA autofirmada con llave RSA de 2048 bits, siguiendo el estándar de certificados X.509
3. **Solicitud de certificado (CSR):** generación de una llave privada y una solicitud de certificado
4. **Firma del certificado:** firma de la solicitud usando la CA creada, generando un certificado válido
5. **Verificación:** inspección del certificado generado y verificación externa con una herramienta en línea

## Conceptos clave

- **Firma digital:** garantiza autoría e integridad de un documento mediante criptografía asimétrica
- **Certificado digital:** un tercero confiable (CA) vincula una identidad con una llave pública
- **X.509:** estándar que define la estructura de los certificados digitales usados en HTTPS/TLS

## Aprendizajes

Trabajar con OpenSSL en distintos entornos (Ubuntu, Debian y WSL) ayudó a entender que, aunque cambie el sistema operativo, el proceso de creación y firma de certificados es el mismo. Esta práctica ayudó a entender qué pasa exactamente detrás del candado de un sitio HTTPS.

## Evidencia

Ver capturas del proceso en la carpeta [`capturas/`](./capturas).