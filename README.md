# CsStrike

CsStrike adalah tool ringkas dan basic dari CsCrew untuk tujuan testing kestabilan server dan bypass protection seperti Cloudflare.

Tool ini akan hantar ribuan request rawak dengan kombinasi User-Agent, IP spoof, dan HTTP method (GET, POST, PUT, DELETE). Ia juga mampu detect WAF secara automatik.

Contoh penggunaan:

1. Install dulu jika perlu:
   pip install aiohttp colorama pyfiglet

2. Run:
   python csstrike.py

3. Masukkan URL:
   https://example.com

Tool ini akan jalan secara automatik dan log status setiap request.

Kegunaan hanya untuk pentesting sah, audit keselamatan, atau ujian load pada sistem sendiri. Dilarang guna pada sistem orang tanpa kebenaran.

Dibuat oleh Adxxmwashere atau Adxxm untuk CsCrew dan juga untuk anda diluar sana
