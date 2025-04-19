
# 🤖 SELENIUM AI CHATBOT TESTING

Automatización de pruebas QA para un stub de chatbot dinámico en Flask, empleando Selenium WebDriver y pytest.

---

## 📋 ÍNDICE

- [🚀 Vista General](#-vista-general)  
- [⚙️ Prerrequisitos](#️-prerrequisitos)  
- [🛠️ Instalación y Setup](#️-instalación-y-setup)  
- [🔧 Cómo ejecutar el Stub](#-cómo-ejecutar-el-stub)  
- [🧪 Casos de Prueba Automatizados](#-casos-de-prueba-automatizados)  
- [📁 Estructura del Proyecto](#-estructura-del-proyecto)  
- [📄 Licencia](#-licencia)

---

## 🚀 VISTA GENERAL

Este proyecto demuestra un flujo completo de QA para un chatbot stub:

1. **Stub dinámico** en Flask que simula un bot “Echo”.  
2. **Automatización** con Selenium: envío de prompts, espera de respuesta y validación con `assert`.  
3. **Reporte** de fallos en CSV/JSON.  
4. **pytest** para orquestar y ejecutar los tests.

---

## ⚙️ PRERREQUISITOS

- Python 3.x  
- Flask  
- Selenium (`pip install selenium`)  
- ChromeDriver (versión compatible con tu Chrome)  
- pytest (opcional: `pip install pytest`)  
- Git

---

## 🛠️ INSTALACIÓN Y SETUP

1. Clonar este repositorio:  
   ```bash
   git clone https://github.com/tu-usuario/selenium-ai-chatbot-testing.git
   cd selenium-ai-chatbot-testing
   ```

2. Crear y activar un entorno virtual (recomendado):
  ```bash
  python -m venv venv
  source venv/bin/activate   # macOS/Linux
  venv\Scripts\activate      # Windows
  ```

3. Instalar dependencias:

  ```bash
  pip install flask selenium pytest
  ```

4. Descargar ChromeDriver y ubicarlo en (por ejemplo):

  ```bash
  ./drivers/chromedriver.exe
  ```

Ajusta la ruta en tests/test_chatbot_selenium.py si es necesario.

5. 
6. 
