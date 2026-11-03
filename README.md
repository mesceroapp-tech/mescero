# Mes Cero

Calculadora de salida de deudas. Una sola página, sin servidor, sin cuentas.
Todo el cálculo corre en el navegador del usuario: nada de lo que escriben sale de su dispositivo.

## Por qué existe
Las calculadoras de deuda que hay son gringas y asumen tarjetas revolventes.
En Latinoamérica casi todo es cuota fija y la gente sabe "me faltan 28 cuotas de 2,345",
no el capital. Si ese total se toma como saldo, se cobra el interés dos veces.
`capitalDe()` lo descuenta con la fórmula de anualidad. Esa es la diferencia.

## Costo de operación
Cero. Es un archivo estático. Cuesta lo mismo con 10 visitas que con 10 millones.

## Desplegar
Cloudflare Pages o Render (static site), apuntando al repo. Sin build.

## Pendiente
- Dominio propio
- Artículos de blog para SEO (es el canal de este producto)
- Desbloqueo de pago: guardar plan, PDF, seguimiento mensual
