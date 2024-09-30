# INFORME TÉCNICO
<br>

## MODELOS DE EJECUCIÓN
### Arquitectura Cliente-Servidor
Es una arquitectura en la que participan dos componentes, el cliente, que consume unos servicios, y el servidor, que los proporciona. Entre ambos se efectua una comunicación de red principalmente mediante el protocolo de comunicación HTTP, aunque existen otros como SMTP para el correo electrónico o FTP para la transferencia de archivos.
<br>

El cliente es el navegador o equipo del usuario, mientras que el servidor es el equipo donde estarían instaladas las aplicaciones o servicios. Dentro de los servidores existen diversos tipos como servidores web, de correo, servidores de bases de datos, etc.
<br>

La función de la arquitectura cliente-servidor es realizar la separación de las funciones y responsabilidades del software en distintas capas.
<br>
<br>

Los distintos modelos de arquitecturas cliente-servidor:
- **Arquitectura de dos niveles** : Los clientes realizan solicitudes directas al servidor sin la intervención de intermediarios.
    - Ejemplo: Videojuegos online.

- **Arquitectura de tres niveles** : Se introduce un intermediario entre el cliente y el servidor que tiene normalmente la responsabilidad de aplicar una capa de lógica de negocio.
    - Ejemplo: Redes sociales.
<br>
<br>


## LENGUAJES DE PROGRAMACIÓN MÁS USADOS EN CLIENTE
### JavaScript
Es un lenguaje interpretado, débilmente tipado y con tipos dinámicos.
- Sus ventajas son su rápidez de desarrollo y poca verbosidad.
- Sus desventajas son su lentitud de ejecución y su falta de seguridad debido al tipado débil y dinámico.

### TypeScript
Es un lenguaje interpretado, fuertemente tipado y con tipos estáticos.
- Sus ventajas son la rapidez de desarrollo, poca verbosidad y seguridad de tipos.
- Sus desventaja es su lentitud de ejecución.

### C# (Blazor)
Es un lenguaje compilado, fuertemente tipado y con tipos estáticos.
- Sus ventajas son su velocidad de ejecución y su seguridad de tipos.
- Sus desventajas son su velocidad de desarrollo más tediosa y una verbosidad superior.
<br>
<br>


## COMPATIBILIDAD DE NAVEGADORES
Los principales problemas de compatibilidad con los navegadores son: 
- **Validación de HTML y CSS** : El código se lee y se gestiona de forma diferente según el navegador utilizado.
    - Solución: Utilización de herramientas de validación de código.
- **Falta de Resets CSS** : Los navegadores utilizan por defecto su propio estilo CSS. Para usar el propio es necesario sobreescribir el predeterminado. Si no se hace, la página web puede mostrarse de forma diferente según el navegador que se utilice.
    - Solución: Utilizar hojas de estilo de reset CSS.
- **Error de DOCTYPE** : No poner el Doctype puede causar errores en la representación de nuestra web (especialmente en navegadores antiguos).
    - Solución: Escribir: !DOCTYPE html en los archivos de nuestra web.
- **Problemas con JavaScript** : Los problemas de compatibilidad pueden producirse al utilizar funciones modernas navegadores antiguos o versiones obsoletas.
    - Solución: Utilizar herramientas como Caniuse para comprobar la compatibilidad del código con los distintos navegadores y versiones.
- **Problemas de compatibilidad del diseño** : El diseño por defecto de los navegadores puede causar problemas de compatibilidad multi navegador.
    - Solución: Usar herramientas como Flexbox y CSS grids para trabajar con diseños modernos.
- **Utilizar librerías y frameworks multi navegador no confiables** : Utilizar frameworks y bibliotecas no confiables, puede haber problemas de compatibilidad multi navegador.
    - Solución: Utilizar frameworks conocidos y de confianza.
- **No utilizar hojas de estilo independientes para los diferentes navegadores** : Los navegadores más antiguos no admiten los elementos de estilo más recientes.
    - Solución: Utilizar una hoja de estilo distinta para cada navegador.
- **Detección de navegadores obsoletos** : La detección de los navegadores obsoletos a menudo es un problema con JavaScript.
    - Solución: Eliminar la detección del navegador.
- **Falta de pruebas en dispositivos reales** : Para garantizar que la web no tiene errores y funciona en varios navegadores y dispositivos, es mejor probarla en dispositivos reales.
    - Solución: Uso de dispositivos reales.
