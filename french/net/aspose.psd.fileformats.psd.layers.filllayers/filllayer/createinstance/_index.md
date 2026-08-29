---
title: "FillLayer.CreateInstance"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Méthode FillLayer. Crée une nouvelle instance de la classe FillLayer selon le type de remplissage."
type: docs
weight: 10
url: /fr/net/aspose.psd.fileformats.psd.layers.filllayers/filllayer/createinstance/
---
{{< psd/tize >}}
## FillLayer.CreateInstance method

Créez une nouvelle instance de la classe [`FillLayer`](../) selon le type de remplissage.

```csharp
public static FillLayer CreateInstance(FillType fillType)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fillType | FillType | Le type de couche de remplissage. |

### Valeur de retour

Renvoie une nouvelle instance de la classe [`FillLayer`](../) selon le type de remplissage.

## Exemples

L'exemple suivant montre comment ajouter la couche de type FillLayer à l'exécution.

```csharp
[C#]

string outputFilePath = "output.psd";

using (var image = new PsdImage(100, 100))
{
    FillLayer colorFillLayer = FillLayer.CreateInstance(FillType.Color);
    colorFillLayer.DisplayName = "Color Fill Layer";
    image.AddLayer(colorFillLayer);

    FillLayer gradientFillLayer = FillLayer.CreateInstance(FillType.Gradient);
    gradientFillLayer.DisplayName = "Gradient Fill Layer";
    image.AddLayer(gradientFillLayer);

    FillLayer patternFillLayer = FillLayer.CreateInstance(FillType.Pattern);
    patternFillLayer.DisplayName = "Pattern Fill Layer";
    patternFillLayer.Opacity = 50;
    image.AddLayer(patternFillLayer);

    image.Save(outputFilePath);
}
```

### Voir aussi

* enum [FillType](../../../aspose.psd.fileformats.psd.layers.fillsettings/filltype/)
* class [FillLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillLayers](../../../aspose.psd.fileformats.psd.layers.filllayers/)
* assembly [Aspose.PSD](../../../)


