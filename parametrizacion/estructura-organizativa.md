# 🏗️ Definición y Asignación de Elementos de Estructura Organizativa

Este documento describe la creación y asignación de elementos organizativos en SAP S/4HANA MM para facilitar la gestión logística.

---

## 🎯 Objetivo

Establecer una estructura organizativa funcional que permita gestionar eficazmente los procesos de aprovisionamiento y almacenamiento.

---

## 🧩 Elementos creados

### 🏢 Sociedad
- Se utiliza la sociedad existente: **1010**

### 🏭 Centro
- Se ha creado el centro **Z19** por copia del centro estándar **1010**
- Este centro será el núcleo operativo para los almacenes definidos

### 🗂️ Almacenes asociados al centro Z19
Se han creado 4 almacenes siguiendo la codificación establecida:

| Código | Nombre     | Ubicación aproximada |
|--------|------------|----------------------|
| 01     | Huelva     | Huelva               |
| 02     | Palos      | Palos de la Frontera |
| 03     | Aracena    | Aracena              |
| 04     | Jabugo     | Jabugo               |

---

## 🛠️ Método de creación

- El centro Z19 se creó copiando la configuración del centro 1010, siguiendo las instrucciones del sistema.
- Los almacenes se asignaron al centro Z19 respetando la codificación y nomenclatura funcional.

---

## 📌 Observaciones

- Esta estructura permite una gestión descentralizada del inventario.
- Facilita la trazabilidad de materiales por ubicación física.
- Mejora la eficiencia en procesos logísticos como entradas, salidas y transferencias.

 ## Definición y Asignación de Elementos de Estructura Organizativa

La configuración de la estructura organizativa se realiza a través del menú de customizing en SAP, accediendo mediante la transacción **SPRO**.

A continuación se muestra un ejemplo de la definición de una sociedad utilizando la transacción **OX01**:

![Definición de sociedad en OX01](imagenes/ox01-definicion-sociedad.png)

> En esta pantalla se introducen los datos clave de la sociedad, como el nombre, país y moneda.

<img width="886" height="471" alt="image" src="https://github.com/user-attachments/assets/6d6a4584-24ca-4306-9c8b-414d9ddaae43" />
<img width="886" height="471" alt="image" src="https://github.com/user-attachments/assets/543cf583-3d7a-4130-bc50-de38721fc116" />
<img width="886" height="471" alt="image" src="https://github.com/user-attachments/assets/2c1dcd8b-63fc-4c23-af87-a3ceec123bab" />

![Definición de sociedad en OX01](imagenes/ox01-definicion-sociedad.png)

> ![Definición de centro en OX02](imagenes/ox02-definicion-centro.png)

> Aquí se configuran los centros logísticos que forman parte de la estructura operativa.
![Asignación en SPRO](imagenes/spro-asignacion-compras.png)

> En esta vista se realiza la vinculación entre la organización de compras y la sociedad correspondiente.

---

## 🔗 Documentos Relacionados

- [Configuración de Centros](configuracion-centros.md)
- [Glosario SAP MM](../glosario.md)
