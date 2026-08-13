---
title: "GaussWienerFilterOptions Classe"
type: docs
weight: 60
url: /fr/python-net/aspose.psd.imagefilters.filteroptions/gausswienerfilteroptions/
---

**Summary:** Gauss Wiener Filter Options<br/>            Deblur gauss

**Module:** [aspose.psd.imagefilters.filteroptions](/psd/python-net/aspose.psd.imagefilters.filteroptions/)

**Full Name:** aspose.psd.imagefilters.filteroptions.GaussWienerFilterOptions

**Inheritance:** DeconvolutionFilterOptions

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GaussWienerFilterOptions()](#GaussWienerFilterOptions__1) | Initialise une nouvelle instance de la classe [GaussWienerFilterOptions](/psd/python-net/aspose.psd.imagefilters.filteroptions/gausswienerfilteroptions/).<br/>            Avec les paramètres par défaut. |
| [GaussWienerFilterOptions(radius, smooth)](#GaussWienerFilterOptions_radius_smooth_2) | Initialise une nouvelle instance de la classe [GaussWienerFilterOptions](/psd/python-net/aspose.psd.imagefilters.filteroptions/gausswienerfilteroptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| luminosité | double | r/w | Obtient ou définit la luminosité.<br/>            plage recommandée 1 - 1.5<br/>            valeur par défaut = 1.15 |
| grayscale | bool | r/w | Obtient ou définit une valeur indiquant si ce [DeconvolutionFilterOptions](/psd/python-net/aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions/) est en niveaux de gris.<br/>            Retourne le mode niveaux de gris ou le mode RVB. |
| is_partial_loaded | bool | r | Obtient une valeur indiquant si cette instance est partiellement chargée. |
| rayon | int | r/w | Obtient ou définit le rayon. |
| lissage | double | r/w | Obtient ou définit le lissage. |
| snr | double | r/w | Obtient ou définit le SNR (rapport signal/bruit)<br/>            plage recommandée 0,002 - 0,009, valeur par défaut = 0,007 |


### Constructor: GaussWienerFilterOptions() {#GaussWienerFilterOptions__1}


```
 GaussWienerFilterOptions() 
```

Initialise une nouvelle instance de la classe [GaussWienerFilterOptions](/psd/python-net/aspose.psd.imagefilters.filteroptions/gausswienerfilteroptions/).<br/>            Avec les paramètres par défaut.

### Constructor: GaussWienerFilterOptions(radius, smooth) {#GaussWienerFilterOptions_radius_smooth_2}


```
 GaussWienerFilterOptions(radius, smooth) 
```

Initialise une nouvelle instance de la classe [GaussWienerFilterOptions](/psd/python-net/aspose.psd.imagefilters.filteroptions/gausswienerfilteroptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rayon | int | Le rayon. |
| lissage | double | Le lissage. |

