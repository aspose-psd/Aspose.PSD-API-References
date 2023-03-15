---
title: ImageLoadersRegistry.GetFirstSupportedDescriptor
second_title: Aspose.PSD voor .NET API-referentie
description: ImageLoadersRegistry methode. Haalt de eerste gevonden ondersteunde descriptor op die geschikt is voor de gespecificeerdestream en eventueel deloadOptions .
type: docs
weight: 40
url: /nl/net/aspose.psd/imageloadersregistry/getfirstsupporteddescriptor/
---
## ImageLoadersRegistry.GetFirstSupportedDescriptor method

Haalt de eerste gevonden ondersteunde descriptor op die geschikt is voor de gespecificeerde*stream* en eventueel de*loadOptions* .

```csharp
public static IImageLoaderDescriptor GetFirstSupportedDescriptor(Stream stream, 
    LoadOptions loadOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | Stream | De stroom. |
| loadOptions | LoadOptions | De laadopties. |

### Winstwaarde

De loader-descriptor die het opgegeven ondersteunt*stream* En*loadOptions* of null als een dergelijke descriptor niet wordt gevonden.

### Opmerkingen

De eerste loader-descriptor is de laatst geregistreerde.

### Zie ook

* interface [IImageLoaderDescriptor](../../iimageloaderdescriptor/)
* class [LoadOptions](../../loadoptions/)
* class [ImageLoadersRegistry](../)
* naamruimte [Aspose.PSD](../../imageloadersregistry/)
* montage [Aspose.PSD](../../../)


