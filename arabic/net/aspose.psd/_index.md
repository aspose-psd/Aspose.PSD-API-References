---
title: "Aspose.PSD"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "مساحة الاسم هي النواة للمساحات المتداخلة وأبسط الكائنات المستخدمة في معالجة Aspose.PSD"
type: docs
weight: 10
url: /ar/net/aspose.psd/
---
{{< psd/tize >}}
مساحة الاسم هي الأساس لمساحات الأسماء المتداخلة وأبسط الكائنات المستخدمة في معالجة Aspose.PSD.

## الفئات

| فئة | الوصف |
| --- | --- |
| [AggregateException](./aggregateexception/) | يجمع استثناءات متعددة. |
| [Blend](./blend/) | يحدد نمط المزج. لا يمكن وراثة هذه الفئة. |
| [Brush](./brush/) | فئة الفرشاة الأساسية. |
| [BuildVersionInfo](./buildversioninfo/) | يحتوي على معلومات إصدار البناء الحالي. |
| [Cache](./cache/) | يحتوي على إعدادات الذاكرة المؤقتة. |
| [CmykColorHelper](./cmykcolorhelper/) | طرق مساعدة للعمل مع لون CMYK المقدم كقيمة عدد صحيح موقعة 32-بت. توفر واجهة برمجة تطبيقات مماثلة للهيكل [`CmykColor`](../aspose.psd/cmykcolor/). إنها أخف وزنًا لأن لون CMYK يُقدم كـ Int32 فقط بدلاً من هيكل يحتوي على حقول داخلية. يرجى تفضيل استخدام الطرق الثابتة لهذه الفئة عندما يكون ذلك ممكنًا بدلاً من الهيكل المهمل [`CmykColor`](../aspose.psd/cmykcolor/). |
| [ColorBlend](./colorblend/) | يحدد مصفوفات من الألوان والمواقع المستخدمة في استيفاء مزج الألوان في تدرج متعدد الألوان. لا يمكن وراثة هذه الفئة. |
| [ColorMap](./colormap/) | يحدد خريطة لتحويل الألوان. عدة طرق في فئة [`ImageAttributes`](../aspose.psd/imageattributes/) تعدل ألوان الصورة باستخدام جدول إعادة تعيين الألوان، وهو مصفوفة من هياكل [`ColorMap`](../aspose.psd/colormap/). غير قابل للوراثة. |
| [ColorMatrix](./colormatrix/) | يحدد مصفوفة 5 × 5 تحتوي على إحداثيات مساحة RGBA. عدة طرق في فئة [`ImageAttributes`](../aspose.psd/imageattributes/) تعدل ألوان الصورة باستخدام مصفوفة ألوان. لا يمكن وراثة هذه الفئة. |
| [ColorPalette](./colorpalette/) | يحدد مصفوفة من الألوان التي تشكل لوحة ألوان. الألوان هي ألوان ARGB 32-بت. غير قابل للوراثة. |
| [ColorPaletteHelper](./colorpalettehelper/) | فئة مساعدة لتعديل لوحات الألوان. |
| [ColorTranslator](./colortranslator/) | يترجم الألوان إلى ومن هياكل لون GDI+. لا يمكن وراثة هذه الفئة. |
| [CompositeException](./compositeexception/) | الاستثناء المركب |
| [CustomLineCap](./customlinecap/) | يحتوي على غطاء خط مخصص معرف من قبل المستخدم. |
| [DataStreamSupporter](./datastreamsupporter/) | حاوية تدفق البيانات. |
| [DisposableObject](./disposableobject/) | يمثل كائنًا قابلًا للتصرف. |
| [Figure](./figure/) | الشكل. حاوية للأشكال. |
| [FileStreamContainer](./filestreamcontainer/) | مساعد لمعالجة تدفق الملفات. |
| [Font](./font/) | يحدد تنسيقًا معينًا للنص، بما في ذلك نوع الخط، الحجم، وسمات النمط. لا يمكن توريث هذه الفئة. |
| [FontSettings](./fontsettings/) | إعدادات خط عارض صيغ المتجهات العامة لـ PSD. |
| [Graphics](./graphics/) | يمثل الرسومات وفقًا لمحرك الرسومات المستخدم في التجميع الحالي. |
| [GraphicsPath](./graphicspath/) | يمثل سلسلة من الخطوط والمنحنيات المتصلة. لا يمكن توريث هذه الفئة. |
| [Image](./image/) | الصورة هي الفئة الأساسية لجميع أنواع الصور. |
| [ImageAttributes](./imageattributes/) | كائن [`ImageAttributes`](../aspose.psd/imageattributes/) يحتوي على معلومات حول كيفية تعديل ألوان البت ماب وملف التعريف أثناء العرض. كائن [`ImageAttributes`](../aspose.psd/imageattributes/) يحتفظ بعدة إعدادات لتعديل اللون، بما في ذلك مصفوفات تعديل اللون، مصفوفات تعديل التدرج الرمادي، قيم تصحيح غاما، جداول خريطة الألوان، وقيم عتبة اللون. أثناء العرض، يمكن تصحيح الألوان، تعتيمها، إضاءتها، وإزالتها. لتطبيق هذه التعديلات، قم بتهيئة كائن [`ImageAttributes`](../aspose.psd/imageattributes/) ومرّر مسار ذلك الكائن (إلى جانب مسار [`Image`](../aspose.psd/image/)) إلى طريقة DrawImage method. |
| [ImageCreatorsRegistry](./imagecreatorsregistry/) | يمثل سجل منشئي الصور. |
| [ImageExportersRegistry](./imageexportersregistry/) | يمثل سجل مصدري الصور. |
| [ImageLoadersRegistry](./imageloadersregistry/) | يمثل سجل محملي الصور. |
| [ImageOptionsBase](./imageoptionsbase/) | خيارات الصورة الأساسية. |
| [ImageResizeSettings](./imageresizesettings/) | فئة إعدادات تغيير حجم الصورة |
| [IntRange](./intrange/) | فئة لتمثيل تسلسل العناصر |
| [License](./license/) | يوفر طرقًا لترخيص المكوّن. |
| [LoadOptions](./loadoptions/) | يمثل خيارات التحميل. |
| [Matrix](./matrix/) | يستبدل مصفوفة GDI+. |
| [Metered](./metered/) | يوفر طرقًا لتعيين المفتاح المقنن. |
| [NonGenericDictionary](./nongenericdictionary/) | يمثل قاموسًا غير عام. |
| [NonGenericList](./nongenericlist/) | قائمة غير عامة من الكائنات |
| [ObjectWithBounds](./objectwithbounds/) | الكائن الذي له حدود. |
| [OpenTypeFontsCache](./opentypefontscache/) | ذاكرة تخزين مؤقت لخطوط OpenType المثبتة في النظام. |
| [Pen](./pen/) | يحدد كائنًا يُستخدم لرسم الخطوط والمنحنيات والأشكال. |
| [PixelDataFormat](./pixeldataformat/) | تنسيق بيانات البكسل. هذا كائن غير قابل للتغيير. |
| [PixelsData](./pixelsdata/) | الفئة لتخزين بيانات بكسلات الصورة وحدودها. |
| [PluginLicenseException](./pluginlicenseexception/) | استثناء لرخصة الإضافة |
| [ProgressEventHandler](./progresseventhandler/) | مرجع دالة معالج حدث التقدم |
| [RasterCachedImage](./rastercachedimage/) | يمثل صورة نقطية تدعم عمليات الرسومات النقطية. تقوم هذه الصورة بتخزين بيانات البكسل مؤقتًا عند الحاجة. |
| [RasterImage](./rasterimage/) | يمثل صورة نقطية تدعم عمليات الرسومات النقطية. |
| [RawDataSettings](./rawdatasettings/) | إعدادات البيانات الخام |
| [Region](./region/) | يصف داخل الشكل الرسومي المكوّن من مستطيلات ومسارات. لا يمكن وراثة هذه الفئة. |
| [ResolutionSetting](./resolutionsetting/) | إعداد الدقة لخيارات حفظ الصورة. |
| [Shape](./shape/) | الشكل. مجموعة مستمرة من النقاط متصلة باستخدام قاعدة محددة. |
| [ShapeSegment](./shapesegment/) | يمثل مقطع الشكل. المقطع هو خط أو منحنى يربط نقطتين. |
| [Source](./source/) | المصدر يُستخدم لاحتواء جميع المعلومات ذات الصلة لأنبوب الكائن. |
| [SplitStreamContainer](./splitstreamcontainer/) | يمثل حاوية تدفق مقسمة تحتوي على التدفق وتوفر روتينات معالجة التدفق. |
| [StreamContainer](./streamcontainer/) | يمثل حاوية تدفق تحتوي على التدفق وتوفر روتينات معالجة التدفق. |
| [StringFormat](./stringformat/) | يحتوي على معلومات تخطيط النص (مثل المحاذاة، الاتجاه وإيقافات الجدولة) وتعديلات العرض (مثل إدراج الحذف والاستبدال الرقمي الوطني) وميزات OpenType. لا يمكن وراثة هذه الفئة. |
| [TransparencySupporter](./transparencysupporter/) | الكائن الداعم للشفافية. |
| [VectorImage](./vectorimage/) | الصورة المتجهة هي الفئة الأساسية لجميع أنواع الصور المتجهة. |
## Structures

