---
title: "Classe ProgressEventHandlerInfo"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.ProgressManagement.ProgressEventHandlerInfo. Cette classe représente les informations sur la progression des opérations de chargement/enregistrement/exportation d'image qui peuvent être utilisées dans une application externe pour afficher la progression de la conversion à l'utilisateur final."
type: docs
weight: 5800
url: /fr/net/aspose.psd.progressmanagement/progresseventhandlerinfo/
---
{{< psd/tize >}}
## ProgressEventHandlerInfo class

Cette classe représente les informations sur la progression des opérations de chargement/enregistrement/exportation d'images, qui peuvent être utilisées dans une application externe pour afficher la progression de la conversion à l'utilisateur final

```csharp
public class ProgressEventHandlerInfo
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Description](../../aspose.psd.progressmanagement/progresseventhandlerinfo/description/) { get; } | Obtient la description de l'événement |
| [EventType](../../aspose.psd.progressmanagement/progresseventhandlerinfo/eventtype/) { get; } | Obtient le type de l'événement. |
| [MaxValue](../../aspose.psd.progressmanagement/progresseventhandlerinfo/maxvalue/) { get; } | Obtient la limite supérieure de la valeur de progression. |
| [Value](../../aspose.psd.progressmanagement/progresseventhandlerinfo/value/) { get; } | Obtient la valeur de progression actuelle. |

## Exemples

L'exemple suivant montre que la progression de la conversion de document fonctionne correctement et sans exception.

```csharp
[C#]

string sourceFilePath = "Apple.psd";
Stream outputStream = new MemoryStream();

Aspose.PSD.ProgressEventHandler localProgressEventHandler = delegate(ProgressEventHandlerInfo progressInfo)
{
    string message = string.Format(
        "{0} {1}: {2} out of {3}",
        progressInfo.Description,
        progressInfo.EventType,
        progressInfo.Value,
        progressInfo.MaxValue);
    Console.WriteLine(message);
};

Console.WriteLine("---------- Loading Apple.psd ----------");
var loadOptions = new PsdLoadOptions() { ProgressEventHandler = localProgressEventHandler };
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath, loadOptions))
{
    Console.WriteLine("---------- Saving Apple.psd to PNG format ----------");
    image.Save(
        outputStream,
        new PngOptions()
            {
                ColorType = PngColorType.Truecolor,
                ProgressEventHandler = localProgressEventHandler
            });

    Console.WriteLine("---------- Saving Apple.psd to PSD format ----------");
    image.Save(
        outputStream,
        new PsdOptions()
            {
                ColorMode = ColorModes.Rgb,
                ChannelsCount = 4,
                ProgressEventHandler = localProgressEventHandler
            });
}
```

### Voir aussi

* namespace [Aspose.PSD.ProgressManagement](../../aspose.psd.progressmanagement/)
* assembly [Aspose.PSD](../../)


