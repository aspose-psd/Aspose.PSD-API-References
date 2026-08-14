---
title: "ImageAttributes Klasse"
type: docs
weight: 2180
url: /de/python-net/aspose.psd/imageattributes/
---

**Summary:** An [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) object contains information about how bitmap and metafile colors are manipulated during rendering. An [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) object maintains several color-adjustment settings, including color-adjustment matrices, grayscale-adjustment matrices, gamma-correction values, color-map tables, and color-threshold values. During rendering, colors can be corrected, darkened, lightened, and removed. To apply such manipulations, initialize an [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) object and pass the path of that [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) object (along with the path of an [Image](/psd/python-net/aspose.psd/image/)) to the DrawImage method.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ImageAttributes

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [ImageAttributes()](#ImageAttributes__1) | Initialisiert eine neue Instanz der ImageAttributes-Klasse |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| clear_brush_remap_table() | Löscht die Pinsel-Farbzuordnungstabelle dieses [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) Objekts. |
| clear_color_key() | Löscht den Farbschlüssel (Transparenzbereich) für die Standardkategorie. |
| [clear_color_key(type)](#clear_color_key_type_1) | Löscht den Farbschlüssel (Transparenzbereich) für eine angegebene Kategorie. |
| clear_color_matrix() | Löscht die Farbkorrekturmatrix für die Standardkategorie. |
| [clear_color_matrix(type)](#clear_color_matrix_type_2) | Löscht die Farbkorrekturmatrix für eine angegebene Kategorie. |
| clear_gamma() | Deaktiviert die Gammakorrektur für die Standardkategorie. |
| [clear_gamma(type)](#clear_gamma_type_3) | Deaktiviert die Gammakorrektur für eine angegebene Kategorie. |
| clear_no_op() | Löscht die NoOp-Einstellung für die Standardkategorie. |
| [clear_no_op(type)](#clear_no_op_type_4) | Löscht die NoOp-Einstellung für eine angegebene Kategorie. |
| clear_output_channel() | Löscht die CMYK (Cyan-Magenta-Gelb-Schwarz) Ausgangskanal-Einstellung für die Standardkategorie. |
| [clear_output_channel(type)](#clear_output_channel_type_5) | Löscht die (Cyan-Magenta-Gelb-Schwarz) Ausgangskanal-Einstellung für eine angegebene Kategorie. |
| clear_output_channel_color_profile() | Löscht die Farbprofil-Einstellung des Ausgangskanals für die Standardkategorie. |
| [clear_output_channel_color_profile(type)](#clear_output_channel_color_profile_type_6) | Löscht die Farbprofil-Einstellung des Ausgangskanals für eine angegebene Kategorie. |
| clear_remap_table() | Löscht die Farbzuordnungstabelle für die Standardkategorie. |
| [clear_remap_table(type)](#clear_remap_table_type_7) | Löscht die Farbzuordnungstabelle für eine angegebene Kategorie. |
| clear_threshold() | Löscht den Schwellenwert für die Standardkategorie. |
| [clear_threshold(type)](#clear_threshold_type_8) | Löscht den Schwellenwert für eine angegebene Kategorie. |
| [set_brush_remap_table(map)](#set_brush_remap_table_map_9) | Setzt die Farb-Remap-Tabelle für die Pinselkategorie. |
| [set_color_key(color_low, color_high)](#set_color_key_color_low_color_high_10) | Setzt den Farbenschlüssel für die Standardkategorie. |
| [set_color_key(color_low, color_high, type)](#set_color_key_color_low_color_high_type_11) | Setzt den Farbenschlüssel (Transparenzbereich) für eine angegebene Kategorie. |
| [set_color_matrices(new_color_matrix, gray_matrix)](#set_color_matrices_new_color_matrix_gray_matrix_12) | Setzt die Farbkorrekturmatrix und die Graustufen‑Korrekturmatrix für die Standardkategorie. |
| [set_color_matrices(new_color_matrix, gray_matrix, flags)](#set_color_matrices_new_color_matrix_gray_matrix_flags_13) | Setzt die Farbkorrekturmatrix und die Graustufen‑Korrekturmatrix für die Standardkategorie. |
| [set_color_matrices(new_color_matrix, gray_matrix, mode, type)](#set_color_matrices_new_color_matrix_gray_matrix_mode_type_14) | Setzt die Farbkorrekturmatrix und die Graustufen‑Korrekturmatrix für eine angegebene Kategorie. |
| [set_color_matrix(new_color_matrix)](#set_color_matrix_new_color_matrix_15) | Setzt die Farbkorrekturmatrix für die Standardkategorie. |
| [set_color_matrix(new_color_matrix, flags)](#set_color_matrix_new_color_matrix_flags_16) | Setzt die Farbkorrekturmatrix für die Standardkategorie. |
| [set_color_matrix(new_color_matrix, mode, type)](#set_color_matrix_new_color_matrix_mode_type_17) | Setzt die Farbkorrekturmatrix für eine angegebene Kategorie. |
| [set_gamma(gamma)](#set_gamma_gamma_18) | Setzt den Gammawert für die Standardkategorie. |
| [set_gamma(gamma, type)](#set_gamma_gamma_type_19) | Setzt den Gammawert für eine angegebene Kategorie. |
| set_no_op() | Deaktiviert die Farbkorrektur für die Standardkategorie. |
| [set_no_op(type)](#set_no_op_type_20) | Deaktiviert die Farbkorrektur für eine angegebene Kategorie. |
| [set_output_channel(flags)](#set_output_channel_flags_21) | Setzt den CMYK (Cyan-Magenta-Gelb-Schwarz) Ausgabekanal für die Standardkategorie. |
| [set_output_channel(flags, type)](#set_output_channel_flags_type_22) | Setzt den CMYK (Cyan-Magenta-Gelb-Schwarz) Ausgabekanal für eine angegebene Kategorie. |
| [set_output_channel_color_profile(color_profile_filename)](#set_output_channel_color_profile_color_profile_filename_23) | Setzt die Farbprofildatei des Ausgabekanals für die Standardkategorie. |
| [set_output_channel_color_profile(color_profile_filename, type)](#set_output_channel_color_profile_color_profile_filename_type_24) | Setzt die Farbprofildatei des Ausgabekanals für eine angegebene Kategorie. |
| [set_remap_table(map)](#set_remap_table_map_25) | Setzt die Farb-Remap-Tabelle für die Standardkategorie. |
| [set_remap_table(map, type)](#set_remap_table_map_type_26) | Setzt die Farb-Remap-Tabelle für eine angegebene Kategorie. |
| [set_threshold(threshold)](#set_threshold_threshold_27) | Setzt den Schwellenwert (Transparenzbereich) für die Standardkategorie. |
| [set_threshold(threshold, type)](#set_threshold_threshold_type_28) | Setzt den Schwellenwert (Transparenzbereich) für eine angegebene Kategorie. |
| [set_wrap_mode(mode)](#set_wrap_mode_mode_29) | Setzt den Wrap‑Modus, der verwendet wird, um zu bestimmen, wie eine Textur über eine Form oder an Formgrenzen gekachelt wird. Eine Textur wird über eine Form gekachelt, um sie auszufüllen, wenn die Textur kleiner ist als die Form, die sie füllt. |
| [set_wrap_mode(mode, color)](#set_wrap_mode_mode_color_30) | Setzt den Wrap‑Modus und die Farbe, die verwendet werden, um zu bestimmen, wie eine Textur über eine Form oder an Formgrenzen gekachelt wird. Eine Textur wird über eine Form gekachelt, um sie auszufüllen, wenn die Textur kleiner ist als die Form, die sie füllt. |
| [set_wrap_mode(mode, color, clamp)](#set_wrap_mode_mode_color_clamp_31) | Setzt den Wrap‑Modus und die Farbe, die verwendet werden, um zu bestimmen, wie eine Textur über eine Form oder an Formgrenzen gekachelt wird. Eine Textur wird über eine Form gekachelt, um sie auszufüllen, wenn die Textur kleiner ist als die Form, die sie füllt. |


### Constructor: ImageAttributes() {#ImageAttributes__1}


```
 ImageAttributes() 
```

Initialisiert eine neue Instanz der ImageAttributes-Klasse

### Method: clear_color_key(type) {#clear_color_key_type_1}


```
 clear_color_key(type) 
```

Löscht den Farbschlüssel (Transparenzbereich) für eine angegebene Kategorie.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Ein Element von [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/), das die Kategorie angibt, für die der Farb‑Schlüssel gelöscht wird. |

### Method: clear_color_matrix(type) {#clear_color_matrix_type_2}


```
 clear_color_matrix(type) 
```

Löscht die Farbkorrekturmatrix für eine angegebene Kategorie.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Ein Element von [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/), das die Kategorie angibt, für die die Farb‑Anpassungsmatrix gelöscht wird. |

### Method: clear_gamma(type) {#clear_gamma_type_3}


```
 clear_gamma(type) 
```

Deaktiviert die Gammakorrektur für eine angegebene Kategorie.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Ein Element von [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/), das die Kategorie angibt, für die die Gammakorrektur deaktiviert ist. |

### Method: clear_no_op(type) {#clear_no_op_type_4}


```
 clear_no_op(type) 
```

Löscht die NoOp-Einstellung für eine angegebene Kategorie.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Ein Element von [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/), das die Kategorie angibt, für die die NoOp‑Einstellung gelöscht wird. |

### Method: clear_output_channel(type) {#clear_output_channel_type_5}


```
 clear_output_channel(type) 
```

Löscht die (Cyan-Magenta-Gelb-Schwarz) Ausgangskanal-Einstellung für eine angegebene Kategorie.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Ein Element von [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/), das die Kategorie angibt, für die die Einstellung des Ausgabekanals gelöscht wird. |

### Method: clear_output_channel_color_profile(type) {#clear_output_channel_color_profile_type_6}


```
 clear_output_channel_color_profile(type) 
```

Löscht die Farbprofil-Einstellung des Ausgangskanals für eine angegebene Kategorie.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Ein Element von [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/), das die Kategorie angibt, für die die Profil‑Einstellung des Ausgabekanals gelöscht wird. |

### Method: clear_remap_table(type) {#clear_remap_table_type_7}


```
 clear_remap_table(type) 
```

Löscht die Farbzuordnungstabelle für eine angegebene Kategorie.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Ein Element von [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/), das die Kategorie angibt, für die die Remap‑Tabelle gelöscht wird. |

### Method: clear_threshold(type) {#clear_threshold_type_8}


```
 clear_threshold(type) 
```

Löscht den Schwellenwert für eine angegebene Kategorie.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Ein Element von [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/), das die Kategorie angibt, für die der Schwellenwert gelöscht wird. |

### Method: set_brush_remap_table(map) {#set_brush_remap_table_map_9}


```
 set_brush_remap_table(map) 
```

Setzt die Farb-Remap-Tabelle für die Pinselkategorie.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| map | [ColorMap[]](/psd/python-net/aspose.psd/colormap) | Ein Array von [ColorMap](/psd/python-net/aspose.psd/colormap/)-Objekten. |

### Method: set_color_key(color_low, color_high) {#set_color_key_color_low_color_high_10}


```
 set_color_key(color_low, color_high) 
```

Setzt den Farbenschlüssel für die Standardkategorie.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| color_low | [Color](/psd/python-net/aspose.psd/color) | Der niedrige Farb‑Schlüsselwert. |
| color_high | [Color](/psd/python-net/aspose.psd/color) | Der hohe Farb‑Schlüsselwert. |

### Method: set_color_key(color_low, color_high, type) {#set_color_key_color_low_color_high_type_11}


```
 set_color_key(color_low, color_high, type) 
```

Setzt den Farbenschlüssel (Transparenzbereich) für eine angegebene Kategorie.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| color_low | [Color](/psd/python-net/aspose.psd/color) | Der niedrige Farb‑Schlüsselwert. |
| color_high | [Color](/psd/python-net/aspose.psd/color) | Der hohe Farb‑Schlüsselwert. |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Ein Element von [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/), das die Kategorie angibt, für die der Farb‑Schlüssel gesetzt wird. |

### Method: set_color_matrices(new_color_matrix, gray_matrix) {#set_color_matrices_new_color_matrix_gray_matrix_12}


```
 set_color_matrices(new_color_matrix, gray_matrix) 
```

Setzt die Farbkorrekturmatrix und die Graustufen‑Korrekturmatrix für die Standardkategorie.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | Die Farb‑Anpassungsmatrix. |
| gray_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | Die Graustufen‑Anpassungsmatrix. |

### Method: set_color_matrices(new_color_matrix, gray_matrix, flags) {#set_color_matrices_new_color_matrix_gray_matrix_flags_13}


```
 set_color_matrices(new_color_matrix, gray_matrix, flags) 
```

Setzt die Farbkorrekturmatrix und die Graustufen‑Korrekturmatrix für die Standardkategorie.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | Die Farb‑Anpassungsmatrix. |
| gray_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | Die Graustufen‑Anpassungsmatrix. |
| flags | [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag) | Ein Element von [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag/), das den Bild‑ und Farbtyp angibt, der von den Farb‑ und Graustufen‑Anpassungsmatrizen betroffen ist. |

### Method: set_color_matrices(new_color_matrix, gray_matrix, mode, type) {#set_color_matrices_new_color_matrix_gray_matrix_mode_type_14}


```
 set_color_matrices(new_color_matrix, gray_matrix, mode, type) 
```

Setzt die Farbkorrekturmatrix und die Graustufen‑Korrekturmatrix für eine angegebene Kategorie.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | Die Farb‑Anpassungsmatrix. |
| gray_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | Die Graustufen‑Anpassungsmatrix. |
| mode | [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag) | Ein Element von [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag/), das den Bild‑ und Farbtyp angibt, der von den Farb‑ und Graustufen‑Anpassungsmatrizen betroffen ist. |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Ein Element von [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/), das die Kategorie angibt, für die die Farb‑ und Graustufen‑Anpassungsmatrizen gesetzt werden. |

### Method: set_color_matrix(new_color_matrix) {#set_color_matrix_new_color_matrix_15}


```
 set_color_matrix(new_color_matrix) 
```

Setzt die Farbkorrekturmatrix für die Standardkategorie.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | Die Farb‑Anpassungsmatrix. |

### Method: set_color_matrix(new_color_matrix, flags) {#set_color_matrix_new_color_matrix_flags_16}


```
 set_color_matrix(new_color_matrix, flags) 
```

Setzt die Farbkorrekturmatrix für die Standardkategorie.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | Die Farb‑Anpassungsmatrix. |
| flags | [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag) | Ein Element von [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag/), das den Bild‑ und Farbtyp angibt, der von der Farb‑Anpassungsmatrix betroffen ist. |

### Method: set_color_matrix(new_color_matrix, mode, type) {#set_color_matrix_new_color_matrix_mode_type_17}


```
 set_color_matrix(new_color_matrix, mode, type) 
```

Setzt die Farbkorrekturmatrix für eine angegebene Kategorie.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | Die Farb‑Anpassungsmatrix. |
| mode | [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag) | Ein Element von [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag/), das den Bild‑ und Farbtyp angibt, der von der Farb‑Anpassungsmatrix betroffen ist. |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Ein Element von [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/), das die Kategorie angibt, für die die Farb‑Anpassungsmatrix gesetzt wird. |

### Method: set_gamma(gamma) {#set_gamma_gamma_18}


```
 set_gamma(gamma) 
```

Setzt den Gammawert für die Standardkategorie.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Gamma | float | Der Gammakorrekturwert. |

### Method: set_gamma(gamma, type) {#set_gamma_gamma_type_19}


```
 set_gamma(gamma, type) 
```

Setzt den Gammawert für eine angegebene Kategorie.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Gamma | float | Der Gammakorrekturwert. |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Ein Element der [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/)-Aufzählung, das die Kategorie angibt, für die der Gamma‑Wert gesetzt wird. |

### Method: set_no_op(type) {#set_no_op_type_20}


```
 set_no_op(type) 
```

Deaktiviert die Farbkorrektur für eine angegebene Kategorie.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Ein Element von [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/), das die Kategorie angibt, für die die Farbkorrektur ausgeschaltet ist. |

### Method: set_output_channel(flags) {#set_output_channel_flags_21}


```
 set_output_channel(flags) 
```

Setzt den CMYK (Cyan-Magenta-Gelb-Schwarz) Ausgabekanal für die Standardkategorie.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| flags | [ColorChannelFlag](/psd/python-net/aspose.psd/colorchannelflag) | Ein Element von [ColorChannelFlag](/psd/python-net/aspose.psd/colorchannelflag/), das den Ausgabekanal angibt. |

### Method: set_output_channel(flags, type) {#set_output_channel_flags_type_22}


```
 set_output_channel(flags, type) 
```

Setzt den CMYK (Cyan-Magenta-Gelb-Schwarz) Ausgabekanal für eine angegebene Kategorie.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| flags | [ColorChannelFlag](/psd/python-net/aspose.psd/colorchannelflag) | Ein Element von [ColorChannelFlag](/psd/python-net/aspose.psd/colorchannelflag/), das den Ausgabekanal angibt. |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Ein Element von [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/), das die Kategorie angibt, für die der Ausgabekanal gesetzt wird. |

### Method: set_output_channel_color_profile(color_profile_filename) {#set_output_channel_color_profile_color_profile_filename_23}


```
 set_output_channel_color_profile(color_profile_filename) 
```

Setzt die Farbprofildatei des Ausgabekanals für die Standardkategorie.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| color_profile_filename | string | Der Pfadname einer Farbprofildatei. Wenn die Farbprofildatei im Verzeichnis %SystemRoot%\\System32\\Spool\\Drivers\\Color liegt, kann dieser Parameter der Dateiname sein. Andernfalls muss dieser Parameter den vollqualifizierten Pfadnamen enthalten. |

### Method: set_output_channel_color_profile(color_profile_filename, type) {#set_output_channel_color_profile_color_profile_filename_type_24}


```
 set_output_channel_color_profile(color_profile_filename, type) 
```

Setzt die Farbprofildatei des Ausgabekanals für eine angegebene Kategorie.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| color_profile_filename | string | Der Pfadname einer Farbprofildatei. Wenn die Farbprofildatei im Verzeichnis %SystemRoot%\\System32\\Spool\\Drivers\\Color liegt, kann dieser Parameter der Dateiname sein. Andernfalls muss dieser Parameter den vollqualifizierten Pfadnamen enthalten. |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Ein Element von [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/), das die Kategorie angibt, für die die Ausgabekanal‑Farbprofildatei festgelegt ist. |

### Method: set_remap_table(map) {#set_remap_table_map_25}


```
 set_remap_table(map) 
```

Setzt die Farb-Remap-Tabelle für die Standardkategorie.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| map | [ColorMap[]](/psd/python-net/aspose.psd/colormap) | Ein Array von Farbpaaren des Typs [ColorMap](/psd/python-net/aspose.psd/colormap/). Jedes Farbpaar enthält eine vorhandene Farbe (den ersten Wert) und die Farbe, auf die sie abgebildet wird (den zweiten Wert). |

### Method: set_remap_table(map, type) {#set_remap_table_map_type_26}


```
 set_remap_table(map, type) 
```

Setzt die Farb-Remap-Tabelle für eine angegebene Kategorie.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| map | [ColorMap[]](/psd/python-net/aspose.psd/colormap) | Ein Array von Farbpaaren des Typs [ColorMap](/psd/python-net/aspose.psd/colormap/). Jedes Farbpaar enthält eine vorhandene Farbe (den ersten Wert) und die Farbe, auf die sie abgebildet wird (den zweiten Wert). |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Ein Element von [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/), das die Kategorie angibt, für die die Farb‑Remap‑Tabelle festgelegt ist. |

### Method: set_threshold(threshold) {#set_threshold_threshold_27}


```
 set_threshold(threshold) 
```

Setzt den Schwellenwert (Transparenzbereich) für die Standardkategorie.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| threshold | float | Eine Gleitkommazahl, die den Schwellenwert angibt. |

### Method: set_threshold(threshold, type) {#set_threshold_threshold_type_28}


```
 set_threshold(threshold, type) 
```

Setzt den Schwellenwert (Transparenzbereich) für eine angegebene Kategorie.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| threshold | float | Ein Schwellenwert von 0,0 bis 1,0, der als Trennstelle verwendet wird, um Farben zu sortieren, die entweder einem Maximal‑ oder einem Minimalwert zugeordnet werden. |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Ein Element von [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/), das die Kategorie angibt, für die der Farbschwellenwert festgelegt ist. |

### Method: set_wrap_mode(mode) {#set_wrap_mode_mode_29}


```
 set_wrap_mode(mode) 
```

Setzt den Wrap‑Modus, der verwendet wird, um zu bestimmen, wie eine Textur über eine Form oder an Formgrenzen gekachelt wird. Eine Textur wird über eine Form gekachelt, um sie auszufüllen, wenn die Textur kleiner ist als die Form, die sie füllt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Ein Element von [WrapMode](/psd/python-net/aspose.psd/wrapmode/), das angibt, wie wiederholte Kopien eines Bildes verwendet werden, um einen Bereich zu kacheln. |

### Method: set_wrap_mode(mode, color) {#set_wrap_mode_mode_color_30}


```
 set_wrap_mode(mode, color) 
```

Setzt den Wrap‑Modus und die Farbe, die verwendet werden, um zu bestimmen, wie eine Textur über eine Form oder an Formgrenzen gekachelt wird. Eine Textur wird über eine Form gekachelt, um sie auszufüllen, wenn die Textur kleiner ist als die Form, die sie füllt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Ein Element von [WrapMode](/psd/python-net/aspose.psd/wrapmode/), das angibt, wie wiederholte Kopien eines Bildes verwendet werden, um einen Bereich zu kacheln. |
| color | [Color](/psd/python-net/aspose.psd/color) | Ein [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/)-Objekt, das die Farbe von Pixeln außerhalb eines gerenderten Bildes angibt. Diese Farbe ist sichtbar, wenn der Modusparameter auf [WrapMode.CLAMP](/psd/python-net/aspose.psd/wrapmode/) gesetzt ist und das Quellrechteck, das an DrawImage übergeben wird, größer ist als das Bild selbst. |

### Method: set_wrap_mode(mode, color, clamp) {#set_wrap_mode_mode_color_clamp_31}


```
 set_wrap_mode(mode, color, clamp) 
```

Setzt den Wrap‑Modus und die Farbe, die verwendet werden, um zu bestimmen, wie eine Textur über eine Form oder an Formgrenzen gekachelt wird. Eine Textur wird über eine Form gekachelt, um sie auszufüllen, wenn die Textur kleiner ist als die Form, die sie füllt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Ein Element von [WrapMode](/psd/python-net/aspose.psd/wrapmode/), das angibt, wie wiederholte Kopien eines Bildes verwendet werden, um einen Bereich zu kacheln. |
| color | [Color](/psd/python-net/aspose.psd/color) | Ein Farbobjekt, das die Farbe von Pixeln außerhalb eines gerenderten Bildes angibt. Diese Farbe ist sichtbar, wenn der Modusparameter auf [WrapMode.CLAMP](/psd/python-net/aspose.psd/wrapmode/) gesetzt ist und das Quellrechteck, das an DrawImage übergeben wird, größer ist als das Bild selbst. |
| clamp | bool | Dieser Parameter hat keine Wirkung. Setzen Sie ihn auf false. |