| الهيكل | الوصف |
| --- | --- |
| [CmykColor](./cmykcolor/) | لون CMYK للبكسل. |
| [Color](./color/) | لون البكسل. |
| [Point](./point/) | يمثل زوجًا مرتبًا من إحداثيات x و y الصحيحة التي تحدد نقطة في مستوى ثنائي الأبعاد. |
| [PointF](./pointf/) | يمثل زوجًا مرتبًا من إحداثيات x و y ذات الفاصلة العائمة التي تحدد نقطة في مستوى ثنائي الأبعاد. |
| [Rectangle](./rectangle/) | يخزن مجموعة من أربعة أعداد صحيحة تمثل موقع وحجم المستطيل. |
| [RectangleF](./rectanglef/) | يخزن مجموعة من أربعة أعداد عائمة تمثل موقع وحجم المستطيل. |
| [Size](./size/) | يمثل الحجم. |
| [SizeF](./sizef/) | يخزن زوجًا مرتبًا من الأعداد العائمة، عادةً العرض والارتفاع لمستطيل. |
## الواجهات

| الواجهة | الوصف |
| --- | --- |
| [IAdvancedBufferProcessor](./iadvancedbufferprocessor/) | معالج المخزن المؤقت المتقدم. |
| [IBufferProcessor](./ibufferprocessor/) | معالج المخزن المؤقت. |
| [IColorConverter](./icolorconverter/) | محول اللون. |
| [IColorPalette](./icolorpalette/) | واجهة لوحة الألوان. |
| [IImageCreator](./iimagecreator/) | منشئ الصورة. |
| [IImageCreatorDescriptor](./iimagecreatordescriptor/) | وصف image creator descriptor الذي يحدد خصائص المنشئ. يُستخدم creator descriptor لتجاوز الحاجة إلى احتواء كل مثال من منشئ الصورة في الذاكرة ومشكلات تعدد الخيوط. |
| [IImageDescriptor](./iimagedescriptor/) | وصف image descriptor. يحتوي على الخصائص والطرق الأساسية لجميع أنواع image descriptor الأخرى. |
| [IImageExporter](./iimageexporter/) | مصدّر image exporter. يمكنه تصدير البيانات من تنسيق Aspose.PSD الداخلي إلى تنسيق بيانات محدد. |
| [IImageExporterDescriptor](./iimageexporterdescriptor/) | يمثل image exporter descriptor. يُستخدم exporter descriptor لتجاوز الحاجة إلى احتواء كل مثال من المصدّر في الذاكرة ومشكلات تعدد الخيوط. |
| [IImageLoader](./iimageloader/) | محمل image loader. |
| [IImageLoaderDescriptor](./iimageloaderdescriptor/) | image loader descriptor الذي يحدد خصائص المحمل. يُستخدم loader descriptor لتجاوز الحاجة إلى احتواء كل مثال من image loader في الذاكرة ومشكلات تعدد الخيوط. |
| [IIndexedColorConverter](./iindexedcolorconverter/) | color converter لتنسيقات الصورة المفهرسة. |
| [IKeyedObject](./ikeyedobject/) | يمثل interface للكائنات ذات المفاتيح. |
| [IObjectWithBounds](./iobjectwithbounds/) | يمثل كائنًا بحدود. |
| [IOrderedShape](./iorderedshape/) | يمثل شكلًا مرتبًا. الشكل المرتب هو مجموعة مستمرة من النقاط لها نقطة بداية ونقطة نهاية. المجموعة المستمرة من النقاط متصلة باستخدام قاعدة محددة. |
| [IPartialArgb32PixelLoader](./ipartialargb32pixelloader/) | يتوافق مع بكسلات ARGB 32-بت التي تم تحميلها جزئيًا. |
| [IPartialArgb64PixelLoader](./ipartialargb64pixelloader/) | محمل بكسلات ARGB 64-بت. |
| [IPartialPixelLoader](./ipartialpixelloader/) | يتوافق مع البكسلات التي تم تحميلها جزئيًا. |
| [IPartialRawDataLoader](./ipartialrawdataloader/) | محمل البيانات الجزئية. |
| [IPsdColorPalette](./ipsdcolorpalette/) | لوحة ألوان pasd |
| [IRasterImageArgb32PixelLoader](./irasterimageargb32pixelloader/) | محمل بكسل ARGB 32-بت raster image. |
| [IRasterImagePixelLoader](./irasterimagepixelloader/) | محمل بكسل raster image. |
| [IRasterImageRawDataLoader](./irasterimagerawdataloader/) | محمل بيانات الصورة النقطية الخام. |
## تعداد

