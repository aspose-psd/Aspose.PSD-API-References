---
title: "ImageLoadersRegistry.GetFirstSupportedDescriptorByFileFormat"
second_title: "Aspose.PSD för .NET API‑referens"
description: "ImageLoadersRegistry-metoden. Hämtar det första stödda filformatet efter dess typnamn."
type: docs
weight: 50
url: /sv/net/aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbyfileformat/
---
{{< psd/tize >}}
## ImageLoadersRegistry.GetFirstSupportedDescriptorByFileFormat method

Hämtar det första stödjade filformatet efter dess typnamn.

```csharp
public static IImageLoaderDescriptor GetFirstSupportedDescriptorByFileFormat(FileFormat fileFormat)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileFormat | FileFormat | Det stödda beskrivningsfilformatet. |

### Returvärde

Den först hittade laddarbeskrivaren eller null om ingen sådan beskrivare hittas.

## Anmärkningar

Den första laddarbeskrivaren kommer faktiskt att vara den sist registrerade.

### Se även

* interface [IImageLoaderDescriptor](../../iimageloaderdescriptor/)
* enum [FileFormat](../../fileformat/)
* class [ImageLoadersRegistry](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


