---
title: "Enumeración ExifProperties"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Aspose.PSD.Exif.ExifProperties enumeración. Lista de etiquetas Exif"
type: docs
weight: 1010
url: /es/net/aspose.psd.exif/exifproperties/
---
{{< psd/tize >}}
## ExifProperties enumeration

Lista de etiquetas Exif

```csharp
public enum ExifProperties : ushort
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| ImageWidth | `256` | El número de columnas de datos de imagen, igual al número de píxeles por fila. |
| ImageLength | `257` | El número de filas de datos de imagen. |
| BitsPerSample | `258` | El número de bits por componente de imagen. En este estándar cada componente de la imagen tiene 8 bits, por lo que el valor para esta etiqueta es 8. |
| Compression | `259` | El esquema de compresión utilizado para los datos de imagen. Cuando una imagen primaria está comprimida en JPEG, esta designación no es necesaria y se omite. |
| PhotometricInterpretation | `262` | La composición de píxeles. |
| ImageDescription | `270` | Una cadena de caracteres que brinda el título de la imagen. Puede ser un comentario como "1988 company picnic" o similar. |
| Make | `271` | El fabricante del equipo de grabación. Este es el fabricante del DSC, escáner, digitalizador de video u otro equipo que generó la imagen. Cuando el campo se deja en blanco, se considera desconocido. |
| Model | `272` | El nombre o número de modelo del equipo. Este es el nombre o número de modelo del DSC, escáner, digitalizador de video u otro equipo que generó la imagen. Cuando el campo se deja en blanco, se considera desconocido. |
| Orientation | `274` | La orientación de la imagen vista en términos de filas y columnas. |
| SamplesPerPixel | `277` | El número de componentes por píxel. Dado que este estándar se aplica a imágenes RGB y YCbCr, el valor establecido para esta etiqueta es 3. |
| XResolution | `282` | El número de píxeles por ResolutionUnit en la dirección ImageWidth. Cuando la resolución de la imagen es desconocida, se designa 72 [dpi]. |
| YResolution | `283` | El número de píxeles por ResolutionUnit en la dirección ImageLength. Se designa el mismo valor que XResolution. |
| PlanarConfiguration | `284` | Indica si los componentes de píxel se registran en formato chunky o planar. Si este campo no existe, se asume el valor predeterminado de TIFF de 1 (chunky). |
| ResolutionUnit | `296` | La unidad para medir XResolution y YResolution. La misma unidad se usa para ambos XResolution y YResolution. Si la resolución de la imagen es desconocida, se designa 2 (pulgadas). |
| TransferFunction | `301` | Una función de transferencia para la imagen, descrita en estilo tabular. Normalmente esta etiqueta no es necesaria, ya que el espacio de color se especifica en la etiqueta de información del espacio de color ColorSpace. |
| Software | `305` | Esta etiqueta registra el nombre y la versión del software o firmware de la cámara o dispositivo de entrada de imagen utilizado para generar la imagen. El formato detallado no está especificado, pero se recomienda seguir el ejemplo que se muestra a continuación. Cuando el campo se deja en blanco, se considera desconocido. |
| DateTime | `306` | La fecha y hora de creación de la imagen. En el estándar Exif, es la fecha y hora en que se modificó el archivo. |
| Artist | `315` | Esta etiqueta registra el nombre del propietario de la cámara, fotógrafo o creador de la imagen. El formato detallado no está especificado, pero se recomienda que la información se escriba como en el ejemplo a continuación para facilitar la interoperabilidad. Cuando el campo se deja en blanco, se considera desconocido. Ej.) "Camera owner, John Smith; Photographer, Michael Brown; Image creator, Ken James" |
| WhitePoint | `318` | La cromaticidad del punto blanco de la imagen. Normalmente esta etiqueta no es necesaria, ya que el espacio de color se especifica en la etiqueta de información del espacio de color ColorSpace. |
| PrimaryChromaticities | `319` | La cromaticidad de los tres colores primarios de la imagen. Normalmente esta etiqueta no es necesaria, ya que el espacio de color se especifica en la etiqueta de información del espacio de color ColorSpace. |
| YCbCrCoefficients | `529` | Los coeficientes matriciales para la transformación de datos de imagen de RGB a YCbCr. |
| YCbCrSubSampling | `530` | La relación de muestreo de los componentes de crominancia en relación con el componente de luminancia. |
| YCbCrPositioning | `531` | La posición de los componentes de crominancia en relación con el componente de luminancia. Este campo se designa solo para datos comprimidos en JPEG o datos YCbCr sin comprimir. El valor predeterminado de TIFF es 1 (centrado); pero cuando Y:Cb:Cr = 4:2:2, este estándar recomienda que se use 2 (co-situado) para registrar los datos, con el fin de mejorar la calidad de la imagen al verla en sistemas de TV. Cuando este campo no existe, el lector debe asumir el valor predeterminado de TIFF. En el caso de Y:Cb:Cr = 4:2:0, se recomienda el valor predeterminado de TIFF (centrado). Si el lector no tiene la capacidad de soportar ambos tipos de YCbCrPositioning, debe seguir el valor predeterminado de TIFF sin importar el valor en este campo. Es preferible que los lectores " puedan soportar tanto la posición centrada como la co-situada. |
| ReferenceBlackWhite | `532` | El valor de punto negro de referencia y el valor de punto blanco de referencia. No se proporcionan valores predeterminados en TIFF, pero los valores a continuación se dan como predeterminados aquí. El espacio de color se declara en una etiqueta de información del espacio de color, siendo el predeterminado el valor que brinda las características óptimas de la imagen Interoperabilidad bajo estas condiciones |
| Copyright | `33432` | Información de derechos de autor. En este estándar la etiqueta se usa para indicar tanto los derechos de autor del fotógrafo como del editor. Es el aviso de derechos de autor de la persona u organización que reclama derechos sobre la imagen. La declaración de derechos de autor de Interoperabilidad, incluyendo fecha y derechos, debe escribirse en este campo; por ejemplo, "Copyright, John Smith, 19xx. All rights reserved.". En este estándar el campo registra tanto los derechos de autor del fotógrafo como del editor, con cada uno registrado en una parte separada de la declaración. Cuando hay una distinción clara entre los derechos de autor del fotógrafo y del editor, estos deben escribirse en el orden de fotógrafo seguido por los derechos de autor del editor, separados por NULL (en este caso, como la declaración también termina con un NULL, hay dos códigos NULL). Cuando solo se proporciona el derecho de autor del fotógrafo, se termina con un código NULL. Cuando solo se proporciona el derecho de autor del editor, la parte del fotógrafo consiste en un espacio seguido de un código NULL terminador, luego se da el derecho de autor del editor. Cuando el campo se deja en blanco, se trata como desconocido. |
| ExposureTime | `33434` | Tiempo de exposición, dado en segundos. |
| FNumber | `33437` | El número F. |
| ExposureProgram | `34850` | La clase del programa utilizado por la cámara para establecer la exposición cuando se toma la foto. |
| SpectralSensitivity | `34852` | Indica la sensibilidad espectral de cada canal de la cámara utilizada. |
| PhotographicSensitivity | `34855` | Indica la velocidad ISO y la latitud ISO de la cámara o dispositivo de entrada según lo especificado en ISO 12232. |
| OECF | `34856` | Indica la Función de Conversión Opto-Eléctrica (OECF) especificada en ISO 14524. |
| ExifVersion | `36864` | La versión exif. |
| DateTimeOriginal | `36867` | La fecha y hora en que se generaron los datos originales de la imagen. |
| DateTimeDigitized | `36868` | La fecha y hora de digitalización. |
| ComponentsConfiguration | `37121` | La configuración de componentes. |
| CompressedBitsPerPixel | `37122` | Específico de datos comprimidos; indica los bits comprimidos por píxel. |
| ShutterSpeedValue | `37377` | El valor de velocidad de obturación. |
| ApertureValue | `37378` | El valor de apertura del objetivo. |
| BrightnessValue | `37379` | El valor de brillo. |
| ExposureBiasValue | `37380` | El valor de compensación de exposición. |
| MaxApertureValue | `37381` | El valor de apertura máxima. |
| SubjectDistance | `37382` | La distancia al sujeto, dada en metros. |
| MeteringMode | `37383` | El modo de medición. |
| LightSource | `37384` | El tipo de fuente de luz. |
| Flash | `37385` | Indica el estado del flash cuando se tomó la imagen. |
| FocalLength | `37386` | La distancia focal real del objetivo, en mm. |
| SubjectArea | `37396` | Esta etiqueta indica la ubicación y el área del sujeto principal en la escena general. |
| MakerNote | `37500` | Una etiqueta para fabricantes de escritores Exif para registrar cualquier información deseada. El contenido depende del fabricante, pero esta etiqueta no debe usarse para nada distinto a su propósito previsto. |
| UserComment | `37510` | Una etiqueta para usuarios de Exif que permite escribir palabras clave o comentarios en la imagen además de los que aparecen en ImageDescription, y sin las limitaciones de código de caracteres de la etiqueta ImageDescription. |
| SubsecTime | `37520` | Una etiqueta utilizada para registrar fracciones de segundo para la etiqueta DateTime. |
| SubsecTimeOriginal | `37521` | Una etiqueta utilizada para registrar fracciones de segundo para la etiqueta DateTimeOriginal. |
| SubsecTimeDigitized | `37522` | Una etiqueta utilizada para registrar fracciones de segundo para la etiqueta DateTimeDigitized. |
| FlashpixVersion | `40960` | La versión del formato Flashpix compatible con un archivo FPXR. |
| ColorSpace | `40961` | La etiqueta de información del espacio de color (ColorSpace) siempre se registra como el especificador del espacio de color. |
| RelatedSoundFile | `40964` | El archivo de sonido relacionado. |
| FlashEnergy | `41483` | Indica la energía del estroboscopio en el momento en que se captura la imagen, medida en Beam Candle Power Seconds (BCPS). |
| SpatialFrequencyResponse | `41484` | Esta etiqueta registra la tabla de frecuencia espacial de la cámara o dispositivo de entrada y los valores SFR en la dirección del ancho de la imagen, la altura de la imagen y la dirección diagonal, según lo especificado en ISO 12233. |
| FocalPlaneXResolution | `41486` | Indica el número de píxeles en la dirección del ancho de la imagen (X) por FocalPlaneResolutionUnit en el plano focal de la cámara. |
| FocalPlaneYResolution | `41487` | Indica el número de píxeles en la dirección de la altura de la imagen (Y) por FocalPlaneResolutionUnit en el plano focal de la cámara. |
| FocalPlaneResolutionUnit | `41488` | Indica la unidad para medir FocalPlaneXResolution y FocalPlaneYResolution. Este valor es el mismo que ResolutionUnit. |
| SubjectLocation | `41492` | Indica la ubicación del sujeto principal en la escena. El valor de esta etiqueta representa el píxel en el centro del sujeto principal relativo al borde izquierdo, antes del procesamiento de rotación según la etiqueta Rotation. |
| ExposureIndex | `41493` | Indica el índice de exposición seleccionado en la cámara o dispositivo de entrada en el momento en que se captura la imagen. |
| SensingMethod | `41495` | Indica el tipo de sensor de imagen en la cámara o dispositivo de entrada. |
| FileSource | `41728` | La fuente del archivo. |
| SceneType | `41729` | Indica el tipo de escena. Si una DSC grabó la imagen, el valor de esta etiqueta siempre debe ser 1, indicando que la imagen fue fotografiada directamente. |
| CFAPattern | `41730` | Indica el patrón geométrico de la matriz de filtros de color (CFA) del sensor de imagen cuando se utiliza un sensor de área de color de un solo chip. No se aplica a todos los métodos de detección. |
| CustomRendered | `41985` | Esta etiqueta indica el uso de procesamiento especial en los datos de la imagen, como renderizado orientado a la salida. Cuando se realiza procesamiento especial, se espera que el lector desactive o minimice cualquier procesamiento adicional. |
| ExposureMode | `41986` | Esta etiqueta indica el modo de exposición configurado cuando se tomó la imagen. En modo de auto-bracketing, la cámara dispara una serie de fotogramas de la misma escena con diferentes configuraciones de exposición. |
| WhiteBalance | `41987` | Esta etiqueta indica el modo de balance de blancos configurado cuando se tomó la imagen. |
| DigitalZoomRatio | `41988` | Esta etiqueta indica la relación de zoom digital cuando se tomó la imagen. Si el numerador del valor registrado es 0, esto indica que no se utilizó zoom digital. |
| FocalLengthIn35MmFilm | `41989` | Esta etiqueta indica la distancia focal equivalente asumiendo una cámara de película de 35 mm, en mm. Un valor de 0 significa que la distancia focal es desconocida. Tenga en cuenta que esta etiqueta difiere de la etiqueta FocalLength. |
| SceneCaptureType | `41990` | Esta etiqueta indica el tipo de escena que se fotografió. También puede usarse para registrar el modo en que se tomó la imagen. |
| GainControl | `41991` | Esta etiqueta indica el grado de ajuste general de ganancia de la imagen. |
| Contrast | `41992` | Esta etiqueta indica la dirección del procesamiento de contraste aplicado por la cámara cuando se tomó la imagen. |
| Saturation | `41993` | Esta etiqueta indica la dirección del procesamiento de saturación aplicado por la cámara cuando se tomó la imagen. |
| Sharpness | `41994` | Esta etiqueta indica la dirección del procesamiento de nitidez aplicado por la cámara cuando se tomó la imagen |
| DeviceSettingDescription | `41995` | Esta etiqueta indica información sobre las condiciones de captura de una cámara de modelo particular. La etiqueta se usa solo para indicar las condiciones de captura en el lector. |
| SubjectDistanceRange | `41996` | Esta etiqueta indica la distancia al sujeto. |
| ImageUniqueID | `42016` | El identificador único de la imagen. |
| GPSVersionID | `0` | Indica la versión de GPSInfoIFD. |
| GPSLatitudeRef | `1` | Indica si la latitud es norte o sur. |
| GPSLatitude | `2` | Indica la latitud. La latitud se expresa como tres valores RATIONAL que dan los grados, minutos y segundos, respectivamente. Si la latitud se expresa en grados, minutos y segundos, un formato típico sería dd/1,mm/1,ss/1. Cuando se usan grados y minutos y, por ejemplo, se dan fracciones de minutos con hasta dos decimales, el formato sería dd/1,mmmm/100,0/1. |
| GPSLongitudeRef | `3` | Indica si la longitud es este u oeste. |
| GPSLongitude | `4` | Indica la longitud. La longitud se expresa como tres valores RATIONAL que dan los grados, minutos y segundos, respectivamente. Si la longitud se expresa en grados, minutos y segundos, un formato típico sería ddd/1,mm/1,ss/1. Cuando se usan grados y minutos y, por ejemplo, se dan fracciones de minutos con hasta dos decimales, el formato sería ddd/1,mmmm/100,0/1. |
| GPSAltitudeRef | `5` | Indica la altitud utilizada como altitud de referencia. Si la referencia es el nivel del mar y la altitud está por encima del nivel del mar, se da 0. Si la altitud está por debajo del nivel del mar, se da un valor de 1 y la altitud se indica como un valor absoluto en la etiqueta GPSAltitude. |
| GPSAltitude | `6` | Indica la altitud basada en la referencia en GPSAltitudeRef. La altitud se expresa como un valor RATIONAL. La unidad de referencia es metros. |
| GPSTimestamp | `7` | Indica la hora como UTC (Tiempo Universal Coordinado). TimeStamp se expresa como tres valores RATIONAL que dan la hora, el minuto y el segundo. |
| GPSSatellites | `8` | Indica los satélites GPS utilizados para las mediciones. Esta etiqueta puede usarse para describir el número de satélites, su número de identificación, ángulo de elevación, azimut, SNR y otra información en notación ASCII. El formato no está especificado. Si el receptor GPS es incapaz de tomar mediciones, el valor de la etiqueta se establecerá en NULL. |
| GPSStatus | `9` | Indica el estado del receptor GPS cuando se registra la imagen. |
| GPSMeasureMode | `10` | Indica el modo de medición GPS. - 2- o 3-dimensional. |
| GPSDOP | `11` | Indica el DOP GPS (grado de precisión de los datos). Se escribe un valor HDOP durante la medición bidimensional y PDOP durante la medición tridimensional. |
| GPSSpeedRef | `12` | Indica la unidad utilizada para expresar la velocidad de movimiento del receptor GPS. 'K' 'M' y 'N' representan kilómetros por hora, millas por hora y nudos. |
| GPSSpeed | `13` | Indica la velocidad del movimiento del receptor GPS. |
| GPSTrackRef | `14` | Indica la referencia para dar la dirección del movimiento del receptor GPS. 'T' denota dirección verdadera y 'M' dirección magnética. |
| GPSTrack | `15` | Indica la dirección del movimiento del receptor GPS. El rango de valores es de 0.00 a 359.99. |
| GPSImgDirectionRef | `16` | Indica la referencia para dar la dirección de la imagen cuando se captura. 'T' denota dirección verdadera y 'M' dirección magnética. |
| GPSImgDirection | `17` | Indica la dirección de la imagen cuando se capturó. El rango de valores es de 0.00 a 359.99. |
| GPSMapDatum | `18` | Indica los datos de levantamiento geodésico utilizados por el receptor GPS. |
| GPSDestLatitudeRef | `19` | Indica si la latitud del punto de destino es latitud norte o sur. El valor ASCII 'N' indica latitud norte, y 'S' indica latitud sur. |
| GPSDestLatitude | `20` | Indica la latitud del punto de destino. La latitud se expresa como tres valores RATIONAL que dan los grados, minutos y segundos, respectivamente. Si la latitud se expresa en grados, minutos y segundos, un formato típico sería dd/1,mm/1,ss/1. Cuando se usan grados y minutos y, por ejemplo, se dan fracciones de minutos con hasta dos decimales, el formato sería dd/1,mmmm/100,0/1. |
| GPSDestLongitudeRef | `21` | Indica si la longitud del punto de destino es longitud este u oeste. El ASCII 'E' indica longitud este, y 'W' indica longitud oeste. |
| GPSDestLongitude | `22` | Indica la longitud del punto de destino. La longitud se expresa como tres valores RATIONAL que dan los grados, minutos y segundos, respectivamente. Si la longitud se expresa en grados, minutos y segundos, un formato típico sería ddd/1,mm/1,ss/1. Cuando se usan grados y minutos y, por ejemplo, se dan fracciones de minutos con hasta dos decimales, el formato sería ddd/1,mmmm/100,0/1. |
| GPSDestBearingRef | `23` | Indica la referencia utilizada para dar el rumbo al punto de destino. 'T' denota dirección verdadera y 'M' dirección magnética. |
| GPSDestBearing | `24` | Indica el rumbo al punto de destino. El rango de valores es de 0.00 a 359.99. |
| GPSDestDistanceRef | `25` | Indica la unidad utilizada para expresar la distancia al punto de destino. 'K', 'M' y 'N' representan kilómetros, millas y nudos. |
| GPSDestDistance | `26` | Indica la distancia al punto de destino. |
| GPSProcessingMethod | `27` | Una cadena de caracteres que registra el nombre del método utilizado para la localización. El primer byte indica el código de caracteres usado, y a continuación sigue el nombre del método. |
| GPSAreaInformation | `28` | Una cadena de caracteres que registra el nombre del área GPS. El primer byte indica el código de caracteres usado, y a continuación sigue el nombre del área GPS. |
| GPSDateStamp | `29` | Una cadena de caracteres que registra la información de fecha y hora relativa a UTC (Tiempo Universal Coordinado). El formato es AAAA:MM:DD. |
| GPSDifferential | `30` | Indica si se aplica corrección diferencial al receptor GPS. |
| StripOffsets | `273` | Para cada tira, el desplazamiento en bytes de esa tira. Se recomienda seleccionar esto de modo que el número de bytes de la tira no supere los 64 Kbytes. Etiqueta Aux. |
| JPEGInterchangeFormat | `513` | El desplazamiento al byte de inicio (SOI) de los datos de miniatura JPEG comprimidos. No se utiliza para los datos JPEG de la imagen principal. |
| JPEGInterchangeFormatLength | `514` | El número de bytes de los datos de miniatura JPEG comprimidos. No se utiliza para los datos JPEG de la imagen principal. Las miniaturas JPEG no se dividen sino que se registran como una secuencia continua de bits JPEG desde SOI hasta EOI. No deben registrarse los marcadores Appn y COM. Las miniaturas comprimidas deben registrarse en no más de 64 Kbytes, incluyendo todos los demás datos que se registrarán en APP1. |
| ExifIfdPointer | `34665` | Un puntero al Exif IFD. La interoperabilidad, Exif IFD tiene la misma estructura que el IFD especificado en TIFF. Sin embargo, normalmente no contiene datos de imagen como en el caso de TIFF. |
| GPSIfdPointer | `34853` | El puntero gps ifd. |
| RowsPerStrip | `278` | El número de filas por tira. Este es el número de filas en la imagen de una tira cuando una imagen se divide en tiras. |
| StripByteCounts | `279` | El número total de bytes en cada tira. |
| PixelXDimension | `40962` | Información específica de datos comprimidos. Cuando se registra un archivo comprimido, el ancho válido de la imagen significativa debe registrarse en esta etiqueta, exista o no datos de relleno o un marcador de reinicio. |
| PixelYDimension | `40963` | Información específica de datos comprimidos. Cuando se registra un archivo comprimido, la altura válida de la imagen significativa debe registrarse en esta etiqueta. |
| Gamma | `42240` | Valor gamma |
| SensitivityType | `34864` | Tipo de sensibilidad fotográfica |
| StandardOutputSensitivity | `34865` | Indica la sensibilidad de salida estándar de la cámara |
| RecommendedExposureIndex | `34866` | Indica el índice de exposición recomendado |
| ISOSpeed | `34867` | Información sobre el valor de velocidad ISO según lo definido en ISO 12232 |
| ISOSpeedLatitudeYYY | `34868` | Esta etiqueta indica el valor de latitud de velocidad ISO yyy según lo definido en ISO 12232 |
| ISOSpeedLatitudeZZZ | `34869` | Esta etiqueta indica el valor de latitud de velocidad ISO zzz según lo definido en ISO 12232 |
| CameraOwnerName | `42032` | Contiene el nombre del propietario de la cámara |
| BodySerialNumber | `42033` | Contiene el número de serie del cuerpo de la cámara |
| LensMake | `42035` | Esta etiqueta registra el fabricante del objetivo |
| LensModel | `42036` | Esta etiqueta registra el nombre del modelo y el número de modelo del lens`s |
| LensSerialNumber | `42037` | Esta etiqueta registra el número de serie del objetivo intercambiable |
| LensSpecification | `42034` | Esta etiqueta indica la distancia focal mínima, la distancia focal máxima, el número F mínimo en la distancia focal mínima y el número F mínimo en la distancia focal máxima |

### Ver también

* namespace [Aspose.PSD.Exif](../../aspose.psd.exif/)
* assembly [Aspose.PSD](../../)


