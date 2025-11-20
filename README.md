Guia de instalacion de dependencias

 
 python -m venv .venv
  .\.venv\Scripts\Activate.ps1

- WSL / Linux / macOS:
  python3 -m venv .venv
  source .venv/bin/activate

2) Actualizar pip (recomendado)
- PowerShell / WSL:
  python -m pip install --upgrade pip setuptools wheel

3) Instalar Kivy
- Instalación básica (suficiente para desarrollo local):
  pip install kivy

- Nota: si necesitas extras o dependencias específicas para multimedia/soporte de audio/video, revisa la documentación oficial de Kivy:
  https://kivy.org/doc/stable/installation/installation.html

4) Verificar la instalación
- Ejecuta en la terminal:
  python -c "import kivy; print(kivy.__version__)"
