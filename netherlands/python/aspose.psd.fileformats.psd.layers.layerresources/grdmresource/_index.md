---
title: "GrdmResource Klasse"
type: docs
weight: 340
url: /nl/python-net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/
---

**Summary:** Class GrdmResource. Contains information about Gradient-Map layer.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.GrdmResource

**Inheritance:** AdjustmentLayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [GrdmResource(psd_version)](#GrdmResource_psd_version_1) | Initialiseert een nieuw exemplaar van de [GrdmResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | De PSB-specifieke resourcehandtekening. |
| RESOURCE_SIGNATURE [static] | int | r | De algemene resourcehandtekening. |
| TYPE_TOOL_KEY [static] | int | r | De type tool info sleutel. |
| color_model | short | r/w | Kleurmodel.<br/>            Wanneer 'Gradient type' = 'Noise', kunnen we 'Color Model' toewijzen aan RGB/SHB/LAB (3/4/6). |
| color_points | [IGradientColorPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | r/w | Haalt de kleurpunten op of stelt ze in. |
| dither | bool | r/w | Is de gradient geditherd. |
| expansion_count | short | r/w | Expansietelling ( = 2 voor Photoshop 6.0). |
| gradient_mode | [GradientKind](/psd/python-net/aspose.psd.fileformats.psd.layers.gradient/gradientkind/) | r/w | Modus voor deze gradient<br/>            Bepaalt 'Gradient Type' = 'Solid/Noise' (0/1). |
| gradient_name | string | r/w | Naam van de gradient: Unicode‑string, opgevuld. |
| interpolatie | short | r/w | Interpolatie. Bepaalt de gladheid, wanneer 'Gradient Type' = 'Solid' (GradientMode = 0). |
| key | int | r | Haalt de laagresource key op. |
| lengte | int | r | Haalt de lengte van de laagresource op in bytes. |
| maximum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | Maximumkleur van PixelDataFormat.Rgba64Bpp‑formaat.<br/>            Kleur heeft ARGB‑kanalen, elk kanaal is 16‑bit. |
| minimum_color | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | Minimumkleur van PixelDataFormat.Rgba64Bpp‑formaat.<br/>            Kleur heeft ARGB‑kanalen, elk kanaal is 16‑bit. |
| psd_version | int | r | Haalt de minimale psd-versie op die vereist is voor de laagresource. 0 geeft geen beperkingen aan. |
| reverse | bool | r/w | Is de gradient omgekeerd. |
| rnd_number_seed | int | r/w | De willekeurige getalzaad gebruikt om kleuren te genereren voor de Noise-gradient. |
| roughness | int | r/w | Ruwheidsfactor<br/>            Wanneer 'Gradient type' = 'Noise', kunnen we 'Roughness' toewijzen (0 - 2048). |
| show_transparency | short | r/w | Vlag voor het tonen van transparantie<br/>            Wanneer 'Gradient type' = 'Noise', kunnen we 'Add transparency' op true zetten. |
| signature | int | r | Haalt de handtekening op. |
| transparency_points | [IGradientTransparencyPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint/) | r/w | Haalt de transparantiepunten op of stelt ze in. |
| use_vector_color | short | r/w | Vlag voor het gebruiken van vectorkleur. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Slaat resource‑data op in de opgegeven streamcontainer. |


### Constructor: GrdmResource(psd_version) {#GrdmResource_psd_version_1}


```
 GrdmResource(psd_version) 
```

Initialiseert een nieuw exemplaar van de [GrdmResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| psd_version | int | De psd‑versie van de resource. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Slaat resource‑data op in de opgegeven streamcontainer.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | De streamcontainer. |
| psd_version | int | De PSD‑versie. |

