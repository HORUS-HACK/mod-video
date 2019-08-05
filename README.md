# SayCheese v1.0
Tome fotos de la cámara web simplemente enviando un enlace malicioso

![cheese](https://i.ibb.co/X2QK7zQ/21.gif)

# How it works?
<p>The tool generates a malicious HTTPS page using Serveo or Ngrok Port Forwarding methods, and a javascript code to cam requests using MediaDevices.getUserMedia. </p>

<p>El método MediaDevices.getUserMedia () solicita al usuario permiso para usar una entrada de medios que produce un MediaStream con pistas que contienen los tipos de medios solicitados. Esa transmisión puede incluir, por ejemplo, una pista de video (producida por una fuente de video virtual o de hardware, como una cámara, un dispositivo de grabación de video, un servicio para compartir pantalla, etc.), una pista de audio (de manera similar, producida por un dispositivo físico o fuente de audio virtual como un micrófono, convertidor A / D o similar) y posiblemente otros tipos de pistas. </p>

[See more about MediaDEvices.getUserMedia() here](https://developer.mozilla.org/en-US/docs/Web/API/MediaDevices/getUserMedia)
<p> Para convencer al objetivo de que otorgue permisos para acceder a la cámara, la página utiliza un código javascript y una moificacion de los parametros de la camara, puede decirle a las victimas que se trata de una aplicacion que muestra como seras dentro de 50 años.</p>

## Installing (Kali Linux/Termux):

```
https://github.com/HORUS-HACK/mod-video.git
cd mod-video
bash horus.sh
```

