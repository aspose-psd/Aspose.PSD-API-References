---
title: "Color.FromArgb"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método Color. Crea una estructura Color a partir de un valor ARGB de 32 bits"
type: docs
weight: 1430
url: /es/net/aspose.psd/color/fromargb/
---
{{< psd/tize >}}
## FromArgb(int) {#fromargb}

Crea una estructura [`Color`](../) a partir de un valor ARGB de 32 bits.

```csharp
public static Color FromArgb(int argb)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| argb | Int32 | Un valor que especifica el valor ARGB de 32 bits. |

### Valor devuelto

La estructura [`Color`](../) que este método crea.

### Ver también

* struct [Color](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FromArgb(int, int, int, int) {#fromargb_3}

Crea una estructura [`Color`](../) a partir de los cuatro valores de los componentes ARGB (alpha, red, green, y blue). Aunque este método permite pasar un valor de 32 bits para cada componente, el valor de cada componente está limitado a 8 bits.

```csharp
public static Color FromArgb(int alpha, int red, int green, int blue)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| alpha | Int32 | El componente alpha. Los valores válidos son de 0 a 255. |
| rojo | Int32 | El componente red. Los valores válidos son de 0 a 255. |
| verde | Int32 | El componente green. Los valores válidos son de 0 a 255. |
| azul | Int32 | El componente blue. Los valores válidos son de 0 a 255. |

### Valor devuelto

El [`Color`](../) que este método crea.

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentOutOfRangeException | *alpha*, *red*, *green* o *blue* es menor que 0 o mayor que 255. |

### Ver también

* struct [Color](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FromArgb(int, Color) {#fromargb_1}

Crea una estructura [`Color`](../) a partir de la estructura [`Color`](../) especificada, pero con el nuevo valor alfa especificado. Aunque este método permite pasar un valor de 32 bits para el valor alfa, el valor está limitado a 8 bits.

```csharp
public static Color FromArgb(int alpha, Color baseColor)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| alpha | Int32 | El valor alfa para el nuevo [`Color`](../). Los valores válidos son de 0 a 255. |
| baseColor | Color | El [`Color`](../) del cual crear el nuevo [`Color`](../). |

### Valor devuelto

El [`Color`](../) que este método crea.

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentOutOfRangeException | *alpha* es menor que 0 o mayor que 255. |

### Ver también

* struct [Color](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## FromArgb(int, int, int) {#fromargb_2}

Crea una estructura [`Color`](../) a partir de los valores de color de 8 bits especificados (rojo, verde y azul). El valor alfa es implícitamente 255 (totalmente opaco). Aunque este método permite pasar un valor de 32 bits para cada componente de color, el valor de cada componente está limitado a 8 bits.

```csharp
public static Color FromArgb(int red, int green, int blue)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| red | Int32 | El valor del componente rojo para el nuevo [`Color`](../). Los valores válidos son de 0 a 255. |
| green | Int32 | El valor del componente verde para el nuevo [`Color`](../). Los valores válidos son de 0 a 255. |
| blue | Int32 | El valor del componente azul para el nuevo [`Color`](../). Los valores válidos son de 0 a 255. |

### Valor devuelto

El [`Color`](../) que este método crea.

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentOutOfRangeException | *red*, *green* o *blue* es menor que 0 o mayor que 255. |

### Ver también

* struct [Color](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


