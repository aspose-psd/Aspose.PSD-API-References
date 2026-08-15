---
title: "Region 클래스"
type: docs
weight: 3870
url: /ko/python-net/aspose.psd/region/
---

**Summary:** Describes the interior of a graphics shape composed of rectangles and paths. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Region

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [Region()](#Region__1) | 새로운 [Region](/psd/python-net/aspose.psd/region/)을 초기화합니다. |
| [Region(path)](#Region_path_2) | 지정된 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)를 사용하여 새로운 [Region](/psd/python-net/aspose.psd/region/)을 초기화합니다. |
| [Region(rect)](#Region_rect_3) | 지정된 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조에서 새로운 [Region](/psd/python-net/aspose.psd/region/)을 초기화합니다. |
| [Region(rect)](#Region_rect_4) | 지정된 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조에서 새로운 [Region](/psd/python-net/aspose.psd/region/)을 초기화합니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [complement(path)](#complement_path_1) | 이 [Region](/psd/python-net/aspose.psd/region/)을 업데이트하여 지정된 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 중 이 [Region](/psd/python-net/aspose.psd/region/)과 교차하지 않는 부분을 포함하도록 합니다. |
| [complement(rect)](#complement_rect_2) | 이 [Region](/psd/python-net/aspose.psd/region/)을 업데이트하여 지정된 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조 중 이 [Region](/psd/python-net/aspose.psd/region/)과 교차하지 않는 부분을 포함하도록 합니다. |
| [complement(rect)](#complement_rect_3) | 이 [Region](/psd/python-net/aspose.psd/region/)을 업데이트하여 지정된 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조 중 이 [Region](/psd/python-net/aspose.psd/region/)과 교차하지 않는 부분을 포함하도록 합니다. |
| [complement(region)](#complement_region_4) | 이 [Region](/psd/python-net/aspose.psd/region/)을 업데이트하여 지정된 [Region](/psd/python-net/aspose.psd/region/) 중 이 [Region](/psd/python-net/aspose.psd/region/)과 교차하지 않는 부분을 포함하도록 합니다. |
| [deep_clone()](#deep_clone__5) | 이 [Region](/psd/python-net/aspose.psd/region/)의 정확한 깊은 복사본을 생성합니다. |
| [exclude(path)](#exclude_path_6) | 이 [Region](/psd/python-net/aspose.psd/region/)을 업데이트하여 지정된 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)와 교차하지 않는 내부의 부분만 포함하도록 합니다. |
| [exclude(rect)](#exclude_rect_7) | 이 [Region](/psd/python-net/aspose.psd/region/)을 업데이트하여 지정된 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조와 교차하지 않는 내부의 부분만 포함하도록 합니다. |
| [exclude(rect)](#exclude_rect_8) | 이 [Region](/psd/python-net/aspose.psd/region/)을 업데이트하여 지정된 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조와 교차하지 않는 내부의 부분만 포함하도록 합니다. |
| [exclude(region)](#exclude_region_9) | 이 [Region](/psd/python-net/aspose.psd/region/)을 업데이트하여 지정된 [Region](/psd/python-net/aspose.psd/region/)와 교차하지 않는 내부의 부분만 포함하도록 합니다. |
| [intersect(path)](#intersect_path_10) | 이 [Region](/psd/python-net/aspose.psd/region/)을 지정된 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)와의 교차 영역으로 업데이트합니다. |
| [intersect(rect)](#intersect_rect_11) | 이 [Region](/psd/python-net/aspose.psd/region/)을 지정된 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조와의 교차 영역으로 업데이트합니다. |
| [intersect(rect)](#intersect_rect_12) | 이 [Region](/psd/python-net/aspose.psd/region/)을 지정된 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조와의 교차 영역으로 업데이트합니다. |
| [intersect(region)](#intersect_region_13) | 이 [Region](/psd/python-net/aspose.psd/region/)을 지정된 [Region](/psd/python-net/aspose.psd/region/)와의 교차 영역으로 업데이트합니다. |
| [is_empty(g)](#is_empty_g_14) | 지정된 그리기 표면에서 이 [Region](/psd/python-net/aspose.psd/region/)이 빈 내부를 가지고 있는지 테스트합니다. |
| [is_infinite(g)](#is_infinite_g_15) | 지정된 그리기 표면에서 이 [Region](/psd/python-net/aspose.psd/region/)이 무한한 내부를 가지고 있는지 테스트합니다. |
| [is_visible(point)](#is_visible_point_16) | 지정된 [PointF](/psd/python-net/aspose.psd/pointf/) 구조가 이 [Region](/psd/python-net/aspose.psd/region/)에 포함되는지 테스트합니다. |
| [is_visible(point)](#is_visible_point_17) | 지정된 [PointF](/psd/python-net/aspose.psd/pointf/) 구조가 이 [Region](/psd/python-net/aspose.psd/region/)에 포함되는지 테스트합니다. |
| [is_visible(point, g)](#is_visible_point_g_18) | 지정된 [Graphics](/psd/python-net/aspose.psd/graphics/)를 사용하여 그릴 때 지정된 [PointF](/psd/python-net/aspose.psd/pointf/) 구조가 이 [Region](/psd/python-net/aspose.psd/region/)에 포함되는지 테스트합니다. |
| [is_visible(point, g)](#is_visible_point_g_19) | 지정된 [Graphics](/psd/python-net/aspose.psd/graphics/)를 사용하여 그릴 때 지정된 [PointF](/psd/python-net/aspose.psd/pointf/) 구조가 이 [Region](/psd/python-net/aspose.psd/region/)에 포함되는지 테스트합니다. |
| [is_visible(rect)](#is_visible_rect_20) | 지정된 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조의 일부가 이 [Region](/psd/python-net/aspose.psd/region/)에 포함되는지 테스트합니다. |
| [is_visible(rect)](#is_visible_rect_21) | 지정된 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조의 일부가 이 [Region](/psd/python-net/aspose.psd/region/)에 포함되는지 테스트합니다. |
| [is_visible(rect, g)](#is_visible_rect_g_22) | 지정된 [Graphics](/psd/python-net/aspose.psd/graphics/)를 사용하여 그릴 때 지정된 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조의 일부가 이 [Region](/psd/python-net/aspose.psd/region/)에 포함되는지 테스트합니다. |
| [is_visible(rect, g)](#is_visible_rect_g_23) | 지정된 [Graphics](/psd/python-net/aspose.psd/graphics/)를 사용하여 그릴 때 지정된 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조의 일부가 이 [Region](/psd/python-net/aspose.psd/region/)에 포함되는지 테스트합니다. |
| [is_visible(x, y)](#is_visible_x_y_24) | 지정된 점이 이 [Region](/psd/python-net/aspose.psd/region/)에 포함되는지 테스트합니다. |
| [is_visible(x, y, g)](#is_visible_x_y_g_25) | 지정된 [Graphics](/psd/python-net/aspose.psd/graphics/)를 사용하여 그릴 때 지정된 점이 이 [Region](/psd/python-net/aspose.psd/region/)에 포함되는지 테스트합니다. |
| [is_visible(x, y, g)](#is_visible_x_y_g_26) | 지정된 [Graphics](/psd/python-net/aspose.psd/graphics/)를 사용하여 그릴 때 지정된 점이 이 [Region](/psd/python-net/aspose.psd/region/)에 포함되는지 테스트합니다. |
| [is_visible(x, y, width, height)](#is_visible_x_y_width_height_27) | 지정된 사각형의 일부가 이 [Region](/psd/python-net/aspose.psd/region/) 안에 포함되는지 테스트합니다. |
| [is_visible(x, y, width, height)](#is_visible_x_y_width_height_28) | 지정된 사각형의 일부가 이 [Region](/psd/python-net/aspose.psd/region/) 안에 포함되는지 테스트합니다. |
| [is_visible(x, y, width, height, g)](#is_visible_x_y_width_height_g_29) | 지정된 [Graphics](/psd/python-net/aspose.psd/graphics/)를 사용하여 그릴 때, 지정된 사각형의 일부가 이 [Region](/psd/python-net/aspose.psd/region/) 안에 포함되는지 테스트합니다. |
| [is_visible(x, y, width, height, g)](#is_visible_x_y_width_height_g_30) | 지정된 [Graphics](/psd/python-net/aspose.psd/graphics/)를 사용하여 그릴 때, 지정된 사각형의 일부가 이 [Region](/psd/python-net/aspose.psd/region/) 안에 포함되는지 테스트합니다. |
| make_empty() | 이 [Region](/psd/python-net/aspose.psd/region/)을 빈 내부로 초기화합니다. |
| make_infinite() | 이 [Region](/psd/python-net/aspose.psd/region/) 객체를 무한한 내부로 초기화합니다. |
| [transform(matrix)](#transform_matrix_31) | 지정된 [Matrix](/psd/python-net/aspose.psd/matrix/)를 사용하여 이 [Region](/psd/python-net/aspose.psd/region/)을 변환합니다. |
| [translate(dx, dy)](#translate_dx_dy_32) | 지정된 양만큼 이 [Region](/psd/python-net/aspose.psd/region/)의 좌표를 오프셋합니다. |
| [translate(dx, dy)](#translate_dx_dy_33) | 지정된 양만큼 이 [Region](/psd/python-net/aspose.psd/region/)의 좌표를 오프셋합니다. |
| [union(path)](#union_path_34) | 이 [Region](/psd/python-net/aspose.psd/region/)을 자체와 지정된 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)의 합집합으로 업데이트합니다. |
| [union(rect)](#union_rect_35) | 이 [Region](/psd/python-net/aspose.psd/region/)을 자체와 지정된 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조의 합집합으로 업데이트합니다. |
| [union(rect)](#union_rect_36) | 이 [Region](/psd/python-net/aspose.psd/region/)을 자체와 지정된 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조의 합집합으로 업데이트합니다. |
| [union(region)](#union_region_37) | 이 [Region](/psd/python-net/aspose.psd/region/)을 자체와 지정된 [Region](/psd/python-net/aspose.psd/region/)의 합집합으로 업데이트합니다. |
| [xor(path)](#xor_path_38) | 이 [Region](/psd/python-net/aspose.psd/region/)을 자체와 지정된 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)의 교집합을 제외한 합집합으로 업데이트합니다. |
| [xor(rect)](#xor_rect_39) | 이 [Region](/psd/python-net/aspose.psd/region/)을 자체와 지정된 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조의 교집합을 제외한 합집합으로 업데이트합니다. |
| [xor(rect)](#xor_rect_40) | 이 [Region](/psd/python-net/aspose.psd/region/)을 자체와 지정된 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조의 교집합을 제외한 합집합으로 업데이트합니다. |
| [xor(region)](#xor_region_41) | 이 [Region](/psd/python-net/aspose.psd/region/)을 자체와 지정된 [Region](/psd/python-net/aspose.psd/region/)의 교집합을 제외한 합집합으로 업데이트합니다. |


### Constructor: Region() {#Region__1}


```
 Region() 
```

새로운 [Region](/psd/python-net/aspose.psd/region/)을 초기화합니다.

### Constructor: Region(path) {#Region_path_2}


```
 Region(path) 
```

지정된 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)를 사용하여 새로운 [Region](/psd/python-net/aspose.psd/region/)을 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | 새로운 [Region](/psd/python-net/aspose.psd/region/)을 정의하는 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)입니다. |

### Constructor: Region(rect) {#Region_rect_3}


```
 Region(rect) 
```

지정된 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조에서 새로운 [Region](/psd/python-net/aspose.psd/region/)을 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 새로운 [Region](/psd/python-net/aspose.psd/region/)의 내부를 정의하는 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조입니다. |

### Constructor: Region(rect) {#Region_rect_4}


```
 Region(rect) 
```

지정된 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조에서 새로운 [Region](/psd/python-net/aspose.psd/region/)을 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 새로운 [Region](/psd/python-net/aspose.psd/region/)의 내부를 정의하는 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조입니다. |

### Method: complement(path) {#complement_path_1}


```
 complement(path) 
```

이 [Region](/psd/python-net/aspose.psd/region/)을 업데이트하여 지정된 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) 중 이 [Region](/psd/python-net/aspose.psd/region/)과 교차하지 않는 부분을 포함하도록 합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | 이 [Region](/psd/python-net/aspose.psd/region/)을 보완하는 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)입니다. |

### Method: complement(rect) {#complement_rect_2}


```
 complement(rect) 
```

이 [Region](/psd/python-net/aspose.psd/region/)을 업데이트하여 지정된 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조 중 이 [Region](/psd/python-net/aspose.psd/region/)과 교차하지 않는 부분을 포함하도록 합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 이 [Region](/psd/python-net/aspose.psd/region/)을 보완하는 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조입니다. |

### Method: complement(rect) {#complement_rect_3}


```
 complement(rect) 
```

이 [Region](/psd/python-net/aspose.psd/region/)을 업데이트하여 지정된 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조 중 이 [Region](/psd/python-net/aspose.psd/region/)과 교차하지 않는 부분을 포함하도록 합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 이 [Region](/psd/python-net/aspose.psd/region/)을 보완하는 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조입니다. |

### Method: complement(region) {#complement_region_4}


```
 complement(region) 
```

이 [Region](/psd/python-net/aspose.psd/region/)을 업데이트하여 지정된 [Region](/psd/python-net/aspose.psd/region/) 중 이 [Region](/psd/python-net/aspose.psd/region/)과 교차하지 않는 부분을 포함하도록 합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | 이 [Region](/psd/python-net/aspose.psd/region/) 객체를 보완하는 [Region](/psd/python-net/aspose.psd/region/) 객체입니다. |

### Method: deep_clone() {#deep_clone__5}


```
 deep_clone() 
```

이 [Region](/psd/python-net/aspose.psd/region/)의 정확한 깊은 복사본을 생성합니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| [Region](/psd/python-net/aspose.psd/region) | 이 메서드가 생성하는 [Region](/psd/python-net/aspose.psd/region/)입니다. |


### Method: exclude(path) {#exclude_path_6}


```
 exclude(path) 
```

이 [Region](/psd/python-net/aspose.psd/region/)을 업데이트하여 지정된 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)와 교차하지 않는 내부의 부분만 포함하도록 합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | 이 [Region](/psd/python-net/aspose.psd/region/)에서 제외할 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)입니다. |

### Method: exclude(rect) {#exclude_rect_7}


```
 exclude(rect) 
```

이 [Region](/psd/python-net/aspose.psd/region/)을 업데이트하여 지정된 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조와 교차하지 않는 내부의 부분만 포함하도록 합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 이 [Region](/psd/python-net/aspose.psd/region/)에서 제외할 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조입니다. |

### Method: exclude(rect) {#exclude_rect_8}


```
 exclude(rect) 
```

이 [Region](/psd/python-net/aspose.psd/region/)을 업데이트하여 지정된 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조와 교차하지 않는 내부의 부분만 포함하도록 합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 이 [Region](/psd/python-net/aspose.psd/region/)에서 제외할 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조입니다. |

### Method: exclude(region) {#exclude_region_9}


```
 exclude(region) 
```

이 [Region](/psd/python-net/aspose.psd/region/)을 업데이트하여 지정된 [Region](/psd/python-net/aspose.psd/region/)와 교차하지 않는 내부의 부분만 포함하도록 합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | 이 [Region](/psd/python-net/aspose.psd/region/)에서 제외할 [Region](/psd/python-net/aspose.psd/region/)입니다. |

### Method: intersect(path) {#intersect_path_10}


```
 intersect(path) 
```

이 [Region](/psd/python-net/aspose.psd/region/)을 지정된 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)와의 교차 영역으로 업데이트합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | 이 [Region](/psd/python-net/aspose.psd/region/)와 교차할 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)입니다. |

### Method: intersect(rect) {#intersect_rect_11}


```
 intersect(rect) 
```

이 [Region](/psd/python-net/aspose.psd/region/)을 지정된 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조와의 교차 영역으로 업데이트합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 이 [Region](/psd/python-net/aspose.psd/region/)와 교차할 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조입니다. |

### Method: intersect(rect) {#intersect_rect_12}


```
 intersect(rect) 
```

이 [Region](/psd/python-net/aspose.psd/region/)을 지정된 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조와의 교차 영역으로 업데이트합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 이 [Region](/psd/python-net/aspose.psd/region/)와 교차할 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조입니다. |

### Method: intersect(region) {#intersect_region_13}


```
 intersect(region) 
```

이 [Region](/psd/python-net/aspose.psd/region/)을 지정된 [Region](/psd/python-net/aspose.psd/region/)와의 교차 영역으로 업데이트합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | 이 [Region](/psd/python-net/aspose.psd/region/)와 교차할 [Region](/psd/python-net/aspose.psd/region/)입니다. |

### Method: is_empty(g) {#is_empty_g_14}


```
 is_empty(g) 
```

지정된 그리기 표면에서 이 [Region](/psd/python-net/aspose.psd/region/)이 빈 내부를 가지고 있는지 테스트합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | 그리기 표면을 나타내는 [Graphics](/psd/python-net/aspose.psd/graphics/)입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | 변환 <paramref name="g" />이 적용될 때 이 [Region](/psd/python-net/aspose.psd/region/)의 내부가 비어 있으면 true; 그렇지 않으면 false. |


### Method: is_infinite(g) {#is_infinite_g_15}


```
 is_infinite(g) 
```

지정된 그리기 표면에서 이 [Region](/psd/python-net/aspose.psd/region/)이 무한한 내부를 가지고 있는지 테스트합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | 그리기 표면을 나타내는 [Graphics](/psd/python-net/aspose.psd/graphics/)입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | 변환 <paramref name="g" />이 적용될 때 이 [Region](/psd/python-net/aspose.psd/region/)의 내부가 무한하면 true; 그렇지 않으면 false. |


### Method: is_visible(point) {#is_visible_point_16}


```
 is_visible(point) 
```

지정된 [PointF](/psd/python-net/aspose.psd/pointf/) 구조가 이 [Region](/psd/python-net/aspose.psd/region/)에 포함되는지 테스트합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | 테스트할 [PointF](/psd/python-net/aspose.psd/pointf/) 구조체. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | <paramref name="point" />이 이 [Region](/psd/python-net/aspose.psd/region/)에 포함되면 true; 그렇지 않으면 false. |


### Method: is_visible(point) {#is_visible_point_17}


```
 is_visible(point) 
```

지정된 [PointF](/psd/python-net/aspose.psd/pointf/) 구조가 이 [Region](/psd/python-net/aspose.psd/region/)에 포함되는지 테스트합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | 테스트할 [PointF](/psd/python-net/aspose.psd/pointf/) 구조체. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | <paramref name="point" />이 이 [Region](/psd/python-net/aspose.psd/region/)에 포함되면 true; 그렇지 않으면 false. |


### Method: is_visible(point, g) {#is_visible_point_g_18}


```
 is_visible(point, g) 
```

지정된 [Graphics](/psd/python-net/aspose.psd/graphics/)를 사용하여 그릴 때 지정된 [PointF](/psd/python-net/aspose.psd/pointf/) 구조가 이 [Region](/psd/python-net/aspose.psd/region/)에 포함되는지 테스트합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | 테스트할 [PointF](/psd/python-net/aspose.psd/pointf/) 구조체. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | 그래픽 컨텍스트를 나타내는 [Graphics](/psd/python-net/aspose.psd/graphics/) 객체. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | <paramref name="point" />이 이 [Region](/psd/python-net/aspose.psd/region/)에 포함되면 true; 그렇지 않으면 false. |


### Method: is_visible(point, g) {#is_visible_point_g_19}


```
 is_visible(point, g) 
```

지정된 [Graphics](/psd/python-net/aspose.psd/graphics/)를 사용하여 그릴 때 지정된 [PointF](/psd/python-net/aspose.psd/pointf/) 구조가 이 [Region](/psd/python-net/aspose.psd/region/)에 포함되는지 테스트합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | 테스트할 [PointF](/psd/python-net/aspose.psd/pointf/) 구조체. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | 그래픽 컨텍스트를 나타내는 [Graphics](/psd/python-net/aspose.psd/graphics/) 객체. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | <paramref name="point" />이 이 [Region](/psd/python-net/aspose.psd/region/)에 포함되면 true; 그렇지 않으면 false. |


### Method: is_visible(rect) {#is_visible_rect_20}


```
 is_visible(rect) 
```

지정된 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조의 일부가 이 [Region](/psd/python-net/aspose.psd/region/)에 포함되는지 테스트합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 테스트할 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조체. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | <paramref name="rect" />의 일부라도 이 [Region](/psd/python-net/aspose.psd/region/)에 포함되면 true; 그렇지 않으면 false. |


### Method: is_visible(rect) {#is_visible_rect_21}


```
 is_visible(rect) 
```

지정된 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조의 일부가 이 [Region](/psd/python-net/aspose.psd/region/)에 포함되는지 테스트합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 테스트할 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조체. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | <paramref name="rect" />의 일부라도 이 [Region](/psd/python-net/aspose.psd/region/)에 포함되면 true; 그렇지 않으면 false. |


### Method: is_visible(rect, g) {#is_visible_rect_g_22}


```
 is_visible(rect, g) 
```

지정된 [Graphics](/psd/python-net/aspose.psd/graphics/)를 사용하여 그릴 때 지정된 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조의 일부가 이 [Region](/psd/python-net/aspose.psd/region/)에 포함되는지 테스트합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 테스트할 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조체. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | 그래픽 컨텍스트를 나타내는 [Graphics](/psd/python-net/aspose.psd/graphics/) 객체. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | <paramref name="rect" />이 이 [Region](/psd/python-net/aspose.psd/region/)에 포함되면 true; 그렇지 않으면 false. |


### Method: is_visible(rect, g) {#is_visible_rect_g_23}


```
 is_visible(rect, g) 
```

지정된 [Graphics](/psd/python-net/aspose.psd/graphics/)를 사용하여 그릴 때 지정된 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조의 일부가 이 [Region](/psd/python-net/aspose.psd/region/)에 포함되는지 테스트합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 테스트할 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조체. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | 그래픽 컨텍스트를 나타내는 [Graphics](/psd/python-net/aspose.psd/graphics/) 객체. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | <paramref name="rect" />이 이 [Region](/psd/python-net/aspose.psd/region/)에 포함되면 true; 그렇지 않으면 false. |


### Method: is_visible(x, y) {#is_visible_x_y_24}


```
 is_visible(x, y) 
```

지정된 점이 이 [Region](/psd/python-net/aspose.psd/region/)에 포함되는지 테스트합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| x | float | 테스트할 점의 x 좌표입니다. |
| y | float | 테스트할 점의 y 좌표입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | True when 지정된 점이 이 [Region](/psd/python-net/aspose.psd/region/)에 포함되면 true; 그렇지 않으면 false. |


### Method: is_visible(x, y, g) {#is_visible_x_y_g_25}


```
 is_visible(x, y, g) 
```

지정된 [Graphics](/psd/python-net/aspose.psd/graphics/)를 사용하여 그릴 때 지정된 점이 이 [Region](/psd/python-net/aspose.psd/region/)에 포함되는지 테스트합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| x | float | 테스트할 점의 x 좌표입니다. |
| y | float | 테스트할 점의 y 좌표입니다. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | 그래픽 컨텍스트를 나타내는 [Graphics](/psd/python-net/aspose.psd/graphics/) 객체. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | True when 지정된 점이 이 [Region](/psd/python-net/aspose.psd/region/)에 포함되면 true; 그렇지 않으면 false. |


### Method: is_visible(x, y, g) {#is_visible_x_y_g_26}


```
 is_visible(x, y, g) 
```

지정된 [Graphics](/psd/python-net/aspose.psd/graphics/)를 사용하여 그릴 때 지정된 점이 이 [Region](/psd/python-net/aspose.psd/region/)에 포함되는지 테스트합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| x | int | 테스트할 점의 x 좌표입니다. |
| y | int | 테스트할 점의 y 좌표입니다. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | 그래픽 컨텍스트를 나타내는 [Graphics](/psd/python-net/aspose.psd/graphics/) 객체. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | True when 지정된 점이 이 [Region](/psd/python-net/aspose.psd/region/)에 포함되면 true; 그렇지 않으면 false. |


### Method: is_visible(x, y, width, height) {#is_visible_x_y_width_height_27}


```
 is_visible(x, y, width, height) 
```

지정된 사각형의 일부가 이 [Region](/psd/python-net/aspose.psd/region/) 안에 포함되는지 테스트합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| x | float | 테스트할 사각형의 왼쪽 위 모서리 x좌표. |
| y | float | 테스트할 사각형의 왼쪽 위 모서리 y좌표. |
| width | float | 테스트할 사각형의 너비. |
| 높이 | float | 테스트할 사각형의 높이. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | 지정된 사각형의 일부라도 이 [Region](/psd/python-net/aspose.psd/region/) 객체에 포함되면 true; 그렇지 않으면 false. |


### Method: is_visible(x, y, width, height) {#is_visible_x_y_width_height_28}


```
 is_visible(x, y, width, height) 
```

지정된 사각형의 일부가 이 [Region](/psd/python-net/aspose.psd/region/) 안에 포함되는지 테스트합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| x | int | 테스트할 사각형의 왼쪽 위 모서리 x좌표. |
| y | int | 테스트할 사각형의 왼쪽 위 모서리 y좌표. |
| width | int | 테스트할 사각형의 너비. |
| 높이 | int | 테스트할 사각형의 높이. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | 지정된 사각형의 일부라도 이 [Region](/psd/python-net/aspose.psd/region/) 객체에 포함되면 true; 그렇지 않으면 false. |


### Method: is_visible(x, y, width, height, g) {#is_visible_x_y_width_height_g_29}


```
 is_visible(x, y, width, height, g) 
```

지정된 [Graphics](/psd/python-net/aspose.psd/graphics/)를 사용하여 그릴 때, 지정된 사각형의 일부가 이 [Region](/psd/python-net/aspose.psd/region/) 안에 포함되는지 테스트합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| x | float | 테스트할 사각형의 왼쪽 위 모서리 x좌표. |
| y | float | 테스트할 사각형의 왼쪽 위 모서리 y좌표. |
| width | float | 테스트할 사각형의 너비. |
| 높이 | float | 테스트할 사각형의 높이. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | 그래픽 컨텍스트를 나타내는 [Graphics](/psd/python-net/aspose.psd/graphics/) 객체. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | 지정된 사각형의 일부라도 이 [Region](/psd/python-net/aspose.psd/region/)에 포함되면 true; 그렇지 않으면 false. |


### Method: is_visible(x, y, width, height, g) {#is_visible_x_y_width_height_g_30}


```
 is_visible(x, y, width, height, g) 
```

지정된 [Graphics](/psd/python-net/aspose.psd/graphics/)를 사용하여 그릴 때, 지정된 사각형의 일부가 이 [Region](/psd/python-net/aspose.psd/region/) 안에 포함되는지 테스트합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| x | int | 테스트할 사각형의 왼쪽 위 모서리 x좌표. |
| y | int | 테스트할 사각형의 왼쪽 위 모서리 y좌표. |
| width | int | 테스트할 사각형의 너비. |
| 높이 | int | 테스트할 사각형의 높이. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | 그래픽 컨텍스트를 나타내는 [Graphics](/psd/python-net/aspose.psd/graphics/) 객체. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | 지정된 사각형의 일부라도 이 [Region](/psd/python-net/aspose.psd/region/)에 포함되면 true; 그렇지 않으면 false. |


### Method: transform(matrix) {#transform_matrix_31}


```
 transform(matrix) 
```

지정된 [Matrix](/psd/python-net/aspose.psd/matrix/)를 사용하여 이 [Region](/psd/python-net/aspose.psd/region/)을 변환합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | 이 [Region](/psd/python-net/aspose.psd/region/)을 변환할 [Matrix](/psd/python-net/aspose.psd/matrix/). |

### Method: translate(dx, dy) {#translate_dx_dy_32}


```
 translate(dx, dy) 
```

지정된 양만큼 이 [Region](/psd/python-net/aspose.psd/region/)의 좌표를 오프셋합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| dx | float | 이 [Region](/psd/python-net/aspose.psd/region/)을 수평으로 오프셋할 양. |
| dy | float | 이 [Region](/psd/python-net/aspose.psd/region/)을 수직으로 오프셋할 양. |

### Method: translate(dx, dy) {#translate_dx_dy_33}


```
 translate(dx, dy) 
```

지정된 양만큼 이 [Region](/psd/python-net/aspose.psd/region/)의 좌표를 오프셋합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| dx | int | 이 [Region](/psd/python-net/aspose.psd/region/)을 수평으로 오프셋할 양. |
| dy | int | 이 [Region](/psd/python-net/aspose.psd/region/)을 수직으로 오프셋할 양. |

### Method: union(path) {#union_path_34}


```
 union(path) 
```

이 [Region](/psd/python-net/aspose.psd/region/)을 자체와 지정된 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)의 합집합으로 업데이트합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | 이 [Region](/psd/python-net/aspose.psd/region/)와 결합할 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |

### Method: union(rect) {#union_rect_35}


```
 union(rect) 
```

이 [Region](/psd/python-net/aspose.psd/region/)을 자체와 지정된 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조의 합집합으로 업데이트합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 이 [Region](/psd/python-net/aspose.psd/region/)와 결합할 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조체. |

### Method: union(rect) {#union_rect_36}


```
 union(rect) 
```

이 [Region](/psd/python-net/aspose.psd/region/)을 자체와 지정된 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조의 합집합으로 업데이트합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 이 [Region](/psd/python-net/aspose.psd/region/)와 결합할 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조체. |

### Method: union(region) {#union_region_37}


```
 union(region) 
```

이 [Region](/psd/python-net/aspose.psd/region/)을 자체와 지정된 [Region](/psd/python-net/aspose.psd/region/)의 합집합으로 업데이트합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | 이 [Region](/psd/python-net/aspose.psd/region/)와 결합할 [Region](/psd/python-net/aspose.psd/region/). |

### Method: xor(path) {#xor_path_38}


```
 xor(path) 
```

이 [Region](/psd/python-net/aspose.psd/region/)을 자체와 지정된 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/)의 교집합을 제외한 합집합으로 업데이트합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | 이 [Region](/psd/python-net/aspose.psd/region/)와 XOR 연산할 [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/). |

### Method: xor(rect) {#xor_rect_39}


```
 xor(rect) 
```

이 [Region](/psd/python-net/aspose.psd/region/)을 자체와 지정된 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조의 교집합을 제외한 합집합으로 업데이트합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 이 [Region](/psd/python-net/aspose.psd/region/)와 XOR 연산할 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조체. |

### Method: xor(rect) {#xor_rect_40}


```
 xor(rect) 
```

이 [Region](/psd/python-net/aspose.psd/region/)을 자체와 지정된 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조의 교집합을 제외한 합집합으로 업데이트합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 이 [Region](/psd/python-net/aspose.psd/region/)와 XOR 연산할 [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 구조체. |

### Method: xor(region) {#xor_region_41}


```
 xor(region) 
```

이 [Region](/psd/python-net/aspose.psd/region/)을 자체와 지정된 [Region](/psd/python-net/aspose.psd/region/)의 교집합을 제외한 합집합으로 업데이트합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | 이 [Region](/psd/python-net/aspose.psd/region/)와 XOR 연산할 [Region](/psd/python-net/aspose.psd/region/). |

