---
title: "MultiPageOptions 클래스"
type: docs
weight: 70
url: /ko/python-net/aspose.psd.imageoptions/multipageoptions/
---

**Summary:** Base class for multiple pages supported formats

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.MultiPageOptions

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [MultiPageOptions()](#MultiPageOptions__1) | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) 클래스의 새 인스턴스를 초기화합니다. |
| [MultiPageOptions(page)](#MultiPageOptions_page_2) | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) 클래스의 새 인스턴스를 초기화합니다. |
| [MultiPageOptions(page, export_area)](#MultiPageOptions_page_export_area_3) | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) 클래스의 새 인스턴스를 초기화합니다. |
| [MultiPageOptions(page_titles)](#MultiPageOptions_page_titles_4) | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) 클래스의 새 인스턴스를 초기화합니다. |
| [MultiPageOptions(page_titles, export_area)](#MultiPageOptions_page_titles_export_area_5) | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) 클래스의 새 인스턴스를 초기화합니다. |
| [MultiPageOptions(pages)](#MultiPageOptions_pages_6) | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) 클래스의 새 인스턴스를 초기화합니다. |
| [MultiPageOptions(pages, export_area)](#MultiPageOptions_pages_export_area_7) | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) 클래스의 새 인스턴스를 초기화합니다. |
| [MultiPageOptions(range)](#MultiPageOptions_range_8) | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) 클래스의 새 인스턴스를 초기화합니다. |
| [MultiPageOptions(range, export_area)](#MultiPageOptions_range_export_area_9) | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) 클래스의 새 인스턴스를 초기화합니다. |
| [MultiPageOptions(ranges)](#MultiPageOptions_ranges_10) | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) 클래스의 새 인스턴스를 초기화합니다. |
| [MultiPageOptions(ranges, export_area)](#MultiPageOptions_ranges_export_area_11) | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) 클래스의 새 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | 내보내기 영역을 가져오거나 설정합니다. |
| merge_layers | bool | r/w | 값을 가져오거나 설정합니다. [merege layers]인지 여부를 나타냅니다. |
| mode | [MultiPageMode](/psd/python-net/aspose.psd.imageoptions/multipagemode) | r/w | 모드를 가져오거나 설정합니다. |
| output_layers_names | 문자열 | r/w | 출력 레이어 이름을 가져오거나 설정합니다(내보내기 형식이 레이어 명명을 지원하는 경우에 작동합니다, 예를 들어 Psd). |
| page_rasterization_options | [VectorRasterizationOptions[]](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | 페이지 래스터화 옵션을 가져오거나 설정합니다. |
| page_titles | 문자열 | r/w | 페이지 제목을 가져오거나 설정합니다. |
| pages | int | r/w | 페이지를 가져오거나 설정합니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [init_pages(ranges)](#init_pages_ranges_1) | 범위 배열에서 페이지를 초기화합니다. |


### Constructor: MultiPageOptions() {#MultiPageOptions__1}


```
 MultiPageOptions() 
```

[MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) 클래스의 새 인스턴스를 초기화합니다.

### Constructor: MultiPageOptions(page) {#MultiPageOptions_page_2}


```
 MultiPageOptions(page) 
```

[MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| page | int |  |

### Constructor: MultiPageOptions(page, export_area) {#MultiPageOptions_page_export_area_3}


```
 MultiPageOptions(page, export_area) 
```

[MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| page | int |  |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 내보내기 영역입니다. |

### Constructor: MultiPageOptions(page_titles) {#MultiPageOptions_page_titles_4}


```
 MultiPageOptions(page_titles) 
```

[MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| page_titles | 문자열 | 페이지 제목입니다. |

### Constructor: MultiPageOptions(page_titles, export_area) {#MultiPageOptions_page_titles_export_area_5}


```
 MultiPageOptions(page_titles, export_area) 
```

[MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| page_titles | 문자열 | 페이지 제목입니다. |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 내보내기 영역입니다. |

### Constructor: MultiPageOptions(pages) {#MultiPageOptions_pages_6}


```
 MultiPageOptions(pages) 
```

[MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pages | int | 페이지입니다. |

### Constructor: MultiPageOptions(pages, export_area) {#MultiPageOptions_pages_export_area_7}


```
 MultiPageOptions(pages, export_area) 
```

[MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| pages | int | 페이지 배열입니다. |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 내보내기 영역입니다. |

### Constructor: MultiPageOptions(range) {#MultiPageOptions_range_8}


```
 MultiPageOptions(range) 
```

[MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| range | [IntRange](/psd/python-net/aspose.psd/intrange) |  |

### Constructor: MultiPageOptions(range, export_area) {#MultiPageOptions_range_export_area_9}


```
 MultiPageOptions(range, export_area) 
```

[MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| range | [IntRange](/psd/python-net/aspose.psd/intrange) |  |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 내보내기 영역입니다. |

### Constructor: MultiPageOptions(ranges) {#MultiPageOptions_ranges_10}


```
 MultiPageOptions(ranges) 
```

[MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| ranges | [IntRange[]](/psd/python-net/aspose.psd/intrange) | 다음 [IntRange](/psd/python-net/aspose.psd/intrange/). |

### Constructor: MultiPageOptions(ranges, export_area) {#MultiPageOptions_ranges_export_area_11}


```
 MultiPageOptions(ranges, export_area) 
```

[MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| ranges | [IntRange[]](/psd/python-net/aspose.psd/intrange) | 다음 [IntRange](/psd/python-net/aspose.psd/intrange/). |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 내보내기 영역입니다. |

### Method: init_pages(ranges) {#init_pages_ranges_1}


```
 init_pages(ranges) 
```

범위 배열에서 페이지를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| ranges | [IntRange[]](/psd/python-net/aspose.psd/intrange) | 범위입니다. |

