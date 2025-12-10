## Cómo ejecutar el proyecto
# Examen Final

Una mini aplicación web que muestra datos del alumno.


---

## **Ejecución local con Docker**

### 1️. Clonar el repositorio
```
git clone https://github.com/pauliCodes-x/final-asato-paula.git
cd final-asato-paula
```

### 2. Construir la imagen Docker

```bash
docker build -t final-asato-paula .
```


### 3. Ejecutar el contenedor
```bash
docker run -d -p final-asato-paula
```

Luego abrir en el navegador:
- http://localhost:8080

---