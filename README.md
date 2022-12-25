# Qrcode
## Scanner de code QR pour la connexion du hotspot MikroTik

### Comment utiliser

1. Ajouter un bouton dans login.html
```html
<button onclick="window.location='https://phenix-it.github.io/qr';">QR Code</button>
```
2. Ajouter le script suivant dans MikroTik via le Terminal.
```
/ip hotspot walled-garden ip
add action=accept comment="Phenix Hotspot QR Code Scanner" disabled=no dst-host=phenix-it.github.io
```

### Powered by webqr.com
