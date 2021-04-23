# Reverse Proxy Image für den office checkin

Enthält das Dockerfile und die Konfiguration für den Reverse Proxy. Dieses Repository wird nur benötigt, wenn Sie das Office Check-In Deployment via Docker realisieren möchten.
Mittels des Reverse Proxys werden die Anfragen an den App Service auf die korrekten Container weitergeleitet.

## Deployment

Um den reverse proxy zu benutzen, müssen Sie zunächst unter ``conf.d/frontend.conf`` den server_name anpassen.
Nachdem dies geschehen ist, können Sie das Docker-Image bauen und in Ihre Container-Registry pushen.

