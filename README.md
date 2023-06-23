# IMPLANTLABS

Una plataforma multimodal y base de datos para la adquisición y análisis de datos de investigación en Audiología.

## Instrucciones

1. Instalación de [Node.js 16.x LTS](https://nodejs.org/download/release/latest-v16.x/)

2. Descarga de dependencias.

```bash
npm i --force
```

3. Ejecución de IMPLANTLABS.

```bash
npm run start
```

4. Acceso: [http://localhost:1337/admin](http://localhost:1337/admin)

Usuario: admin@localhost.com
Password: admin12A

## Desarrollo

- Reconstruir el proyecto completo y el panel de administración.

```bash
npm run-script build
```

- Ejecutar en modo desarrollo

```bash
npm run develop
```

## Producción

El archivo conf.json contiene la ruta de los certificados de seguridad, ruta del directorio de datos de los pacientes, puertos de escucha y dominio de IMPLANTLABS.
