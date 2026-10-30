# punto_venta_dolores
Paso 1.2 · Prueba ROJA: formatear pesos
<img width="1931" height="486" alt="image" src="https://github.com/user-attachments/assets/b3daaada-12a5-479e-ab24-161f387f873b" />



Paso 1.3 · Verde: implementar
<img width="1904" height="97" alt="image" src="https://github.com/user-attachments/assets/b70de43d-5ecc-4851-ae47-cd6f2e0bc8f2" />




Paso 1.4 · Segunda prueba: texto a centavos
<img width="1913" height="814" alt="image" src="https://github.com/user-attachments/assets/e689306b-b079-468b-9977-a6430d9b4602" />



Reemplaza dinero.dart por la versión completa: Verde
<img width="888" height="118" alt="image" src="https://github.com/user-attachments/assets/c966a335-24cd-431f-b8ef-e06cb6dbb3cc" />



Paso 2.1 · Prueba ROJA
<img width="1922" height="846" alt="image" src="https://github.com/user-attachments/assets/52b029eb-d78b-498a-8df9-498a6ec10a2f" />






Paso 2.2 · VERDE
<img width="994" height="122" alt="image" src="https://github.com/user-attachments/assets/904cb37a-3d30-4643-aa7e-c4ebbc586278" />




Ciclo 3.1 · Sumar cantidades
🔴 ROJO: escribe la prueba (debe FALLAR)
<img width="1928" height="816" alt="image" src="https://github.com/user-attachments/assets/dc04ac67-baaa-472c-98fd-3c8dfa68ee08" />




🟢 VERDE: el código mínimo para pasar
Versión mínima de carrito.dart (aún sin validaciones ni IVA real):
📄 lib/dominio/carrito.dart  (versión 1)
<img width="780" height="122" alt="image" src="https://github.com/user-attachments/assets/3a8fb4b3-913b-4494-9a5f-380fc9855a1f" />





Ciclo 3.2 · No vender lo que no hay
🔴 ROJO: escribe la prueba (debe FALLAR)
Solo queda 1 nieve; el cliente intenta llevarse 2.
<img width="1915" height="472" alt="image" src="https://github.com/user-attachments/assets/cd220b1b-0ff4-41db-9bed-8eea4eeefb24" />








🟢 VERDE: el código mínimo para pasar
Dentro de agregar, antes de modificar nada, valida:
<img width="1155" height="120" alt="image" src="https://github.com/user-attachments/assets/37345db6-a6d6-4205-bd89-57efa7a38792" />










Ciclo 3.3 · IVA incluido, con enteros DEBE FALLAR
<img width="1935" height="809" alt="image" src="https://github.com/user-attachments/assets/b520b61a-25cc-471d-bd4f-0341392ab9c7" />










🟢 VERDE: el código mínimo para pasar
Versión final de carrito.dart completa (con tasa configurable, quitar, vaciar y cambio):
<img width="787" height="111" alt="image" src="https://github.com/user-attachments/assets/9715459f-9a86-4866-8863-4724fbe9fef9" />














Ciclo 3.4 · Cambio, pago corto y carrito vacío
🔴 ROJO: escribe la prueba (debe FALLAR)
Tres situaciones reales de caja:
<img width="1917" height="868" alt="image" src="https://github.com/user-attachments/assets/b23ce4a1-1ae4-4a06-b003-71496adebc28" />






🟢 VERDE: el código mínimo para pasar
El método cambio() ya está en la versión final de arriba. Ejecuta flutter test: las 11 pruebas del dominio deben pasar.
<img width="821" height="102" alt="image" src="https://github.com/user-attachments/assets/62397036-0a9e-4116-943c-f8bbd21703cb" />








Ciclo 4.3 · Guardar y buscar
🔴 ROJO: escribe la prueba (debe FALLAR)
Escribe dos pruebas dentro de main():
<img width="1919" height="801" alt="image" src="https://github.com/user-attachments/assets/d188b99a-e1bb-441e-a2e6-650d21f3f6ce" />











Ciclo 5.1 · Cobrar descuenta inventario
🔴 ROJO: escribe la prueba (debe FALLAR)
Compramos 2 de 5 nieves y pagamos $100.00 (total $50.00, cambio $50.00):











