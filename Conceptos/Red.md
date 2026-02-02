# PROXY
Es un dispositivo o servicio que se encuentra en medio de una conexión y actua como mediador, que puede inspeccionar el contenido del tráfico. Operan en la Capa 7 del modelo OSI.
Hay varios tipos:
<pre>
    1. PROXY DEDICADO / PROXY DE REENVIO
        Un proxy de reenvío es cuando un cliente realiza una solicitud a una computadora, y esta la ejecuta. Otro ejemplo es Burp Suite.
    2. PROXY INVERSO
        Filtra las solicitudes entrantes, el objetivo es escuchar una dirección y reenviarla a una direccion cerrada.
</pre>

<hr style="height:5px; border:none; color:#333; background-color:#333;" />


# Modelo OSI
Es un modelo de referencia que se puede utilizar para describir y definir la comunicación entre sistemas. Tiene 7 capas, durante la transmision cada capa añade una cabecera que controla e identifica el paquete (`Encapsulacion`).<br>Capas:
<pre>
    7.Aplicación - Controla la entrada y salida de datos y proporciona las funciones de la aplicación.
    6.Presentación - Transferir la presentación de datos
    5.Sesión - Controla la conexion lógica entre dos sistemas.
    4.Transporte - Controla los datos transferidos, puede evitar situaciones de congestión.
    3.Red -  Las conexiones se establecen en redes de conmutación de circuitos y los paquetes de datos se reenvían en redes de conmutación de paquetes.
    2.Enlace - Permite una transmisión fiable y sin errores en el medio fisico. El fujo de bits de la Capa 1 se divide en tramas.
    1.Física - La transmisión se reaiza mediante líneas de transmisión cableadas o inalámbricas.
</pre>

<hr style="height:5px; border:none; color:#333; background-color:#333;" />


# Modelo TCP/IP
Es un protocolo de comunicacion que permite a los host conectarse a Internet. Representa `Transmission Control Protocol (TCP)` de la capa 4 de OSI y `Internet Protocol (IP)` de la capa 3 de OSI. Tiene 4 capas.<br>Capas:
<pre>
    4.Aplicacion - Permite que las aplicaciones accedan a los servicios de las otras capas y define los protocolos que las aplicaciones utilizan para intercambiar datos. 
    3.Transporte - responsable de proporcionar servicios de sesión (TCP) y datagramas (UDP) para la capa de aplicación. 
    2.Red - Responsable de las funciones de direccionamiento, empaquetado y enrutamiento del host. 
    1.Enlace - Se encarga de colocar los paquetes TCP/IP en el medio de red y recibir los paquetes correspondientes. 
</pre>