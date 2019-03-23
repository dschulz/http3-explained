## Niveles de transporte y aplicación

El protocolo IETF QUIC es un protocolo de transporte, sobre el cual otros
protocolos de aplicación pueden ser usados. El protocolo de nivel de aplicación
inicial es HTTP/3 (h3).

La capa de transporte admite conexiones y _streams_.

La versión de QUIC legada de Google tenía transporte y HTTP entremezclados
todo en uno y fue un protocolo de propósito mas especializado para enviar _frames_ HTTP/2 sobre UDP.