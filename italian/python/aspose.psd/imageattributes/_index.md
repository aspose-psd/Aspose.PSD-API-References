---
title: "Classe ImageAttributes"
type: docs
weight: 2180
url: /it/python-net/aspose.psd/imageattributes/
---

**Summary:** An [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) object contains information about how bitmap and metafile colors are manipulated during rendering. An [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) object maintains several color-adjustment settings, including color-adjustment matrices, grayscale-adjustment matrices, gamma-correction values, color-map tables, and color-threshold values. During rendering, colors can be corrected, darkened, lightened, and removed. To apply such manipulations, initialize an [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) object and pass the path of that [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) object (along with the path of an [Image](/psd/python-net/aspose.psd/image/)) to the DrawImage method.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ImageAttributes

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ImageAttributes()](#ImageAttributes__1) | Inizializza una nuova istanza della classe ImageAttributes |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| clear_brush_remap_table() | Cancella la tabella di rimappatura dei colori del pennello di questo oggetto [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/). |
| clear_color_key() | Cancella la chiave di colore (intervallo di trasparenza) per la categoria predefinita. |
| [clear_color_key(type)](#clear_color_key_type_1) | Cancella la chiave di colore (intervallo di trasparenza) per una categoria specificata. |
| clear_color_matrix() | Cancella la matrice di regolazione del colore per la categoria predefinita. |
| [clear_color_matrix(type)](#clear_color_matrix_type_2) | Cancella la matrice di regolazione del colore per una categoria specificata. |
| clear_gamma() | Disabilita la correzione gamma per la categoria predefinita. |
| [clear_gamma(type)](#clear_gamma_type_3) | Disabilita la correzione gamma per una categoria specificata. |
| clear_no_op() | Cancella l'impostazione NoOp per la categoria predefinita. |
| [clear_no_op(type)](#clear_no_op_type_4) | Cancella l'impostazione NoOp per una categoria specificata. |
| clear_output_channel() | Cancella l'impostazione del canale di uscita CMYK (ciano-magenta-giallo-nero) per la categoria predefinita. |
| [clear_output_channel(type)](#clear_output_channel_type_5) | Cancella l'impostazione del canale di uscita (ciano-magenta-giallo-nero) per una categoria specificata. |
| clear_output_channel_color_profile() | Cancella l'impostazione del profilo colore del canale di uscita per la categoria predefinita. |
| [clear_output_channel_color_profile(type)](#clear_output_channel_color_profile_type_6) | Cancella l'impostazione del profilo colore del canale di uscita per una categoria specificata. |
| clear_remap_table() | Cancella la tabella di rimappatura del colore per la categoria predefinita. |
| [clear_remap_table(type)](#clear_remap_table_type_7) | Cancella la tabella di rimappatura del colore per una categoria specificata. |
| clear_threshold() | Cancella il valore di soglia per la categoria predefinita. |
| [clear_threshold(type)](#clear_threshold_type_8) | Cancella il valore di soglia per una categoria specificata. |
| [set_brush_remap_table(map)](#set_brush_remap_table_map_9) | Imposta la tabella di rimappatura del colore per la categoria pennello. |
| [set_color_key(color_low, color_high)](#set_color_key_color_low_color_high_10) | Imposta la chiave di colore per la categoria predefinita. |
| [set_color_key(color_low, color_high, type)](#set_color_key_color_low_color_high_type_11) | Imposta la chiave di colore (intervallo di trasparenza) per una categoria specificata. |
| [set_color_matrices(new_color_matrix, gray_matrix)](#set_color_matrices_new_color_matrix_gray_matrix_12) | Imposta la matrice di regolazione del colore e la matrice di regolazione della scala di grigi per la categoria predefinita. |
| [set_color_matrices(new_color_matrix, gray_matrix, flags)](#set_color_matrices_new_color_matrix_gray_matrix_flags_13) | Imposta la matrice di regolazione del colore e la matrice di regolazione della scala di grigi per la categoria predefinita. |
| [set_color_matrices(new_color_matrix, gray_matrix, mode, type)](#set_color_matrices_new_color_matrix_gray_matrix_mode_type_14) | Imposta la matrice di regolazione del colore e la matrice di regolazione della scala di grigi per una categoria specificata. |
| [set_color_matrix(new_color_matrix)](#set_color_matrix_new_color_matrix_15) | Imposta la matrice di regolazione del colore per la categoria predefinita. |
| [set_color_matrix(new_color_matrix, flags)](#set_color_matrix_new_color_matrix_flags_16) | Imposta la matrice di regolazione del colore per la categoria predefinita. |
| [set_color_matrix(new_color_matrix, mode, type)](#set_color_matrix_new_color_matrix_mode_type_17) | Imposta la matrice di regolazione del colore per una categoria specificata. |
| [set_gamma(gamma)](#set_gamma_gamma_18) | Imposta il valore gamma per la categoria predefinita. |
| [set_gamma(gamma, type)](#set_gamma_gamma_type_19) | Imposta il valore gamma per una categoria specificata. |
| set_no_op() | Disattiva la regolazione del colore per la categoria predefinita. |
| [set_no_op(type)](#set_no_op_type_20) | Disattiva la regolazione del colore per una categoria specificata. |
| [set_output_channel(flags)](#set_output_channel_flags_21) | Imposta il canale di output CMYK (ciano-magenta-giallo-nero) per la categoria predefinita. |
| [set_output_channel(flags, type)](#set_output_channel_flags_type_22) | Imposta il canale di output CMYK (ciano-magenta-giallo-nero) per una categoria specificata. |
| [set_output_channel_color_profile(color_profile_filename)](#set_output_channel_color_profile_color_profile_filename_23) | Imposta il file del profilo colore del canale di output per la categoria predefinita. |
| [set_output_channel_color_profile(color_profile_filename, type)](#set_output_channel_color_profile_color_profile_filename_type_24) | Imposta il file del profilo colore del canale di output per una categoria specificata. |
| [set_remap_table(map)](#set_remap_table_map_25) | Imposta la tabella di rimappatura del colore per la categoria predefinita. |
| [set_remap_table(map, type)](#set_remap_table_map_type_26) | Imposta la tabella di rimappatura del colore per una categoria specificata. |
| [set_threshold(threshold)](#set_threshold_threshold_27) | Imposta la soglia (intervallo di trasparenza) per la categoria predefinita. |
| [set_threshold(threshold, type)](#set_threshold_threshold_type_28) | Imposta la soglia (intervallo di trasparenza) per una categoria specificata. |
| [set_wrap_mode(mode)](#set_wrap_mode_mode_29) | Imposta la modalità di avvolgimento utilizzata per decidere come ripetere una texture su una forma, o ai bordi della forma. Una texture viene ripetuta su una forma per riempirla quando la texture è più piccola della forma da riempire. |
| [set_wrap_mode(mode, color)](#set_wrap_mode_mode_color_30) | Imposta la modalità di avvolgimento e il colore utilizzati per decidere come ripetere una texture su una forma, o ai bordi della forma. Una texture viene ripetuta su una forma per riempirla quando la texture è più piccola della forma da riempire. |
| [set_wrap_mode(mode, color, clamp)](#set_wrap_mode_mode_color_clamp_31) | Imposta la modalità di avvolgimento e il colore utilizzati per decidere come ripetere una texture su una forma, o ai bordi della forma. Una texture viene ripetuta su una forma per riempirla quando la texture è più piccola della forma da riempire. |


### Constructor: ImageAttributes() {#ImageAttributes__1}


```
 ImageAttributes() 
```

Inizializza una nuova istanza della classe ImageAttributes

### Method: clear_color_key(type) {#clear_color_key_type_1}


```
 clear_color_key(type) 
```

Cancella la chiave di colore (intervallo di trasparenza) per una categoria specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Un elemento di [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) che specifica la categoria per la quale la chiave di colore viene cancellata. |

### Method: clear_color_matrix(type) {#clear_color_matrix_type_2}


```
 clear_color_matrix(type) 
```

Cancella la matrice di regolazione del colore per una categoria specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Un elemento di [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) che specifica la categoria per la quale la matrice di regolazione del colore viene cancellata. |

### Method: clear_gamma(type) {#clear_gamma_type_3}


```
 clear_gamma(type) 
```

Disabilita la correzione gamma per una categoria specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Un elemento di [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) che specifica la categoria per la quale la correzione gamma è disabilitata. |

### Method: clear_no_op(type) {#clear_no_op_type_4}


```
 clear_no_op(type) 
```

Cancella l'impostazione NoOp per una categoria specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Un elemento di [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) che specifica la categoria per la quale l'impostazione NoOp viene cancellata. |

### Method: clear_output_channel(type) {#clear_output_channel_type_5}


```
 clear_output_channel(type) 
```

Cancella l'impostazione del canale di uscita (ciano-magenta-giallo-nero) per una categoria specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Un elemento di [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) che specifica la categoria per la quale l'impostazione del canale di output viene cancellata. |

### Method: clear_output_channel_color_profile(type) {#clear_output_channel_color_profile_type_6}


```
 clear_output_channel_color_profile(type) 
```

Cancella l'impostazione del profilo colore del canale di uscita per una categoria specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Un elemento di [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) che specifica la categoria per la quale l'impostazione del profilo del canale di output viene cancellata. |

### Method: clear_remap_table(type) {#clear_remap_table_type_7}


```
 clear_remap_table(type) 
```

Cancella la tabella di rimappatura del colore per una categoria specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Un elemento di [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) che specifica la categoria per la quale la tabella di rimappatura viene cancellata. |

### Method: clear_threshold(type) {#clear_threshold_type_8}


```
 clear_threshold(type) 
```

Cancella il valore di soglia per una categoria specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Un elemento di [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) che specifica la categoria per la quale la soglia viene cancellata. |

### Method: set_brush_remap_table(map) {#set_brush_remap_table_map_9}


```
 set_brush_remap_table(map) 
```

Imposta la tabella di rimappatura del colore per la categoria pennello.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| map | [ColorMap[]](/psd/python-net/aspose.psd/colormap) | Un array di oggetti [ColorMap](/psd/python-net/aspose.psd/colormap/). |

### Method: set_color_key(color_low, color_high) {#set_color_key_color_low_color_high_10}


```
 set_color_key(color_low, color_high) 
```

Imposta la chiave di colore per la categoria predefinita.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| color_low | [Color](/psd/python-net/aspose.psd/color) | Il valore basso della chiave di colore. |
| color_high | [Color](/psd/python-net/aspose.psd/color) | Il valore alto della chiave di colore. |

### Method: set_color_key(color_low, color_high, type) {#set_color_key_color_low_color_high_type_11}


```
 set_color_key(color_low, color_high, type) 
```

Imposta la chiave di colore (intervallo di trasparenza) per una categoria specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| color_low | [Color](/psd/python-net/aspose.psd/color) | Il valore basso della chiave di colore. |
| color_high | [Color](/psd/python-net/aspose.psd/color) | Il valore alto della chiave di colore. |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Un elemento di [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) che specifica la categoria per la quale la chiave di colore è impostata. |

### Method: set_color_matrices(new_color_matrix, gray_matrix) {#set_color_matrices_new_color_matrix_gray_matrix_12}


```
 set_color_matrices(new_color_matrix, gray_matrix) 
```

Imposta la matrice di regolazione del colore e la matrice di regolazione della scala di grigi per la categoria predefinita.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | La matrice di regolazione del colore. |
| gray_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | La matrice di regolazione della scala di grigi. |

### Method: set_color_matrices(new_color_matrix, gray_matrix, flags) {#set_color_matrices_new_color_matrix_gray_matrix_flags_13}


```
 set_color_matrices(new_color_matrix, gray_matrix, flags) 
```

Imposta la matrice di regolazione del colore e la matrice di regolazione della scala di grigi per la categoria predefinita.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | La matrice di regolazione del colore. |
| gray_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | La matrice di regolazione della scala di grigi. |
| flags | [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag) | Un elemento di [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag/) che specifica il tipo di immagine e colore che saranno influenzati dalle matrici di regolazione del colore e della scala di grigi. |

### Method: set_color_matrices(new_color_matrix, gray_matrix, mode, type) {#set_color_matrices_new_color_matrix_gray_matrix_mode_type_14}


```
 set_color_matrices(new_color_matrix, gray_matrix, mode, type) 
```

Imposta la matrice di regolazione del colore e la matrice di regolazione della scala di grigi per una categoria specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | La matrice di regolazione del colore. |
| gray_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | La matrice di regolazione della scala di grigi. |
| mode | [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag) | Un elemento di [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag/) che specifica il tipo di immagine e colore che saranno influenzati dalle matrici di regolazione del colore e della scala di grigi. |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Un elemento di [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) che specifica la categoria per la quale le matrici di regolazione del colore e della scala di grigi sono impostate. |

### Method: set_color_matrix(new_color_matrix) {#set_color_matrix_new_color_matrix_15}


```
 set_color_matrix(new_color_matrix) 
```

Imposta la matrice di regolazione del colore per la categoria predefinita.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | La matrice di regolazione del colore. |

### Method: set_color_matrix(new_color_matrix, flags) {#set_color_matrix_new_color_matrix_flags_16}


```
 set_color_matrix(new_color_matrix, flags) 
```

Imposta la matrice di regolazione del colore per la categoria predefinita.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | La matrice di regolazione del colore. |
| flags | [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag) | Un elemento di [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag/) che specifica il tipo di immagine e colore che saranno influenzati dalla matrice di regolazione del colore. |

### Method: set_color_matrix(new_color_matrix, mode, type) {#set_color_matrix_new_color_matrix_mode_type_17}


```
 set_color_matrix(new_color_matrix, mode, type) 
```

Imposta la matrice di regolazione del colore per una categoria specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | La matrice di regolazione del colore. |
| mode | [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag) | Un elemento di [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag/) che specifica il tipo di immagine e colore che saranno influenzati dalla matrice di regolazione del colore. |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Un elemento di [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) che specifica la categoria per la quale la matrice di regolazione del colore è impostata. |

### Method: set_gamma(gamma) {#set_gamma_gamma_18}


```
 set_gamma(gamma) 
```

Imposta il valore gamma per la categoria predefinita.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| gamma | float | Il valore di correzione gamma. |

### Method: set_gamma(gamma, type) {#set_gamma_gamma_type_19}


```
 set_gamma(gamma, type) 
```

Imposta il valore gamma per una categoria specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| gamma | float | Il valore di correzione gamma. |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Un elemento dell'enumerazione [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) che specifica la categoria per la quale il valore gamma è impostato. |

### Method: set_no_op(type) {#set_no_op_type_20}


```
 set_no_op(type) 
```

Disattiva la regolazione del colore per una categoria specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Un elemento di [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) che specifica la categoria per la quale la correzione colore è disattivata. |

### Method: set_output_channel(flags) {#set_output_channel_flags_21}


```
 set_output_channel(flags) 
```

Imposta il canale di output CMYK (ciano-magenta-giallo-nero) per la categoria predefinita.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| flags | [ColorChannelFlag](/psd/python-net/aspose.psd/colorchannelflag) | Un elemento di [ColorChannelFlag](/psd/python-net/aspose.psd/colorchannelflag/) che specifica il canale di output. |

### Method: set_output_channel(flags, type) {#set_output_channel_flags_type_22}


```
 set_output_channel(flags, type) 
```

Imposta il canale di output CMYK (ciano-magenta-giallo-nero) per una categoria specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| flags | [ColorChannelFlag](/psd/python-net/aspose.psd/colorchannelflag) | Un elemento di [ColorChannelFlag](/psd/python-net/aspose.psd/colorchannelflag/) che specifica il canale di output. |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Un elemento di [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) che specifica la categoria per la quale il canale di output è impostato. |

### Method: set_output_channel_color_profile(color_profile_filename) {#set_output_channel_color_profile_color_profile_filename_23}


```
 set_output_channel_color_profile(color_profile_filename) 
```

Imposta il file del profilo colore del canale di output per la categoria predefinita.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| color_profile_filename | string | Il percorso di un file di profilo colore. Se il file di profilo colore si trova nella directory %SystemRoot%\System32\Spool\Drivers\Color, questo parametro può essere il nome del file. Altrimenti, questo parametro deve contenere il percorso completo. |

### Method: set_output_channel_color_profile(color_profile_filename, type) {#set_output_channel_color_profile_color_profile_filename_type_24}


```
 set_output_channel_color_profile(color_profile_filename, type) 
```

Imposta il file del profilo colore del canale di output per una categoria specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| color_profile_filename | string | Il percorso di un file di profilo colore. Se il file di profilo colore si trova nella directory %SystemRoot%\System32\Spool\Drivers\Color, questo parametro può essere il nome del file. Altrimenti, questo parametro deve contenere il percorso completo. |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Un elemento di [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) che specifica la categoria per la quale il file di profilo colore del canale di output è impostato. |

### Method: set_remap_table(map) {#set_remap_table_map_25}


```
 set_remap_table(map) 
```

Imposta la tabella di rimappatura del colore per la categoria predefinita.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| map | [ColorMap[]](/psd/python-net/aspose.psd/colormap) | Un array di coppie di colore di tipo [ColorMap](/psd/python-net/aspose.psd/colormap/). Ogni coppia di colore contiene un colore esistente (il primo valore) e il colore a cui verrà mappato (il secondo valore). |

### Method: set_remap_table(map, type) {#set_remap_table_map_type_26}


```
 set_remap_table(map, type) 
```

Imposta la tabella di rimappatura del colore per una categoria specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| map | [ColorMap[]](/psd/python-net/aspose.psd/colormap) | Un array di coppie di colore di tipo [ColorMap](/psd/python-net/aspose.psd/colormap/). Ogni coppia di colore contiene un colore esistente (il primo valore) e il colore a cui verrà mappato (il secondo valore). |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Un elemento di [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) che specifica la categoria per la quale la tabella di rimappatura colore è impostata. |

### Method: set_threshold(threshold) {#set_threshold_threshold_27}


```
 set_threshold(threshold) 
```

Imposta la soglia (intervallo di trasparenza) per la categoria predefinita.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| threshold | float | Un numero reale che specifica il valore della soglia. |

### Method: set_threshold(threshold, type) {#set_threshold_threshold_type_28}


```
 set_threshold(threshold, type) 
```

Imposta la soglia (intervallo di trasparenza) per una categoria specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| threshold | float | Un valore di soglia da 0,0 a 1,0 utilizzato come punto di interruzione per ordinare i colori che saranno mappati a un valore massimo o minimo. |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | Un elemento di [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) che specifica la categoria per la quale è impostata la soglia di colore. |

### Method: set_wrap_mode(mode) {#set_wrap_mode_mode_29}


```
 set_wrap_mode(mode) 
```

Imposta la modalità di avvolgimento utilizzata per decidere come ripetere una texture su una forma, o ai bordi della forma. Una texture viene ripetuta su una forma per riempirla quando la texture è più piccola della forma da riempire.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Un elemento di [WrapMode](/psd/python-net/aspose.psd/wrapmode/) che specifica come le copie ripetute di un'immagine vengono utilizzate per riempire un'area. |

### Method: set_wrap_mode(mode, color) {#set_wrap_mode_mode_color_30}


```
 set_wrap_mode(mode, color) 
```

Imposta la modalità di avvolgimento e il colore utilizzati per decidere come ripetere una texture su una forma, o ai bordi della forma. Una texture viene ripetuta su una forma per riempirla quando la texture è più piccola della forma da riempire.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Un elemento di [WrapMode](/psd/python-net/aspose.psd/wrapmode/) che specifica come le copie ripetute di un'immagine vengono utilizzate per riempire un'area. |
| color | [Color](/psd/python-net/aspose.psd/color) | Un oggetto [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) che specifica il colore dei pixel al di fuori di un'immagine renderizzata. Questo colore è visibile se il parametro mode è impostato su [WrapMode.CLAMP](/psd/python-net/aspose.psd/wrapmode/) e il rettangolo sorgente passato a DrawImage è più grande dell'immagine stessa. |

### Method: set_wrap_mode(mode, color, clamp) {#set_wrap_mode_mode_color_clamp_31}


```
 set_wrap_mode(mode, color, clamp) 
```

Imposta la modalità di avvolgimento e il colore utilizzati per decidere come ripetere una texture su una forma, o ai bordi della forma. Una texture viene ripetuta su una forma per riempirla quando la texture è più piccola della forma da riempire.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Un elemento di [WrapMode](/psd/python-net/aspose.psd/wrapmode/) che specifica come le copie ripetute di un'immagine vengono utilizzate per riempire un'area. |
| color | [Color](/psd/python-net/aspose.psd/color) | Un oggetto colore che specifica il colore dei pixel al di fuori di un'immagine renderizzata. Questo colore è visibile se il parametro mode è impostato su [WrapMode.CLAMP](/psd/python-net/aspose.psd/wrapmode/) e il rettangolo sorgente passato a DrawImage è più grande dell'immagine stessa. |
| blocco | bool | Questo parametro non ha effetto. Impostalo su false. |

