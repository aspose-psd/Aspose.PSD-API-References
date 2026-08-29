---
title: "ImageAttributes.SetOutputChannelColorProfile"
second_title: "Aspose.PSD för .NET API‑referens"
description: "ImageAttributes-metod. Anger filen för output channel colorprofile för standardkategorin."
type: docs
weight: 180
url: /sv/net/aspose.psd/imageattributes/setoutputchannelcolorprofile/
---
{{< psd/tize >}}
## SetOutputChannelColorProfile(string) {#setoutputchannelcolorprofile}

Ställer in färgprofilfilen för utkanalen för standardkategorin.

```csharp
public void SetOutputChannelColorProfile(string colorProfileFilename)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| colorProfileFilename | String | Sökvägsnamnet för en färgprofilfil. Om färgprofilfilen finns i katalogen %SystemRoot%\\System32\\Spool\\Drivers\\Color kan denna parameter vara filnamnet. Annars måste denna parameter vara det fullständigt kvalificerade sökvägsnamnet. |

### Se även

* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## SetOutputChannelColorProfile(string, ColorAdjustType) {#setoutputchannelcolorprofile_1}

Ställer in färgprofilfilen för utkanalen för en specificerad kategori.

```csharp
public void SetOutputChannelColorProfile(string colorProfileFilename, ColorAdjustType type)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| colorProfileFilename | String | Sökvägsnamnet för en färgprofilfil. Om färgprofilfilen finns i katalogen %SystemRoot%\\System32\\Spool\\Drivers\\Color kan denna parameter vara filnamnet. Annars måste denna parameter vara det fullständigt kvalificerade sökvägsnamnet. |
| type | ColorAdjustType | Ett element av [`ColorAdjustType`](../../coloradjusttype/) som specificerar den kategori för vilken output channel color-profile-filen är angiven. |

### Se även

* enum [ColorAdjustType](../../coloradjusttype/)
* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


