# Crear y arrancar infraestructura
Para crear y arrancar toda la infraestructura por primera vez:
```bash
docker compose up -d
```
### VirtualHosts
Recuerda añadir al archivo `hosts` el dominio:
```bash
<ip_maquina_anfitrión> web1.com
```
# Otras acciones
Arrancar o parar entorno
```bash
docker compose start/stop
```

Limpiar entorno (elimina contendores, volúmene, redes e imágenes)
```bash
docker compose down -v --rmi all
```