| تعداد | الوصف |
| --- | --- |
| [CacheType](./cachetype/) | يحدد نوع الذاكرة المؤقتة للاستخدام. |
| [CharacterSet](./characterset/) | يمثل مجموعة الأحرف المستخدمة. |
| [ColorAdjustType](./coloradjusttype/) | يحدد أي الكائنات تستخدم معلومات تعديل اللون. |
| [ColorChannelFlag](./colorchannelflag/) | يحدد القنوات الفردية في مساحة اللون CMYK (سماوي، أرجواني، أصفر، أسود). تُستخدم هذه التعدادات بواسطة طرق SetOutputChannel. |
| [ColorCompareMethod](./colorcomparemethod/) | طريقة مقارنة اللون لضبط إلى أقرب جار |
| [ColorMatrixFlag](./colormatrixflag/) | يحدد أنواع الصور والألوان التي سيتأثر بها إعدادات تعديل اللون وتدرج الرمادي لكائن [`ImageAttributes`](../aspose.psd/imageattributes/). |
| [ColorQuantizationMethod](./colorquantizationmethod/) | طرق تكميم الألوان |
| [CompositingQuality](./compositingquality/) | يحدد مستوى الجودة للاستخدام أثناء التركيب. |
| [DashCap](./dashcap/) | يحدد نوع الشكل الرسومي لاستخدامه على طرفي كل شرطة في خط متقطع. |
| [DashStyle](./dashstyle/) | يحدد نمط الخطوط المتقطعة المرسومة باستخدام كائن [`Pen`](../aspose.psd/pen/). |
| [DataRecoveryMode](./datarecoverymode/) | وضع استعادة البيانات. |
| [DitheringMethod](./ditheringmethod/) | طريقة التدرج. |
| [DitheringMethods](./ditheringmethods/) | طرق التدرج المستخدمة للتحكم في تحويل اللون. |
| [FileFormat](./fileformat/) | أحد صيغ ملفات PSD المدعومة. |
| [FillMode](./fillmode/) | يحدد كيفية تعبئة داخل مسار مغلق. |
| [FontStyle](./fontstyle/) | يحدد معلومات النمط المطبقة على النص. |
| [GraphicsUnit](./graphicsunit/) | يحدد وحدة القياس للبيانات المعطاة. |
| [HatchStyle](./hatchstyle/) | يحدد الأنماط المختلفة المتاحة لكائنات [`HatchBrush`](../aspose.psd.brushes/hatchbrush/). |
| [HotkeyPrefix](./hotkeyprefix/) | يحدد نوع العرض لبادئات مفاتيح الاختصار المتعلقة بالنص. |
| [ImageFilterType](./imagefiltertype/) | مرشحات الصورة للاستخدام |
| [InterpolationMode](./interpolationmode/) | التعداد [`InterpolationMode`](../aspose.psd/interpolationmode/) يحدد الخوارزمية المستخدمة عند تحجيم أو تدوير الصور. |
| [KnownColor](./knowncolor/) | يحدد ألوان النظام المعروفة. |
| [LineCap](./linecap/) | يحدد أنماط القمم المتاحة التي يمكن لكائن [`Pen`](../aspose.psd/pen/) إنهاء الخط بها. |
| [LineJoin](./linejoin/) | يحدد كيفية ربط مقاطع الخط أو المنحنى المتتالية في شكل (مسار فرعي) موجود داخل كائن [`GraphicsPath`](../aspose.psd/graphicspath/). |
| [MatrixOrder](./matrixorder/) | يحدد ترتيب عمليات تحويل المصفوفة. |
| [PdfComplianceVersion](./pdfcomplianceversion/) | يحدد مستوى توافق PDF لملف الإخراج. |
| [PenAlignment](./penalignment/) | يحدد محاذاة كائن [`Pen`](../aspose.psd/pen/) بالنسبة إلى الخط النظري ذي العرض الصفري. |
| [PenType](./pentype/) | يحدد نوع التعبئة التي يستخدمها كائن [`Pen`](../aspose.psd/pen/) لملء الخطوط. |
| [PixelFormat](./pixelformat/) | المعنى الفعلي لتنسيق بيانات البكسل. |
| [ResizeType](./resizetype/) | يحدد نوع تغيير الحجم. |
| [ResolutionUnit](./resolutionunit/) | تعداد وحدة الدقة. |
| [RotateFlipType](./rotatefliptype/) | يحدد مقدار دوران الصورة والمحور المستخدم لقلب الصورة. |
| [SeekOrigin](./seekorigin/) | يوفر الحقول التي تمثل نقاط المرجع في [`StreamContainer`](../aspose.psd/streamcontainer/) للبحث. |
| [SmoothingMode](./smoothingmode/) | يحدد ما إذا كان يتم تطبيق التنعيم (مضاد التعرج) على الخطوط والمنحنيات وحواف المناطق المملوءة. |
| [StringAlignment](./stringalignment/) | يحدد محاذاة سلسلة النص بالنسبة إلى مستطيل التخطيط الخاص بها. |
| [StringDigitSubstitute](./stringdigitsubstitute/) | التعداد يحدد كيفية استبدال الأرقام في سلسلة وفقًا لإعدادات المستخدم الإقليمية أو اللغة. |
| [StringFormatFlags](./stringformatflags/) | يحدد معلومات العرض والتخطيط لسلاسل النص. |
| [StringTrimming](./stringtrimming/) | يحدد كيفية قص الأحرف من سلسلة لا تتناسب تمامًا مع شكل التخطيط. |
| [TextRenderingHint](./textrenderinghint/) | يحدد جودة عرض النص. |
| [WarpMode](./warpmode/) | يحدد نوع تحويل الالتواء المطبق. |
| [WrapMode](./wrapmode/) | يحدد كيفية تجانب النسيج أو التدرج عندما يكون أصغر من المنطقة التي يتم ملؤها. |


