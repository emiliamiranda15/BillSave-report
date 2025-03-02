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
## 5. Análisis y Diseño del Sistema

### 5.1. Análisis de Datos

El análisis de datos desempeña un papel fundamental en cualquier proyecto, ya que proporciona una visión profunda y significativa que impulsa la toma de decisiones informadas y la eficacia operativa.

### 5.1.1. Datos de Entrada

#### **Login Page (Pantalla de inicio de sesión)**
| Nombre | Descripción | Tipo de Datos | Formato |
|--------|------------|--------------|---------|
| Usuario | Correo electrónico o nombre de usuario. | Texto | Cadena de caracteres |
| Contraseña | Clave de acceso del usuario. | Texto (password) | Cadena de caracteres |

#### **Register Page (Página de Registro)**
| Nombre | Descripción | Tipo de Datos | Formato |
|--------|------------|--------------|---------|
| Nombre completo | Nombre y apellido del usuario. | Texto | Cadena de caracteres |
| Correo electrónico | Dirección de correo del usuario. | Texto | Correo electrónico válido |
| Nombre de usuario | Identificador único del usuario. | Texto | Cadena de caracteres |
| Contraseña | Clave de acceso del usuario. | Texto (password) | Cadena de caracteres |
| Confirmación de contraseña | Validación de la contraseña ingresada. | Texto (password) | Cadena de caracteres |
| Aceptar términos y condiciones | Confirmación de aceptación de términos. | Booleano | Verdadero/Falso |

#### **Portfolio Form Page (Formulario de cartera)**
| Nombre | Descripción | Tipo de Datos | Formato |
|--------|------------|--------------|---------|
| Nombre del portafolio | Identificación del portafolio financiero. | Texto | Cadena de caracteres |
| Fecha de descuento | Fecha en la que se aplica el descuento del portafolio. | Fecha | DD/MM/AAAA |

#### **Document Form Page (Formulario de documento)**
| Nombre | Descripción | Tipo de Datos | Formato |
|--------|------------|--------------|---------|
| Código del documento | Código único del documento financiero. | Texto | Cadena de caracteres |
| Valor nominal | Valor nominal del documento. | Número decimal | Numérico |
| Fecha de emisión | Fecha de emisión del documento. | Fecha | DD/MM/AAAA |
| Fecha de vencimiento | Fecha límite del documento financiero. | Fecha | DD/MM/AAAA |
| Tasa nominal o efectiva | Tasa de interés aplicada al documento. | Número decimal | Numérico |
| Moneda | Tipo de moneda utilizada (S/ o USD). | Texto | Cadena de caracteres |

---

### 5.1.2. Datos Intermedios (Cálculos y Procesamientos)
| Nombre | Descripción | Tipo de Datos | Formato |
|--------|------------|--------------|---------|
| TCEA promedio del portafolio | Cálculo del Tasa de Costo Efectivo Anual promedio de los documentos. | Número decimal | Numérico |
| Estado del documento financiero | Cálculo del estado actual del documento (Activo, Vencido, Pagado). | Texto | Cadena de caracteres |

---

### 5.1.3. Datos de Salida
#### **Estado de cuenta actual:**
| Nombre | Descripción | Tipo de Datos | Formato |
|--------|------------|--------------|---------|
| Número total de portafolios activos | Cantidad de portafolios en estado activo. | Número entero | Número entero |
| Número total de documentos en el sistema | Cantidad de documentos registrados en el sistema. | Número entero | Número entero |
| Reporte financiero generado | Informe con datos financieros de portafolios y documentos. | Documento generado | Documento |




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

# 8. Sistema de Información

## 8.1. Conectividad

El sistema BillSave ha sido diseñado con una infraestructura que permite la comunicación eficiente entre los diferentes módulos y garantiza la seguridad de los datos. La conectividad en el sistema se ha implementado mediante los siguientes principios:

- **Protocolo seguro:** Se usa **HTTPS** para proteger la comunicación entre el cliente y el servidor.
- **API RESTful:** El sistema utiliza una API basada en **REST** para permitir la interacción entre la interfaz de usuario y la base de datos.
- **Base de datos en la nube:** PostgreSQL alojado en un servidor remoto, con acceso restringido a través de roles y autenticación segura.
- **Autenticación con JSON Web Token (JWT):** Cada usuario que inicia sesión recibe un **token de autenticación** que permite el acceso a los distintos módulos del sistema.
- **Escalabilidad y disponibilidad:** Se utiliza un balanceador de carga que distribuye las solicitudes en función del tráfico recibido.

---

## 8.2. Base de Datos y Desarrollo de Back-End

El sistema BillSave utiliza **PostgreSQL** como motor de base de datos, asegurando un almacenamiento eficiente y seguro de la información. 

### **8.2.1. Beneficios de PostgreSQL**
- **Alto rendimiento y escalabilidad:** Capaz de manejar grandes volúmenes de datos sin comprometer la velocidad de procesamiento.
- **Soporte para transacciones ACID:** Garantiza la integridad de los datos mediante la atomicidad, consistencia, aislamiento y durabilidad.
- **Extensibilidad:** Permite la adición de nuevos tipos de datos y funciones personalizadas.
- **Seguridad avanzada:** Soporta autenticación basada en roles y cifrado de datos en reposo y en tránsito.

### **8.2.2. Tecnologías Utilizadas**

