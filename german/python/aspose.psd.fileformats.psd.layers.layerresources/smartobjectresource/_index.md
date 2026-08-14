---
title: "SmartObjectResource Klasse"
type: docs
weight: 900
url: /de/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/
---

**Summary:** Defines the SmartObjectResource class that contains information about a smart object layer in a PSD file.<br/>            Is is the base class for Sold and Sole resources that is used to support smart object layers in the Adobe� Photoshop� images.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.SmartObjectResource

**Inheritance:** IPlacedLayerResource, ISmartObjectLayerResource, PlacedResource

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Die PSB-spezifische Ressourcen-Signatur. |
| RESOURCE_SIGNATURE [static] | int | r | Die allgemeine Ressourcen-Signatur. |
| anti_alias_policy | int | r/w | Liest oder setzt die Anti-Alias-Richtlinie der Smart-Object-Ebenendaten im PSD-Bild. |
| bottom | double | r/w | Liest oder setzt die untere Position der platzierten Ebene im PSD-Bild. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Liest oder setzt die Begrenzungen der platzierten Ebene in der PSD-Datei. |
| comp | int | r/w | Liest oder setzt den comp-Wert der Smart-Object-Ebenendaten in der PSD-Datei.<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">Layer-Comps in Smart Objects</see> |
| comp_id | int | r/w | Liest oder setzt die ID der derzeit ausgewählten Komposition für das untergeordnete Dokument, die -1 ist, wenn keine ausgewählt ist.<br/>            Kompositionen sind Zusammensetzungen eines Seitenlayouts, die Designer erstellen können. Mit Layer‑Kompositionen können Sie mehrere Versionen<br/>            eines Layouts in einer einzigen Adobe‑Photoshop‑Datei erstellen, verwalten und anzeigen. Eine Layer‑Komposition ist ein Schnappschuss eines Zustands des Ebenen‑Panels. Layer‑Kompositionen speichern drei Arten von Ebenenoptionen, aber<br/>            diese Eigenschaft liest die Auswahl‑Kennung der Layer‑Komposition für die Smart‑Object‑Ebene in der PSD‑Datei.<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">Layer‑Kompositionen in Smart Objects</see> |
| Zuschneiden | int | r/w | Liest oder setzt den Zuschnitt der Smart‑Object‑Ebenendaten im PSD‑Bild. |
| duration_denominator | int | r/w | Liest oder setzt den Dauer‑Nenner. |
| duration_numerator | int | r/w | Liest oder setzt den Dauer‑Zähler. |
| frame_count | int | r/w | Liest oder setzt die Bildanzahl der Smart‑Object‑Ebenendaten in der PSD‑Datei. |
| frame_step_denominator | int | r/w | Liest oder setzt den Bildschritt‑Nenner. |
| frame_step_numerator | int | r/w | Liest oder setzt den Bildschritt‑Zähler. |
| height | double | r/w | Liest oder setzt die Höhe. |
| horizontal_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | Liest oder setzt die Maßeinheit der horizontalen Netzpunkte. |
| horizontal_mesh_points | double | r/w | Liest oder setzt die horizontalen Netzpunkte der platzierten Ebene in der PSD-Datei. |
| is_custom | bool | r/w | Liest oder setzt einen Wert, der angibt, ob dieser Instanz-Warp-Stil benutzerdefiniert ist.<br/>            Wenn true, enthält er Netzpunkte. Wenn auf false gesetzt, löscht er Netzpunkte. |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | Liest oder setzt die Deskriptor‑Elemente der Smart‑Object‑Ebenendaten in der PSD‑Datei. |
| Schlüssel | int | r | Liest den Schicht-Ressourcen-Schlüssel. |
| left | double | r/w | Liest oder setzt die linke Position der platzierten Ebene in der PSD-Datei. |
| Länge | int | r | Liest die Länge der Smart‑Object‑Ressource in Bytes. |
| non_affine_transform_matrix | double | r/w | Liest oder setzt die nicht‑affine Transformationsmatrix der Smart‑Object‑Ebenendaten in der PSD‑Datei. |
| original_comp_id | int | r | Liest die ursprüngliche ID der derzeit ausgewählten Komposition für das untergeordnete Dokument, die -1 ist, wenn keine ausgewählt ist.<br/>            Diese Eigenschaft liest die ursprüngliche Auswahl‑Kennung der Layer‑Komposition für die Smart‑Object‑Ebene in der PSD‑Datei.<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">Layer‑Kompositionen in Smart Objects</see> |
| page_number | int | r/w | Liest oder setzt die Seitenzahl der Smart‑Object‑Ebenendaten in der PSD‑Datei. |
| perspective | double | r/w | Liest oder setzt den Perspektivwert der platzierten Ebene in der PSD-Datei. |
| perspective_other | double | r/w | Liest oder setzt den anderen Perspektivwert der platzierten Ebene in der PSD-Datei. |
| placed_id | Guid | r/w | Liest oder setzt die eindeutige Kennung dieser Smart‑Object‑Ebenendaten im PSD‑Bild. |
| placed_layer_type | [PlacedLayerType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedlayertype) | r/w | Liest oder setzt den Typ der Smart‑Object‑Ebenendaten in der PSD‑Datei. |
| psd_version | int | r | Liefert die minimale psd-Version, die für die Ebenenressource erforderlich ist. 0 bedeutet keine Einschränkungen. |
| resolution | double | r/w | Liest oder setzt die Auflösung der Smart‑Object‑Ebenendaten in der PSD‑Datei. |
| resolution_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | Liest oder setzt die Einheit der Auflösung der Smart‑Object‑Ebenendaten in der PSD‑Datei. |
| rechts | double | r/w | Liest oder setzt die rechte Position der platzierten Ebene in der PSD-Datei. |
| signature | int | r | Liefert die Signatur. |
| oben | double | r/w | Liest oder setzt die obere Position der platzierten Ebene im PSD-Bild. |
| total_pages | int | r/w | Liest oder setzt die Gesamtseitenzahl der Smart-Object-Ebenendaten in der PSD-Datei. |
| transform_matrix | double | r/w | Liest oder setzt die Transformationsmatrix der Smart-Object-Ebenendaten in der PSD-Datei. |
| u_order | int | r/w | Liest oder setzt den U-Ordnungswert der platzierten Ebene in der PSD-Datei. |
| unique_id | Guid | r/w | Liest oder setzt die global eindeutige Kennung der Smart-Object-Ebenendaten [SmartObjectResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/) im PSD-Bild. |
| v_order | int | r/w | Liest oder setzt den V-Ordnungswert der platzierten Ebene in der PSD-Datei. |
| Wert | double | r/w | Liest oder setzt den Warp-Wert der platzierten Ebene im PSD-Bild. |
| version | int | r | Liefert die Version der platzierten Ebene in der PSD-Datei, normalerweise 3. |
| vertical_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | Liest oder setzt die Maßeinheit der vertikalen Netzpunkte. |
| vertical_mesh_points | double | r/w | Liest oder setzt die horizontalen Netzpunkte der platzierten Ebene in der PSD-Datei. |
| width | double | r/w | Liest oder setzt die Breite. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Speichert die Smart-Object-Ressource in den angegebenen Stream-Container. |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Speichert die Smart-Object-Ressource in den angegebenen Stream-Container.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Der Stream-Container, in dem gespeichert werden soll. |
| psd_version | int | Die PSD-Version. |

