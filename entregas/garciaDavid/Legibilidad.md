# Legibilidad

## Descripción
Aquí explico los fallos que he encontrado en mis códigos según la teoría de IDSW2.

| Asignatura       | Enlace |
|------------------|--------|
| **Programación 1** | [Code1](https://github.com/DavidGarciaCosta/prg1-22-23/blob/main/retos/entregas/davidGarcia/adivinar/Entrega2.java) |
| **Programación 1**          | [Code2](https://github.com/DavidGarciaCosta/PRG1-22-23-ExamenParcial/blob/main/entregas/garciaDavid/CarreraDeCamellosdavid.java) |
| **Programación 1**          | [Code3](https://github.com/DavidGarciaCosta/PRG1-22-23-ExamenExtraordinario/blob/main/garciaDavid/VisiCalc.java) |
| **Programación 2**          | [Code4](https://github.com/DavidGarciaCosta/progra2-22-23/tree/main/ejercicios/entregas/davidGarcia/EX000-PooIntroduccion/src) |

## Nombrado

**Nombres con caracteres especiales o poco convencionales** (área por area) [Code1](https://github.com/DavidGarciaCosta/prg1-22-23/blob/365b4b64c858de91ff012acbd813fdefd62fb138/retos/entregas/davidGarcia/adivinar/Entrega2.java#L16)

**Mayúsculas en nombres de variables** (no sigue la convención camelCase) [Code1](https://github.com/DavidGarciaCosta/prg1-22-23/blob/365b4b64c858de91ff012acbd813fdefd62fb138/retos/entregas/davidGarcia/adivinar/Entrega2.java#L25) | [Code1](https://github.com/DavidGarciaCosta/prg1-22-23/blob/365b4b64c858de91ff012acbd813fdefd62fb138/retos/entregas/davidGarcia/adivinar/Entrega2.java#L32)

**Nombres desinformativos** (x, y → Podrían llamarse numero1, numero2 para mayor claridad || l → Podría llamarse lado || b, h → Mejor base y altura || r → Mejor radio) [Code1](https://github.com/DavidGarciaCosta/prg1-22-23/blob/365b4b64c858de91ff012acbd813fdefd62fb138/retos/entregas/davidGarcia/adivinar/Entrega2.java#L9) | [Code1](https://github.com/DavidGarciaCosta/prg1-22-23/blob/365b4b64c858de91ff012acbd813fdefd62fb138/retos/entregas/davidGarcia/adivinar/Entrega2.java#L17) | [Code1](https://github.com/DavidGarciaCosta/prg1-22-23/blob/365b4b64c858de91ff012acbd813fdefd62fb138/retos/entregas/davidGarcia/adivinar/Entrega2.java#L23) | [Line](https://github.com/DavidGarciaCosta/prg1-22-23/blob/365b4b64c858de91ff012acbd813fdefd62fb138/retos/entregas/davidGarcia/adivinar/Entrega2.java#L24) | [Line](https://github.com/DavidGarciaCosta/prg1-22-23/blob/365b4b64c858de91ff012acbd813fdefd62fb138/retos/entregas/davidGarcia/adivinar/Entrega2.java#L30)

**Evitar nombres en serie** [Code1](https://github.com/DavidGarciaCosta/prg1-22-23/blob/365b4b64c858de91ff012acbd813fdefd62fb138/retos/entregas/davidGarcia/adivinar/Entrega2.java#L46)

## Comentarios

**Comentarios**(ausentes) [Code2](https://github.com/DavidGarciaCosta/PRG1-22-23-ExamenParcial/blob/44e7e7c1217a9f49065cddfe440bb96008c30852/entregas/garciaDavid/CarreraDeCamellosdavid.java#L15) | [Code2 14-30](https://github.com/DavidGarciaCosta/PRG1-22-23-ExamenParcial/blob/44e7e7c1217a9f49065cddfe440bb96008c30852/entregas/garciaDavid/CarreraDeCamellosdavid.java#L17)

## Formato y Consistencia 

**Mensaje de salida confusa** [Code2](https://github.com/DavidGarciaCosta/PRG1-22-23-ExamenParcial/blob/44e7e7c1217a9f49065cddfe440bb96008c30852/entregas/garciaDavid/CarreraDeCamellosdavid.java#L13) | [Code2](https://github.com/DavidGarciaCosta/PRG1-22-23-ExamenParcial/blob/44e7e7c1217a9f49065cddfe440bb96008c30852/entregas/garciaDavid/CarreraDeCamellosdavid.java#L45) | [Code2](https://github.com/DavidGarciaCosta/PRG1-22-23-ExamenParcial/blob/44e7e7c1217a9f49065cddfe440bb96008c30852/entregas/garciaDavid/CarreraDeCamellosdavid.java#L46)

**Línea Innecesaria**(Ecxel ya se pasa como parámetro) [Code3](https://github.com/DavidGarciaCosta/PRG1-22-23-ExamenExtraordinario/blob/8e999f8ea5442e3857fe7cf2a5b393e9b176e649/garciaDavid/VisiCalc.java#L86)

## Código Muerto 

**Uso incorrecto** [Code2](https://github.com/DavidGarciaCosta/PRG1-22-23-ExamenParcial/blob/44e7e7c1217a9f49065cddfe440bb96008c30852/entregas/garciaDavid/CarreraDeCamellosdavid.java#L5) | [Code2 9-12](https://github.com/DavidGarciaCosta/PRG1-22-23-ExamenParcial/blob/44e7e7c1217a9f49065cddfe440bb96008c30852/entregas/garciaDavid/CarreraDeCamellosdavid.java#L9)

**Eliminar línea** [Code3](https://github.com/DavidGarciaCosta/PRG1-22-23-ExamenExtraordinario/blob/8e999f8ea5442e3857fe7cf2a5b393e9b176e649/garciaDavid/VisiCalc.java#L86)

## DRY

**Código repetitivo** [Code2 17-44](https://github.com/DavidGarciaCosta/PRG1-22-23-ExamenParcial/blob/44e7e7c1217a9f49065cddfe440bb96008c30852/entregas/garciaDavid/CarreraDeCamellosdavid.java#L17)

**Código repetitivo** [Code3 79-83](https://github.com/DavidGarciaCosta/PRG1-22-23-ExamenExtraordinario/blob/8e999f8ea5442e3857fe7cf2a5b393e9b176e649/garciaDavid/VisiCalc.java#L79)

## YAGNI

**Variables sin utilidad** [Code2 9-12](https://github.com/DavidGarciaCosta/PRG1-22-23-ExamenParcial/blob/44e7e7c1217a9f49065cddfe440bb96008c30852/entregas/garciaDavid/CarreraDeCamellosdavid.java#L9)

**Main sin utilidad** [Code4](https://github.com/DavidGarciaCosta/progra2-22-23/blob/main/ejercicios/entregas/davidGarcia/EX000-PooIntroduccion/src/Main.java)

**Test sin utilidad** [Code4 17-35](https://github.com/DavidGarciaCosta/progra2-22-23/blob/e05244509481f4a6dfd344b11fab1c0d648fe0c8/ejercicios/entregas/davidGarcia/EX000-PooIntroduccion/src/BankAccountTest.java#L17)
