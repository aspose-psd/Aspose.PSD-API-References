---
title: "ImageAttributes 클래스"
type: docs
weight: 2180
url: /ko/python-net/aspose.psd/imageattributes/
---

**Summary:** An [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) object contains information about how bitmap and metafile colors are manipulated during rendering. An [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) object maintains several color-adjustment settings, including color-adjustment matrices, grayscale-adjustment matrices, gamma-correction values, color-map tables, and color-threshold values. During rendering, colors can be corrected, darkened, lightened, and removed. To apply such manipulations, initialize an [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) object and pass the path of that [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) object (along with the path of an [Image](/psd/python-net/aspose.psd/image/)) to the DrawImage method.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ImageAttributes

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [ImageAttributes()](#ImageAttributes__1) | ImageAttributes 클래스의 새 인스턴스를 초기화합니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| clear_brush_remap_table() | 이 [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) 객체의 브러시 색상 재매핑 테이블을 지웁니다. |
| clear_color_key() | 기본 카테고리의 색 키(투명도 범위)를 지웁니다. |
| [clear_color_key(type)](#clear_color_key_type_1) | 지정된 카테고리의 색 키(투명도 범위)를 지웁니다. |
| clear_color_matrix() | 기본 카테고리의 색 보정 매트릭스를 지웁니다. |
| [clear_color_matrix(type)](#clear_color_matrix_type_2) | 지정된 카테고리의 색 보정 매트릭스를 지웁니다. |
| clear_gamma() | 기본 카테고리의 감마 보정을 비활성화합니다. |
| [clear_gamma(type)](#clear_gamma_type_3) | 지정된 카테고리의 감마 보정을 비활성화합니다. |
| clear_no_op() | 기본 카테고리의 NoOp 설정을 지웁니다. |
| [clear_no_op(type)](#clear_no_op_type_4) | 지정된 카테고리의 NoOp 설정을 지웁니다. |
| clear_output_channel() | 기본 카테고리의 CMYK(시안-마젠타-옐로-블랙) 출력 채널 설정을 지웁니다. |
| [clear_output_channel(type)](#clear_output_channel_type_5) | 지정된 카테고리의 (시안-마젠타-옐로-블랙) 출력 채널 설정을 지웁니다. |
| clear_output_channel_color_profile() | 기본 카테고리의 출력 채널 색 프로필 설정을 지웁니다. |
| [clear_output_channel_color_profile(type)](#clear_output_channel_color_profile_type_6) | 지정된 카테고리의 출력 채널 색 프로필 설정을 지웁니다. |
| clear_remap_table() | 기본 카테고리의 색 재매핑 테이블을 지웁니다. |
| [clear_remap_table(type)](#clear_remap_table_type_7) | 지정된 카테고리의 색 재매핑 테이블을 지웁니다. |
| clear_threshold() | 기본 카테고리의 임계값을 지웁니다. |
| [clear_threshold(type)](#clear_threshold_type_8) | 지정된 카테고리의 임계값을 지웁니다. |
| [set_brush_remap_table(map)](#set_brush_remap_table_map_9) | 브러시 카테고리의 색 재매핑 테이블을 설정합니다. |
| [set_color_key(color_low, color_high)](#set_color_key_color_low_color_high_10) | 기본 카테고리에 대한 색상 키를 설정합니다. |
| [set_color_key(color_low, color_high, type)](#set_color_key_color_low_color_high_type_11) | 지정된 카테고리에 대한 색상 키(투명도 범위)를 설정합니다. |
| [set_color_matrices(new_color_matrix, gray_matrix)](#set_color_matrices_new_color_matrix_gray_matrix_12) | 기본 카테고리에 대한 색상 보정 행렬 및 그레이스케일 보정 행렬을 설정합니다. |
| [set_color_matrices(new_color_matrix, gray_matrix, flags)](#set_color_matrices_new_color_matrix_gray_matrix_flags_13) | 기본 카테고리에 대한 색상 보정 행렬 및 그레이스케일 보정 행렬을 설정합니다. |
| [set_color_matrices(new_color_matrix, gray_matrix, mode, type)](#set_color_matrices_new_color_matrix_gray_matrix_mode_type_14) | 지정된 카테고리에 대한 색상 보정 행렬 및 그레이스케일 보정 행렬을 설정합니다. |
| [set_color_matrix(new_color_matrix)](#set_color_matrix_new_color_matrix_15) | 기본 카테고리에 대한 색상 보정 행렬을 설정합니다. |
| [set_color_matrix(new_color_matrix, flags)](#set_color_matrix_new_color_matrix_flags_16) | 기본 카테고리에 대한 색상 보정 행렬을 설정합니다. |
| [set_color_matrix(new_color_matrix, mode, type)](#set_color_matrix_new_color_matrix_mode_type_17) | 지정된 카테고리에 대한 색상 보정 행렬을 설정합니다. |
| [set_gamma(gamma)](#set_gamma_gamma_18) | 기본 카테고리에 대한 감마 값을 설정합니다. |
| [set_gamma(gamma, type)](#set_gamma_gamma_type_19) | 지정된 카테고리에 대한 감마 값을 설정합니다. |
| set_no_op() | 기본 카테고리에 대한 색상 보정을 끕니다. |
| [set_no_op(type)](#set_no_op_type_20) | 지정된 카테고리에 대한 색상 보정을 끕니다. |
| [set_output_channel(flags)](#set_output_channel_flags_21) | 기본 카테고리에 대한 CMYK(시안-마젠타-옐로-블랙) 출력 채널을 설정합니다. |
| [set_output_channel(flags, type)](#set_output_channel_flags_type_22) | 지정된 카테고리에 대한 CMYK(시안-마젠타-옐로-블랙) 출력 채널을 설정합니다. |
| [set_output_channel_color_profile(color_profile_filename)](#set_output_channel_color_profile_color_profile_filename_23) | 기본 카테고리에 대한 출력 채널 색상 프로파일 파일을 설정합니다. |
| [set_output_channel_color_profile(color_profile_filename, type)](#set_output_channel_color_profile_color_profile_filename_type_24) | 지정된 카테고리에 대한 출력 채널 색상 프로파일 파일을 설정합니다. |
| [set_remap_table(map)](#set_remap_table_map_25) | 기본 카테고리에 대한 색상 재매핑 테이블을 설정합니다. |
| [set_remap_table(map, type)](#set_remap_table_map_type_26) | 지정된 카테고리에 대한 색상 재매핑 테이블을 설정합니다. |
| [set_threshold(threshold)](#set_threshold_threshold_27) | 기본 카테고리에 대한 임계값(투명도 범위)을 설정합니다. |
| [set_threshold(threshold, type)](#set_threshold_threshold_type_28) | 지정된 카테고리에 대한 임계값(투명도 범위)을 설정합니다. |
| [set_wrap_mode(mode)](#set_wrap_mode_mode_29) | 텍스처를 도형 전체 또는 도형 경계에 타일링하는 방식을 결정하는 랩 모드를 설정합니다. 텍스처가 채우려는 도형보다 작을 경우, 텍스처가 도형 전체에 타일링되어 채워집니다. |
| [set_wrap_mode(mode, color)](#set_wrap_mode_mode_color_30) | 텍스처를 도형 전체 또는 도형 경계에 타일링하는 방식을 결정하는 랩 모드와 색상을 설정합니다. 텍스처가 채우려는 도형보다 작을 경우, 텍스처가 도형 전체에 타일링되어 채워집니다. |
| [set_wrap_mode(mode, color, clamp)](#set_wrap_mode_mode_color_clamp_31) | 텍스처를 도형 전체 또는 도형 경계에 타일링하는 방식을 결정하는 랩 모드와 색상을 설정합니다. 텍스처가 채우려는 도형보다 작을 경우, 텍스처가 도형 전체에 타일링되어 채워집니다. |


### Constructor: ImageAttributes() {#ImageAttributes__1}


```
 ImageAttributes() 
```

ImageAttributes 클래스의 새 인스턴스를 초기화합니다.

### Method: clear_color_key(type) {#clear_color_key_type_1}


```
 clear_color_key(type) 
```

지정된 카테고리의 색 키(투명도 범위)를 지웁니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | 색상 키가 지워지는 카테고리를 지정하는 [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) 요소입니다. |

### Method: clear_color_matrix(type) {#clear_color_matrix_type_2}


```
 clear_color_matrix(type) 
```

지정된 카테고리의 색 보정 매트릭스를 지웁니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | 색상 보정 행렬이 지워지는 카테고리를 지정하는 [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) 요소입니다. |

### Method: clear_gamma(type) {#clear_gamma_type_3}


```
 clear_gamma(type) 
```

지정된 카테고리의 감마 보정을 비활성화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | 감마 보정이 비활성화되는 카테고리를 지정하는 [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) 요소입니다. |

### Method: clear_no_op(type) {#clear_no_op_type_4}


```
 clear_no_op(type) 
```

지정된 카테고리의 NoOp 설정을 지웁니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | NoOp 설정이 지워지는 카테고리를 지정하는 [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) 요소입니다. |

### Method: clear_output_channel(type) {#clear_output_channel_type_5}


```
 clear_output_channel(type) 
```

지정된 카테고리의 (시안-마젠타-옐로-블랙) 출력 채널 설정을 지웁니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | 출력 채널 설정이 지워지는 범주를 지정하는 [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) 요소입니다. |

### Method: clear_output_channel_color_profile(type) {#clear_output_channel_color_profile_type_6}


```
 clear_output_channel_color_profile(type) 
```

지정된 카테고리의 출력 채널 색 프로필 설정을 지웁니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | 출력 채널 프로파일 설정이 지워지는 범주를 지정하는 [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) 요소입니다. |

### Method: clear_remap_table(type) {#clear_remap_table_type_7}


```
 clear_remap_table(type) 
```

지정된 카테고리의 색 재매핑 테이블을 지웁니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | 재매핑 테이블이 지워지는 범주를 지정하는 [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) 요소입니다. |

### Method: clear_threshold(type) {#clear_threshold_type_8}


```
 clear_threshold(type) 
```

지정된 카테고리의 임계값을 지웁니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | 임계값이 지워지는 범주를 지정하는 [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) 요소입니다. |

### Method: set_brush_remap_table(map) {#set_brush_remap_table_map_9}


```
 set_brush_remap_table(map) 
```

브러시 카테고리의 색 재매핑 테이블을 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| map | [ColorMap[]](/psd/python-net/aspose.psd/colormap) | [ColorMap](/psd/python-net/aspose.psd/colormap/) 객체들의 배열입니다. |

### Method: set_color_key(color_low, color_high) {#set_color_key_color_low_color_high_10}


```
 set_color_key(color_low, color_high) 
```

기본 카테고리에 대한 색상 키를 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| color_low | [Color](/psd/python-net/aspose.psd/color) | 낮은 색키 값입니다. |
| color_high | [Color](/psd/python-net/aspose.psd/color) | 높은 색키 값입니다. |

### Method: set_color_key(color_low, color_high, type) {#set_color_key_color_low_color_high_type_11}


```
 set_color_key(color_low, color_high, type) 
```

지정된 카테고리에 대한 색상 키(투명도 범위)를 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| color_low | [Color](/psd/python-net/aspose.psd/color) | 낮은 색키 값입니다. |
| color_high | [Color](/psd/python-net/aspose.psd/color) | 높은 색키 값입니다. |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | 색키가 설정되는 범주를 지정하는 [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) 요소입니다. |

### Method: set_color_matrices(new_color_matrix, gray_matrix) {#set_color_matrices_new_color_matrix_gray_matrix_12}


```
 set_color_matrices(new_color_matrix, gray_matrix) 
```

기본 카테고리에 대한 색상 보정 행렬 및 그레이스케일 보정 행렬을 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | 색상 보정 행렬입니다. |
| gray_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | 그레이스케일 보정 행렬입니다. |

### Method: set_color_matrices(new_color_matrix, gray_matrix, flags) {#set_color_matrices_new_color_matrix_gray_matrix_flags_13}


```
 set_color_matrices(new_color_matrix, gray_matrix, flags) 
```

기본 카테고리에 대한 색상 보정 행렬 및 그레이스케일 보정 행렬을 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | 색상 보정 행렬입니다. |
| gray_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | 그레이스케일 보정 행렬입니다. |
| flags | [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag) | 색상 보정 및 그레이스케일 보정 행렬의 영향을 받는 이미지 및 색상의 유형을 지정하는 [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag/) 요소입니다. |

### Method: set_color_matrices(new_color_matrix, gray_matrix, mode, type) {#set_color_matrices_new_color_matrix_gray_matrix_mode_type_14}


```
 set_color_matrices(new_color_matrix, gray_matrix, mode, type) 
```

지정된 카테고리에 대한 색상 보정 행렬 및 그레이스케일 보정 행렬을 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | 색상 보정 행렬입니다. |
| gray_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | 그레이스케일 보정 행렬입니다. |
| mode | [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag) | 색상 보정 및 그레이스케일 보정 행렬의 영향을 받는 이미지 및 색상의 유형을 지정하는 [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag/) 요소입니다. |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | 색상 보정 및 그레이스케일 보정 행렬이 설정되는 범주를 지정하는 [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) 요소입니다. |

### Method: set_color_matrix(new_color_matrix) {#set_color_matrix_new_color_matrix_15}


```
 set_color_matrix(new_color_matrix) 
```

기본 카테고리에 대한 색상 보정 행렬을 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | 색상 보정 행렬입니다. |

### Method: set_color_matrix(new_color_matrix, flags) {#set_color_matrix_new_color_matrix_flags_16}


```
 set_color_matrix(new_color_matrix, flags) 
```

기본 카테고리에 대한 색상 보정 행렬을 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | 색상 보정 행렬입니다. |
| flags | [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag) | 색상 보정 행렬의 영향을 받는 이미지 및 색상의 유형을 지정하는 [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag/) 요소입니다. |

### Method: set_color_matrix(new_color_matrix, mode, type) {#set_color_matrix_new_color_matrix_mode_type_17}


```
 set_color_matrix(new_color_matrix, mode, type) 
```

지정된 카테고리에 대한 색상 보정 행렬을 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | 색상 보정 행렬입니다. |
| mode | [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag) | 색상 보정 행렬의 영향을 받는 이미지 및 색상의 유형을 지정하는 [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag/) 요소입니다. |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | 색상 보정 행렬이 설정되는 범주를 지정하는 [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) 요소입니다. |

### Method: set_gamma(gamma) {#set_gamma_gamma_18}


```
 set_gamma(gamma) 
```

기본 카테고리에 대한 감마 값을 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 감마 | float | 감마 보정 값입니다. |

### Method: set_gamma(gamma, type) {#set_gamma_gamma_type_19}


```
 set_gamma(gamma, type) 
```

지정된 카테고리에 대한 감마 값을 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 감마 | float | 감마 보정 값입니다. |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | 감마 값이 설정되는 범주를 지정하는 [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) 열거형 요소입니다. |

### Method: set_no_op(type) {#set_no_op_type_20}


```
 set_no_op(type) 
```

지정된 카테고리에 대한 색상 보정을 끕니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | 색 보정이 해제되는 범주를 지정하는 [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) 요소입니다. |

### Method: set_output_channel(flags) {#set_output_channel_flags_21}


```
 set_output_channel(flags) 
```

기본 카테고리에 대한 CMYK(시안-마젠타-옐로-블랙) 출력 채널을 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| flags | [ColorChannelFlag](/psd/python-net/aspose.psd/colorchannelflag) | 출력 채널을 지정하는 [ColorChannelFlag](/psd/python-net/aspose.psd/colorchannelflag/) 요소입니다. |

### Method: set_output_channel(flags, type) {#set_output_channel_flags_type_22}


```
 set_output_channel(flags, type) 
```

지정된 카테고리에 대한 CMYK(시안-마젠타-옐로-블랙) 출력 채널을 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| flags | [ColorChannelFlag](/psd/python-net/aspose.psd/colorchannelflag) | 출력 채널을 지정하는 [ColorChannelFlag](/psd/python-net/aspose.psd/colorchannelflag/) 요소입니다. |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | 출력 채널이 설정되는 범주를 지정하는 [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) 요소입니다. |

### Method: set_output_channel_color_profile(color_profile_filename) {#set_output_channel_color_profile_color_profile_filename_23}


```
 set_output_channel_color_profile(color_profile_filename) 
```

기본 카테고리에 대한 출력 채널 색상 프로파일 파일을 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| color_profile_filename | 문자열 | 컬러 프로파일 파일의 경로 이름입니다. 컬러 프로파일 파일이 %SystemRoot%\System32\Spool\Drivers\Color 디렉터리에 있는 경우, 이 매개변수는 파일 이름이 될 수 있습니다. 그렇지 않으면, 이 매개변수는 전체 경로 이름이어야 합니다. |

### Method: set_output_channel_color_profile(color_profile_filename, type) {#set_output_channel_color_profile_color_profile_filename_type_24}


```
 set_output_channel_color_profile(color_profile_filename, type) 
```

지정된 카테고리에 대한 출력 채널 색상 프로파일 파일을 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| color_profile_filename | 문자열 | 컬러 프로파일 파일의 경로 이름입니다. 컬러 프로파일 파일이 %SystemRoot%\System32\Spool\Drivers\Color 디렉터리에 있는 경우, 이 매개변수는 파일 이름이 될 수 있습니다. 그렇지 않으면, 이 매개변수는 전체 경로 이름이어야 합니다. |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | 출력 채널 컬러 프로파일 파일이 설정되는 범주를 지정하는 [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) 요소입니다. |

### Method: set_remap_table(map) {#set_remap_table_map_25}


```
 set_remap_table(map) 
```

기본 카테고리에 대한 색상 재매핑 테이블을 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| map | [ColorMap[]](/psd/python-net/aspose.psd/colormap) | [ColorMap](/psd/python-net/aspose.psd/colormap/) 유형의 색상 쌍 배열입니다. 각 색상 쌍은 기존 색상(첫 번째 값)과 매핑될 색상(두 번째 값)을 포함합니다. |

### Method: set_remap_table(map, type) {#set_remap_table_map_type_26}


```
 set_remap_table(map, type) 
```

지정된 카테고리에 대한 색상 재매핑 테이블을 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| map | [ColorMap[]](/psd/python-net/aspose.psd/colormap) | [ColorMap](/psd/python-net/aspose.psd/colormap/) 유형의 색상 쌍 배열입니다. 각 색상 쌍은 기존 색상(첫 번째 값)과 매핑될 색상(두 번째 값)을 포함합니다. |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | 색상 재매핑 테이블이 설정되는 범주를 지정하는 [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) 요소입니다. |

### Method: set_threshold(threshold) {#set_threshold_threshold_27}


```
 set_threshold(threshold) 
```

기본 카테고리에 대한 임계값(투명도 범위)을 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 임계값 | float | 임계값을 지정하는 실수입니다. |

### Method: set_threshold(threshold, type) {#set_threshold_threshold_type_28}


```
 set_threshold(threshold, type) 
```

지정된 카테고리에 대한 임계값(투명도 범위)을 설정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| 임계값 | float | 0.0에서 1.0 사이의 임계값으로, 색상을 정렬하는 중단점으로 사용되며 최대값 또는 최소값에 매핑됩니다. |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/)의 요소로, 색상 임계값이 설정되는 범주를 지정합니다. |

### Method: set_wrap_mode(mode) {#set_wrap_mode_mode_29}


```
 set_wrap_mode(mode) 
```

텍스처를 도형 전체 또는 도형 경계에 타일링하는 방식을 결정하는 랩 모드를 설정합니다. 텍스처가 채우려는 도형보다 작을 경우, 텍스처가 도형 전체에 타일링되어 채워집니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | [WrapMode](/psd/python-net/aspose.psd/wrapmode/)의 요소로, 이미지의 반복 복사본이 영역을 타일링하는 방식을 지정합니다. |

### Method: set_wrap_mode(mode, color) {#set_wrap_mode_mode_color_30}


```
 set_wrap_mode(mode, color) 
```

텍스처를 도형 전체 또는 도형 경계에 타일링하는 방식을 결정하는 랩 모드와 색상을 설정합니다. 텍스처가 채우려는 도형보다 작을 경우, 텍스처가 도형 전체에 타일링되어 채워집니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | [WrapMode](/psd/python-net/aspose.psd/wrapmode/)의 요소로, 이미지의 반복 복사본이 영역을 타일링하는 방식을 지정합니다. |
| color | [Color](/psd/python-net/aspose.psd/color) | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) 객체로, 렌더링된 이미지 외부 픽셀의 색상을 지정합니다. 모드 매개변수가 [WrapMode.CLAMP](/psd/python-net/aspose.psd/wrapmode/)으로 설정되고 DrawImage에 전달된 소스 사각형이 이미지 자체보다 클 경우 이 색상이 표시됩니다. |

### Method: set_wrap_mode(mode, color, clamp) {#set_wrap_mode_mode_color_clamp_31}


```
 set_wrap_mode(mode, color, clamp) 
```

텍스처를 도형 전체 또는 도형 경계에 타일링하는 방식을 결정하는 랩 모드와 색상을 설정합니다. 텍스처가 채우려는 도형보다 작을 경우, 텍스처가 도형 전체에 타일링되어 채워집니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | [WrapMode](/psd/python-net/aspose.psd/wrapmode/)의 요소로, 이미지의 반복 복사본이 영역을 타일링하는 방식을 지정합니다. |
| color | [Color](/psd/python-net/aspose.psd/color) | 렌더링된 이미지 외부 픽셀의 색상을 지정하는 색상 객체입니다. 모드 매개변수가 [WrapMode.CLAMP](/psd/python-net/aspose.psd/wrapmode/)으로 설정되고 DrawImage에 전달된 소스 사각형이 이미지 자체보다 클 경우 이 색상이 표시됩니다. |
| 클램프 | bool | 이 매개변수는 효과가 없습니다. false로 설정하십시오. |

