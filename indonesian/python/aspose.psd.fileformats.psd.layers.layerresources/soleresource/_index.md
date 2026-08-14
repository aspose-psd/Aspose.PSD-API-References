---
title: "Kelas SoLeResource"
type: docs
weight: 940
url: /id/python-net/aspose.psd.fileformats.psd.layers.layerresources/soleresource/
---

**Summary:** Defines the SoLeResource class that contains information about a smart object layer in a PSD file.<br/>            Is is used to support smart object layers with external file links in the Adobe� Photoshop� images.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.SoLeResource

**Inheritance:** IPlacedLayerResource, ISmartObjectLayerResource, SmartObjectResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [SoLeResource()](#SoLeResource__1) | Menginisialisasi instance baru dari kelas [SoLeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soleresource/). |
| [SoLeResource(unique_id, is_custom, has_comp_info)](#SoLeResource_unique_id_is_custom_has_comp_info_2) | Menginisialisasi instance baru dari kelas [SoLeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soleresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Signature sumber daya khusus PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Signature sumber daya umum. |
| TYPE_TOOL_KEY [static] | int | r | Kunci info alat tipe: 'SoLE'. |
| anti_alias_policy | int | r/w | Mendapatkan atau mengatur kebijakan anti alias dari data lapisan objek pintar dalam gambar PSD. |
| bawah | double | r/w | Mendapatkan atau mengatur lokasi bawah lapisan yang ditempatkan dalam gambar PSD. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Mendapatkan atau mengatur batas lapisan yang ditempatkan dalam file PSD. |
| comp | int | r/w | Mendapatkan atau mengatur nilai comp dari data lapisan objek pintar dalam file PSD.<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">Layer comps in Smart Objects</see> |
| comp_id | int | r/w | Mendapatkan atau mengatur ID comp yang saat ini dipilih untuk dokumen anak, yang akan bernilai -1 jika tidak ada yang dipilih.<br/>            Comp adalah komposisi dari tata letak halaman yang dapat dibuat oleh desainer. Dengan menggunakan layer comps, Anda dapat membuat, mengelola, dan melihat banyak versi<br/>            dari sebuah tata letak dalam satu file Adobe� Photoshop�. Sebuah layer comp adalah snapshot dari keadaan panel Layers. Layer comps menyimpan tiga jenis opsi lapisan tetapi<br/>            properti ini mendapatkan pengidentifikasi pemilihan Layer Comp untuk lapisan objek pintar dalam file PSD.<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">Layer comps in Smart Objects</see> |
| crop | int | r/w | Mendapatkan atau mengatur pemotongan data lapisan objek pintar dalam gambar PSD. |
| duration_denominator | int | r/w | Mendapatkan atau mengatur penyebut durasi. |
| duration_numerator | int | r/w | Mendapatkan atau mengatur pembilang durasi. |
| frame_count | int | r/w | Mendapatkan atau mengatur jumlah frame data lapisan objek pintar dalam file PSD. |
| frame_step_denominator | int | r/w | Mendapatkan atau mengatur penyebut langkah frame. |
| frame_step_numerator | int | r/w | Mendapatkan atau mengatur pembilang langkah frame. |
| tinggi | double | r/w | Mendapatkan atau mengatur tinggi. |
| horizontal_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | Mendapatkan atau mengatur satuan ukuran titik mesh horizontal. |
| horizontal_mesh_points | double | r/w | Mendapatkan atau mengatur titik mesh horizontal dari lapisan yang ditempatkan dalam file PSD. |
| is_custom | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah gaya warp instance ini khusus.<br/>            Jika true, ia berisi titik mesh. Jika diset ke false, ia menghapus titik mesh. |
| items | [OSTypeStructure[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | r/w | Mendapatkan atau mengatur item deskriptor data lapisan objek pintar dalam file PSD. |
| key | int | r | Mendapatkan kunci sumber daya lapisan. |
| kiri | double | r/w | Mendapatkan atau mengatur lokasi kiri lapisan yang ditempatkan dalam file PSD. |
| panjang | int | r | Mendapatkan panjang sumber daya objek pintar dalam byte. |
| non_affine_transform_matrix | double | r/w | Mendapatkan atau mengatur matriks transformasi non-afin data lapisan objek pintar dalam file PSD. |
| original_comp_id | int | r | Mendapatkan ID asli dari Comp yang saat ini dipilih untuk dokumen anak, yang akan menjadi -1 jika tidak ada yang dipilih.<br/>            Properti ini mendapatkan pengidentifikasi pemilihan layer Comp asli untuk lapisan objek pintar dalam file PSD.<br/>            <see href="https://helpx.adobe.com/photoshop/using/layer-comps.html">Komposisi layer dalam Objek Pintar</see> |
| page_number | int | r/w | Mendapatkan atau mengatur nomor halaman data lapisan objek pintar dalam file PSD. |
| perspective | double | r/w | Mendapatkan atau mengatur nilai perspektif lapisan yang ditempatkan dalam file PSD. |
| perspective_other | double | r/w | Mendapatkan atau mengatur nilai perspektif lainnya dari lapisan yang ditempatkan dalam file PSD. |
| placed_id | Guid | r/w | Mendapatkan atau mengatur pengidentifikasi unik data lapisan objek pintar ini dalam gambar PSD. |
| placed_layer_type | [PlacedLayerType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedlayertype) | r/w | Mendapatkan atau mengatur tipe data lapisan objek pintar dalam file PSD. |
| psd_version | int | r | Mendapatkan versi psd minimal yang diperlukan untuk sumber daya lapisan. 0 menunjukkan tidak ada batasan. |
| resolution | double | r/w | Mendapatkan atau mengatur resolusi data lapisan objek pintar dalam file PSD. |
| resolution_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | Mendapatkan atau mengatur satuan ukuran resolusi data lapisan objek pintar dalam file PSD. |
| kanan | double | r/w | Mendapatkan atau mengatur lokasi kanan lapisan yang ditempatkan dalam file PSD. |
| signature | int | r | Mendapatkan signature. |
| atas | double | r/w | Mendapatkan atau mengatur lokasi atas lapisan yang ditempatkan dalam gambar PSD. |
| total_pages | int | r/w | Mendapatkan atau mengatur jumlah total halaman data lapisan objek pintar dalam file PSD. |
| transform_matrix | double | r/w | Mendapatkan atau mengatur matriks transformasi data lapisan objek pintar dalam file PSD. |
| u_order | int | r/w | Mendapatkan atau mengatur nilai urutan U lapisan yang ditempatkan dalam file PSD. |
| unique_id | Guid | r/w | Mendapatkan atau mengatur pengidentifikasi unik global data lapisan objek pintar [SmartObjectResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/) dalam gambar PSD. |
| v_order | int | r/w | Mendapatkan atau mengatur nilai urutan V lapisan yang ditempatkan dalam file PSD. |
| value | double | r/w | Mendapatkan atau mengatur nilai warp lapisan yang ditempatkan dalam gambar PSD. |
| version | int | r | Mendapatkan versi lapisan yang ditempatkan dalam file PSD, biasanya 3-5. |
| vertical_mesh_point_unit | [UnitTypes](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/unittypes/) | r/w | Mendapatkan atau mengatur satuan ukuran titik mesh vertikal. |
| vertical_mesh_points | double | r/w | Mendapatkan atau mengatur titik mesh horizontal dari lapisan yang ditempatkan dalam file PSD. |
| width | double | r/w | Mendapatkan atau mengatur lebar. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Menyimpan sumber daya objek pintar ke kontainer aliran yang ditentukan. |


### Constructor: SoLeResource() {#SoLeResource__1}


```
 SoLeResource() 
```

Menginisialisasi instance baru dari kelas [SoLeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soleresource/).

### Constructor: SoLeResource(unique_id, is_custom, has_comp_info) {#SoLeResource_unique_id_is_custom_has_comp_info_2}


```
 SoLeResource(unique_id, is_custom, has_comp_info) 
```

Menginisialisasi instance baru dari kelas [SoLeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soleresource/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| unique_id | Guid | Pengidentifikasi unik dari data lapisan yang ditempatkan [PlLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/plldresource/). |
| is_custom | bool | jika disetel ke <c>true</c> [is custom]. |
| has_comp_info | bool | jika disetel ke <c>true</c> [has comp information]. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Menyimpan sumber daya objek pintar ke kontainer aliran yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Kontainer aliran untuk disimpan. |
| psd_version | int | Versi PSD. |

