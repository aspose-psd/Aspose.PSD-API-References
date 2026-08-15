---
title: "ColorComponent-klass"
type: docs
weight: 10
url: /sv/python-net/aspose.psd.fileformats.psd.core.rawcolor/colorcomponent/
---

**Summary:** Color component is an abstraction over Channel Value and Channel Value.<br/>            Any color is composed from an array of ColorComponent

**Module:** [aspose.psd.fileformats.psd.core.rawcolor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/)

**Full Name:** aspose.psd.fileformats.psd.core.rawcolor.ColorComponent

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [ColorComponent(bit_depth, full_name)](#ColorComponent_bit_depth_full_name_1) | Initierar en ny instans av klassen [ColorComponent](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/colorcomponent/).<br/>            Vänligen kontrollera |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| bit_depth | byte | r | Hämtar bitdjupet för Color Component/Channel |
| beskrivning | string | r | Hämtar beskrivningen av Color Component |
| full_name | string | r | Hämtar det fullständiga namnet på color component med namn och mellanslagsseparerad beskrivning |
| name | string | r | Hämtar namnet på color component. |
| permitted_full_names [static] | string | r | Hämtar de tillåtna fullständiga namnen. |
| värde | ulong | r/w | Hämtar eller anger värdet. <br/>            Observera att om du försöker ange ett värde som är mer än <br/>            möjligt att lagras i nuvarande bitdjup, får du ett undantag |


### Constructor: ColorComponent(bit_depth, full_name) {#ColorComponent_bit_depth_full_name_1}


```
 ColorComponent(bit_depth, full_name) 
```

Initierar en ny instans av klassen [ColorComponent](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/colorcomponent/).<br/>            Vänligen kontrollera

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| bit_depth | byte | Bitdjupet. |
| full_name | string | Det fullständiga namnet. |

