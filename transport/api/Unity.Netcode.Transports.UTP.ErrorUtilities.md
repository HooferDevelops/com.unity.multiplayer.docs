---  
id: Unity.Netcode.Transports.UTP.ErrorUtilities  
title: Unity.Netcode.Transports.UTP.ErrorUtilities  
---

<div class="markdown level0 summary">

Helper utility class to convert error codes to human readable error
messages.

</div>

<div class="markdown level0 conceptual">

</div>

<div class="inheritance">

##### Inheritance

<div class="level0">

System.Dynamic.ExpandoObject

</div>

<div class="level1">

System.Dynamic.ExpandoObject

</div>

</div>

<div class="inheritedMembers">

##### Inherited Members

<div>

Object.Equals(Object)

</div>

<div>

Object.Equals(Object, Object)

</div>

<div>

Object.GetHashCode()

</div>

<div>

Object.GetType()

</div>

<div>

Object.MemberwiseClone()

</div>

<div>

Object.ReferenceEquals(Object, Object)

</div>

<div>

Object.ToString()

</div>

</div>

##### **Namespace**: System.Dynamic.ExpandoObject

##### **Assembly**: MLAPI.dll

##### Syntax

``` lang-csharp
public static class ErrorUtilities
```

## 

### ErrorToString(Networking.Transport.Error.StatusCode, UInt64)

<div class="markdown level1 summary">

Convert error code to human readable error message.

</div>

<div class="markdown level1 conceptual">

</div>

#### Declaration

``` lang-csharp
public static string ErrorToString(Networking.Transport.Error.StatusCode error, ulong connectionId)
```

#### Parameters

| Type                                  | Name         | Description                        |
|---------------------------------------|--------------|------------------------------------|
| Networking.Transport.Error.StatusCode | error        | Status code of the error           |
| System.UInt64                         | connectionId | Subject connection ID of the error |

#### Returns

| Type          | Description                   |
|---------------|-------------------------------|
| System.String | Human readable error message. |