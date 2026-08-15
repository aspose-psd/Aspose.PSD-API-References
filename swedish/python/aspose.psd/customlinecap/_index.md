---
title: "CustomLineCap-klass"
type: docs
weight: 1010
url: /sv/python-net/aspose.psd/customlinecap/
---

**Summary:** Encapsulates a custom user-defined line cap.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.CustomLineCap

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [CustomLineCap(fill_path, stroke_path)](#CustomLineCap_fill_path_stroke_path_1) | Initierar en ny instans av klassen [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) med den angivna konturen och fyllningen. |
| [CustomLineCap(fill_path, stroke_path, base_cap)](#CustomLineCap_fill_path_stroke_path_base_cap_2) | Initierar en ny instans av klassen [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) från den angivna befintliga uppräkningen [LineCap](/psd/python-net/aspose.psd/linecap/) med den angivna konturen och fyllningen. |
| [CustomLineCap(fill_path, stroke_path, base_cap, base_inset)](#CustomLineCap_fill_path_stroke_path_base_cap_base_inset_3) | Initierar en ny instans av klassen [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) från den angivna befintliga uppräkningen [LineCap](/psd/python-net/aspose.psd/linecap/) med den angivna konturen, fyllningen och inskjutningen. |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| base_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | r/w | Hämtar eller anger uppräkningen [LineCap](/psd/python-net/aspose.psd/linecap/) som denna [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) är baserad på. |
| base_inset | float | r/w | Hämtar eller anger avståndet mellan toppen och linjen. |
| fill_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | r/w | Hämtar eller anger objektet som definierar fyllningen för den anpassade toppen. |
| stroke_join | [LineJoin](/psd/python-net/aspose.psd/linejoin) | r/w | Hämtar eller anger uppräkningen [LineJoin](/psd/python-net/aspose.psd/linejoin/) som bestämmer hur linjer som utgör detta [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) objekt sammanfogas. |
| stroke_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | r/w | Hämtar eller anger objektet som definierar konturen för den anpassade toppen. |
| width_scale | float | r/w | Hämtar eller anger mängden med vilken detta [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) klassobjekt ska skalas i förhållande till bredden på objektet. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [get_stroke_caps(start_cap, end_cap)](#get_stroke_caps_start_cap_end_cap_1) | Hämtar de kapslar som används för att starta och avsluta linjer som utgör denna anpassade kapsel. |
| [set_stroke_caps(start_cap, end_cap)](#set_stroke_caps_start_cap_end_cap_2) | Ställer in de kapslar som används för att starta och avsluta linjer som utgör denna anpassade kapsel. |


### Constructor: CustomLineCap(fill_path, stroke_path) {#CustomLineCap_fill_path_stroke_path_1}


```
 CustomLineCap(fill_path, stroke_path) 
```

Initierar en ny instans av klassen [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) med den angivna konturen och fyllningen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| fill_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Ett [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)‑objekt som definierar fyllningen för den anpassade kapseln. |
| stroke_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Ett [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)‑objekt som definierar konturen för den anpassade kapseln. |

### Constructor: CustomLineCap(fill_path, stroke_path, base_cap) {#CustomLineCap_fill_path_stroke_path_base_cap_2}


```
 CustomLineCap(fill_path, stroke_path, base_cap) 
```

Initierar en ny instans av klassen [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) från den angivna befintliga uppräkningen [LineCap](/psd/python-net/aspose.psd/linecap/) med den angivna konturen och fyllningen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| fill_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Ett [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)‑objekt som definierar fyllningen för den anpassade kapseln. |
| stroke_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Ett [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)‑objekt som definierar konturen för den anpassade kapseln. |
| base_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | Den linjekap som används för att skapa den anpassade kapseln. |

### Constructor: CustomLineCap(fill_path, stroke_path, base_cap, base_inset) {#CustomLineCap_fill_path_stroke_path_base_cap_base_inset_3}


```
 CustomLineCap(fill_path, stroke_path, base_cap, base_inset) 
```

Initierar en ny instans av klassen [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) från den angivna befintliga uppräkningen [LineCap](/psd/python-net/aspose.psd/linecap/) med den angivna konturen, fyllningen och inskjutningen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| fill_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Ett [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)‑objekt som definierar fyllningen för den anpassade kapseln. |
| stroke_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Ett [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)‑objekt som definierar konturen för den anpassade kapseln. |
| base_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | Den linjekap som används för att skapa den anpassade kapseln. |
| base_inset | float | Avståndet mellan kapseln och linjen. |

### Method: get_stroke_caps(start_cap, end_cap) {#get_stroke_caps_start_cap_end_cap_1}


```
 get_stroke_caps(start_cap, end_cap) 
```

Hämtar de kapslar som används för att starta och avsluta linjer som utgör denna anpassade kapsel.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| start_cap | [LineCap[]](/psd/python-net/aspose.psd/linecap) | Den [LineCap](/psd/python-net/aspose.psd/linecap/)‑enumerationen som används i början av en linje inom denna kapsel. |
| end_cap | [LineCap[]](/psd/python-net/aspose.psd/linecap) | Den [LineCap](/psd/python-net/aspose.psd/linecap/)‑enumerationen som används i slutet av en linje inom denna kapsel. |

### Method: set_stroke_caps(start_cap, end_cap) {#set_stroke_caps_start_cap_end_cap_2}


```
 set_stroke_caps(start_cap, end_cap) 
```

Ställer in de kapslar som används för att starta och avsluta linjer som utgör denna anpassade kapsel.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| start_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | Den [LineCap](/psd/python-net/aspose.psd/linecap/)‑enumerationen som används i början av en linje inom denna kapsel. |
| end_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | Den [LineCap](/psd/python-net/aspose.psd/linecap/)‑enumerationen som används i slutet av en linje inom denna kapsel. |

