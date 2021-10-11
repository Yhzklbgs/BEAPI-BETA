## REQUIREDMENT ##
```PY
pip3 install httpx && pip3 install httpx[http2]
```

## EXAMPLE ##
```PY
import BEAPI
client = BEAPI.BEAPI()
qr = client.lineGetQr("IOSIPAD\t10.5.2\tiPhone 8\t11.2.5")
print("Link QR: "+qr["result"]["qrlink"])
print("IP: "+qr["result"]["ip"])
pincode = client.lineGetQrPincode(qr["result"]["session"])
print("Pincode: "+pincode["result"]["pincode"])
auth = client.lineGetQrAuth(qr["result"]["session"])
print("AccessToken: "+auth["result"]["accessToken"])
print("Cert: "+auth["result"]["certificate"])

```

## INFORMATION ##
STATUS: ACTIVE
<br />
UPDATE STATUS: CONTINUE 
<br />
LAST UPDATE: 11/10/21
<br />
MAX CONCURRENT: 1
<br />
LICENSE: FREE
