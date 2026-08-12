---
title: "RawColor.RawColor"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Constructor RawColor. Inicializa una nueva instancia de la clase RawColor"
type: docs
weight: 10
url: /es/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/rawcolor/
---
{{< psd/tize >}}
## RawColor(ColorComponent[]) {#constructor}

Inicializa una nueva instancia de la clase [`RawColor`](../).

```csharp
public RawColor(ColorComponent[] components)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| componentes | ColorComponent[] | Los componentes de color personalizados. |

### Ver también

* class [ColorComponent](../../colorcomponent/)
* class [RawColor](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)

---

## RawColor(PixelDataFormat, short) {#constructor_1}

Inicializa una nueva instancia de la clase [`RawColor`](../) a partir del formato de datos de píxel usando modos de color predefinidos

```csharp
public RawColor(PixelDataFormat pixelDataFormat, short colorMode = 0)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pixelDataFormat | PixelDataFormat | El formato de datos de píxel. |
| colorMode | Int16 | Modo que seguirá el color. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | El recuento de canales difiere de PixelFormat, no se puede obtener el índice de los canales. Por favor, cree RawColor con el argumento de la matriz de Componentes |

### Ver también

* class [PixelDataFormat](../../../aspose.psd/pixeldataformat/)
* class [RawColor](../)
* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../../)


