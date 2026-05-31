# Tareas pendientes

## Portfolio personal
- [ ] Subir la página a internet (GitHub Pages - gratis)
- [ ] Comprar dominio thiagovitelli.com.ar en nic.ar
- [ ] Conectar el dominio a la página publicada
- [ ] Agregar proyectos reales cuando estén listos para mostrar

---

## Proyecto buscador de negocios (Google Maps)

### Paso 1 — Google Cloud Console
- [ ] Entrar a console.cloud.google.com con cuenta de Google
- [ ] Crear un proyecto nuevo (ej: "buscador-negocios")
- [ ] Ir al menú "APIs y servicios" → "Biblioteca"
- [ ] Buscar y activar "Places API"
- [ ] Buscar y activar "Maps JavaScript API"
- [ ] Ir a "APIs y servicios" → "Credenciales"
- [ ] Hacer clic en "Crear credencial" → "Clave de API"
- [ ] Copiar y guardar la API key generada (formato: AIzaSy...)
- [ ] Opcional: restringir la clave a solo las APIs activadas (más seguro)

### Paso 2 — Configuración local
- [ ] Verificar si Python está instalado: abrir CMD y escribir `python --version`
- [ ] Si no está: descargar desde python.org e instalar (marcar "Add to PATH")
- [ ] Instalar librerías necesarias: `pip install requests beautifulsoup4 pandas`

### Paso 2 — Script
- [ ] Elegir ciudad y rubro para la primera prueba
- [ ] Construir el script que busca negocios en Google Maps
- [ ] Agregar filtro: negocios sin página web
- [ ] Agregar verificador: negocios con web vieja (copyright antiguo, diseño desactualizado)

### Paso 3 — Resultados
- [ ] Generar página HTML con la lista de prospectos
- [ ] Incluir en cada tarjeta: nombre, rubro, teléfono, dirección, estado de su web
- [ ] Generar mensaje de prospección listo para copiar y enviar por WhatsApp o Instagram
