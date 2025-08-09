# 📝 Manual de Usuario: Crear Pedido de Compra

Este manual describe el proceso paso a paso para crear un pedido de compra en SAP S/4HANA MM.

---

## 🎯 Objetivo

Permitir al usuario crear un pedido de compra para adquirir materiales o servicios de un proveedor externo.

---

## 🧭 Navegación SAP

**Transacción:** `ME21N`  
**Ruta:** Logística → Gestión de materiales → Compras → Pedido → Crear

---

## 🛠️ Pasos para Crear el Pedido

1. **Seleccionar tipo de documento:** NB (Pedido estándar)
2. **Ingresar proveedor:** Código del proveedor en el campo correspondiente
3. **Definir organización de compras y centro**
4. **Añadir posición del pedido:**
   - Código de material
   - Cantidad
   - Fecha de entrega
   - Precio
5. **Verificar condiciones de precio**
6. **Guardar el pedido**

---

## 📌 Notas Importantes

- El proveedor debe estar activo y asignado a la organización de compras.
- El material debe estar extendido al centro correspondiente.
- Verifica que el pedido esté completo antes de guardar.

---

## 📷 Ejemplo Visual

<img width="1920" height="1020" alt="pedido cacao" src="https://github.com/user-attachments/assets/6fec9bda-c238-4663-8922-c87cb1ffecee" />


---

## 🔗 Documentos Relacionados

- [Glosario SAP MM](../glosario.md)
- [Caso de Prueba: Pedido de Compra](../pruebas-funcionales/caso-prueba-pedido-compra.md)
