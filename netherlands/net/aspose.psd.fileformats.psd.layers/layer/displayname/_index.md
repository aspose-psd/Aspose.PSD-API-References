---
title: Layer.DisplayName
second_title: Aspose.PSD voor .NET API-referentie
description: Layer eigendom. Haalt de weergavenaam van de laag op of stelt deze in.
type: docs
weight: 100
url: /nl/net/aspose.psd.fileformats.psd.layers/layer/displayname/
---
## Layer.DisplayName property

Haalt de weergavenaam van de laag op of stelt deze in.

```csharp
public string DisplayName { get; set; }
```

### Eigendoms-waarde

De weergavenaam van de laag.

### Voorbeelden

Het volgende voorbeeld demonstreert de mogelijkheid om de waarde DisplayName in te stellen, waarin de naam van de laag correct wordt weergegeven.

```csharp
[C#]

// breng wijzigingen aan in de laagnamen en sla deze op
string sourceFileName = "layers with names.psd";
string output = "output.psd";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];
        // stel een nieuwe waarde in de eigenschap DisplayName in
        layer.DisplayName += "_changed";
    }

    image.Save(output);
}
```

### Zie ook

* class [Layer](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* montage [Aspose.PSD](../../../)


