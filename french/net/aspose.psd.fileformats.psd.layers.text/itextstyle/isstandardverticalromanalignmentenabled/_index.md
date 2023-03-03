---
title: ITextStyle.IsStandardVerticalRomanAlignmentEnabled
second_title: Référence de l'API Aspose.PSD pour .NET
description: ITextStyle propriété. Obtient ou définit lalignement romain vertical standard. Ceci basé sur la valeur de la ressource BaselineDirection sapplique uniquement lorsque lorientation du texte estVertical .
type: docs
weight: 170
url: /fr/net/aspose.psd.fileformats.psd.layers.text/itextstyle/isstandardverticalromanalignmentenabled/
---
## ITextStyle.IsStandardVerticalRomanAlignmentEnabled property

Obtient ou définit l'alignement romain vertical standard. Ceci basé sur la valeur de la ressource BaselineDirection s'applique uniquement lorsque l'orientation du texte estVertical .

```csharp
public bool IsStandardVerticalRomanAlignmentEnabled { get; set; }
```

### Exemples

Le code suivant illustre la prise en charge de la nouvelle propriété IsStandardVerticalRomanAlignmentEnabled.

```csharp
[C#]

// Le code suivant montre la possibilité de modifier la nouvelle propriété IsStandardVerticalRomanAlignmentEnabled.
// Cela n'affecte pas le rendu pour le moment, mais vous permet uniquement de modifier la valeur de la propriété.

string src = "1346test.psd";
string output = "out_1346test.psd";

using (var image = (PsdImage)Image.Load(src))
{
    var textLayer = image.Layers[1] as TextLayer;
    var textPortion = textLayer.TextData.Items[0];
    if (textPortion.Style.IsStandardVerticalRomanAlignmentEnabled)
    {
        // Lecture correcte
    }
    else
    {
        throw new Exception("Incorrect reading of IsStandardVerticalRomanAlignmentEnabled property value");
    }

    textPortion.Style.IsStandardVerticalRomanAlignmentEnabled = false;
    textLayer.TextData.UpdateLayerData();

    image.Save(output);
}

using (var image = (PsdImage)Image.Load(output))
{
    var textLayer = image.Layers[1] as TextLayer;
    var textPortion = textLayer.TextData.Items[0];
    if (!textPortion.Style.IsStandardVerticalRomanAlignmentEnabled)
    {
        // Lecture correcte
    }
    else
    {
        throw new Exception("Incorrect reading of IsStandardVerticalRomanAlignmentEnabled property value");
    }
}
```

### Voir également

* interface [ITextStyle](../)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.Text](../../itextstyle/)
* Assemblée [Aspose.PSD](../../../)


