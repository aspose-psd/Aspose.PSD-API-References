---
title: "Kelas PlLdResource"
type: docs
weight: 820
url: /id/python-net/aspose.psd.fileformats.psd.layers.layerresources/plldresource/
---

**Summary:** Defines the PlLdResource class that contains information about a placed layer in the PSD file.<br/>            Is is used to support smart object layers in the Adobe� Photoshop� images.<br/>            It was replaced by SoLdResource in the Adobe� Photoshop� CS3

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.PlLdResource

**Inheritance:** IPlacedLayerResource, PlacedResource

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Signature sumber daya khusus PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Signature sumber daya umum. |
| TYPE_TOOL_KEY [static] | int | r | Kunci info type tool. |
| anti_alias_policy | int | r/w | Mendapatkan atau mengatur kebijakan anti alias dari lapisan yang ditempatkan dalam gambar PSD. |
| bawah | double | r/w | Mendapatkan atau mengatur lokasi bawah lapisan yang ditempatkan dalam gambar PSD. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Mendapatkan atau mengatur batas lapisan yang ditempatkan dalam file PSD. |
| horizontal_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | Mendapatkan atau mengatur satuan ukuran titik mesh horizontal. |
| horizontal_mesh_points | double | r/w | Mendapatkan atau mengatur titik mesh horizontal dari lapisan yang ditempatkan dalam file PSD. |
| is_custom | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah gaya warp instance ini khusus.<br/>            Jika true, ia berisi titik mesh. Jika diset ke false, ia menghapus titik mesh. |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | Mendapatkan atau mengatur item warp. |
| key | int | r | Mendapatkan kunci sumber daya lapisan. |
| kiri | double | r/w | Mendapatkan atau mengatur lokasi kiri lapisan yang ditempatkan dalam file PSD. |
| panjang | int | r | Mendapatkan panjang sumber daya PlLd dalam byte. |
| page_number | int | r/w | Mendapatkan atau mengatur nomor halaman lapisan yang ditempatkan dalam file PSD. |
| perspective | double | r/w | Mendapatkan atau mengatur nilai perspektif lapisan yang ditempatkan dalam file PSD. |
| perspective_other | double | r/w | Mendapatkan atau mengatur nilai perspektif lainnya dari lapisan yang ditempatkan dalam file PSD. |
| placed_layer_type | [PlacedLayerType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedlayertype) | r/w | Mendapatkan atau mengatur tipe lapisan yang ditempatkan dalam file PSD. |
| psd_version | int | r | Mendapatkan versi psd minimal yang diperlukan untuk sumber daya lapisan. 0 menunjukkan tidak ada batasan. |
| kanan | double | r/w | Mendapatkan atau mengatur lokasi kanan lapisan yang ditempatkan dalam file PSD. |
| signature | int | r | Mendapatkan signature. |
| atas | double | r/w | Mendapatkan atau mengatur lokasi atas lapisan yang ditempatkan dalam gambar PSD. |
| total_pages | int | r/w | Mendapatkan atau mengatur total halaman lapisan yang ditempatkan dalam file PSD. |
| transform_matrix | double | r/w | Mendapatkan atau mengatur matriks transformasi lapisan yang ditempatkan dalam file PSD. |
| u_order | int | r/w | Mendapatkan atau mengatur nilai urutan U lapisan yang ditempatkan dalam file PSD. |
| unique_id | Guid | r/w | Mendapatkan atau mengatur pengidentifikasi unik global lapisan yang ditempatkan dalam gambar PSD. |
| v_order | int | r/w | Mendapatkan atau mengatur nilai urutan V lapisan yang ditempatkan dalam file PSD. |
| value | double | r/w | Mendapatkan atau mengatur nilai warp lapisan yang ditempatkan dalam gambar PSD. |
| version | int | r | Mendapatkan versi lapisan yang ditempatkan dalam file PSD, biasanya 3. |
| vertical_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | Mendapatkan atau mengatur satuan ukuran titik mesh vertikal. |
| vertical_mesh_points | double | r/w | Mendapatkan atau mengatur titik mesh horizontal dari lapisan yang ditempatkan dalam file PSD. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Menyimpan sumber daya PlLD ke kontainer aliran yang ditentukan. |


### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Menyimpan sumber daya PlLD ke kontainer aliran yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Kontainer aliran untuk disimpan. |
| psd_version | int | Versi PSD. |

