---
title: "Classe ColorComponent"
type: docs
weight: 10
url: /it/python-net/aspose.psd.fileformats.psd.core.rawcolor/colorcomponent/
---

**Summary:** Color component is an abstraction over Channel Value and Channel Value.<br/>            Any color is composed from an array of ColorComponent

**Module:** [aspose.psd.fileformats.psd.core.rawcolor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/)

**Full Name:** aspose.psd.fileformats.psd.core.rawcolor.ColorComponent

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ColorComponent(bit_depth, full_name)](#ColorComponent_bit_depth_full_name_1) | Inizializza una nuova istanza della classe [ColorComponent](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/colorcomponent/).<br/>            Si prega di verificare |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bit_depth | byte | r | Ottiene la profondità di bit del componente/canale colore |
| descrizione | string | r | Ottiene la descrizione del componente colore |
| nome_completo | string | r | Ottiene il nome completo del componente colore con nome e descrizione separata da spazi |
| name | string | r | Restituisce il nome del componente di colore. |
| permitted_full_names [static] | string | r | Restituisce i nomi completi consentiti. |
| value | ulong | r/w | Ottiene o imposta il valore. <br/>            Nota, se provi a impostare un valore superiore a <br/>            quello possibile da memorizzare nella profondità di bit corrente, otterrai un'eccezione |


### Constructor: ColorComponent(bit_depth, full_name) {#ColorComponent_bit_depth_full_name_1}


```
 ColorComponent(bit_depth, full_name) 
```

Inizializza una nuova istanza della classe [ColorComponent](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/colorcomponent/).<br/>            Si prega di verificare

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| bit_depth | byte | La profondità di bit. |
| nome_completo | string | Il nome completo. |

