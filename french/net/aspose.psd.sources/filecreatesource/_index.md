---
title: "Classe FileCreateSource"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.Sources.FileCreateSource. Représente une source de fichier pour la création"
type: docs
weight: 6090
url: /fr/net/aspose.psd.sources/filecreatesource/
---
{{< psd/tize >}}
## FileCreateSource class

Représente une source de fichier pour la création.

```csharp
public sealed class FileCreateSource : FileSource
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [FileCreateSource](filecreatesource/#constructor)(string) | Initialise une nouvelle instance de la classe `FileCreateSource`. |
| [FileCreateSource](filecreatesource/#constructor_1)(string, bool) | Initialise une nouvelle instance de la classe `FileCreateSource`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [FilePath](../../aspose.psd.sources/filecreatesource/filepath/) { get; } | Obtient le chemin du fichier à créer. |
| override [IsTemporal](../../aspose.psd.sources/filecreatesource/istemporal/) { get; } | Obtient une valeur indiquant si le fichier sera temporaire. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [GetStreamContainer](../../aspose.psd.sources/filecreatesource/getstreamcontainer/)() | Obtient le conteneur de flux. |

## Exemples

Cet exemple montre l'utilisation des classes Font et SolidBrush pour dessiner des chaînes sur la surface Image. L'exemple crée une nouvelle Image et dessine des formes à l'aide de Figures et de GraphicsPath

```csharp
[C#]

//Crée une instance de Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Crée et initialise une instance de la classe Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Efface la surface Graphics
    graphics.Clear(Color.Wheat);

    //Crée une instance de Font
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    //Crée une instance de SolidBrush avec la couleur rouge
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    //Dessine une chaîne
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // crée des options d'exportation.
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // enregistrez toutes les modifications
    image.Save("C:\\temp\\output.gif", options);
}
```

### Voir aussi

* class [FileSource](../filesource/)
* namespace [Aspose.PSD.Sources](../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../)


