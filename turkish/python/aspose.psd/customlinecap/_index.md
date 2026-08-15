---
title: "CustomLineCap Sınıfı"
type: docs
weight: 1010
url: /tr/python-net/aspose.psd/customlinecap/
---

**Summary:** Encapsulates a custom user-defined line cap.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.CustomLineCap

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [CustomLineCap(fill_path, stroke_path)](#CustomLineCap_fill_path_stroke_path_1) | Belirtilen ana hat ve dolgu ile [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) sınıfının yeni bir örneğini başlatır. |
| [CustomLineCap(fill_path, stroke_path, base_cap)](#CustomLineCap_fill_path_stroke_path_base_cap_2) | Belirtilen mevcut [LineCap](/psd/python-net/aspose.psd/linecap/) enum'undan, belirtilen ana hat ve dolgu ile [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) sınıfının yeni bir örneğini başlatır. |
| [CustomLineCap(fill_path, stroke_path, base_cap, base_inset)](#CustomLineCap_fill_path_stroke_path_base_cap_base_inset_3) | Belirtilen mevcut [LineCap](/psd/python-net/aspose.psd/linecap/) enum'undan, belirtilen ana hat, dolgu ve iç boşluk ile [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) sınıfının yeni bir örneğini başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| base_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | r/w | Bu [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) temel aldığı [LineCap](/psd/python-net/aspose.psd/linecap/) enum'ını alır veya ayarlar. |
| base_inset | float | r/w | Kap ile çizgi arasındaki mesafeyi alır veya ayarlar. |
| fill_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | r/w | Özel kap için dolguyu tanımlayan nesneyi alır veya ayarlar. |
| stroke_join | [LineJoin](/psd/python-net/aspose.psd/linejoin) | r/w | Bu [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) nesnesini oluşturan çizgilerin nasıl birleştirileceğini belirleyen [LineJoin](/psd/python-net/aspose.psd/linejoin/) enum'ını alır veya ayarlar. |
| stroke_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | r/w | Özel kapağın ana hatını tanımlayan nesneyi alır veya ayarlar. |
| width_scale | float | r/w | Bu [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) Sınıf nesnesini, nesnenin genişliğine göre ölçeklendirme miktarını alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [get_stroke_caps(start_cap, end_cap)](#get_stroke_caps_start_cap_end_cap_1) | Bu özel kapağı oluşturan çizgilerin başlangıç ve bitişinde kullanılan kapları alır. |
| [set_stroke_caps(start_cap, end_cap)](#set_stroke_caps_start_cap_end_cap_2) | Bu özel kapağı oluşturan çizgilerin başlangıç ve bitişinde kullanılan kapları ayarlar. |


### Constructor: CustomLineCap(fill_path, stroke_path) {#CustomLineCap_fill_path_stroke_path_1}


```
 CustomLineCap(fill_path, stroke_path) 
```

Belirtilen ana hat ve dolgu ile [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| fill_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Özel kap için dolguyu tanımlayan bir [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) nesnesi. |
| stroke_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Özel kapağın ana hatını tanımlayan bir [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) nesnesi. |

### Constructor: CustomLineCap(fill_path, stroke_path, base_cap) {#CustomLineCap_fill_path_stroke_path_base_cap_2}


```
 CustomLineCap(fill_path, stroke_path, base_cap) 
```

Belirtilen mevcut [LineCap](/psd/python-net/aspose.psd/linecap/) enum'undan, belirtilen ana hat ve dolgu ile [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| fill_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Özel kap için dolguyu tanımlayan bir [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) nesnesi. |
| stroke_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Özel kapağın ana hatını tanımlayan bir [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) nesnesi. |
| base_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | Özel kap oluşturulacak çizgi kapağı. |

### Constructor: CustomLineCap(fill_path, stroke_path, base_cap, base_inset) {#CustomLineCap_fill_path_stroke_path_base_cap_base_inset_3}


```
 CustomLineCap(fill_path, stroke_path, base_cap, base_inset) 
```

Belirtilen mevcut [LineCap](/psd/python-net/aspose.psd/linecap/) enum'undan, belirtilen ana hat, dolgu ve iç boşluk ile [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| fill_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Özel kap için dolguyu tanımlayan bir [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) nesnesi. |
| stroke_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Özel kapağın ana hatını tanımlayan bir [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) nesnesi. |
| base_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | Özel kap oluşturulacak çizgi kapağı. |
| base_inset | float | Kap ile çizgi arasındaki mesafe. |

### Method: get_stroke_caps(start_cap, end_cap) {#get_stroke_caps_start_cap_end_cap_1}


```
 get_stroke_caps(start_cap, end_cap) 
```

Bu özel kapağı oluşturan çizgilerin başlangıç ve bitişinde kullanılan kapları alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| start_cap | [LineCap[]](/psd/python-net/aspose.psd/linecap) | Bu kap içinde bir çizginin başlangıcında kullanılan [LineCap](/psd/python-net/aspose.psd/linecap/) enum'ı. |
| end_cap | [LineCap[]](/psd/python-net/aspose.psd/linecap) | Bu kap içinde bir çizginin sonunda kullanılan [LineCap](/psd/python-net/aspose.psd/linecap/) enum'ı. |

### Method: set_stroke_caps(start_cap, end_cap) {#set_stroke_caps_start_cap_end_cap_2}


```
 set_stroke_caps(start_cap, end_cap) 
```

Bu özel kapağı oluşturan çizgilerin başlangıç ve bitişinde kullanılan kapları ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| start_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | Bu kap içinde bir çizginin başlangıcında kullanılan [LineCap](/psd/python-net/aspose.psd/linecap/) enum'ı. |
| end_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | Bu kap içinde bir çizginin sonunda kullanılan [LineCap](/psd/python-net/aspose.psd/linecap/) enum'ı. |

