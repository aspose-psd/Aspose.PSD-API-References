---
title: Graphics.DrawString
second_title: Referencia de API de Aspose.PSD para .NET
description: Graphics método. Dibuja la cadena de texto especificada en la ubicación especificada con elBrush yFont objetos.
type: docs
weight: 320
url: /es/net/aspose.psd/graphics/drawstring/
---
## DrawString(string, Font, Brush, float, float) {#drawstring_4}

Dibuja la cadena de texto especificada en la ubicación especificada con el[`Brush`](../../brush/) y[`Font`](../../font/) objetos.

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| s | String | Cuerda para dibujar. |
| font | Font | [`Font`](../../font/) que define el formato de texto de la cadena. |
| brush | Brush | [`Brush`](../../brush/) que determina el color y la textura del texto dibujado. |
| x | Single | La coordenada x de la esquina superior izquierda del texto dibujado. |
| y | Single | La coordenada y de la esquina superior izquierda del texto dibujado. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *brush* es nulo. -o- *s* es nulo. |

### Ver también

* class [Font](../../font/)
* class [Brush](../../brush/)
* class [Graphics](../)
* espacio de nombres [Aspose.PSD](../../graphics/)
* asamblea [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, PointF) {#drawstring}

Dibuja la cadena de texto especificada en la ubicación especificada con el[`Brush`](../../brush/) y[`Font`](../../font/) objetos.

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| s | String | Cuerda para dibujar. |
| font | Font | [`Font`](../../font/) que define el formato de texto de la cadena. |
| brush | Brush | [`Brush`](../../brush/) que determina el color y la textura del texto dibujado. |
| point | PointF | [`PointF`](../../pointf/) estructura que especifica la esquina superior izquierda del texto dibujado. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *brush* es nulo. -o- *s* es nulo. |

### Ejemplos

Este ejemplo demuestra el uso de la clase Font y SolidBrush para dibujar cadenas en la superficie de la imagen. El ejemplo crea una nueva imagen y dibuja formas usando Figuras y GraphicsPath

```csharp
[C#]

//Crea una instancia de Imagen
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Crea e inicializa una instancia de la clase Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    // Limpia la superficie gráfica
    graphics.Clear(Color.Wheat);

    //Crea una instancia de Font
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    //Crear una instancia de SolidBrush con color rojo
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    // Dibujar una cadena
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // crear opciones de exportación.
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // guarda todos los cambios
    image.Save("C:\\temp\\output.gif", options);
}
```

### Ver también

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* espacio de nombres [Aspose.PSD](../../graphics/)
* asamblea [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, float, float, StringFormat) {#drawstring_5}

Dibuja la cadena de texto especificada en la ubicación especificada con el[`Brush`](../../brush/) y[`Font`](../../font/) objetos usando los atributos de formato del especificado[`StringFormat`](../../stringformat/) .

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y, StringFormat format)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| s | String | Cuerda para dibujar. |
| font | Font | [`Font`](../../font/) que define el formato de texto de la cadena. |
| brush | Brush | [`Brush`](../../brush/) que determina el color y la textura del texto dibujado. |
| x | Single | La coordenada x de la esquina superior izquierda del texto dibujado. |
| y | Single | La coordenada y de la esquina superior izquierda del texto dibujado. |
| format | StringFormat | [`StringFormat`](../../stringformat/) que especifica los atributos de formato, como el espaciado entre líneas y la alineación, que se aplican al texto dibujado. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *brush* es nulo. -o- *s* es nulo. |

### Ver también

* class [Font](../../font/)
* class [Brush](../../brush/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* espacio de nombres [Aspose.PSD](../../graphics/)
* asamblea [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, PointF, StringFormat) {#drawstring_1}

Dibuja la cadena de texto especificada en la ubicación especificada con el[`Brush`](../../brush/) y[`Font`](../../font/) objetos usando los atributos de formato del especificado[`StringFormat`](../../stringformat/) .

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point, StringFormat format)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| s | String | Cuerda para dibujar. |
| font | Font | [`Font`](../../font/) que define el formato de texto de la cadena. |
| brush | Brush | [`Brush`](../../brush/) que determina el color y la textura del texto dibujado. |
| point | PointF | [`PointF`](../../pointf/) estructura que especifica la esquina superior izquierda del texto dibujado. |
| format | StringFormat | [`StringFormat`](../../stringformat/) que especifica los atributos de formato, como el espaciado entre líneas y la alineación, que se aplican al texto dibujado. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *brush* es nulo. -o- *s* es nulo. |

### Ver también

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* espacio de nombres [Aspose.PSD](../../graphics/)
* asamblea [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, RectangleF) {#drawstring_2}

Dibuja la cadena de texto especificada en el rectángulo especificado con el[`Brush`](../../brush/) y[`Font`](../../font/) objetos.

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| s | String | Cuerda para dibujar. |
| font | Font | [`Font`](../../font/) que define el formato de texto de la cadena. |
| brush | Brush | [`Brush`](../../brush/) que determina el color y la textura del texto dibujado. |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef/) estructura que especifica la ubicación del texto dibujado. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *brush* es nulo. -o- *s* es nulo. |

### Ver también

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* espacio de nombres [Aspose.PSD](../../graphics/)
* asamblea [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, RectangleF, StringFormat) {#drawstring_3}

Dibuja la cadena de texto especificada en el rectángulo especificado con el[`Brush`](../../brush/) y[`Font`](../../font/) objetos usando los atributos de formato del especificado[`StringFormat`](../../stringformat/) .

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle, 
    StringFormat format)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| s | String | Cuerda para dibujar. |
| font | Font | [`Font`](../../font/) que define el formato de texto de la cadena. |
| brush | Brush | [`Brush`](../../brush/) que determina el color y la textura del texto dibujado. |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef/) estructura que especifica la ubicación del texto dibujado. |
| format | StringFormat | [`StringFormat`](../../stringformat/) que especifica los atributos de formato, como el espaciado entre líneas y la alineación, que se aplican al texto dibujado. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *brush* es nulo. -o- *s* es nulo. -o- *brush* es nulo. |

### Ver también

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* espacio de nombres [Aspose.PSD](../../graphics/)
* asamblea [Aspose.PSD](../../../)


