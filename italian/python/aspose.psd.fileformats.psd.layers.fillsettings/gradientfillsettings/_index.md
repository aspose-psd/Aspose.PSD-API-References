---
title: "Classe GradientFillSettings"
type: docs
weight: 50
url: /it/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/
---

**Summary:** Gradient fill effect settings.

**Module:** [aspose.psd.fileformats.psd.layers.fillsettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/)

**Full Name:** aspose.psd.fileformats.psd.layers.fillsettings.GradientFillSettings

**Inheritance:** IFillSettings, IGradientFillSettings, BaseGradientFillSettings

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GradientFillSettings()](#GradientFillSettings__1) | Inizializza una nuova istanza della classe [GradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| align_with_layer | bool | r/w | Ottiene o imposta un valore che indica se [align with layer]. |
| angolo | double | r/w | Ottiene o imposta l'angolo. |
| color | [Color](/psd/python-net/aspose.psd/color) | r/w | Ottiene o imposta il colore. |
| color_points | [IGradientColorPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | r/w | Ottiene o imposta i punti di colore. |
| dither | bool | r/w | Ottiene o imposta un valore che indica se questo [BaseGradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings/) è dither. |
| fill_type | [FillType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/filltype) | r | Il tipo di riempimento. |
| gradient_mode | [GradientKind](/psd/python-net/aspose.psd.fileformats.psd.layers.gradient/gradientkind/) | r | Ottiene la modalità per questo gradiente.<br/>            Determina 'Tipo di gradiente' = 'Solido/Rumore' (0/1). |
| gradient_name | string | r/w | Ottiene o imposta il nome del gradiente. |
| gradient_type | [GradientType](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradienttype) | r/w | Ottiene o imposta il tipo del gradiente. |
| horizontal_offset | double | r/w | Ottiene o imposta lo spostamento orizzontale in percentuale. |
| interpolazione | short | r/w | Interpolazione. Determina la fluidità, quando 'Gradient Type' = 'Solid'. Intervallo di valori: 0-4096. |
| reverse | bool | r/w | Ottiene o imposta un valore che indica se questo [BaseGradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/basegradientfillsettings/) è invertito. |
| scale | int | r/w | Ottiene o imposta la scala. |
| transparency_points | [IGradientTransparencyPoint[]](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) | r/w | Ottiene o imposta i punti di trasparenza. |
| vertical_offset | double | r/w | Ottiene o imposta lo spostamento verticale in percentuale. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_color_point()](#add_color_point__1) | Aggiunge il punto colore. |
| [add_transparency_point()](#add_transparency_point__2) | Aggiunge il punto colore. |
| [generate_lfx_2_resource_nodes()](#generate_lfx_2_resource_nodes__3) | Genera i nodi risorsa LFX2. |
| [remove_color_point(point)](#remove_color_point_point_4) | Rimuove il punto colore. |
| [remove_transparency_point(point)](#remove_transparency_point_point_5) | Rimuove il punto di trasparenza. |


### Constructor: GradientFillSettings() {#GradientFillSettings__1}


```
 GradientFillSettings() 
```

Inizializza una nuova istanza della classe [GradientFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/).

### Method: add_color_point() {#add_color_point__1}


```
 add_color_point() 
```

Aggiunge il punto colore.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [GradientColorPoint](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradientcolorpoint) | Punto colore creato |


### Method: add_transparency_point() {#add_transparency_point__2}


```
 add_transparency_point() 
```

Aggiunge il punto colore.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [GradientTransparencyPoint](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/gradienttransparencypoint) | Punto di trasparenza creato |


### Method: generate_lfx_2_resource_nodes()  [static] {#generate_lfx_2_resource_nodes__3}


```
 generate_lfx_2_resource_nodes() 
```

Genera i nodi risorsa LFX2.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| System.Collections.Generic.List<Aspose.PSD.FileFormats.Psd.Layers.LayerResources.OSTypeStructure> | Elenco generato di [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) |


### Method: remove_color_point(point) {#remove_color_point_point_4}


```
 remove_color_point(point) 
```

Rimuove il punto colore.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point | [IGradientColorPoint](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint) | Il punto. |

### Method: remove_transparency_point(point) {#remove_transparency_point_point_5}


```
 remove_transparency_point(point) 
```

Rimuove il punto di trasparenza.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point | [IGradientTransparencyPoint](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) | Il punto. |

