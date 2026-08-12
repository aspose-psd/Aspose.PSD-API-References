---
title: "Enumeración WarpStyles"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Aspose.PSD.FileFormats.Psd.Layers.Warp.WarpStyles enum. Tipos de estilos de warp compatibles"
type: docs
weight: 4020
url: /es/net/aspose.psd.fileformats.psd.layers.warp/warpstyles/
---
{{< psd/tize >}}
## WarpStyles enumeration

Tipos de estilos de warp compatibles

```csharp
public enum WarpStyles
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| None | `0` | El estilo se establece cuando la capa no tiene deformación |
| Custom | `1` | Estilo con movimiento arbitrario de puntos |
| Arc | `2` | Estilo de arco del warp |
| ArcUpper | `3` | Estilo de arco superior del warp |
| ArcLower | `4` | Estilo de arco inferior del warp |
| Arch | `5` | Estilo de arco del warp |
| Bulge | `6` | Estilo de abultamiento del warp |
| Flag | `7` | Estilo de bandera del warp |
| Fish | `8` | Estilo de pez del warp |
| Rise | `9` | Estilo de elevación del warp |
| Wave | `10` | Estilo de onda del warp |
| Twist | `11` | Tipo de torsión del warp |
| Squeeze | `12` | Tipo de compresión del warp |
| Inflate | `13` | Tipo de inflado de warp |

## Ejemplos

El siguiente código muestra cómo manipular WarpSettings para realizar una transformación de deformación en SmartObjectLayer y TexLayer.

```csharp
[C#]

string sourceFile = "smart_without_warp.psd";

var opt = new PsdLoadOptions()
{
    LoadEffectsResource = true,
    AllowWarpRepaint = true
};

string[] outputImageFile = new string[4];
string[] outputPsdFile = new string[4];

for (int caseIndex = 0; caseIndex < outputImageFile.Length; caseIndex++)
{
    outputImageFile[caseIndex] = "export_" + caseIndex + ".png";
    outputPsdFile[caseIndex] = "export_" + caseIndex + ".psd";

    using (PsdImage img = (PsdImage)Image.Load(sourceFile, opt))
    {
        foreach (Layer layer in img.Layers)
        {
            if (layer is SmartObjectLayer)
            {
                var smartLayer = (SmartObjectLayer)layer;
                smartLayer.WarpSettings = GetWarpSettingsByIndex(smartLayer.WarpSettings, caseIndex);
            }

            if (layer is TextLayer)
            {
                var textLayer = (TextLayer)layer;

                if (caseIndex != 3)
                {
                    textLayer.WarpSettings = GetWarpSettingsByIndex(textLayer.WarpSettings, caseIndex);
                }
            }
        }

        img.Save(outputPsdFile[caseIndex], new PsdOptions());
    }

    using (PsdImage img = (PsdImage)Image.Load(outputPsdFile[caseIndex], opt))
    {
        img.Save(outputImageFile[caseIndex],
            new PngOptions() { CompressionLevel = 9, ColorType = PngColorType.TruecolorWithAlpha });
    }
}

WarpSettings GetWarpSettingsByIndex(WarpSettings warpParams, int caseIndex)
{
    switch (caseIndex)
    {
        case 0:
            warpParams.Style = WarpStyles.Rise;
            warpParams.Rotate = WarpRotates.Horizontal;
            warpParams.Value = 20;
            break;
        case 1:
            warpParams.Style = WarpStyles.Rise;
            warpParams.Rotate = WarpRotates.Vertical;
            warpParams.Value = 10;
            break;
        case 2:
            warpParams.Style = WarpStyles.Flag;
            warpParams.Rotate = WarpRotates.Horizontal;
            warpParams.Value = 30;
            break;
        case 3:
            warpParams.Style = WarpStyles.Custom;
            warpParams.MeshPoints[2].Y += 70;
            break;
    }

    return warpParams;
}
```

### Ver también

* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../)