| Tecnología | Propósito |
|------------|------------|
| **PostgreSQL** | Base de datos para almacenar información de usuarios, carteras y documentos. |
| **Spring Boot** | Framework en Java para gestionar la lógica del sistema. |
| **Spring Data JPA** | Abstracción para la persistencia de datos. |
| **Spring Security** | Mecanismo de autenticación y control de acceso. |
| **JWT (JSON Web Token)** | Seguridad y autenticación de usuarios. |
| **AWS S3** | Almacenamiento de reportes y documentos financieros. |
| **Docker** | Contenedorización del backend para fácil despliegue. |

### **8.2.3. Estructura de la Base de Datos**

#### **Tabla: Usuario**
| Campo | Tipo de Dato | Descripción |
|--------|-------------|-------------|
| id_usuario | INT (PK) | Identificador único del usuario. |
| nombre | VARCHAR(100) | Nombre completo del usuario. |
| correo | VARCHAR(100) | Correo electrónico del usuario. |
| contraseña | TEXT | Contraseña encriptada. |
| fecha_registro | TIMESTAMP | Fecha de creación de la cuenta. |

#### **Tabla: Carteras**
| Campo | Tipo de Dato | Descripción |
|--------|-------------|-------------|
| id_cartera | INT (PK) | Identificador único de la cartera. |
| nombre | VARCHAR(100) | Nombre de la cartera. |
| fecha_descuento | DATE | Fecha de descuento. |
| tcea | DECIMAL(10,2) | Tasa de Costo Efectiva Anual. |
| usuario_id | INT (FK) | Relación con el usuario propietario. |

#### **Tabla: Documentos**
| Campo | Tipo de Dato | Descripción |
|--------|-------------|-------------|
| id_documento | INT (PK) | Identificador único del documento. |
| id_cartera | INT (FK) | Relación con la cartera a la que pertenece. |
| valor_nominal | DECIMAL(10,2) | Valor nominal del documento. |
| fecha_emision | DATE | Fecha de emisión del documento. |
| fecha_vencimiento | DATE | Fecha de vencimiento. |
| tasa | DECIMAL(5,2) | Tasa de interés aplicada. |
| moneda | VARCHAR(3) | Moneda del documento (S/ o USD). |

---

## 8.3. Código Fuente y Gestión en GitHub

Para este proyecto se utilizó **GitHub** como plataforma para alojar y gestionar de manera colaborativa los avances a lo largo del desarrollo del sistema. Las principales ventajas de su uso incluyen:

- **Control de versiones:** Permite un seguimiento detallado de los cambios realizados en el código.
- **Colaboración eficiente:** Facilita el trabajo en equipo a través de ramas (`branches`) y solicitudes de extracción (`pull requests`).
- **Automatización:** Integración con **GitHub Actions** para realizar pruebas y despliegues automáticos.

**Estructura del Repositorio:**
```
/billsave-backend
  ├── src/
  │   ├── main/
  │   │   ├── controllers/
  │   │   ├── services/
  │   │   ├── models/
  │   │   ├── repository/
  ├── application.properties
  ├── pom.xml
```

- **`controllers/`**: Gestiona las solicitudes HTTP.
- **`services/`**: Contiene la lógica de negocio.
- **`models/`**: Define las entidades de la base de datos.
- **`repository/`**: Proporciona acceso a la base de datos.

---

## 8.4. Soporte y Ayuda Técnica

Para garantizar la asistencia técnica a los usuarios de BillSave, se han habilitado los siguientes canales:

1. **Soporte vía correo electrónico:** Disponible para resolver problemas técnicos y consultas generales.
2. **Centro de ayuda en línea:** Documentación con guías de uso y resolución de problemas frecuentes.
3. **Foro comunitario:** Espacio donde los usuarios pueden compartir experiencias y soluciones.

---

## 8.5. Pruebas y Validación del Sistema

Para asegurar la calidad del software, se han llevado a cabo las siguientes pruebas:

- **Pruebas Unitarias:** Validación de cada componente con **JUnit**.
- **Pruebas de Integración:** Verificación de la comunicación entre módulos usando **Postman**.
- **Pruebas de Seguridad:** Evaluación de autenticación con **OWASP ZAP**.
- **Pruebas de Rendimiento:** Simulación de carga con **JMeter**.

### **8.5.1. Resultados de las Pruebas**
| Tipo de Prueba | Resultado |
|----------------|------------|
| Inicio de sesión | ✅ Exitoso |
| Registro de usuarios | ✅ Exitoso |
| Creación de cartera | ✅ Exitoso |
| Cálculo de TCEA | ✅ Validado |
| Generación de reportes | ✅ Sin errores |

---



## Anexos
- Presentación de alto impacto académico/comercial de la aplicación, encartes, brochures informativos u otros materiales relacionados con la aplicación.

## Bibliografía
# 9. Referencias

1. Oracle. (2023). *Java Platform, Standard Edition Documentation*. Oracle Corporation. Recuperado de https://docs.oracle.com/javase/8/docs/

2. PostgreSQL Global Development Group. (2023). *PostgreSQL 15 Documentation*. Recuperado de https://www.postgresql.org/docs/15/index.html

3. Pivotal Software. (2023). *Spring Boot Reference Guide*. Recuperado de https://docs.spring.io/spring-boot/docs/current/reference/html/

4. GitHub, Inc. (2023). *GitHub Documentation*. Recuperado de https://docs.github.com/en

5. OWASP Foundation. (2023). *OWASP ZAP - The Zed Attack Proxy*. Recuperado de https://www.zaproxy.org/

6. Apache Software Foundation. (2023). *Apache JMeter User Manual*. Recuperado de https://jmeter.apache.org/usermanual/index.html

