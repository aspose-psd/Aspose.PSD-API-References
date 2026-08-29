---
title: "Classe CustomLineCap"
type: docs
weight: 1010
url: /fr/python-net/aspose.psd/customlinecap/
---

**Summary:** Encapsulates a custom user-defined line cap.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.CustomLineCap

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [CustomLineCap(fill_path, stroke_path)](#CustomLineCap_fill_path_stroke_path_1) | Initialise une nouvelle instance de la classe [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) avec le contour et le remplissage spécifiés. |
| [CustomLineCap(fill_path, stroke_path, base_cap)](#CustomLineCap_fill_path_stroke_path_base_cap_2) | Initialise une nouvelle instance de la classe [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) à partir de l'énumération [LineCap](/psd/python-net/aspose.psd/linecap/) existante spécifiée, avec le contour et le remplissage spécifiés. |
| [CustomLineCap(fill_path, stroke_path, base_cap, base_inset)](#CustomLineCap_fill_path_stroke_path_base_cap_base_inset_3) | Initialise une nouvelle instance de la classe [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) à partir de l'énumération [LineCap](/psd/python-net/aspose.psd/linecap/) existante spécifiée, avec le contour, le remplissage et l'encoche spécifiés. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| base_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | r/w | Obtient ou définit l'énumération [LineCap](/psd/python-net/aspose.psd/linecap/) sur laquelle repose ce [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/). |
| base_inset | float | r/w | Obtient ou définit la distance entre le cap et la ligne. |
| fill_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | r/w | Obtient ou définit l'objet qui définit le remplissage du cap personnalisé. |
| stroke_join | [LineJoin](/psd/python-net/aspose.psd/linejoin) | r/w | Obtient ou définit l'énumération [LineJoin](/psd/python-net/aspose.psd/linejoin/) qui détermine comment les lignes qui composent cet objet [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) sont jointes. |
| stroke_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | r/w | Obtient ou définit l'objet qui définit le contour du cap personnalisé. |
| width_scale | float | r/w | Obtient ou définit la quantité par laquelle mettre à l'échelle cet objet de classe [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) par rapport à la largeur de l'objet. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_stroke_caps(start_cap, end_cap)](#get_stroke_caps_start_cap_end_cap_1) | Obtient les caps utilisés pour commencer et terminer les lignes qui composent ce cap personnalisé. |
| [set_stroke_caps(start_cap, end_cap)](#set_stroke_caps_start_cap_end_cap_2) | Définit les caps utilisés pour commencer et terminer les lignes qui composent ce cap personnalisé. |


### Constructor: CustomLineCap(fill_path, stroke_path) {#CustomLineCap_fill_path_stroke_path_1}


```
 CustomLineCap(fill_path, stroke_path) 
```

Initialise une nouvelle instance de la classe [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) avec le contour et le remplissage spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| fill_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Un objet [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) qui définit le remplissage du cap personnalisé. |
| stroke_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Un objet [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) qui définit le contour du cap personnalisé. |

### Constructor: CustomLineCap(fill_path, stroke_path, base_cap) {#CustomLineCap_fill_path_stroke_path_base_cap_2}


```
 CustomLineCap(fill_path, stroke_path, base_cap) 
```

Initialise une nouvelle instance de la classe [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) à partir de l'énumération [LineCap](/psd/python-net/aspose.psd/linecap/) existante spécifiée, avec le contour et le remplissage spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| fill_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Un objet [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) qui définit le remplissage du cap personnalisé. |
| stroke_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Un objet [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) qui définit le contour du cap personnalisé. |
| base_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | Le cap de ligne à partir duquel créer le cap personnalisé. |

### Constructor: CustomLineCap(fill_path, stroke_path, base_cap, base_inset) {#CustomLineCap_fill_path_stroke_path_base_cap_base_inset_3}


```
 CustomLineCap(fill_path, stroke_path, base_cap, base_inset) 
```

Initialise une nouvelle instance de la classe [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) à partir de l'énumération [LineCap](/psd/python-net/aspose.psd/linecap/) existante spécifiée, avec le contour, le remplissage et l'encoche spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| fill_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Un objet [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) qui définit le remplissage du cap personnalisé. |
| stroke_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Un objet [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) qui définit le contour du cap personnalisé. |
| base_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | Le cap de ligne à partir duquel créer le cap personnalisé. |
| base_inset | float | La distance entre le cap et la ligne. |

### Method: get_stroke_caps(start_cap, end_cap) {#get_stroke_caps_start_cap_end_cap_1}


```
 get_stroke_caps(start_cap, end_cap) 
```

Obtient les caps utilisés pour commencer et terminer les lignes qui composent ce cap personnalisé.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| start_cap | [LineCap[]](/psd/python-net/aspose.psd/linecap) | L'énumération [LineCap](/psd/python-net/aspose.psd/linecap/) utilisée au début d'une ligne dans ce cap. |
| end_cap | [LineCap[]](/psd/python-net/aspose.psd/linecap) | L'énumération [LineCap](/psd/python-net/aspose.psd/linecap/) utilisée à la fin d'une ligne dans ce cap. |

### Method: set_stroke_caps(start_cap, end_cap) {#set_stroke_caps_start_cap_end_cap_2}


```
 set_stroke_caps(start_cap, end_cap) 
```

Définit les caps utilisés pour commencer et terminer les lignes qui composent ce cap personnalisé.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| start_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | L'énumération [LineCap](/psd/python-net/aspose.psd/linecap/) utilisée au début d'une ligne dans ce cap. |
| end_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | L'énumération [LineCap](/psd/python-net/aspose.psd/linecap/) utilisée à la fin d'une ligne dans ce cap. |

