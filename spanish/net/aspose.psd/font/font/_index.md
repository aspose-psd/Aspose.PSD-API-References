---
title: Font.Font
second_title: Referencia de API de Aspose.PSD para .NET
description: Font constructor. Inicializa un nuevoFont que utiliza el especificado existenteFont yFontStyle enumeración.
type: docs
weight: 10
url: /es/net/aspose.psd/font/font/
---
## Font(Font, FontStyle) {#constructor}

Inicializa un nuevo[`Font`](../) que utiliza el especificado existente[`Font`](../) y[`FontStyle`](../../fontstyle/) enumeración.

```csharp
public Font(Font prototype, FontStyle newStyle)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| prototype | Font | La existencia[`Font`](../) a partir de la cual crear el nuevo[`Font`](../). |
| newStyle | FontStyle | El[`FontStyle`](../../fontstyle/) para aplicar a la nueva[`Font`](../) . Múltiples valores de la[`FontStyle`](../../fontstyle/) La enumeración se puede combinar con el operador OR. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *prototype* es nulo. |

### Ver también

* enum [FontStyle](../../fontstyle/)
* class [Font](../)
* espacio de nombres [Aspose.PSD](../../font/)
* asamblea [Aspose.PSD](../../../)

---

## Font(string, float) {#constructor_1}

Inicializa un nuevo[`Font`](../) usando un tamaño específico. El conjunto de caracteres se establece enDefault , la unidad gráfica paraPoint , el estilo de fuente paraRegular .

```csharp
public Font(string fontName, float emSize)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fontName | String | Una representación de cadena de la[`Font`](../) nombre. |
| emSize | Single | El tamaño em, en puntos, de la nueva fuente. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* es menor o igual a 0, se evalúa como infinito o no es un número válido. |
| ArgumentNullException | *fontName* es nulo. |

### Ver también

* class [Font](../)
* espacio de nombres [Aspose.PSD](../../font/)
* asamblea [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle) {#constructor_2}

Inicializa un nuevo[`Font`](../) usando un tamaño y estilo especificado. El conjunto de caracteres se establece enDefault , la unidad gráfica paraPoint .

```csharp
public Font(string fontName, float emSize, FontStyle style)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fontName | String | Una representación de cadena de la[`Font`](../) nombre. |
| emSize | Single | El tamaño em, en puntos, de la nueva fuente. |
| style | FontStyle | El[`FontStyle`](../../fontstyle/) de la nueva fuente. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* es menor o igual a 0, se evalúa como infinito o no es un número válido. |
| ArgumentNullException | *fontName* es nulo. |

### Ver también

* enum [FontStyle](../../fontstyle/)
* class [Font](../)
* espacio de nombres [Aspose.PSD](../../font/)
* asamblea [Aspose.PSD](../../../)

---

## Font(string, float, GraphicsUnit) {#constructor_5}

Inicializa un nuevo[`Font`](../) utilizando un tamaño y una unidad específicos. El conjunto de caracteres se establece enDefault el estilo se establece enRegular .

```csharp
public Font(string fontName, float emSize, GraphicsUnit unit)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fontName | String | Una representación de cadena de la[`Font`](../) nombre. |
| emSize | Single | El tamaño em de la nueva fuente en las unidades especificadas por el*unit* parámetro. |
| unit | GraphicsUnit | El[`GraphicsUnit`](../../graphicsunit/) de la nueva fuente. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* es menor o igual a 0, se evalúa como infinito o no es un número válido. |
| ArgumentNullException | *fontName* es nulo. |

### Ver también

* enum [GraphicsUnit](../../graphicsunit/)
* class [Font](../)
* espacio de nombres [Aspose.PSD](../../font/)
* asamblea [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit, CharacterSet) {#constructor_4}

Inicializa un nuevo[`Font`](../) utilizando un tamaño, estilo, unidad y conjunto de caracteres especificados.

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit, 
    CharacterSet characterSet)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fontName | String | Una representación de cadena de la[`Font`](../) nombre. |
| emSize | Single | El tamaño em de la nueva fuente en las unidades especificadas por el*unit* parámetro. |
| style | FontStyle | El[`FontStyle`](../../fontstyle/) de la nueva fuente. |
| unit | GraphicsUnit | El[`GraphicsUnit`](../../graphicsunit/) de la nueva fuente. |
| characterSet | CharacterSet | Un juego de caracteres para usar con esta fuente. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* es menor o igual a 0, se evalúa como infinito o no es un número válido. |
| ArgumentNullException | *fontName* es nulo. |

### Ver también

* enum [FontStyle](../../fontstyle/)
* enum [GraphicsUnit](../../graphicsunit/)
* enum [CharacterSet](../../characterset/)
* class [Font](../)
* espacio de nombres [Aspose.PSD](../../font/)
* asamblea [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit) {#constructor_3}

Inicializa un nuevo[`Font`](../) utilizando un tamaño, estilo y unidad especificados.

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fontName | String | Una representación de cadena de la[`Font`](../) nombre. |
| emSize | Single | El tamaño em de la nueva fuente en las unidades especificadas por el*unit* parámetro. |
| style | FontStyle | El[`FontStyle`](../../fontstyle/) de la nueva fuente. |
| unit | GraphicsUnit | El[`GraphicsUnit`](../../graphicsunit/) de la nueva fuente. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* es menor o igual a 0, se evalúa como infinito o no es un número válido. |
| ArgumentNullException | *fontName* es nulo. |

### Ver también

* enum [FontStyle](../../fontstyle/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Font](../)
* espacio de nombres [Aspose.PSD](../../font/)
* asamblea [Aspose.PSD](../../../)


