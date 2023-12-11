#Proyecto Final
# Tienda de Tenis Online

¡Bienvenido a la Tienda de Tenis Online! Esta aplicación web simple permite a los usuarios explorar productos de tenis, agregarlos al carrito, y realizar compras seguras. Además, ofrece funciones como registrarse, iniciar sesión y recibir ofertas especiales por correo electrónico.

# Características

- **Explorar Categorías:** Descubre una variedad de productos de tenis para hombres y mujeres.
- **Carrito de Compras:** Agrega productos al carrito y realiza pagos de manera segura.
- **Registro e Inicio de Sesión:** Crea una cuenta para acceder a funciones exclusivas.
- **Ofertas Especiales:** Recibe ofertas especiales directamente en tu correo electrónico.

# Instalación

1. Clona este repositorio: `git clone https://github.com/tu_usuario/tu-repositorio.git`
2. Instala las dependencias: `pip install -r requirements.txt`
3. Ejecuta la aplicación: `python app.py`

# Uso

1. Visita la página principal: [http://localhost:5000/](http://localhost:5000/)
2. Explora las categorías de productos.
3. Regístrate o inicia sesión para acceder a funciones adicionales.
4. Agrega productos al carrito y realiza pagos.

# Configuración del Correo Electrónico

Para recibir ofertas especiales por correo electrónico, asegúrate de configurar correctamente el servidor SMTP y las credenciales en el archivo `app.py`.

```python
# Configuración del Correo Electrónico
app.config['MAIL_SERVER'] = 'tu_servidor_smtp'
app.config['MAIL_PORT'] = 587  
app.config['MAIL_USE_TLS'] = True  
app.config['MAIL_USERNAME'] = 'tu_correo_electronico'
app.config['MAIL_PASSWORD'] = 'tu_contraseña'
app.config['MAIL_DEFAULT_SENDER'] = 'tu_correo_electronico'

Proporciona instrucciones detalladas sobre cómo instalar tu proyecto. Incluye dependencias y pasos específicos si es necesario.

```bash
python -m venv venv
source venv/bin/activate  # En sistemas basados en Unix/Linux

venv\Scripts\activate  # En sistemas basados en Windows
