---
title: "Classe PsdLoadOptions"
type: docs
weight: 30
url: /fr/python-net/aspose.psd.imageloadoptions/psdloadoptions/
---

**Summary:** Psd load options

**Module:** [aspose.psd.imageloadoptions](/psd/python-net/aspose.psd.imageloadoptions/)

**Full Name:** aspose.psd.imageloadoptions.PsdLoadOptions

**Inheritance:** LoadOptions

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PsdLoadOptions()](#PsdLoadOptions__1) | Initialise une nouvelle instance de la classe PsdLoadOptions |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| allow_warp_repaint | bool | r/w | Obtient ou définit s'il faut enregistrer avec l'image rendue, avec ou sans transformation de déformation. |
| buffer_size_hint | int | r/w | Obtient ou définit l'indice de taille du tampon qui définit la taille maximale autorisée pour tous les tampons internes. |
| data_background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Obtient ou définit le [Image](/psd/python-net/aspose.psd/image/) d'arrière-plan [Color](/psd/python-net/aspose.psd/color/). |
| data_recovery_mode | [DataRecoveryMode](/psd/python-net/aspose.psd/datarecoverymode) | r/w | Obtient ou définit le mode de récupération des données. |
| ignore_alpha_channel | bool | r/w | Obtient ou définit une valeur indiquant si [ignorer le canal alpha]. |
| ignore_text_layer_width_on_update | bool | r/w | Obtient ou définit une valeur indiquant si la largeur fixe du calque texte PSD sera ignorée lors de l'exécution de l'opération UpdateText. |
| load_effects_resource | bool | r/w | Obtient ou définit une valeur indiquant si [charger les ressources d'effets] (par défaut la ressource n'est pas chargée). Lorsque cette option est définie, seuls les effets pris en charge seront rendus dans l'image fusionnée finale. |
| read_only_mode | bool | r/w | Obtient ou définit une valeur indiquant si [utiliser le mode lecture seule]. Il s'agit du mode lecture seule, pris en charge pour une compatibilité identique avec Adobe Photoshop.<br/>            Lorsque cette option est définie, toutes les modifications appliquées aux calques ne seront pas enregistrées dans l'image finale. Toutes les données proviennent de la section ImageData, de sorte qu'elles sont identiques à Photoshop. <br/>            Par défaut, toutes les images chargées ne sont pas compatibles de manière identique avec Adobe Photoshop. |
| use_disk_for_load_effects_resource | bool | r/w | Obtient ou définit une valeur indiquant si [utiliser le disque pour charger les ressources d'effets] (par défaut le disque est utilisé pour charger les ressources d'effets, mais la mémoire peut être utilisée si elle est suffisante en définissant cette valeur à false). |
| use_icc_profile_conversion | bool | r/w | Obtient ou définit une valeur indiquant si la conversion de profil ICC doit être appliquée. |


### Constructor: PsdLoadOptions() {#PsdLoadOptions__1}


```
 PsdLoadOptions() 
```

Initialise une nouvelle instance de la classe PsdLoadOptions

