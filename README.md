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
Para muchas empresas pequeñas y medianas (PYME), este puede ser un gran desafío para mantener un flujo de caja saludable. A menudo tienen dinero que no es para la recolección de cartas o facturas, pero inmediatamente necesitan dinero para continuar operando, pagando a los proveedores o invirtiendo en su crecimiento. En estos casos, una solución generalizada es reducir estas cartas o facturas, es decir, venderlas a la unidad financiera a cambio de recibir dinero antes de la fecha de vencimiento.
Sin embargo, este proceso no siempre es tan simple como parece. Las empresas deben calcular las tasas de descuento correctamente, saber cuánto les costará realmente esta operación y comprender cómo afecta su rentabilidad. Nuestra aplicación se usa aquí. El objetivo de este proyecto es desarrollar una aplicación web/móvil que ayude a las PYME a administrar su cartera de letras y facturas de una manera simple y eficiente. Con esta herramienta, pueden revelar y administrar sus documentos comerciales, establecer fechas de descuento y calcular automáticamente el porcentaje del costo efectivo anual (TCEA), todo rápidamente y sin complicaciones. Además, la aplicación opera en las plantas y en dólares y le permite elegir entre precios nominales o efectivos que se adapten a las necesidades de cada usuario.
La seguridad también es la clave, por lo que el acceso estará protegido por el usuario y la contraseña. Además, los mensajes detallados que muestran la cartera y su TCEA relevante pueden en cualquier momento, lo que permite a las empresas tomar mejores decisiones financieras.
En resumen, el propósito de esta aplicación es simplificar el proceso económico, que, si bien puede parecer técnico, es importante para la estabilidad y el crecimiento de muchas PYME. Al ofrecer una herramienta intuitiva y eficiente, queremos ayudar a más empresas a acceder a la liquidez sin complicaciones y con información clara sobre el costo y los beneficios de cada operación.

## Objetivo del Estudiante (Student Outcome)
Descripción de los logros que el estudiante espera alcanzar a través del desarrollo del proyecto.

## Definiciones generales y conceptos básicos
Explicación de los términos y conceptos clave utilizados en el proyecto.

## Marco Legal y Teórico
- Marco normativo para el Perú.  
- Conceptos y metodologías que se aplican al caso, respaldados por referencias bibliográficas o normas legales.

## Análisis y Diseño del Sistema

### Análisis de Datos
- **Datos de Entrada**: Descripción de las constantes/variables, tipos, tamaños, formatos, valores por defecto y restricciones.  
- **Datos de Salida**: Descripción de las variables, tipos, tamaños y formatos.  
- **Datos Intermedios**: Descripción de las variables, tipos, tamaños y formatos.

### Diseño de la Interface
- Presentación de las pantallas de interacción con el sistema.  
- Uso de medios electrónicos para recibir ayuda sobre el uso del sistema.

### Marco conceptual (fórmulas)
En este apartado, se presentan las fórmulas matemáticas utilizadas en el desarrollo de la aplicación, enfocadas en el cálculo de la Tasa de Coste Efectivo Anual (TCEA) tanto a nivel individual (para cada letra o factura) como a nivel global (para toda la cartera de documentos).
El proceso inicia con la determinación de la TCEA individual de cada letra o factura descontada, considerando el valor recibido tras aplicar los descuentos e impuestos correspondientes. Posteriormente, se calcula la TCEA de la cartera, obteniendo un valor ponderado en función del monto nominal de cada documento.
Las fórmulas clave utilizadas en estos cálculos son las siguientes:
  1. Tasa de Coste Efectivo Anual (TCEA):
     La TCEA es un indicador financiero que refleja el costo total del descuento de una cartera de letras o facturas, expresado en términos anuales. Se calcula con la siguiente fórmula:
     
     ![image](https://github.com/user-attachments/assets/4f8d8ec3-23fc-4f82-a21f-d91badd4ba00)
     * TCEA = Tasa de Coste Efectivo Anual
     * VE = Valor entregado por la entidad financiera al vencimiento de la factura o letra
     * VR = Valor recibido por la empresa
     * n = Número de días hasta el vencimiento de la factura o letra
      
  2. TCEA de la Cartera:
     Una vez obtenida la TCEA individual de cada letra o factura, es necesario calcular la TCEA de la cartera, que representa el costo efectivo anualizado de toda la cartera de documentos descontados. Este cálculo se realiza ponderando la TCEA de cada documento según        su monto nominal, permitiendo obtener una tasa representativa del conjunto de facturas y letras descontadas. Se calcula con la siguiente fórmula:
     ![image](https://github.com/user-attachments/assets/33acbdf8-7987-4713-b4be-0df9fa7c7672)
     * n = Número total de letras o facturas en la cartera
### Diseño de Datos de prueba
- Mínimo 2 juegos de datos de prueba para comprobar la veracidad del modelo.

## Algoritmo
![diagrama_tcea](https://github.com/user-attachments/assets/a1d043eb-1dda-4b85-91c5-cede06514ecb)
El diagrama de flujo representa el proceso de cálculo de la Tasa de Coste Efectivo Anual (TCEA) en la aplicación. Comienza con la recepción del evento DocumentChangedEvent, lo que desencadena la obtención de los documentos asociados a una cartera. Luego, se procede a calcular la TCEA, evaluando cada documento individualmente mediante la validación de fechas, el cálculo de la tasa efectiva y el valor presente. Una vez obtenida la TCEA de toda la cartera, esta información se actualiza en el servicio externo. Finalmente, el proceso concluye, asegurando que la cartera refleje la tasa correcta.

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
