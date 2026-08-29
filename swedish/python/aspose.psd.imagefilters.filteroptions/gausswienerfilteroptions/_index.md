---
title: "GaussWienerFilterOptions klass"
type: docs
weight: 60
url: /sv/python-net/aspose.psd.imagefilters.filteroptions/gausswienerfilteroptions/
---

**Summary:** Gauss Wiener Filter Options<br/>            Deblur gauss

**Module:** [aspose.psd.imagefilters.filteroptions](/psd/python-net/aspose.psd.imagefilters.filteroptions/)

**Full Name:** aspose.psd.imagefilters.filteroptions.GaussWienerFilterOptions

**Inheritance:** DeconvolutionFilterOptions

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [GaussWienerFilterOptions()](#GaussWienerFilterOptions__1) | Initierar en ny instans av [GaussWienerFilterOptions](/psd/python-net/aspose.psd.imagefilters.filteroptions/gausswienerfilteroptions/) klass.<br/>            Med standardinställningar. |
| [GaussWienerFilterOptions(radius, smooth)](#GaussWienerFilterOptions_radius_smooth_2) | Initierar en ny instans av [GaussWienerFilterOptions](/psd/python-net/aspose.psd.imagefilters.filteroptions/gausswienerfilteroptions/) klass. |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| ljusstyrka | double | r/w | Hämtar eller anger ljusstyrkan.<br/>            rekommenderat intervall 1 - 1.5<br/>            standardvärde = 1.15 |
| grayscale | bool | r/w | Hämtar eller anger ett värde som indikerar om detta [DeconvolutionFilterOptions](/psd/python-net/aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions/) är gråskala.<br/>            Returnerar gråskaleläge eller RGB-läge. |
| is_partial_loaded | bool | r | Hämtar ett värde som indikerar om denna instans är delvis inläst. |
| radius | int | r/w | Hämtar eller anger radius. |
| mjuk | double | r/w | Hämtar eller anger smooth. |
| snr | double | r/w | Hämtar eller anger SNR(signal-till-brusförhållande)<br/>            rekommenderat intervall 0.002 - 0.009, standardvärde = 0.007 |


### Constructor: GaussWienerFilterOptions() {#GaussWienerFilterOptions__1}


```
 GaussWienerFilterOptions() 
```

Initierar en ny instans av [GaussWienerFilterOptions](/psd/python-net/aspose.psd.imagefilters.filteroptions/gausswienerfilteroptions/) klass.<br/>            Med standardinställningar.

### Constructor: GaussWienerFilterOptions(radius, smooth) {#GaussWienerFilterOptions_radius_smooth_2}


```
 GaussWienerFilterOptions(radius, smooth) 
```

Initierar en ny instans av [GaussWienerFilterOptions](/psd/python-net/aspose.psd.imagefilters.filteroptions/gausswienerfilteroptions/) klass.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| radius | int | Radien. |
| mjuk | double | Den smooth. |

