---
title: "ImageAttributes Klasse"
type: docs
weight: 2180
url: /nl/python-net/aspose.psd/imageattributes/
---

**Summary:** An [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) object contains information about how bitmap and metafile colors are manipulated during rendering. An [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) object maintains several color-adjustment settings, including color-adjustment matrices, grayscale-adjustment matrices, gamma-correction values, color-map tables, and color-threshold values. During rendering, colors can be corrected, darkened, lightened, and removed. To apply such manipulations, initialize an [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) object and pass the path of that [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) object (along with the path of an [Image](/psd/python-net/aspose.psd/image/)) to the DrawImage method.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ImageAttributes

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [ImageAttributes()](#ImageAttributes__1) | Initialiseert een nieuw exemplaar van de ImageAttributes klasse |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| clear_brush_remap_table() | Wist de kleur‑herkoppelings‑tabel van de penseel van dit [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) object. |
| clear_color_key() | Verwijdert de kleurtoets (transparantiebereik) voor de standaardcategorie. |
| [clear_color_key(type)](#clear_color_key_type_1) | Verwijdert de kleurtoets (transparantiebereik) voor een opgegeven categorie. |
| clear_color_matrix() | Verwijdert de kleuraanpassingsmatrix voor de standaardcategorie. |
| [clear_color_matrix(type)](#clear_color_matrix_type_2) | Verwijdert de kleuraanpassingsmatrix voor een opgegeven categorie. |
| clear_gamma() | Schakelt gamma-correctie uit voor de standaardcategorie. |
| [clear_gamma(type)](#clear_gamma_type_3) | Schakelt gamma-correctie uit voor een opgegeven categorie. |
| clear_no_op() | Verwijdert de NoOp-instelling voor de standaardcategorie. |
| [clear_no_op(type)](#clear_no_op_type_4) | Verwijdert de NoOp-instelling voor een opgegeven categorie. |
| clear_output_channel() | Verwijdert de CMYK (cyaan-magenta-geel-zwart) uitvoerkanaalinstelling voor de standaardcategorie. |
| [clear_output_channel(type)](#clear_output_channel_type_5) | Verwijdert de (cyaan-magenta-geel-zwart) uitvoerkanaalinstelling voor een opgegeven categorie. |
| clear_output_channel_color_profile() | Verwijdert de kleurprofielinstelling van het uitvoerkanaal voor de standaardcategorie. |
| [clear_output_channel_color_profile(type)](#clear_output_channel_color_profile_type_6) | Verwijdert de kleurprofielinstelling van het uitvoerkanaal voor een opgegeven categorie. |
| clear_remap_table() | Verwijdert de kleurherkaarttabel voor de standaardcategorie. |
| [clear_remap_table(type)](#clear_remap_table_type_7) | Verwijdert de kleurherkaarttabel voor een opgegeven categorie. |
| clear_threshold() | Verwijdert de drempelwaarde voor de standaardcategorie. |
| [clear_threshold(type)](#clear_threshold_type_8) | Verwijdert de drempelwaarde voor een opgegeven categorie. |
| [set_brush_remap_table(map)](#set_brush_remap_table_map_9) | Stelt de kleurherkaarttabel in voor de penseelcategorie. |
| [set_color_key(color_low, color_high)](#set_color_key_color_low_color_high_10) | Stelt de kleurensleutel in voor de standaardcategorie. |
| [set_color_key(color_low, color_high, type)](#set_color_key_color_low_color_high_type_11) | Stelt de kleurensleutel (transparantiebereik) in voor een opgegeven categorie. |
| [set_color_matrices(new_color_matrix, gray_matrix)](#set_color_matrices_new_color_matrix_gray_matrix_12) | Stelt de kleurcorrectiematrix en de grijstinten-correctiematrix in voor de standaardcategorie. |
| [set_color_matrices(new_color_matrix, gray_matrix, flags)](#set_color_matrices_new_color_matrix_gray_matrix_flags_13) | Stelt de kleurcorrectiematrix en de grijstinten-correctiematrix in voor de standaardcategorie. |
| [set_color_matrices(new_color_matrix, gray_matrix, mode, type)](#set_color_matrices_new_color_matrix_gray_matrix_mode_type_14) | Stelt de kleurcorrectiematrix en de grijstinten-correctiematrix in voor een opgegeven categorie. |
| [set_color_matrix(new_color_matrix)](#set_color_matrix_new_color_matrix_15) | Stelt de kleurcorrectiematrix in voor de standaardcategorie. |
| [set_color_matrix(new_color_matrix, flags)](#set_color_matrix_new_color_matrix_flags_16) | Stelt de kleurcorrectiematrix in voor de standaardcategorie. |
| [set_color_matrix(new_color_matrix, mode, type)](#set_color_matrix_new_color_matrix_mode_type_17) | Stelt de kleurcorrectiematrix in voor een opgegeven categorie. |
| [set_gamma(gamma)](#set_gamma_gamma_18) | Stelt de gammawaarde in voor de standaardcategorie. |
| [set_gamma(gamma, type)](#set_gamma_gamma_type_19) | Stelt de gammawaarde in voor een opgegeven categorie. |
| set_no_op() | Schakelt de kleurcorrectie uit voor de standaardcategorie. |
| [set_no_op(type)](#set_no_op_type_20) | Schakelt de kleurcorrectie uit voor een opgegeven categorie. |
| [set_output_channel(flags)](#set_output_channel_flags_21) | Stelt het CMYK (cyaan-magenta-geel-zwart) uitvoerkanaal in voor de standaardcategorie. |
| [set_output_channel(flags, type)](#set_output_channel_flags_type_22) | Stelt het CMYK (cyaan-magenta-geel-zwart) uitvoerkanaal in voor een opgegeven categorie. |
| [set_output_channel_color_profile(color_profile_filename)](#set_output_channel_color_profile_color_profile_filename_23) | Stelt het kleurprofielbestand van het uitvoerkanaal in voor de standaardcategorie. |
| [set_output_channel_color_profile(color_profile_filename, type)](#set_output_channel_color_profile_color_profile_filename_type_24) | Stelt het kleurprofielbestand van het uitvoerkanaal in voor een opgegeven categorie. |
| [set_remap_table(map)](#set_remap_table_map_25) | Stelt de kleurhermappingtabel in voor de standaardcategorie. |
| [set_remap_table(map, type)](#set_remap_table_map_type_26) | Stelt de kleurhermappingtabel in voor een opgegeven categorie. |
| [set_threshold(threshold)](#set_threshold_threshold_27) | Stelt de drempel (transparantiebereik) in voor de standaardcategorie. |
| [set_threshold(threshold, type)](#set_threshold_threshold_type_28) | Stelt de drempel (transparantiebereik) in voor een opgegeven categorie. |
| [set_wrap_mode(mode)](#set_wrap_mode_mode_29) | Stelt de wrap-modus in die wordt gebruikt om te bepalen hoe een textuur over een vorm, of op de randen van de vorm, wordt getegeld. Een textuur wordt over een vorm getegeld om deze te vullen wanneer de textuur kleiner is dan de vorm die wordt gevuld. |
| [set_wrap_mode(mode, color)](#set_wrap_mode_mode_color_30) | Stelt de wrap-modus en de kleur in die worden gebruikt om te bepalen hoe een textuur over een vorm, of op de randen van de vorm, wordt getegeld. Een textuur wordt over een vorm getegeld om deze te vullen wanneer de textuur kleiner is dan de vorm die wordt gevuld. |
| [set_wrap_mode(mode, color, clamp)](#set_wrap_mode_mode_color_clamp_31) | Stelt de wrap-modus en de kleur in die worden gebruikt om te bepalen hoe een textuur over een vorm, of op de randen van de vorm, wordt getegeld. Een textuur wordt over een vorm getegeld om deze te vullen wanneer de textuur kleiner is dan de vorm die wordt gevuld. |


### Constructor: ImageAttributes() {#ImageAttributes__1}


```
 ImageAttributes() 
```

Initialiseert een nieuw exemplaar van de ImageAttributes klasse

### Method: clear_color_key(type) {#clear_color_key_type_1}


```
 clear_color_key(type) 
```

Verwijdert de kleurtoets (transparantiebereik) voor een opgegeven categorie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Een element van [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) dat de categorie specificeert waarvoor de kleurensleutel wordt gewist. |

### Method: clear_color_matrix(type) {#clear_color_matrix_type_2}


```
 clear_color_matrix(type) 
```

Verwijdert de kleuraanpassingsmatrix voor een opgegeven categorie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Een element van [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) dat de categorie specificeert waarvoor de kleurcorrectiematrix wordt gewist. |

### Method: clear_gamma(type) {#clear_gamma_type_3}


```
 clear_gamma(type) 
```

Schakelt gamma-correctie uit voor een opgegeven categorie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Een element van [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) dat de categorie specificeert waarvoor gamma-correctie is uitgeschakeld. |

### Method: clear_no_op(type) {#clear_no_op_type_4}


```
 clear_no_op(type) 
```

Verwijdert de NoOp-instelling voor een opgegeven categorie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Een element van [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) dat de categorie specificeert waarvoor de NoOp-instelling wordt gewist. |

### Method: clear_output_channel(type) {#clear_output_channel_type_5}


```
 clear_output_channel(type) 
```

Verwijdert de (cyaan-magenta-geel-zwart) uitvoerkanaalinstelling voor een opgegeven categorie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Een element van [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) dat de categorie specificeert waarvoor de instelling van het uitvoerkanaal wordt gewist. |

### Method: clear_output_channel_color_profile(type) {#clear_output_channel_color_profile_type_6}


```
 clear_output_channel_color_profile(type) 
```

Verwijdert de kleurprofielinstelling van het uitvoerkanaal voor een opgegeven categorie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Een element van [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) dat de categorie specificeert waarvoor de profielinstelling van het uitvoerkanaal wordt gewist. |

### Method: clear_remap_table(type) {#clear_remap_table_type_7}


```
 clear_remap_table(type) 
```

Verwijdert de kleurherkaarttabel voor een opgegeven categorie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Een element van [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) dat de categorie specificeert waarvoor de remap-tabel wordt gewist. |

### Method: clear_threshold(type) {#clear_threshold_type_8}


```
 clear_threshold(type) 
```

Verwijdert de drempelwaarde voor een opgegeven categorie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Een element van [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) dat de categorie specificeert waarvoor de drempelwaarde wordt gewist. |

### Method: set_brush_remap_table(map) {#set_brush_remap_table_map_9}


```
 set_brush_remap_table(map) 
```

Stelt de kleurherkaarttabel in voor de penseelcategorie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| map | [ColorMap[]](/psd/python-net/aspose.psd/colormap) | Een array van [ColorMap](/psd/python-net/aspose.psd/colormap/) objecten. |

### Method: set_color_key(color_low, color_high) {#set_color_key_color_low_color_high_10}


```
 set_color_key(color_low, color_high) 
```

Stelt de kleurensleutel in voor de standaardcategorie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| color_low | [Color](/psd/python-net/aspose.psd/color) | De lage kleur‑sleutelwaarde. |
| color_high | [Color](/psd/python-net/aspose.psd/color) | De hoge kleur‑sleutelwaarde. |

### Method: set_color_key(color_low, color_high, type) {#set_color_key_color_low_color_high_type_11}


```
 set_color_key(color_low, color_high, type) 
```

Stelt de kleurensleutel (transparantiebereik) in voor een opgegeven categorie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| color_low | [Color](/psd/python-net/aspose.psd/color) | De lage kleur‑sleutelwaarde. |
| color_high | [Color](/psd/python-net/aspose.psd/color) | De hoge kleur‑sleutelwaarde. |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Een element van [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) dat de categorie specificeert waarvoor de kleur‑sleutel wordt ingesteld. |

### Method: set_color_matrices(new_color_matrix, gray_matrix) {#set_color_matrices_new_color_matrix_gray_matrix_12}


```
 set_color_matrices(new_color_matrix, gray_matrix) 
```

Stelt de kleurcorrectiematrix en de grijstinten-correctiematrix in voor de standaardcategorie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | De kleur‑aanpassingsmatrix. |
| gray_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | De grijswaarden‑aanpassingsmatrix. |

### Method: set_color_matrices(new_color_matrix, gray_matrix, flags) {#set_color_matrices_new_color_matrix_gray_matrix_flags_13}


```
 set_color_matrices(new_color_matrix, gray_matrix, flags) 
```

Stelt de kleurcorrectiematrix en de grijstinten-correctiematrix in voor de standaardcategorie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | De kleur‑aanpassingsmatrix. |
| gray_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | De grijswaarden‑aanpassingsmatrix. |
| flags | [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag) | Een element van [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag/) dat het type afbeelding en kleur specificeert dat wordt beïnvloed door de kleur‑aanpassings‑ en grijswaarden‑aanpassingsmatrices. |

### Method: set_color_matrices(new_color_matrix, gray_matrix, mode, type) {#set_color_matrices_new_color_matrix_gray_matrix_mode_type_14}


```
 set_color_matrices(new_color_matrix, gray_matrix, mode, type) 
```

Stelt de kleurcorrectiematrix en de grijstinten-correctiematrix in voor een opgegeven categorie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | De kleur‑aanpassingsmatrix. |
| gray_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | De grijswaarden‑aanpassingsmatrix. |
| mode | [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag) | Een element van [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag/) dat het type afbeelding en kleur specificeert dat wordt beïnvloed door de kleur‑aanpassings‑ en grijswaarden‑aanpassingsmatrices. |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Een element van [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) dat de categorie specificeert waarvoor de kleur‑aanpassings‑ en grijswaarden‑aanpassingsmatrices worden ingesteld. |

### Method: set_color_matrix(new_color_matrix) {#set_color_matrix_new_color_matrix_15}


```
 set_color_matrix(new_color_matrix) 
```

Stelt de kleurcorrectiematrix in voor de standaardcategorie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | De kleur‑aanpassingsmatrix. |

### Method: set_color_matrix(new_color_matrix, flags) {#set_color_matrix_new_color_matrix_flags_16}


```
 set_color_matrix(new_color_matrix, flags) 
```

Stelt de kleurcorrectiematrix in voor de standaardcategorie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | De kleur‑aanpassingsmatrix. |
| flags | [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag) | Een element van [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag/) dat het type afbeelding en kleur specificeert dat wordt beïnvloed door de kleur‑aanpassingsmatrix. |

### Method: set_color_matrix(new_color_matrix, mode, type) {#set_color_matrix_new_color_matrix_mode_type_17}


```
 set_color_matrix(new_color_matrix, mode, type) 
```

Stelt de kleurcorrectiematrix in voor een opgegeven categorie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | De kleur‑aanpassingsmatrix. |
| mode | [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag) | Een element van [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag/) dat het type afbeelding en kleur specificeert dat wordt beïnvloed door de kleur‑aanpassingsmatrix. |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Een element van [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) dat de categorie specificeert waarvoor de kleur‑aanpassingsmatrix wordt ingesteld. |

### Method: set_gamma(gamma) {#set_gamma_gamma_18}


```
 set_gamma(gamma) 
```

Stelt de gammawaarde in voor de standaardcategorie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| gamma | float | De gamma‑correctiewaarde. |

### Method: set_gamma(gamma, type) {#set_gamma_gamma_type_19}


```
 set_gamma(gamma, type) 
```

Stelt de gammawaarde in voor een opgegeven categorie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| gamma | float | De gamma‑correctiewaarde. |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Een element van de [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) enumeratie dat de categorie specificeert waarvoor de gamma‑waarde wordt ingesteld. |

### Method: set_no_op(type) {#set_no_op_type_20}


```
 set_no_op(type) 
```

Schakelt de kleurcorrectie uit voor een opgegeven categorie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Een element van [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) dat de categorie specificeert waarvoor kleurcorrectie wordt uitgeschakeld. |

### Method: set_output_channel(flags) {#set_output_channel_flags_21}


```
 set_output_channel(flags) 
```

Stelt het CMYK (cyaan-magenta-geel-zwart) uitvoerkanaal in voor de standaardcategorie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| flags | [ColorChannelFlag](/psd/python-net/aspose.psd/colorchannelflag) | Een element van [ColorChannelFlag](/psd/python-net/aspose.psd/colorchannelflag/) dat het uitvoerkanaal specificeert. |

### Method: set_output_channel(flags, type) {#set_output_channel_flags_type_22}


```
 set_output_channel(flags, type) 
```

Stelt het CMYK (cyaan-magenta-geel-zwart) uitvoerkanaal in voor een opgegeven categorie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| flags | [ColorChannelFlag](/psd/python-net/aspose.psd/colorchannelflag) | Een element van [ColorChannelFlag](/psd/python-net/aspose.psd/colorchannelflag/) dat het uitvoerkanaal specificeert. |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Een element van [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) dat de categorie specificeert waarvoor het uitvoerkanaal wordt ingesteld. |

### Method: set_output_channel_color_profile(color_profile_filename) {#set_output_channel_color_profile_color_profile_filename_23}


```
 set_output_channel_color_profile(color_profile_filename) 
```

Stelt het kleurprofielbestand van het uitvoerkanaal in voor de standaardcategorie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| color_profile_filename | string | De padnaam van een kleur‑profielbestand. Als het kleur‑profielbestand zich bevindt in de %SystemRoot%\\System32\\Spool\\Drivers\\Color map, kan deze parameter de bestandsnaam zijn. Anders moet deze parameter de volledig gekwalificeerde padnaam zijn. |

### Method: set_output_channel_color_profile(color_profile_filename, type) {#set_output_channel_color_profile_color_profile_filename_type_24}


```
 set_output_channel_color_profile(color_profile_filename, type) 
```

Stelt het kleurprofielbestand van het uitvoerkanaal in voor een opgegeven categorie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| color_profile_filename | string | De padnaam van een kleur‑profielbestand. Als het kleur‑profielbestand zich bevindt in de %SystemRoot%\\System32\\Spool\\Drivers\\Color map, kan deze parameter de bestandsnaam zijn. Anders moet deze parameter de volledig gekwalificeerde padnaam zijn. |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Een element van [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) dat de categorie specificeert waarvoor het kleur‑profielbestand van het uitvoerkanaal wordt ingesteld. |

### Method: set_remap_table(map) {#set_remap_table_map_25}


```
 set_remap_table(map) 
```

Stelt de kleurhermappingtabel in voor de standaardcategorie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| map | [ColorMap[]](/psd/python-net/aspose.psd/colormap) | Een array van kleurparen van het type [ColorMap](/psd/python-net/aspose.psd/colormap/). Elk kleurpaar bevat een bestaande kleur (de eerste waarde) en de kleur waarnaar deze wordt gemapt (de tweede waarde). |

### Method: set_remap_table(map, type) {#set_remap_table_map_type_26}


```
 set_remap_table(map, type) 
```

Stelt de kleurhermappingtabel in voor een opgegeven categorie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| map | [ColorMap[]](/psd/python-net/aspose.psd/colormap) | Een array van kleurparen van het type [ColorMap](/psd/python-net/aspose.psd/colormap/). Elk kleurpaar bevat een bestaande kleur (de eerste waarde) en de kleur waarnaar deze wordt gemapt (de tweede waarde). |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Een element van [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) dat de categorie specificeert waarvoor de kleur‑remap‑tabel wordt ingesteld. |

### Method: set_threshold(threshold) {#set_threshold_threshold_27}


```
 set_threshold(threshold) 
```

Stelt de drempel (transparantiebereik) in voor de standaardcategorie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| threshold | float | Een reëel getal dat de drempelwaarde specificeert. |

### Method: set_threshold(threshold, type) {#set_threshold_threshold_type_28}


```
 set_threshold(threshold, type) 
```

Stelt de drempel (transparantiebereik) in voor een opgegeven categorie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| threshold | float | Een drempelwaarde van 0,0 tot 1,0 die wordt gebruikt als een breekpunt om kleuren te sorteren die worden toegewezen aan een maximale of een minimale waarde. |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Een element van [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) dat de categorie specificeert waarvoor de kleurdrempel is ingesteld. |

### Method: set_wrap_mode(mode) {#set_wrap_mode_mode_29}


```
 set_wrap_mode(mode) 
```

Stelt de wrap-modus in die wordt gebruikt om te bepalen hoe een textuur over een vorm, of op de randen van de vorm, wordt getegeld. Een textuur wordt over een vorm getegeld om deze te vullen wanneer de textuur kleiner is dan de vorm die wordt gevuld.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Een element van [WrapMode](/psd/python-net/aspose.psd/wrapmode/) dat aangeeft hoe herhaalde kopieën van een afbeelding worden gebruikt om een gebied te betegelen. |

### Method: set_wrap_mode(mode, color) {#set_wrap_mode_mode_color_30}


```
 set_wrap_mode(mode, color) 
```

Stelt de wrap-modus en de kleur in die worden gebruikt om te bepalen hoe een textuur over een vorm, of op de randen van de vorm, wordt getegeld. Een textuur wordt over een vorm getegeld om deze te vullen wanneer de textuur kleiner is dan de vorm die wordt gevuld.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Een element van [WrapMode](/psd/python-net/aspose.psd/wrapmode/) dat aangeeft hoe herhaalde kopieën van een afbeelding worden gebruikt om een gebied te betegelen. |
| color | [Color](/psd/python-net/aspose.psd/color) | Een [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) object dat de kleur van pixels buiten een gerenderde afbeelding specificeert. Deze kleur is zichtbaar als de modusparameter is ingesteld op [WrapMode.CLAMP](/psd/python-net/aspose.psd/wrapmode/) en de bronrechthoek die aan DrawImage wordt doorgegeven groter is dan de afbeelding zelf. |

### Method: set_wrap_mode(mode, color, clamp) {#set_wrap_mode_mode_color_clamp_31}


```
 set_wrap_mode(mode, color, clamp) 
```

Stelt de wrap-modus en de kleur in die worden gebruikt om te bepalen hoe een textuur over een vorm, of op de randen van de vorm, wordt getegeld. Een textuur wordt over een vorm getegeld om deze te vullen wanneer de textuur kleiner is dan de vorm die wordt gevuld.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Een element van [WrapMode](/psd/python-net/aspose.psd/wrapmode/) dat aangeeft hoe herhaalde kopieën van een afbeelding worden gebruikt om een gebied te betegelen. |
| color | [Color](/psd/python-net/aspose.psd/color) | Een kleurobject dat de kleur van pixels buiten een gerenderde afbeelding specificeert. Deze kleur is zichtbaar als de modusparameter is ingesteld op [WrapMode.CLAMP](/psd/python-net/aspose.psd/wrapmode/) en de bronrechthoek die aan DrawImage wordt doorgegeven groter is dan de afbeelding zelf. |
| klem | bool | Deze parameter heeft geen effect. Stel deze in op false. |

