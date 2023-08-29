<p align="center">
    <h1>🍿 POPCorn</h1>
</p>

<p align="center">
<em>An ASGI web server, for Python.</em>
</p>

---

[![Build Status](https://github.com/encode/uvicorn/workflows/Test%20Suite/badge.svg)](https://github.com/encode/uvicorn/actions)
[![Package version](https://badge.fury.io/py/uvicorn.svg)](https://pypi.python.org/pypi/uvicorn)

**Documentation**: [https://www.uvicorn.org](https://www.uvicorn.org)

**Requirements**: Python 3.8+

POPCorn is an fork of Uvicorn that is an ASGI web server implementation for Python.

Until recently Python has lacked a minimal low-level server/application interface for
async frameworks. The [ASGI specification][asgi] fills this gap, and means we're now able to
start building a common set of tooling usable across all async frameworks.

POPCorn supports HTTP/1.1 and WebSockets.
