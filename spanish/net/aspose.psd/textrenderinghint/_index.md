---
title: "Enumeración TextRenderingHint"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Enumeración Aspose.PSD.TextRenderingHint. Especifica la calidad del renderizado de texto"
type: docs
weight: 6200
url: /es/net/aspose.psd/textrenderinghint/
---
{{< psd/tize >}}
## TextRenderingHint enumeration

Especifica la calidad del renderizado de texto.

```csharp
public enum TextRenderingHint
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| SystemDefault | `0` | Cada carácter se dibuja usando su mapa de bits de glifo, con la sugerencia de renderizado predeterminada del sistema. El texto se dibujará usando cualquier configuración de suavizado de fuentes que el usuario haya seleccionado para el sistema. |
| SingleBitPerPixelGridFit | `1` | Cada carácter se dibuja usando su mapa de bits de glifo. El hinting se usa para mejorar la apariencia de los caracteres en los tallos y curvas. |
| SingleBitPerPixel | `2` | Cada carácter se dibuja usando su mapa de bits de glifo. No se utiliza hinting. |
| AntiAliasGridFit | `3` | Cada carácter se dibuja usando su mapa de bits de glifo antialiasado con hinting. Mucha mejor calidad gracias al antialiasing, pero con un mayor costo de rendimiento. |
| AntiAlias | `4` | Cada carácter se dibuja usando su mapa de bits de glifo antialiasado sin hinting. Mejor calidad gracias al antialiasing. Las diferencias de ancho de los tallos pueden ser notables porque el hinting está desactivado. |
| ClearTypeGridFit | `5` | Cada carácter se dibuja usando su mapa de bits de glifo ClearType con hinting. La configuración de mayor calidad. Se usa para aprovechar las características de fuentes ClearType. |

### Ver también

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


