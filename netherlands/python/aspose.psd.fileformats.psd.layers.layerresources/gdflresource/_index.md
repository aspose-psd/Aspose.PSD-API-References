---
title: "GdFlResource Klasse"
type: docs
weight: 330
url: /nl/python-net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/
---

**Summary:** Class GdFlResource.<br/>            This resource contains information about blending of clipped element.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.GdFlResource

**Inheritance:** FillLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [GdFlResource()](#GdFlResource__1) | Initialiseert een nieuw exemplaar van de GdFlResource klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | De PSB-specifieke resourcehandtekening. |
| RESOURCE_SIGNATURE [static] | int | r | De algemene resourcehandtekening. |
| TYPE_TOOL_KEY [static] | int | r | De type tool info sleutel. |
| align_with_layer | bool | r/w | Haalt een waarde op of stelt een waarde in die aangeeft of [align with layer]. |
| hoek | double | r/w | Haalt of stelt de hoek in. |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | Haalt de kleur van de RGB op. |
| color_model | string | r/w | Kleurmodel - RGB/HSB/LAB (\"RGBC\"/\"HSBl\"/\"LbCl\"). |
| color_points | [IGradientColorPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | r/w | Haalt de kleurpunten op. |
| dither | bool | r/w | Haalt een waarde op of stelt deze in die aangeeft of dit [GdFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/) dither is. |
| gradient_interval | double | r/w | Haalt het gradientinterval op of stelt het in. |
| gradient_mode | string | r/w | Modus voor dit gradient.<br/>            Bepaalt 'Gradient Type' = 'Solid/Noise' = \"CstS\"/\"ClNs\". |
| gradient_name | string | r/w | Haalt de naam van de gradient op of stelt deze in. |
| gradient_type | [GradientType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradienttype/) | r/w | Haalt het type van de gradient op of stelt dit in. |
| horizontal_offset | double | r/w | Haalt of stelt de horizontale offset in. |
| key | int | r | Haalt de laagresource key op. |
| lengte | int | r | Haalt de lengte van de laagresource op in bytes. |
| maximum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | Maximumkleur van PixelDataFormat. |
| minimum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | Minkleur van PixelDataFormat. |
| psd_version | int | r | Haalt de minimale psd-versie op die vereist is voor de laagresource. 0 geeft geen beperkingen aan. |
| reverse | bool | r/w | Haalt een waarde op of stelt deze in die aangeeft of dit [GdFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/) omgekeerd is. |
| rnd_number_seed | int | r/w | De willekeurige getalzaad gebruikt om kleuren te genereren voor de Noise-gradient. |
| roughness | int | r/w | Ruwheidsfactor. |
| scale | int | r/w | Haalt de schaal op of stelt deze in. |
| show_transparency | bool | r/w | Vlag voor het weergeven van transparantie. |
| signature | int | r | Haalt de handtekening op. |
| transparency_points | [IGradientTransparencyPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint/) | r/w | Haalt de transparantiepunten op. |
| use_vector_color | bool | r/w | Vlag voor het gebruiken van vectorkleur. |
| vertical_offset | double | r/w | Haalt de verticale offset op of stelt deze in. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Slaat de bron op in de opgegeven streamcontainer. |


### Constructor: GdFlResource() {#GdFlResource__1}


```
 GdFlResource() 
```

Initialiseert een nieuw exemplaar van de GdFlResource klasse

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Slaat de bron op in de opgegeven streamcontainer.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | De streamcontainer om in op te slaan. |
| psd_version | int | De PSD‑versie. |

