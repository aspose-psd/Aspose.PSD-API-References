---
title: "IImageLoaderDescriptor.CanLoad"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "IImageLoaderDescriptor-Methode. Bestimmt, ob der Bildlader ein neues Bild aus dem angegebenen Stream lesen kann und optional *loadOptions* verwendet."
type: docs
weight: 10
url: /de/net/aspose.psd/iimageloaderdescriptor/canload/
---
{{< psd/tize >}}
## IImageLoaderDescriptor.CanLoad method

Bestimmt, ob der Bildlader ein neues Bild aus dem angegebenen Stream lesen kann und optional die *loadOptions* verwendet.

```csharp
public bool CanLoad(StreamContainer streamContainer, LoadOptions loadOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| `streamContainer` | StreamContainer | Der StreamContainer. |
| loadOptions | LoadOptions | Die Dateiformatdetails, die durch *loadOptions* angegeben werden. *loadOptions* kann null sein. |

### Rückgabewert

`true`, wenn der von diesem Deskriptor erstellte Bildlader das Bild aus dem Stream lesen kann; andernfalls `false`.

### Siehe auch

* class [StreamContainer](../../streamcontainer/)
* class [LoadOptions](../../loadoptions/)
* interface [IImageLoaderDescriptor](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


