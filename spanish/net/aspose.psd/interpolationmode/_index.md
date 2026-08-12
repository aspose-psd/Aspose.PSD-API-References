---
title: "Enumeración InterpolationMode"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Aspose.PSD.InterpolationMode enum. La enumeración InterpolationMode especifica el algoritmo que se usa cuando las imágenes se escalan o rotan"
type: docs
weight: 5520
url: /es/net/aspose.psd/interpolationmode/
---
{{< psd/tize >}}
## InterpolationMode enumeration

La enumeración `InterpolationMode` especifica el algoritmo que se usa cuando las imágenes se escalan o rotan.

```csharp
public enum InterpolationMode
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Invalid | `-1` | Modo de interpolación no válido. |
| Default | `0` | Especifica el modo predeterminado. |
| Low | `1` | Especifica interpolación de baja calidad. |
| High | `2` | Especifica interpolación de alta calidad. |
| Bilinear | `3` | Especifica interpolación bilineal. No se realiza prefiltrado. Este modo no es adecuado para reducir una imagen por debajo del 50 % de su tamaño original. |
| Bicubic | `4` | Especifica interpolación bicúbica. No se realiza prefiltrado. Este modo no es adecuado para reducir una imagen por debajo del 25 % de su tamaño original. |
| NearestNeighbor | `5` | Especifica interpolación del vecino más cercano. |
| HighQualityBilinear | `6` | Especifica interpolación bilineal de alta calidad. Se realiza prefiltrado para garantizar una reducción de alta calidad. |
| HighQualityBicubic | `7` | Especifica interpolación bicúbica de alta calidad. Se realiza prefiltrado para garantizar una reducción de alta calidad. Este modo produce las imágenes transformadas de mayor calidad. |

### Ver también

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


