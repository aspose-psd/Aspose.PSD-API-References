---
title: "Classe CustomLineCap"
type: docs
weight: 1010
url: /it/python-net/aspose.psd/customlinecap/
---

**Summary:** Encapsulates a custom user-defined line cap.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.CustomLineCap

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [CustomLineCap(fill_path, stroke_path)](#CustomLineCap_fill_path_stroke_path_1) | Inizializza una nuova istanza della classe [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) con il contorno e il riempimento specificati. |
| [CustomLineCap(fill_path, stroke_path, base_cap)](#CustomLineCap_fill_path_stroke_path_base_cap_2) | Inizializza una nuova istanza della classe [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) a partire dall'enumerazione [LineCap](/psd/python-net/aspose.psd/linecap/) esistente specificata, con il contorno e il riempimento specificati. |
| [CustomLineCap(fill_path, stroke_path, base_cap, base_inset)](#CustomLineCap_fill_path_stroke_path_base_cap_base_inset_3) | Inizializza una nuova istanza della classe [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) a partire dall'enumerazione [LineCap](/psd/python-net/aspose.psd/linecap/) esistente specificata, con il contorno, il riempimento e l'inserimento specificati. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| base_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | r/w | Ottiene o imposta l'enumerazione [LineCap](/psd/python-net/aspose.psd/linecap/) su cui si basa questo [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/). |
| base_inset | float | r/w | Ottiene o imposta la distanza tra il cap e la linea. |
| fill_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | r/w | Ottiene o imposta l'oggetto che definisce il riempimento per il cap personalizzato. |
| stroke_join | [LineJoin](/psd/python-net/aspose.psd/linejoin) | r/w | Ottiene o imposta l'enumerazione [LineJoin](/psd/python-net/aspose.psd/linejoin/) che determina come le linee che compongono questo oggetto [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) sono unite. |
| stroke_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | r/w | Ottiene o imposta l'oggetto che definisce il contorno del cap personalizzato. |
| width_scale | float | r/w | Ottiene o imposta la quantità con cui scalare questo oggetto di classe [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) rispetto alla larghezza dell'oggetto. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_stroke_caps(start_cap, end_cap)](#get_stroke_caps_start_cap_end_cap_1) | Ottiene i cap usati per avviare e terminare le linee che compongono questo cap personalizzato. |
| [set_stroke_caps(start_cap, end_cap)](#set_stroke_caps_start_cap_end_cap_2) | Imposta i cap usati per avviare e terminare le linee che compongono questo cap personalizzato. |


### Constructor: CustomLineCap(fill_path, stroke_path) {#CustomLineCap_fill_path_stroke_path_1}


```
 CustomLineCap(fill_path, stroke_path) 
```

Inizializza una nuova istanza della classe [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) con il contorno e il riempimento specificati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| fill_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Un oggetto [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) che definisce il riempimento per il cap personalizzato. |
| stroke_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Un oggetto [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) che definisce il contorno del cap personalizzato. |

### Constructor: CustomLineCap(fill_path, stroke_path, base_cap) {#CustomLineCap_fill_path_stroke_path_base_cap_2}


```
 CustomLineCap(fill_path, stroke_path, base_cap) 
```

Inizializza una nuova istanza della classe [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) a partire dall'enumerazione [LineCap](/psd/python-net/aspose.psd/linecap/) esistente specificata, con il contorno e il riempimento specificati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| fill_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Un oggetto [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) che definisce il riempimento per il cap personalizzato. |
| stroke_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Un oggetto [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) che definisce il contorno del cap personalizzato. |
| base_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | Il cap di linea da cui creare il cap personalizzato. |

### Constructor: CustomLineCap(fill_path, stroke_path, base_cap, base_inset) {#CustomLineCap_fill_path_stroke_path_base_cap_base_inset_3}


```
 CustomLineCap(fill_path, stroke_path, base_cap, base_inset) 
```

Inizializza una nuova istanza della classe [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) a partire dall'enumerazione [LineCap](/psd/python-net/aspose.psd/linecap/) esistente specificata, con il contorno, il riempimento e l'inserimento specificati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| fill_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Un oggetto [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) che definisce il riempimento per il cap personalizzato. |
| stroke_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Un oggetto [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) che definisce il contorno del cap personalizzato. |
| base_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | Il cap di linea da cui creare il cap personalizzato. |
| base_inset | float | La distanza tra il cap e la linea. |

### Method: get_stroke_caps(start_cap, end_cap) {#get_stroke_caps_start_cap_end_cap_1}


```
 get_stroke_caps(start_cap, end_cap) 
```

Ottiene i cap usati per avviare e terminare le linee che compongono questo cap personalizzato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| start_cap | [LineCap[]](/psd/python-net/aspose.psd/linecap) | L'enumerazione [LineCap](/psd/python-net/aspose.psd/linecap/) usata all'inizio di una linea all'interno di questo cap. |
| end_cap | [LineCap[]](/psd/python-net/aspose.psd/linecap) | L'enumerazione [LineCap](/psd/python-net/aspose.psd/linecap/) usata alla fine di una linea all'interno di questo cap. |

### Method: set_stroke_caps(start_cap, end_cap) {#set_stroke_caps_start_cap_end_cap_2}


```
 set_stroke_caps(start_cap, end_cap) 
```

Imposta i cap usati per avviare e terminare le linee che compongono questo cap personalizzato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| start_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | L'enumerazione [LineCap](/psd/python-net/aspose.psd/linecap/) usata all'inizio di una linea all'interno di questo cap. |
| end_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | L'enumerazione [LineCap](/psd/python-net/aspose.psd/linecap/) usata alla fine di una linea all'interno di questo cap. |

