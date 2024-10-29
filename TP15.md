#### Tiziano Pirez 4to 4ta

# Introducción a Redes

## Introducción
En este trabajo práctico exploraremos los fundamentos de las redes de computadoras, incluyendo conceptos como el compartir recursos, direcciones físicas, dominios de colisión, tipos de dispositivos de red y filtrado de tráfico.

### Objetivos
- Comprender el concepto de red y sus componentes.
- Identificar los diferentes tipos de recursos que se pueden compartir en una red.
- Conocer los dispositivos utilizados en redes y su funcionamiento.

### Recursos
- Video: [CURSO de REDES 2020 para PRINCIPIANTES # 1 - INTRODUCCIÓN](https://www.youtube.com/watch?v=k2e6eWyn0fE&list=PLg9145ptuAijivEI4t0cb31FA41zqclwO&index=2)

## Actividades

### 1. Recursos Compartidos en una Red
- **Pregunta 1a**: Da un ejemplo de cada categoría de recurso:
  - **Programas**: 
    - **Ejemplo**: Microsoft Office. Este conjunto de aplicaciones permite crear, editar y compartir documentos, hojas de cálculo y presentaciones. En un entorno de red, varias computadoras pueden acceder a versiones compartidas de estos programas, facilitando la colaboración.
  - **Equipos**: 
    - **Ejemplo**: Impresoras. Una impresora conectada a la red permite que múltiples usuarios envíen documentos a imprimir desde sus computadoras, optimizando recursos y reduciendo costos.
  - **Datos**: 
    - **Ejemplo**: Bases de datos. Un servidor de base de datos almacena información que puede ser accedida por diferentes usuarios y aplicaciones en la red, lo que permite un manejo centralizado de datos.

- **Pregunta 1b**: ¿A qué categoría de recursos compartidos nos referimos al trabajar en un procesador de texto en un servidor?
  - **Respuesta**: Nos referimos a **programas**. Cuando varios usuarios trabajan en un procesador de texto que reside en un servidor, están utilizando un software que permite la edición y el almacenamiento colaborativo de documentos. Esto es fundamental en entornos de trabajo donde la colaboración y la productividad son esenciales.

- **Pregunta 1c**: Al acceder a la página web del banco, ¿qué categoría de recursos compartidos estamos utilizando?
  - **Respuesta**: Estamos utilizando la categoría de **datos**. Al consultar el saldo de una cuenta en la página web del banco, estamos accediendo a información específica almacenada en los servidores del banco. Esto implica la transferencia de datos entre el servidor y nuestro dispositivo, permitiéndonos ver información crítica en tiempo real.

- **Pregunta 1d**: Si accedo a otra computadora de la red de mi casa, ¿a qué categoría de recursos compartidos nos referimos?
  - **Respuesta**: Nos referimos a **equipos**. Al acceder a otra computadora en la red local, estamos interactuando con un dispositivo físico, lo que nos permite compartir archivos, recursos y realizar tareas de manera colaborativa.

### 2. Conexiones de Red
- **Pregunta 2**: ¿Qué tipo de cable utilizarías para conectar dos computadoras?
  - **Respuesta**: Para conectar dos computadoras directamente, utilizaríamos un **cable Ethernet (RJ-45)**. Este tipo de cable es fundamental en las redes LAN (Local Area Network) y permite la transmisión de datos a alta velocidad, soportando conexiones de hasta 1 Gbps o más en redes modernas.

### 3. Dominios de Colisión
- **Pregunta 3**: ¿Es mejor tener un dominio de colisión grande o pequeño?
  - **Respuesta**: Es mejor tener un dominio de colisión **pequeño**. En un dominio de colisión, todos los dispositivos comparten el mismo medio de transmisión. Cuando hay muchos dispositivos, aumenta la probabilidad de colisiones de datos, lo que provoca pérdidas de información y lentitud en la red. Al tener dominios más pequeños, se minimizan las colisiones, mejorando la eficiencia y la velocidad de la red.

### 4. Dispositivos de Red
- **Pregunta 4**: Observa la imagen del hub. ¿Para qué sirve un hub? ¿Todos los equipos conectados están en el mismo dominio de colisión? ¿Qué es congestión de la red?
  - **Respuesta**: Un hub sirve como un punto central de conexión para múltiples dispositivos en una red. Cuando un dispositivo envía datos a través del hub, este los transmite a todos los demás puertos, lo que significa que todos los equipos conectados están en el mismo dominio de colisión. Esto puede causar congestión de la red, un estado donde la cantidad de tráfico supera la capacidad de la red, resultando en colisiones, retrasos y potencial pérdida de datos.

### 5. Filtrado de Tráfico
- **Pregunta 5**: ¿El hub filtra tráfico o envía datos a todos los puertos?
  - **Respuesta**: El hub **no filtra tráfico**; simplemente recibe datos de un puerto y los envía a todos los demás puertos. Esta falta de filtrado significa que todos los dispositivos reciben todos los datos, lo que puede llevar a colisiones y una eficiencia reducida en la red.

### 6. Solución de Problemas
- **Pregunta 6**: ¿Qué dispositivo permite solucionar problemas de exceso de tráfico y colisiones?
  - **Respuesta**: Un **switch** es el dispositivo que ayuda a gestionar y reducir los problemas de tráfico y colisiones. A diferencia de un hub, un switch envía datos solamente al dispositivo de destino, lo que minimiza las colisiones y mejora el rendimiento de la red.

### 7. Bridge
- **Pregunta 7**: ¿Qué es un bridge?
  - **Respuesta**: Un bridge es un dispositivo que conecta dos o más segmentos de una red, permitiendo la comunicación entre ellos. Su función principal es filtrar y dirigir el tráfico, lo que ayuda a reducir las colisiones al dividir grandes dominios de colisión en partes más manejables.

### 8. Dirección MAC
- **Pregunta 8**: ¿Qué es una dirección MAC y cuántos bits tiene?
  - **Respuesta**: Una dirección MAC (Media Access Control) es un identificador único asignado a cada interfaz de red. Esta dirección tiene una longitud de **48 bits** y es utilizada para identificar de manera única a los dispositivos en una red local, asegurando que los datos se envíen al dispositivo correcto.

### 9. Dominios de Colisión y Bridge
- **Pregunta 9**: ¿Qué significa que un bridge rompe los dominios de colisión?
  - **Respuesta**: Decir que un bridge "rompe los dominios de colisión" significa que permite que diferentes segmentos de una red se comuniquen sin interferir entre sí. Al filtrar el tráfico basado en direcciones MAC, el bridge evita que las colisiones ocurran entre dispositivos que no están en el mismo segmento de red, mejorando así el rendimiento general.

### 10. Diseño de Redes
- **Pregunta 10**: ¿Qué es más conveniente, muchas máquinas en una red conectadas a un hub o distribuirlas en dos redes conectadas por un bridge?
  - **Respuesta**: Es más conveniente **distribuir las máquinas en dos redes conectadas por un bridge**. Esto no solo reduce la cantidad de dispositivos en un solo dominio de colisión, sino que también mejora el rendimiento al permitir que los dispositivos se comuniquen sin colisiones innecesarias.

### 11. Comparación: Bridge y Switch
- **Pregunta 11**: ¿Qué tienen en común un bridge y un switch respecto a los dominios de colisión?
  - **Respuesta**: Tanto un bridge como un switch actúan para **filtrar tráfico por direcciones MAC**. Ambos dispositivos crean dominios de colisión más pequeños, lo que mejora la eficiencia y el rendimiento de la red al reducir las posibilidades de colisiones de datos.

### 12. Conexión de Redes
- **Pregunta 12**: ¿Cuál dispositivo conecta redes entre sí y cuál conecta computadoras a una red?
  - **Respuesta**: Un **bridge** se utiliza para conectar diferentes redes entre sí, mientras que un **hub** conecta computadoras a una red local. El hub actúa como un punto central que permite la comunicación entre dispositivos en una misma red.

### 13. Dispositivos para Internet
- **Pregunta 13**: ¿Qué dispositivo se usa para interconectar redes y acceder a Internet?
  - **Respuesta**: Un **router** es el dispositivo utilizado para interconectar redes y proporcionar acceso a Internet. Su función es dirigir el tráfico entre diferentes redes, asegurando que los datos se envíen a sus destinos correctos.

### 14. Direcciones IP
- **Pregunta 14**: ¿Las direcciones IP las pone el fabricante de las placas de red?
  - **Respuesta**: No, las direcciones IP **no son asignadas por el fabricante de las placas de red**. Estas direcciones son configuradas por administradores de red o asignadas dinámicamente a través de un servicio llamado DHCP (Dynamic Host Configuration Protocol), que gestiona automáticamente las direcciones en una red.

### 15. Dispositivos de Usuario Final
- **Pregunta 15**: ¿Qué es un dispositivo de usuario final? Menciona ejemplos.
  - **Respuesta**: Un dispositivo de usuario final es cualquier dispositivo que un usuario utiliza para acceder a la red. Ejemplos incluyen computadoras de escritorio, laptops, tablets y smartphones. Estos dispositivos permiten a los usuarios interactuar con servicios y recursos disponibles en la red.

### 16. Dispositivos de Red
- **Pregunta 16**: ¿Qué es un dispositivo de red? Menciona ejemplos.
  - **Respuesta**: Un dispositivo de red es un equipo que facilita la comunicación y el intercambio de datos entre diferentes dispositivos en una red. Ejemplos de dispositivos de red incluyen routers, switches, hubs, y firewalls. Cada uno tiene funciones específicas para gestionar y proteger el tráfico de la red.
