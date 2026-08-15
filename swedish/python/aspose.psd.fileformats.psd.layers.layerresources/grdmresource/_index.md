---
title: "GrdmResource klass"
type: docs
weight: 340
url: /sv/python-net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/
---

**Summary:** Class GrdmResource. Contains information about Gradient-Map layer.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.GrdmResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [GrdmResource(psd_version)](#GrdmResource_psd_version_1) | Initierar en ny instans av [GrdmResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/) klass. |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Den PSB‑specifika resurssignaturen. |
| RESOURCE_SIGNATURE [static] | int | r | Den gemensamma resurssignaturen. |
| TYPE_TOOL_KEY [static] | int | r | Typverktygsinformationsnyckeln. |
| color_model | short | r/w | Färgsmodell.<br/>            När 'Gradient type' = 'Noise' kan vi tilldela 'Color Model' till RGB/SHB/LAB (3/4/6). |
| color_points | [IGradientColorPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | r/w | Hämtar eller anger färgpunkterna. |
| dither | bool | r/w | Är gradienten ditherad. |
| expansion_count | short | r/w | Expansionsantal ( = 2 för Photoshop 6.0). |
| gradient_mode | [GradientKind](/psd/python-net/aspose.psd.fileformats.psd.layers.gradient/gradientkind/) | r/w | Läge för denna gradient<br/>            Bestämmer 'Gradient Type' = 'Solid/Noise' (0/1). |
| gradient_name | string | r/w | Namn på gradienten: Unicode-sträng, utfylld. |
| interpolering | short | r/w | Interpolation. Bestämmer jämnhet när 'Gradient Type' = 'Solid' (GradientMode = 0). |
| nyckel | int | r | Hämtar lagerresursnyckeln. |
| längd | int | r | Hämtar lagerresursens längd i byte. |
| maximum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | Maximal färg för PixelDataFormat.Rgba64Bpp-format.<br/>            Färgen har ARGB-kanaler, varje kanal är 16‑bit. |
| minimum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | Minimal färg för PixelDataFormat.Rgba64Bpp-format.<br/>            Färgen har ARGB-kanaler, varje kanal är 16‑bit. |
| psd_version | int | r | Hämtar den minsta psd-versionen som krävs för lagerresursen. 0 indikerar inga begränsningar. |
| omvänd | bool | r/w | Är gradienten omvänd. |
| rnd_number_seed | int | r/w | Det slumpmässiga talfröet som används för att generera färger för brusgradienten. |
| roughness | int | r/w | Roughness-faktor<br/>            När 'Gradient type' = 'Noise' kan vi tilldela 'Roughness' (0 - 2048). |
| show_transparency | short | r/w | Flagga för att visa transparens<br/>            När 'Gradient type' = 'Noise' kan vi sätta 'Add transparency' till true. |
| signatur | int | r | Hämtar signaturen. |
| transparency_points | [IGradientTransparencyPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint/) | r/w | Hämtar eller anger transparenspunkterna. |
| use_vector_color | short | r/w | Flagga för att använda vektorfärg. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Sparar resursdata till den angivna strömbehållaren. |


### Constructor: GrdmResource(psd_version) {#GrdmResource_psd_version_1}


```
 GrdmResource(psd_version) 
```

Initierar en ny instans av [GrdmResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/) klass.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| psd_version | int | PSD-versionen av resursen. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Sparar resursdata till den angivna strömbehållaren.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Strömbehållaren. |
| psd_version | int | PSD-versionen. |

