---  
id: Unity.Networking.Transport.WebSocketNetworkInterface  
title: Unity.Networking.Transport.WebSocketNetworkInterface  
---

<div class="markdown level0 summary">

</div>

<div class="markdown level0 conceptual">

</div>

<div classs="implements">

##### Implements

<div>

INetworkInterface

</div>

<div>

System.IDisposable

</div>

</div>

<div class="inheritedMembers">

##### Inherited Members

<div>

ValueType.Equals(Object)

</div>

<div>

ValueType.GetHashCode()

</div>

<div>

ValueType.ToString()

</div>

<div>

Object.Equals(Object, Object)

</div>

<div>

Object.GetType()

</div>

<div>

Object.ReferenceEquals(Object, Object)

</div>

</div>

##### **Namespace**: System.Dynamic.ExpandoObject

##### **Assembly**: transport.dll

##### Syntax

``` lang-csharp
public struct WebSocketNetworkInterface : INetworkInterface, IDisposable
```

## 

### LocalEndpoint

<div class="markdown level1 summary">

</div>

<div class="markdown level1 conceptual">

</div>

#### Declaration

``` lang-csharp
public readonly NetworkEndpoint LocalEndpoint { get; }
```

#### Property Value

| Type            | Description |
|-----------------|-------------|
| NetworkEndpoint |             |

## 

### Bind(NetworkEndpoint)

<div class="markdown level1 summary">

</div>

<div class="markdown level1 conceptual">

</div>

#### Declaration

``` lang-csharp
public int Bind(NetworkEndpoint endpoint)
```

#### Parameters

| Type            | Name     | Description |
|-----------------|----------|-------------|
| NetworkEndpoint | endpoint |             |

#### Returns

| Type         | Description |
|--------------|-------------|
| System.Int32 |             |

### Dispose()

<div class="markdown level1 summary">

</div>

<div class="markdown level1 conceptual">

</div>

#### Declaration

``` lang-csharp
public void Dispose()
```

### Initialize(ref NetworkSettings, ref Int32)

<div class="markdown level1 summary">

</div>

<div class="markdown level1 conceptual">

</div>

#### Declaration

``` lang-csharp
public int Initialize(ref NetworkSettings settings, ref int packetPadding)
```

#### Parameters

| Type            | Name          | Description |
|-----------------|---------------|-------------|
| NetworkSettings | settings      |             |
| System.Int32    | packetPadding |             |

#### Returns

| Type         | Description |
|--------------|-------------|
| System.Int32 |             |

### Listen()

<div class="markdown level1 summary">

</div>

<div class="markdown level1 conceptual">

</div>

#### Declaration

``` lang-csharp
public int Listen()
```

#### Returns

| Type         | Description |
|--------------|-------------|
| System.Int32 |             |

### ScheduleReceive(ref ReceiveJobArguments, JobHandle)

<div class="markdown level1 summary">

</div>

<div class="markdown level1 conceptual">

</div>

#### Declaration

``` lang-csharp
public JobHandle ScheduleReceive(ref ReceiveJobArguments arguments, JobHandle dep)
```

#### Parameters

| Type                | Name      | Description |
|---------------------|-----------|-------------|
| ReceiveJobArguments | arguments |             |
| JobHandle           | dep       |             |

#### Returns

| Type      | Description |
|-----------|-------------|
| JobHandle |             |

### ScheduleSend(ref SendJobArguments, JobHandle)

<div class="markdown level1 summary">

</div>

<div class="markdown level1 conceptual">

</div>

#### Declaration

``` lang-csharp
public JobHandle ScheduleSend(ref SendJobArguments arguments, JobHandle dep)
```

#### Parameters

| Type             | Name      | Description |
|------------------|-----------|-------------|
| SendJobArguments | arguments |             |
| JobHandle        | dep       |             |

#### Returns

| Type      | Description |
|-----------|-------------|
| JobHandle |             |

### Implements

<div>

INetworkInterface

</div>

<div>

System.IDisposable

</div>

### Extension Methods

<div>

ManagedNetworkInterfaceExtensions.WrapToUnmanaged\&lt;T&gt;(T)

</div>