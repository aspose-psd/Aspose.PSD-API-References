---
title: "PsdImage.GlobalAngle"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété PsdImage. Obtient ou définit l'angle global"
type: docs
weight: 100
url: /fr/net/aspose.psd.fileformats.psd/psdimage/globalangle/
---
{{< psd/tize >}}
## PsdImage.GlobalAngle property

Obtient ou définit l'angle global.

```csharp
public int GlobalAngle { get; set; }
```

## Exemples

Le code suivant montre la prise en charge de la propriété PsdImage.GlobalAngle pour modifier la valeur de l'angle global.

```csharp
[C#]

// Lorsque la propriété DropShadowEffect.UseGlobalLight est 'true', l'objet DropShadowEffect utilise la valeur d'angle de la propriété PsdImage.GlobalAngle.

using (PsdImage image = (PsdImage)Image.Load("4.psd"))
{
    image.GlobalAngle = 30;
    image.Save("output.psd");
}
```

### Voir aussi

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


