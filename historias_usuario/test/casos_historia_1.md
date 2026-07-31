# Casos de Prueba - Historia de Usuario 01
## HU-01: Registro de usuario

---

# TC-001 - Registro exitoso de usuario

## Objetivo
Verificar que un visitante pueda crear una cuenta utilizando un correo electrónico válido y una contraseña que cumpla los requisitos de seguridad.

## Precondiciones
- El usuario no debe estar registrado.
- La aplicación debe estar disponible.

## Datos de prueba
- Correo: usuario@test.com
- Contraseña: Password123*

## Pasos
1. Ingresar a la pantalla de registro.
2. Escribir un correo electrónico válido.
3. Escribir una contraseña válida.
4. Presionar el botón "Registrarse".

## Resultado esperado
El sistema registra correctamente al usuario, muestra un mensaje de confirmación y permite iniciar sesión.

## Resultado obtenido
Pendiente.

## Estado
Pendiente.

## Notas / Evidencias
Pendiente.

---

# TC-002 - Registro con correo ya existente

## Objetivo
Verificar que el sistema impida registrar un correo electrónico previamente utilizado.

## Precondiciones
- El correo usuario@test.com ya se encuentra registrado.

## Datos de prueba
- Correo: usuario@test.com
- Contraseña: Password123*

## Pasos
1. Ingresar a la pantalla de registro.
2. Escribir un correo ya registrado.
3. Escribir una contraseña válida.
4. Presionar el botón "Registrarse".

## Resultado esperado
El sistema muestra un mensaje indicando que el correo ya existe y no crea una nueva cuenta.

## Resultado obtenido
Pendiente.

## Estado
Pendiente.

## Notas / Evidencias
Pendiente.