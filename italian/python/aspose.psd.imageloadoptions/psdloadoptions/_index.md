---
title: "Classe PsdLoadOptions"
type: docs
weight: 30
url: /it/python-net/aspose.psd.imageloadoptions/psdloadoptions/
---

**Summary:** Psd load options

**Module:** [aspose.psd.imageloadoptions](/psd/python-net/aspose.psd.imageloadoptions/)

**Full Name:** aspose.psd.imageloadoptions.PsdLoadOptions

**Inheritance:** LoadOptions

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PsdLoadOptions()](#PsdLoadOptions__1) | Inizializza una nuova istanza della classe PsdLoadOptions |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| allow_warp_repaint | bool | r/w | Ottiene o imposta se salvare con l'immagine renderizzata, con o senza una trasformazione warp. |
| buffer_size_hint | int | r/w | Ottiene o imposta il suggerimento della dimensione del buffer, che è definito come dimensione massima consentita per tutti i buffer interni. |
| data_background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Ottiene o imposta lo sfondo [Image](/psd/python-net/aspose.psd/image/) [Color](/psd/python-net/aspose.psd/color/). |
| data_recovery_mode | [DataRecoveryMode](/psd/python-net/aspose.psd/datarecoverymode) | r/w | Ottiene o imposta la modalità di recupero dati. |
| ignore_alpha_channel | bool | r/w | Ottiene o imposta un valore che indica se [ignore alpha channel]. |
| ignore_text_layer_width_on_update | bool | r/w | Ottiene o imposta un valore che indica se la larghezza fissa del livello di testo PSD verrà ignorata durante l'esecuzione dell'operazione UpdateText. |
| load_effects_resource | bool | r/w | Ottiene o imposta un valore che indica se [load effects resource] (per impostazione predefinita la risorsa non è caricata). Quando questa opzione è impostata, verranno renderizzati solo gli effetti supportati nell'immagine finale unita. |
| read_only_mode | bool | r/w | Ottiene o imposta un valore che indica se [use read only mode]. Questa è la modalità di sola lettura, supportata per una compatibilità identica con Adobe Photoshop.<br/>            Quando questa opzione è impostata, tutte le modifiche applicate ai livelli non verranno salvate nell'immagine finale. Tutti i dati provengono dalla sezione ImageData, quindi è identica a Photoshop. <br/>            Per impostazione predefinita tutte le immagini caricate non sono compatibili in modo identico con Adobe Photoshop. |
| use_disk_for_load_effects_resource | bool | r/w | Ottiene o imposta un valore che indica se [use disk for load effects resource] (per impostazione predefinita si utilizza il disco per caricare la risorsa degli effetti, ma può essere usata la memoria se è sufficiente impostando questo valore su false). |
| use_icc_profile_conversion | bool | r/w | Ottiene o imposta un valore che indica se la conversione del profilo ICC deve essere applicata. |


### Constructor: PsdLoadOptions() {#PsdLoadOptions__1}


```
 PsdLoadOptions() 
```

Inizializza una nuova istanza della classe PsdLoadOptions

