---
title: "GdFlResource-klass"
type: docs
weight: 330
url: /sv/python-net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/
---

**Summary:** Class GdFlResource.<br/>            This resource contains information about blending of clipped element.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.GdFlResource

**Inheritance:** FillLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [GdFlResource()](#GdFlResource__1) | Initierar en ny instans av klassen GdFlResource |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Den PSB‑specifika resurssignaturen. |
| RESOURCE_SIGNATURE [static] | int | r | Den gemensamma resurssignaturen. |
| TYPE_TOOL_KEY [static] | int | r | Typverktygsinformationsnyckeln. |
| align_with_layer | bool | r/w | Hämtar eller anger ett värde som indikerar om [align with layer]. |
| vinkel | double | r/w | Hämtar eller anger vinkeln. |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | Hämtar färgen för RGB. |
| color_model | string | r/w | Färgsmodell - RGB/HSB/LAB ("RGBC"/"HSBl"/"LbCl"). |
| color_points | [IGradientColorPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | r/w | Hämtar färgpunkterna. |
| dither | bool | r/w | Hämtar eller anger ett värde som indikerar om denna [GdFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/) är dither. |
| gradient_interval | double | r/w | Hämtar eller anger gradientintervallet. |
| gradient_mode | string | r/w | Läge för denna gradient.<br/>            Bestämmer 'Gradient Type' = 'Solid/Noise' = "CstS"/"ClNs". |
| gradient_name | string | r/w | Hämtar eller anger namnet på gradienten. |
| gradient_type | [GradientType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradienttype/) | r/w | Hämtar eller anger typen på gradienten. |
| horizontal_offset | double | r/w | Hämtar eller anger den horisontella förskjutningen. |
| nyckel | int | r | Hämtar lagerresursnyckeln. |
| längd | int | r | Hämtar lagerresursens längd i byte. |
| maximum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | Maximal färg för PixelDataFormat. |
| minimum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | Minimal färg för PixelDataFormat. |
| psd_version | int | r | Hämtar den minsta psd-versionen som krävs för lagerresursen. 0 indikerar inga begränsningar. |
| reverse | bool | r/w | Hämtar eller anger ett värde som indikerar om denna [GdFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/) är omvänd. |
| rnd_number_seed | int | r/w | Det slumpmässiga talfröet som används för att generera färger för brusgradienten. |
| roughness | int | r/w | Roughness-faktor. |
| skala | int | r/w | Hämtar eller anger skalan. |
| show_transparency | bool | r/w | Flagga för att visa transparens. |
| signatur | int | r | Hämtar signaturen. |
| transparency_points | [IGradientTransparencyPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint/) | r/w | Hämtar transparenspunkterna. |
| use_vector_color | bool | r/w | Flagga för att använda vektorfärg. |
| vertical_offset | double | r/w | Hämtar eller anger den vertikala förskjutningen. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Sparar resursen till den angivna strömbehållaren. |


### Constructor: GdFlResource() {#GdFlResource__1}


```
 GdFlResource() 
```

Initierar en ny instans av klassen GdFlResource

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Sparar resursen till den angivna strömbehållaren.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Strömbehållaren att spara till. |
| psd_version | int | PSD-versionen. |

