## Índice

- [Introducción](#introducción)  
  - [Marco conceptual (fórmulas)](#marco-conceptual-fórmulas)  
- [Algoritmo](#algoritmo)  

---

## Introducción
Para muchas empresas pequeñas y medianas (PYME), este puede ser un gran desafío para mantener un flujo de caja saludable. A menudo tienen dinero que no es para la recolección de cartas o facturas, pero inmediatamente necesitan dinero para continuar operando, pagando a los proveedores o invirtiendo en su crecimiento. En estos casos, una solución generalizada es reducir estas cartas o facturas, es decir, venderlas a la unidad financiera a cambio de recibir dinero antes de la fecha de vencimiento.
Sin embargo, este proceso no siempre es tan simple como parece. Las empresas deben calcular las tasas de descuento correctamente, saber cuánto les costará realmente esta operación y comprender cómo afecta su rentabilidad. Nuestra aplicación se usa aquí. El objetivo de este proyecto es desarrollar una aplicación web/móvil que ayude a las PYME a administrar su cartera de letras y facturas de una manera simple y eficiente. Con esta herramienta, pueden revelar y administrar sus documentos comerciales, establecer fechas de descuento y calcular automáticamente el porcentaje del costo efectivo anual (TCEA), todo rápidamente y sin complicaciones. Además, la aplicación opera en las plantas y en dólares y le permite elegir entre precios nominales o efectivos que se adapten a las necesidades de cada usuario.
La seguridad también es la clave, por lo que el acceso estará protegido por el usuario y la contraseña. Además, los mensajes detallados que muestran la cartera y su TCEA relevante pueden en cualquier momento, lo que permite a las empresas tomar mejores decisiones financieras.
En resumen, el propósito de esta aplicación es simplificar el proceso económico, que, si bien puede parecer técnico, es importante para la estabilidad y el crecimiento de muchas PYME. Al ofrecer una herramienta intuitiva y eficiente, queremos ayudar a más empresas a acceder a la liquidez sin complicaciones y con información clara sobre el costo y los beneficios de cada operación.

### Marco conceptual (fórmulas)
El descuento de letras y facturas es una operación financiera en la que una empresa obtiene liquidez inmediata cediendo sus documentos por cobrar a una entidad financiera a cambio de un monto menor al valor nominal. Para evaluar el costo de esta operación y su impacto en la empresa, se utilizan diversas fórmulas matemáticas que permiten calcular el Valor Recibido (VR) y la Tasa de Coste Efectivo Anual (TCEA).

  1. Valor Recibido (VR)
     El Valor Recibido (VR) es el monto que la empresa efectivamente obtiene después de aplicar el descuento financiero y otros gastos asociados a la transacción. Se calcula con la siguiente fórmula:
     ![image](https://github.com/user-attachments/assets/15884a8b-b173-4385-919e-77d36110f087)
     * VR = Valor Recibido por la empresa
     * VN = Valor nominal de la factura o letra
     * D = Monto descontado
     * G = Gastos adicionales (comisiones, costos administrativos, impuestos, etc.)

      NOTA: El monto descontado se obtiene con la siguiente fórmula:
      ![image](https://github.com/user-attachments/assets/58ee829c-1ebe-437f-bb8a-ee0db51a4453)
      Donde:
      * i = Tasa de descuento aplicada (nominal o efectiva)
      * t = Número de días hasta el vencimiento de la factura o letra
  2. Tasa de Coste Efectivo Anual (TCEA)
     La Tasa de Coste Efectivo Anual (TCEA) es un indicador financiero que refleja el costo total del descuento de una cartera de letras o facturas, expresado en términos anuales. Se calcula con la siguiente fórmula:
     ![image](https://github.com/user-attachments/assets/54592f24-e356-47c7-aba8-18068dbdd9fd)
     * TCEA = Tasa de Coste Efectivo Anual
     * VE = Valor entregado por la entidad financiera al vencimiento de la factura o letra
     * VR = Valor Recibido por la empresa después del descuento y gastos
     * n = Número de días hasta el vencimiento de la factura o letra
     
## Algoritmo
![diagrama_tcea](https://github.com/user-attachments/assets/e31b9033-b4ba-4b4b-821a-be20f71b3dea)

## Anexos
- Presentación de alto impacto académico/comercial de la aplicación, encartes, brochures informativos u otros materiales relacionados con la aplicación.

## Bibliografía
- Referencias bibliográficas utilizadas para el desarrollo del proyecto.
