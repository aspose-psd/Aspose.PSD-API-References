---
title: "Classe ColorComponent"
type: docs
weight: 10
url: /fr/python-net/aspose.psd.fileformats.psd.core.rawcolor/colorcomponent/
---

**Summary:** Color component is an abstraction over Channel Value and Channel Value.<br/>            Any color is composed from an array of ColorComponent

**Module:** [aspose.psd.fileformats.psd.core.rawcolor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/)

**Full Name:** aspose.psd.fileformats.psd.core.rawcolor.ColorComponent

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ColorComponent(bit_depth, full_name)](#ColorComponent_bit_depth_full_name_1) | Initialise une nouvelle instance de la classe [ColorComponent](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/colorcomponent/).<br/>            Veuillez vérifier |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bit_depth | byte | r | Obtient la profondeur de bits du composant/canal de couleur. |
| description | chaîne | r | Obtient la description du composant de couleur. |
| full_name | chaîne | r | Obtient le nom complet du composant de couleur avec le nom et la description séparés par des espaces. |
| name | chaîne | r | Obtient le nom du composant de couleur. |
| permitted_full_names [static] | chaîne | r | Obtient les noms complets autorisés. |
| valeur | ulong | r/w | Obtient ou définit la valeur. <br/>            Veuillez noter que si vous essayez de définir une valeur supérieure à <br/>            ce qui peut être stocké avec la profondeur de bits actuelle, une exception sera levée. |


### Constructor: ColorComponent(bit_depth, full_name) {#ColorComponent_bit_depth_full_name_1}


```
 ColorComponent(bit_depth, full_name) 
```

Initialise une nouvelle instance de la classe [ColorComponent](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/colorcomponent/).<br/>            Veuillez vérifier

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| bit_depth | byte | La profondeur de bits. |
| full_name | chaîne | Le nom complet. |

