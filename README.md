# myqr

## QR Code scanner for login hotspot MikroTik

### Cara pakai

1. Tambahkan button di login.html

```html
<button onclick="window.location='https://saifudinzezy.github.io/myqr';">
  QR Code
</button>
```

2. Tambahkan script berikut di MikroTik via Terminal.

```
/ip hotspot walled-garden ip

add action=accept comment="QR Code Scanner" disabled=no dst-host=saifudinzezy.github.io
```

### Powered by webqr.com
