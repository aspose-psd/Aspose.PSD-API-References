---
title: Image.Resize
second_title: .NET API संदर्भ के लिए Aspose.PSD
description: Image तरक. छव क आकर बदलत है डफ़ल्टLeftTopToLeftTopप्रयग कय जत है.
type: docs
weight: 190
url: /hi/net/aspose.psd/image/resize/
---
## Resize(int, int) {#resize}

छवि का आकार बदलता है। डिफ़ॉल्टLeftTopToLeftTopप्रयोग किया जाता है.

```csharp
public void Resize(int newWidth, int newHeight)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| newWidth | Int32 | नई चौड़ाई. |
| newHeight | Int32 | नई ऊंचाई. |

### उदाहरण

निम्न उदाहरण प्रदर्शित करता है कि कैसे PSD छवि का आकार बदलना है और परिणाम हम Aspose.PSD द्वारा प्राप्त करते हैं

```csharp
[C#]

string sourceFileName = "1.psd";
string exportPathPsd = "ResizeTest.psd";
string exportPathPng = "ResizeTest.png";

using (RasterImage image = Image.Load(sourceFileName) as RasterImage)
{
    image.Resize(190, 143);
    image.Save(exportPathPsd, new PsdOptions());
    image.Save(exportPathPng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### यह सभी देखें

* class [Image](../)
* नाम स्थान [Aspose.PSD](../../image/)
* सभा [Aspose.PSD](../../../)

---

## Resize(int, int, ResizeType) {#resize_2}

छवि का आकार बदलता है।

```csharp
public abstract void Resize(int newWidth, int newHeight, ResizeType resizeType)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| newWidth | Int32 | नई चौड़ाई. |
| newHeight | Int32 | नई ऊंचाई. |
| resizeType | ResizeType | आकार बदलने का प्रकार। |

### यह सभी देखें

* enum [ResizeType](../../resizetype/)
* class [Image](../)
* नाम स्थान [Aspose.PSD](../../image/)
* सभा [Aspose.PSD](../../../)

---

## Resize(int, int, ImageResizeSettings) {#resize_1}

छवि का आकार बदलता है।

```csharp
public abstract void Resize(int newWidth, int newHeight, ImageResizeSettings settings)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| newWidth | Int32 | नई चौड़ाई। |
| newHeight | Int32 | नई ऊंचाई। |
| settings | ImageResizeSettings | आकार बदलें सेटिंग्स। |

### यह सभी देखें

* class [ImageResizeSettings](../../imageresizesettings/)
* class [Image](../)
* नाम स्थान [Aspose.PSD](../../image/)
* सभा [Aspose.PSD](../../../)


