---
title: "CustomLineCap Klasse"
type: docs
weight: 1010
url: /de/python-net/aspose.psd/customlinecap/
---

**Summary:** Encapsulates a custom user-defined line cap.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.CustomLineCap

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [CustomLineCap(fill_path, stroke_path)](#CustomLineCap_fill_path_stroke_path_1) | Initialisiert eine neue Instanz der [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) Klasse mit der angegebenen Kontur und Füllung. |
| [CustomLineCap(fill_path, stroke_path, base_cap)](#CustomLineCap_fill_path_stroke_path_base_cap_2) | Initialisiert eine neue Instanz der [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) Klasse aus der angegebenen vorhandenen [LineCap](/psd/python-net/aspose.psd/linecap/) Aufzählung mit der angegebenen Kontur und Füllung. |
| [CustomLineCap(fill_path, stroke_path, base_cap, base_inset)](#CustomLineCap_fill_path_stroke_path_base_cap_base_inset_3) | Initialisiert eine neue Instanz der [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) Klasse aus der angegebenen vorhandenen [LineCap](/psd/python-net/aspose.psd/linecap/) Aufzählung mit der angegebenen Kontur, Füllung und Einrückung. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| base_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | r/w | Liest oder setzt die [LineCap](/psd/python-net/aspose.psd/linecap/) Aufzählung, auf der diese [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) basiert. |
| base_inset | float | r/w | Liest oder setzt den Abstand zwischen der Kappe und der Linie. |
| fill_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | r/w | Liest oder setzt das Objekt, das die Füllung für die benutzerdefinierte Kappe definiert. |
| stroke_join | [LineJoin](/psd/python-net/aspose.psd/linejoin) | r/w | Liest oder setzt die [LineJoin](/psd/python-net/aspose.psd/linejoin/) Aufzählung, die bestimmt, wie Linien, die dieses [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) Objekt bilden, verbunden werden. |
| stroke_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | r/w | Liest oder setzt das Objekt, das die Kontur der benutzerdefinierten Kappe definiert. |
| width_scale | float | r/w | Liest oder setzt den Betrag, um den dieses [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) Klassenobjekt in Bezug auf die Breite des Objekts skaliert wird. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [get_stroke_caps(start_cap, end_cap)](#get_stroke_caps_start_cap_end_cap_1) | Liest die Kappen, die zum Starten und Beenden von Linien verwendet werden, die diese benutzerdefinierte Kappe bilden. |
| [set_stroke_caps(start_cap, end_cap)](#set_stroke_caps_start_cap_end_cap_2) | Setzt die Kappen, die zum Starten und Beenden von Linien verwendet werden, die diese benutzerdefinierte Kappe bilden. |


### Constructor: CustomLineCap(fill_path, stroke_path) {#CustomLineCap_fill_path_stroke_path_1}


```
 CustomLineCap(fill_path, stroke_path) 
```

Initialisiert eine neue Instanz der [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) Klasse mit der angegebenen Kontur und Füllung.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| fill_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Ein [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) Objekt, das die Füllung für die benutzerdefinierte Kappe definiert. |
| stroke_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Ein [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) Objekt, das die Kontur der benutzerdefinierten Kappe definiert. |

### Constructor: CustomLineCap(fill_path, stroke_path, base_cap) {#CustomLineCap_fill_path_stroke_path_base_cap_2}


```
 CustomLineCap(fill_path, stroke_path, base_cap) 
```

Initialisiert eine neue Instanz der [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) Klasse aus der angegebenen vorhandenen [LineCap](/psd/python-net/aspose.psd/linecap/) Aufzählung mit der angegebenen Kontur und Füllung.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| fill_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Ein [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) Objekt, das die Füllung für die benutzerdefinierte Kappe definiert. |
| stroke_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Ein [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) Objekt, das die Kontur der benutzerdefinierten Kappe definiert. |
| base_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | Die Linienkappe, aus der die benutzerdefinierte Kappe erstellt wird. |

### Constructor: CustomLineCap(fill_path, stroke_path, base_cap, base_inset) {#CustomLineCap_fill_path_stroke_path_base_cap_base_inset_3}


```
 CustomLineCap(fill_path, stroke_path, base_cap, base_inset) 
```

Initialisiert eine neue Instanz der [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) Klasse aus der angegebenen vorhandenen [LineCap](/psd/python-net/aspose.psd/linecap/) Aufzählung mit der angegebenen Kontur, Füllung und Einrückung.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| fill_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Ein [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) Objekt, das die Füllung für die benutzerdefinierte Kappe definiert. |
| stroke_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Ein [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) Objekt, das die Kontur der benutzerdefinierten Kappe definiert. |
| base_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | Die Linienkappe, aus der die benutzerdefinierte Kappe erstellt wird. |
| base_inset | float | Der Abstand zwischen der Kappe und der Linie. |

### Method: get_stroke_caps(start_cap, end_cap) {#get_stroke_caps_start_cap_end_cap_1}


```
 get_stroke_caps(start_cap, end_cap) 
```

Liest die Kappen, die zum Starten und Beenden von Linien verwendet werden, die diese benutzerdefinierte Kappe bilden.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| start_cap | [LineCap[]](/psd/python-net/aspose.psd/linecap) | Die [LineCap](/psd/python-net/aspose.psd/linecap/) Aufzählung, die am Anfang einer Linie innerhalb dieser Kappe verwendet wird. |
| end_cap | [LineCap[]](/psd/python-net/aspose.psd/linecap) | Die [LineCap](/psd/python-net/aspose.psd/linecap/) Aufzählung, die am Ende einer Linie innerhalb dieser Kappe verwendet wird. |

### Method: set_stroke_caps(start_cap, end_cap) {#set_stroke_caps_start_cap_end_cap_2}


```
 set_stroke_caps(start_cap, end_cap) 
```

Setzt die Kappen, die zum Starten und Beenden von Linien verwendet werden, die diese benutzerdefinierte Kappe bilden.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| start_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | Die [LineCap](/psd/python-net/aspose.psd/linecap/) Aufzählung, die am Anfang einer Linie innerhalb dieser Kappe verwendet wird. |
| end_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | Die [LineCap](/psd/python-net/aspose.psd/linecap/) Aufzählung, die am Ende einer Linie innerhalb dieser Kappe verwendet wird. |

