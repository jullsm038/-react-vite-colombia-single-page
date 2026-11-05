# React + Vite

# EVALUACION FRONTEND 2

Estudiante: Julissa Fernanda Murillo Zapata
Profesor: Daniel Agudelo

## Comando de instalación y ejecución local (npm install, npm run dev).

npm install && npm run dev
npm install react-router-dom

## Decisiones técnicas tomadas para la interacción de la vista única.

### DEPARTAMENTOS

Creamos la pagina en src>pages>Departamentos En esta vista de departamentos lo primero fue hacer el import conectamos con el link de Api Colombia y asi poder obtener la información de los departamentos. Colocamos la funcion para que se guarden los datos, y con useState(true) y useState(null) para que nos muestre cuando este cargando (setCargando) o genere un error(setError). También con ayuda de .map() organizamos el listado de los departamentos.

### DETALLE DEPARTAMENTO

Creamos la pagina en src>pages>DetalleDepartamento En esta vista se carga la información del departamento especifico, se realiza la conexion con Api Colombia, se organiza la navegacion, también se organiza para que la vista tenga la parte de Departamento, Capital, poblacion, superficie, Municipio.

## Capturas que evidencien su funcionamiento.

### VISTA DEPARTAMENTOS

(./src/assets/vista1-departamentos.png)

### VISTA DETALLE DEPARTAMENTO

(./src/assets/vista2-antioquia.png)
