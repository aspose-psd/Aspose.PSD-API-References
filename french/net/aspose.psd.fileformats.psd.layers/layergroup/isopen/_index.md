---
title: "LayerGroup.IsOpen"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Propriété LayerGroup. Obtient ou définit si le dossier est ouvert ; si défini sur true, le groupe sera en état ouvert au démarrage, sinon en état réduit."
type: docs
weight: 30
url: /fr/net/aspose.psd.fileformats.psd.layers/layergroup/isopen/
---
{{< psd/tize >}}
## LayerGroup.IsOpen property

Obtient ou définit si le dossier est ouvert ; si la valeur est `true`, le groupe sera en état ouvert au démarrage, sinon il sera minimisé.

```csharp
public bool IsOpen { get; set; }
```

## Exemples

Le code suivant montre comment ouvrir et fermer LayerGroup (Dossier) en utilisant la propriété IsOpen.

```csharp
[C#]

// Exemple de lecture et d'écriture de la propriété IsOpen à l'exécution.
string sourceFileName = "LayerGroupOpenClose.psd";
string outputFileName = "OutputLayerGroupOpenClose.psd";

using (var image = (PsdImage) Image.Load(sourceFileName))
{
    foreach (var layer in image.Layers)
    {
        if (layer is LayerGroup && layer.Name == "Group 1")
        {
            bool isOpenedGroup1 = ((LayerGroup) layer).IsOpen;
            ((LayerGroup) layer).IsOpen = !isOpenedGroup1;
        }

        if (layer is LayerGroup && layer.Name == "Group 2")
        {
            bool isOpenedGroup2 = ((LayerGroup) layer).IsOpen;
            ((LayerGroup) layer).IsOpen = !isOpenedGroup2;
        }
    }

    image.Save(outputFileName);
}
```

### Voir aussi

* class [LayerGroup](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


