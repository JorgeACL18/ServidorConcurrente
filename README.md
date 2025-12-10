# Trabajo 28: Servidor Concurrente
Para este trabajo, tuvimos que modificar el código del anterior trabajo (tarea 27) para que este permita la conexión a más de un cliente.

---

### Servidor
A comparación del servidor del trabajo 37, en este tenemos que hacer un hilo para permitir la conexión a más de un cliente al mismo tiempo.

<img width="963" height="1036" alt="Captura de pantalla 2025-12-10 163621" src="https://github.com/user-attachments/assets/ee1781a6-6c72-4d43-804f-e5486d0ebc3e" />

---

### Cliente
El código del cliente se mantiene igual al que utilizamos anteriormente, sólo que habría que duplicarlo para probar el servidor y ver si puede conectar los dos al mismo tiempo.

<img width="810" height="920" alt="Captura de pantalla 2025-12-10 163700" src="https://github.com/user-attachments/assets/261172cf-5702-4419-bf3c-d8566a93c607" />
<img width="810" height="920" alt="Captura de pantalla 2025-12-10 163716" src="https://github.com/user-attachments/assets/e081c902-3a5e-4f5f-8a03-5c665a9b3edc" />

---

### Resultados
Lo últmo que queda por haer es probar que el servidor permite la conexión de varios clientes.

Primero, ejecutamos el servidor:

<img width="345" height="189" alt="Captura de pantalla 2025-12-10 172838" src="https://github.com/user-attachments/assets/8b2237af-e3c2-4e7c-b546-5466bbb20b9a" />


Después, el primer cliente. Veremos que se conecta al servidor:

<img width="361" height="245" alt="Captura de pantalla 2025-12-10 172854" src="https://github.com/user-attachments/assets/a6275bdd-2aa1-4e14-9cbc-dc9a99d6b850" />
<img width="361" height="241" alt="Captura de pantalla 2025-12-10 172903" src="https://github.com/user-attachments/assets/a6d01b08-82b4-4764-b6cf-2fc848cebdb4" />


Y ahora conectamos el segundo cliente:

<img width="472" height="247" alt="Captura de pantalla 2025-12-10 172914" src="https://github.com/user-attachments/assets/d470b177-1a3b-4d21-9b9f-aaa5ef15af4c" />
<img width="478" height="247" alt="Captura de pantalla 2025-12-10 172923" src="https://github.com/user-attachments/assets/0aa54c9e-de26-4ba0-96ed-ee43d6fcc6f5" />


Como ya tenemos los clientes conectados, podemos probar enviando un mensaje al servidor y ver que funciona correctamente.

<img width="359" height="253" alt="Captura de pantalla 2025-12-10 172942" src="https://github.com/user-attachments/assets/2a2d909c-598b-4df4-8876-68395a4f8d45" />
<img width="463" height="251" alt="Captura de pantalla 2025-12-10 173001" src="https://github.com/user-attachments/assets/540281c2-c20e-43bd-b92a-7e6811f7405a" />
<img width="470" height="258" alt="Captura de pantalla 2025-12-10 173015" src="https://github.com/user-attachments/assets/aa64b6c9-582a-4568-9b61-e22dc9fe603a" />

Por último, tenemos que ver si, escribiendo "adios", la conexión con el cliente se cierra.
- Cliente 1:

<img width="652" height="297" alt="Captura de pantalla 2025-12-10 173030" src="https://github.com/user-attachments/assets/f31cf570-8db7-459b-820d-5d0ef242b794" />


- Cliente 2:

<img width="653" height="340" alt="Captura de pantalla 2025-12-10 173042" src="https://github.com/user-attachments/assets/6748f64a-6c5c-495c-8028-63d5ed79e8c8" />







