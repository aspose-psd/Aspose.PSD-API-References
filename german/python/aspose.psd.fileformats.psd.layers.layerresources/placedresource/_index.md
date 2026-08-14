---
title: "PlacedResource‑Klasse"
type: docs
weight: 830
url: /de/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedresource/
---

**Summary:** Defines the PlacedResource class that contains common information about a placed layer or a smart object layer in the PSD file.<br/>            Is is used to support smart object layers in the Adobe� Photoshop� images.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PlacedResource

**Inheritance:** IPlacedLayerResource, LayerResource

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Die PSB-spezifische Ressourcen-Signatur. |
| RESOURCE_SIGNATURE [static] | int | r | Die allgemeine Ressourcen-Signatur. |
| anti_alias_policy | int | r/w | Liest oder setzt die Anti-Alias-Richtlinie der platzierten Ebene im PSD-Bild. |
| bottom | double | r/w | Liest oder setzt die untere Position der platzierten Ebene im PSD-Bild. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Liest oder setzt die Begrenzungen der platzierten Ebene in der PSD-Datei. |
| horizontal_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | Liest oder setzt die Maßeinheit der horizontalen Netzpunkte. |
| horizontal_mesh_points | double | r/w | Liest oder setzt die horizontalen Netzpunkte der platzierten Ebene in der PSD-Datei. |
| is_custom | bool | r/w | Liest oder setzt einen Wert, der angibt, ob dieser Instanz-Warp-Stil benutzerdefiniert ist.<br/>            Wenn true, enthält er Netzpunkte. Wenn auf false gesetzt, löscht er Netzpunkte. |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | Liest oder setzt die Warp-Elemente. |
| Schlüssel | int | r | Liest den Schicht-Ressourcen-Schlüssel. |
| left | double | r/w | Liest oder setzt die linke Position der platzierten Ebene in der PSD-Datei. |
| Länge | int | r | Liest die Länge der Schicht-Ressource in Bytes. |
| page_number | int | r/w | Liest oder setzt die Seitennummer der platzierten Ebene in der PSD-Datei. |
| perspective | double | r/w | Liest oder setzt den Perspektivwert der platzierten Ebene in der PSD-Datei. |
| perspective_other | double | r/w | Liest oder setzt den anderen Perspektivwert der platzierten Ebene in der PSD-Datei. |
| placed_layer_type | [PlacedLayerType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedlayertype) | r/w | Liest oder setzt den Typ der platzierten Ebene in der PSD-Datei. |
| psd_version | int | r | Liefert die minimale psd-Version, die für die Ebenenressource erforderlich ist. 0 bedeutet keine Einschränkungen. |
| rechts | double | r/w | Liest oder setzt die rechte Position der platzierten Ebene in der PSD-Datei. |
| signature | int | r | Liefert die Signatur. |
| oben | double | r/w | Liest oder setzt die obere Position der platzierten Ebene im PSD-Bild. |
| total_pages | int | r/w | Liest oder setzt die Gesamtseitenzahl der platzierten Ebene in der PSD-Datei. |
| transform_matrix | double | r/w | Liest oder setzt die Transformationsmatrix der platzierten Ebene in der PSD-Datei. |
| u_order | int | r/w | Liest oder setzt den U-Ordnungswert der platzierten Ebene in der PSD-Datei. |
| unique_id | Guid | r/w | Liest oder setzt die global eindeutige Kennung der platzierten Ebene im PSD-Bild. |
| v_order | int | r/w | Liest oder setzt den V-Ordnungswert der platzierten Ebene in der PSD-Datei. |
| Wert | double | r/w | Liest oder setzt den Warp-Wert der platzierten Ebene im PSD-Bild. |
| version | int | r | Liefert die Version der platzierten Ebene in der PSD-Datei, normalerweise 3. |
| vertical_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | Liest oder setzt die Maßeinheit der vertikalen Netzpunkte. |
| vertical_mesh_points | double | r/w | Liest oder setzt die horizontalen Netzpunkte der platzierten Ebene in der PSD-Datei. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Speichert die Ressource im angegebenen Stream-Container. |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Speichert die Ressource im angegebenen Stream-Container.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Der Stream-Container, in dem gespeichert werden soll. |
| psd_version | int | Die PSD-Version. |

