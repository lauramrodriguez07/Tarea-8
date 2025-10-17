# Tarea-8
Maquinas virtuales y comunicación entre ellas
### Instalación de maquina virtual de Rocky Linux

Proceso de configuración y reiniciación de la MV
<img width="1282" height="858" alt="image" src="https://github.com/user-attachments/assets/3a091718-f646-4ef9-bb88-d34f04b64f64" />
<img width="1282" height="858" alt="image" src="https://github.com/user-attachments/assets/f7f4f6be-1e56-49f9-8cdf-7e95d0b33301" />
<img width="1282" height="858" alt="image" src="https://github.com/user-attachments/assets/b0084414-f62c-43d3-9451-c67c6aa1f040" />

Con los comandos de (ip addr show) y (ping -c 3 8.8.8.8) se pudo visualizar su ip y ademas verificar si hay una conexión establecida
<img width="1282" height="858" alt="image" src="https://github.com/user-attachments/assets/822f7331-36a5-4a72-81b2-5228353c8fba" />

### Instalación de maquina virtual de Kali Linux

Se instalo y se abrio Kali Linux desde el terminal:
Tambien se visualiza al principio que no es booteable, entonces, lo que se hizo fue ibligarlo a iniciarce para iniciar su configuranción
<img width="1600" height="719" alt="image" src="https://github.com/user-attachments/assets/5095ef8d-a1f9-4352-a03c-e4b7d7daf9c4" />

Ya abierto Kali Linux y terminado su configuración de usuario, se verifico con los comandos de ip addr y ping -c 3 8.8.8.8, su coneccion a la red, como se puede observar a continuación:
<img width="1277" height="659" alt="image" src="https://github.com/user-attachments/assets/28344560-fc65-4562-9115-8e20c4c73153" />

### Instalación de maquina virtual de Windows

Se instalo y se abrio Windows desde el terminal
<img width="1600" height="868" alt="image" src="https://github.com/user-attachments/assets/9d9af0c4-3949-4d29-b078-8b261a5bf1b6" />
Se inicio con la configuracion de windows:
<img width="1600" height="868" alt="image" src="https://github.com/user-attachments/assets/b370beb6-ab0e-4616-a418-7981584fa022" />

Se selecciono el sistema operativo a instalar:
<img width="1600" height="909" alt="image" src="https://github.com/user-attachments/assets/a66b3093-5925-4bf3-95b7-25fd4b555a6c" />
<img width="1600" height="909" alt="image" src="https://github.com/user-attachments/assets/47a9411d-efcb-411f-94de-71618c9a718f" />

Se inicializo la mv
<img width="1316" height="949" alt="image" src="https://github.com/user-attachments/assets/8747d70a-0c2c-4148-9aec-9fdc36c497d2" />
<img width="1298" height="873" alt="image" src="https://github.com/user-attachments/assets/4ed7bfe8-dda6-4f91-999d-33d18ea64017" />

### Ademas se creo la red de bridge para la interconexión entre las tres MV
<img width="1600" height="195" alt="image" src="https://github.com/user-attachments/assets/9b198a40-ca20-4e3f-a30c-3f1d2b28acd5" />
<img width="1293" height="653" alt="image" src="https://github.com/user-attachments/assets/2ff0967e-2e5f-437b-8ff3-e13537ab240e" />

##### Se realizo la configuración de ip de cada una de las maquinas virtuales:

Windows ip configurada:
<img width="1005" height="467" alt="image" src="https://github.com/user-attachments/assets/1c0c94be-99b3-4dc4-83a9-91ea855c2c91" />

Kali ip configurada:
<img width="1299" height="861" alt="image" src="https://github.com/user-attachments/assets/cc0df27c-77ef-4284-96f0-6f2132d44cac" />

Rocky ip configurada:
<img width="1283" height="529" alt="image" src="https://github.com/user-attachments/assets/44cc13fe-3e0f-4315-9bb4-a750efa796ab" />
