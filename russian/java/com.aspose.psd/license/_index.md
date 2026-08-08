---
title: "Лицензия"
second_title: "Aspose.PSD for Java API Справочник"
description: "Предоставляет методы для лицензирования компонента."
type: docs
weight: 65
url: /ru/java/com.aspose.psd/license/
---

**Inheritance:**
java.lang.Object
```
public class License
```

Предоставляет методы для лицензирования компонента.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [License()](#License--) | Инициализирует новый экземпляр этого класса. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getErrorCodeMessages()](#getErrorCodeMessages--) | Получает сообщения кодов ошибок. |
| [getRenewSubscriptionStartMessage()](#getRenewSubscriptionStartMessage--) | Получает сообщение о начале продления подписки. |
| [hashCode()](#hashCode--) |  |
| [isLicensed_internalized()](#isLicensed-internalized--) | Получает значение, указывающее, лицензирован ли продукт. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeLicense()](#removeLicense--) |  |
| [setLicense(File licenseFile)](#setLicense-java.io.File-) | Лицензирует компонент. |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Лицензирует компонент. |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | Лицензирует компонент. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### License() {#License--}
```
public License()
```


Инициализирует новый экземпляр этого класса.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getErrorCodeMessages() {#getErrorCodeMessages--}
```
public static ByteObjDictionary<String> getErrorCodeMessages()
```


Получает сообщения кодов ошибок.

Значение: Сообщения кодов ошибок.

**Returns:**
com.aspose.java.optimization.maps.ByteObjDictionary<java.lang.String> - сообщения кодов ошибок.
### getRenewSubscriptionStartMessage() {#getRenewSubscriptionStartMessage--}
```
public static String getRenewSubscriptionStartMessage()
```


Получает сообщение о начале продления подписки.

Значение: Сообщение о начале продления подписки.

**Returns:**
java.lang.String - сообщение о начале продления подписки.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isLicensed_internalized() {#isLicensed-internalized--}
```
public static boolean isLicensed_internalized()
```


Получает значение, указывающее, лицензирован ли продукт.

**Returns:**
boolean -  true  если продукт лицензирован; иначе  false .
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeLicense() {#removeLicense--}
```
public static void removeLicense()
```




### setLicense(File licenseFile) {#setLicense-java.io.File-}
```
public void setLicense(File licenseFile)
```


Лицензирует компонент.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| licenseFile | java.io.File | представление пути к файлу |

### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public void setLicense(InputStream stream)
```


Лицензирует компонент.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток, содержащий лицензию. |

### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public void setLicense(String licenseName)
```


Лицензирует компонент.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| licenseName | java.lang.String | Может быть полным или коротким именем файла. Используйте пустую строку, чтобы переключиться в режим оценки. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

