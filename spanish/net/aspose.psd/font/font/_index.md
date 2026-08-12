---
title: "Font.Font"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Constructor de Font. Inicializa un nuevo Font que utiliza la Font existente especificada y la enumeración FontStyle."
type: docs
weight: 10
url: /es/net/aspose.psd/font/font/
---
{{< psd/tize >}}
## Font(Font, FontStyle) {#constructor}

Inicializa un nuevo [`Font`](../) que utiliza la [`Font`](../) existente especificada y la enumeración [`FontStyle`](../../fontstyle/).

```csharp
public Font(Font prototype, FontStyle newStyle)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| prototype | Font | La [`Font`](../) existente a partir de la cual crear la nueva [`Font`](../). |
| newStyle | FontStyle | El [`FontStyle`](../../fontstyle/) a aplicar a la nueva [`Font`](../). Se pueden combinar múltiples valores de la enumeración [`FontStyle`](../../fontstyle/) con el operador OR. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *prototype* es nulo. |

### Ver también

* enum [FontStyle](../../fontstyle/)
* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Font(string, float) {#constructor_1}

Inicializa un nuevo [`Font`](../) usando un tamaño especificado. El conjunto de caracteres se establece en Default, la unidad gráfica en Point, el estilo de fuente en Regular.

```csharp
public Font(string fontName, float emSize)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontName | String | Una representación en cadena del nombre del [`Font`](../). |
| emSize | Single | El tamaño em, en puntos, de la nueva fuente. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* es menor o igual a 0, evalúa a infinito o no es un número válido. |
| ArgumentNullException | *fontName* es nulo. |

### Ver también

* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle) {#constructor_2}

Inicializa un nuevo [`Font`](../) usando un tamaño y estilo especificados. El conjunto de caracteres se establece en Default, la unidad gráfica en Point.

```csharp
public Font(string fontName, float emSize, FontStyle style)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontName | String | Una representación en cadena del nombre del [`Font`](../). |
| emSize | Single | El tamaño em, en puntos, de la nueva fuente. |
| style | FontStyle | El [`FontStyle`](../../fontstyle/) de la nueva fuente. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* es menor o igual a 0, evalúa a infinito o no es un número válido. |
| ArgumentNullException | *fontName* es nulo. |

### Ver también

* enum [FontStyle](../../fontstyle/)
* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Font(string, float, GraphicsUnit) {#constructor_5}

Inicializa un nuevo [`Font`](../) usando un tamaño y unidad especificados. El conjunto de caracteres se establece en Default, el estilo se establece en Regular.

```csharp
public Font(string fontName, float emSize, GraphicsUnit unit)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontName | String | Una representación en cadena del nombre del [`Font`](../). |
| emSize | Single | El tamaño em de la nueva fuente en las unidades especificadas por el parámetro *unit*. |
| unit | GraphicsUnit | El [`GraphicsUnit`](../../graphicsunit/) de la nueva fuente. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* es menor o igual a 0, evalúa a infinito o no es un número válido. |
| ArgumentNullException | *fontName* es nulo. |

### Ver también

* enum [GraphicsUnit](../../graphicsunit/)
* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit, CharacterSet) {#constructor_4}

Inicializa un nuevo [`Font`](../) usando un tamaño, estilo, unidad y conjunto de caracteres especificados.

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit, 
    CharacterSet characterSet)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontName | String | Una representación en cadena del nombre del [`Font`](../). |
| emSize | Single | El tamaño em de la nueva fuente en las unidades especificadas por el parámetro *unit*. |
| style | FontStyle | El [`FontStyle`](../../fontstyle/) de la nueva fuente. |
| unit | GraphicsUnit | El [`GraphicsUnit`](../../graphicsunit/) de la nueva fuente. |
| characterSet | CharacterSet | Un conjunto de caracteres para usar con esta fuente. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* es menor o igual a 0, evalúa a infinito o no es un número válido. |
| ArgumentNullException | *fontName* es nulo. |

### Ver también

* enum [FontStyle](../../fontstyle/)
* enum [GraphicsUnit](../../graphicsunit/)
* enum [CharacterSet](../../characterset/)
* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit) {#constructor_3}

Inicializa un nuevo [`Font`](../) usando un tamaño, estilo y unidad especificados.

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontName | String | Una representación en cadena del nombre del [`Font`](../). |
| emSize | Single | El tamaño em de la nueva fuente en las unidades especificadas por el parámetro *unit*. |
| style | FontStyle | El [`FontStyle`](../../fontstyle/) de la nueva fuente. |
| unit | GraphicsUnit | El [`GraphicsUnit`](../../graphicsunit/) de la nueva fuente. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* es menor o igual a 0, evalúa a infinito o no es un número válido. |
| ArgumentNullException | *fontName* es nulo. |

### Ver también

* enum [FontStyle](../../fontstyle/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Font](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


