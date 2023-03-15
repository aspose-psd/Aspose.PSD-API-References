---
title: ImageLoadersRegistry.CreateFirstSupportedLoader
second_title: Aspose.PSD voor .NET API-referentie
description: ImageLoadersRegistry methode. Creëert de eerst gevonden loader die geschikt is voor de gespecificeerdestream en eventueel deloadOptions .
type: docs
weight: 30
url: /nl/net/aspose.psd/imageloadersregistry/createfirstsupportedloader/
---
## ImageLoadersRegistry.CreateFirstSupportedLoader method

Creëert de eerst gevonden loader die geschikt is voor de gespecificeerde*stream* en eventueel de*loadOptions* .

```csharp
public static IImageLoader CreateFirstSupportedLoader(Stream stream, LoadOptions loadOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | Stream | De stroom. |
| loadOptions | LoadOptions | De laadopties. |

### Winstwaarde

De lader die het gespecificeerde ondersteunt*stream* En*loadOptions* of null als een dergelijke lader niet wordt gevonden.

### Opmerkingen

De eerste lader zal de laatst geregistreerde zijn.

### Zie ook

* interface [IImageLoader](../../iimageloader/)
* class [LoadOptions](../../loadoptions/)
* class [ImageLoadersRegistry](../)
* naamruimte [Aspose.PSD](../../imageloadersregistry/)
* montage [Aspose.PSD](../../../)


