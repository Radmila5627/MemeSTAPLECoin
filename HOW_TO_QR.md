# Generate QR Codes (Local)

## Python
Install:
```bash
pip install qrcode[pil]
```

### Buy STAPLE (USDC pair)
```python
import qrcode
url = "https://pancakeswap.finance/swap?outputCurrency=0x891920e5b704524C81c213F78473FC837C66fF31&inputCurrency=0x8ac76a51cc950d9822d68b83fe1ad97b32cd580d"
img = qrcode.make(url)
img.save("qr_buy_staple.png")
```

### BscScan (contract)
```python
import qrcode
url = "https://bscscan.com/token/0x891920e5b704524C81c213F78473FC837C66fF31"
img = qrcode.make(url)
img.save("qr_bscscan_staple.png")
```