# BillSave

<div style="text-align: center;">
  <h1>Documentación de BillSave</h1>
  <img src="https://shorturl.at/7M79G" alt="BillSave Logo" width="300px"/>
</div>

<div style="display: flex; justify-content: center;">
  <div>
    <h4 style="text-align: center; margin-bottom: 1.2rem;">Startup: FinWorkTech</h4>
    <table border="1" style="margin: auto;">
      <thead>
        <tr>
          <td style="text-align: center;"><strong>Miembros:</strong></td>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Gonzalo Andre Quedena</td>
        </tr>
        <tr>
          <td>Dary Jarod Guevara Rojas</td>
        </tr>
        <tr>
          <td>Mirian Emilia Miranda Ccora</td>
        </tr>
        <tr>
          <td>Daniel Jesús Muñoz Fano</td>
        </tr>
        <tr>
          <td>Romina Alejandra Tuesta Marin</td>
        </tr>
      </tbody>
    </table>
    <h5 style="text-align: center; margin-top: 2rem;">2025</h5>
  </div>
</div>

---

## Índice

- [Introducción](#introducción)  
- [Objetivo del Estudiante (Student Outcome)](#objetivo-del-estudiante-student-outcome)  
- [Definiciones generales y conceptos básicos](#definiciones-generales-y-conceptos-básicos)  
- [Marco Legal y Teórico](#marco-legal-y-teórico)  
- [Análisis y Diseño del Sistema](#análisis-y-diseño-del-sistema)  
  - [Análisis de Datos](#análisis-de-datos)  
  - [Diseño de la Interface](#diseño-de-la-interface)  
  - [Marco conceptual (fórmulas)](#marco-conceptual-fórmulas)  
  - [Diseño de Datos de prueba](#diseño-de-datos-de-prueba)  
- [Algoritmo](#algoritmo)  
- [Modelo de la Base de datos](#modelo-de-la-base-de-datos)  
- [Sistema de información](#sistema-de-información)  
- [Anexos](#anexos)  
- [Bibliografía](#bibliografía)

---

## Introducción
Descripción general del proyecto y los objetivos principales de la solución.

## Objetivo del Estudiante (Student Outcome)
Descripción de los logros que el estudiante espera alcanzar a través del desarrollo del proyecto.

## Definiciones generales y conceptos básicos
Explicación de los términos y conceptos clave utilizados en el proyecto.

## Marco Legal y Teórico
- Marco normativo para el Perú.  
- Conceptos y metodologías que se aplican al caso, respaldados por referencias bibliográficas o normas legales.

## Análisis y Diseño del Sistema

### Análisis de Datos
#### Datos de Entrada

| Nombre | Descripción | Tipo de Datos | Formato |
|--------|------------|--------------|---------|
| Correo o usuario | Identificación del usuario para el inicio de sesión. | Texto | Cadena de caracteres |
| Contraseña | Clave de acceso del usuario. | Texto (password) | Cadena de caracteres |
| Nombres y apellidos | Nombre completo del usuario. | Texto | Cadena de caracteres |
| Correo electrónico | Correo electrónico validado del usuario. | Texto (validación de email) | Correo electrónico válido |
| Nombre de usuario | Identificador único del usuario en la plataforma. | Texto (único) | Cadena de caracteres |
| Confirmación de contraseña | Verificación de coincidencia con la contraseña ingresada. | Texto (password) | Cadena de caracteres |

#### Datos Intermedios

| Nombre | Descripción | Tipo de Datos | Formato |
|--------|------------|--------------|---------|
| Token de autenticación | Token generado tras el inicio de sesión. | Texto (token) | Cadena de caracteres |
| Estado de validación de usuario | Indica si el usuario fue validado correctamente. | Booleano | Verdadero/Falso |
| Número de intentos fallidos | Registro de intentos fallidos de inicio de sesión. | Número entero | Número entero |

#### Datos de Salida

| Nombre | Descripción | Tipo de Datos | Formato |
|--------|------------|--------------|---------|
| Mensaje de error - Usuario o contraseña incorrectos | Mensaje cuando las credenciales son incorrectas. | Texto | Cadena de caracteres |
| Confirmación de registro exitoso | Mensaje de confirmación tras completar el registro. | Texto | Cadena de caracteres |
| Exportación de reporte en PDF o Excel | Opción para descargar el reporte financiero. | Archivo descargable | PDF/Excel |


### Diseño de la Interface
- Presentación de las pantallas de interacción con el sistema.  
- Uso de medios electrónicos para recibir ayuda sobre el uso del sistema.

### Marco conceptual (fórmulas)
- Presentación del modelo matemático y las fórmulas utilizadas en la aplicación, como el cálculo del Valor Recibido y la TCEA.

### Diseño de Datos de prueba
- Mínimo 2 juegos de datos de prueba para comprobar la veracidad del modelo.

## Algoritmo
- Pseudocódigo, Diagrama de Flujo o Diagrama de Nassi-Schneiderman que ilustre la solución.

## Modelo de la Base de datos
- Presentación del modelo entidad-relación de la base de datos que se utilizará en la implementación.

## Sistema de información
- Implementación del análisis y diseño del sistema utilizando un lenguaje de programación orientado al desarrollo web o móvil.  
- Requisitos:  
  a) Conectividad.  
  b) Base de datos.  
  c) Código fuente.  
  d) Ayuda y asistencia técnica.  
  e) Validación y pruebas.

## Anexos
- Presentación de alto impacto académico/comercial de la aplicación, encartes, brochures informativos u otros materiales relacionados con la aplicación.

## Bibliografía
- Referencias bibliográficas utilizadas para el desarrollo del proyecto.
