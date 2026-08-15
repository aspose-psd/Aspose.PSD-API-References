---
title: "Clase ColorComponent"
type: docs
weight: 10
url: /es/python-net/aspose.psd.fileformats.psd.core.rawcolor/colorcomponent/
---

**Summary:** Color component is an abstraction over Channel Value and Channel Value.<br/>            Any color is composed from an array of ColorComponent

**Module:** [aspose.psd.fileformats.psd.core.rawcolor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/)

**Full Name:** aspose.psd.fileformats.psd.core.rawcolor.ColorComponent

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [ColorComponent(bit_depth, full_name)](#ColorComponent_bit_depth_full_name_1) | Inicializa una nueva instancia de la clase [ColorComponent](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/colorcomponent/).<br/>            Por favor, verifica |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| bit_depth | byte | r | Obtiene la profundidad de bits del Componente/Canal de Color |
| descripción | string | r | Obtiene la descripción del Componente de Color |
| nombre_completo | string | r | Obtiene el nombre completo del componente de color con nombre y descripción separada por espacios |
| name | string | r | Obtiene el nombre del componente de color. |
| permitted_full_names [static] | string | r | Obtiene los nombres completos permitidos. |
| value | ulong | r/w | Obtiene o establece el valor. <br/>            Tenga en cuenta que, si intenta establecer un valor que sea mayor que <br/>            lo posible almacenar en la profundidad de bits actual, se producirá una excepción |


### Constructor: ColorComponent(bit_depth, full_name) {#ColorComponent_bit_depth_full_name_1}


```
 ColorComponent(bit_depth, full_name) 
```

Inicializa una nueva instancia de la clase [ColorComponent](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/colorcomponent/).<br/>            Por favor, verifica

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| bit_depth | byte | La profundidad de bits. |
| nombre_completo | string | El nombre completo. |

