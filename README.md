# Tarea 1

## Visualizar tarea

Se puede abrir el archivo **index.html** para visualizar el sitio pero lo mas recomendable es ejecutar lo siguiente, se debe tener docker instalado

```
docker-compose up -d
```

Luego ir a la siguiente url [http://localhost:8080](http://localhost:8080) para visualizar el sitio

## Listado de archivos

```
.
├── Dockerfile # docker file para crear la imagen
├── README.md
├── app
│   ├── contacto.html # página de contacto
│   ├── css
│   │   └── style.css # estilo personalizado
│   ├── equipo-medico.html # página de equipo medico
│   ├── img
│   │   ├── bg-2.jpg
│   │   ├── bg-3.jpg
│   │   ├── bg.jpg
│   │   ├── doc-1.png
│   │   ├── hospital-icon.svg
│   │   ├── patient-1.png
│   │   ├── patient-2.png
│   │   ├── patient-3.png
│   │   ├── service-1.png
│   │   ├── service-2.png
│   │   └── service-3.png
│   └── index.html # página principal
└── docker-compose.yml # docker-compose para levantar localmente el sitio
```
