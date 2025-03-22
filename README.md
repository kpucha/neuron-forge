# Neuron Forge

Este es el repositorio principal del proyecto Neuron Forge, que integra dos componentes principales:

- **Backend:** [neuron-forge-spring](https://github.com/kpucha/neuron-forge-spring)  
  (incluido como submódulo en la carpeta `backend`)
- **Frontend:** [neuron-forge-ng](https://github.com/kpucha/neuron-forge-ng)  
  (incluido como submódulo en la carpeta `frontend`)

## Cómo Contribuir

1. **Clonar el repositorio principal con submódulos:**
   ```bash
   git clone --recurse-submodules https://github.com/kpucha/neuron-forge.git
   ```
2. **Realizar cambios en los componentes:**
   - Navega a `backend/` o `frontend/` según corresponda.
   - Realiza tus cambios y haz commit y push en el repositorio respectivo.
3. **Pull Requests:**
   - Las ramas `main` están protegidas; todos los cambios deben integrarse mediante pull requests, que se revisarán y deben pasar los checks de CI.

## Configuración Común y Secrets

- Los secrets compartidos (por ejemplo, claves de despliegue o tokens) se gestionan a nivel de organización o se documentan aquí para uso en ambos proyectos.
- Consulta la documentación interna de cada submódulo para detalles específicos de configuración.

## Flujo de Trabajo

- **Desarrollo y Testing:**  
  Cada repositorio (backend y frontend) tiene su propio workflow de CI configurado con caché para agilizar la construcción y pruebas.
- **Integración:**  
  El repositorio principal permite coordinar y versionar conjuntamente las versiones de backend y frontend mediante submódulos.
