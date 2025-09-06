# Configuración en MacOS y Linux

Ejecute los siguientes comandos en el terminal:

```bash
python3 -m venv .venv
source .venv/bin/activate
source setup.sh
```

# Configuración en Windows

Ejecute los siguientes comandos en el terminal:

```bash
py -m venv .venv
.venv\Scripts\activate
setup
```

# Configuración en Windows

```powershell
py -m venv .venv
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
.venv\Scripts\activate
.\setup.bat

# Ejecución de pruebas

Ejecute el siguiente comando en el terminal:

```bash
pytest
```
