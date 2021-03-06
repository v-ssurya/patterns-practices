---
TOCTitle: 'ModularityException Constructor (SerializationInfo, StreamingContext)'
Title: 'ModularityException Constructor (SerializationInfo, StreamingContext) (Microsoft.Practices.Prism.Modularity)'
ms:assetid: 'M:Microsoft.Practices.Prism.Modularity.ModularityException.\#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)'
ms:mtpsurl: 'modularityexception-constructor-mspp-modularity.md'
---


# ModularityException Constructor (SerializationInfo, StreamingContext)

Initializes a new instance with serialized data.

**Namespace:** [Microsoft.Practices.Prism.Modularity](/patterns-practices/reference/mspp-modularity-namespace)  
**Assembly:** Microsoft.Practices.Prism.Composition (in Microsoft.Practices.Prism.Composition.dll)  
**Version:** 5.0.0.0 (5.0.0.0)

## Syntax

```C#
protected ModularityException(
	SerializationInfo info,
	StreamingContext context
)
```

```VB
'Declaration
Protected Sub New ( 
	info As SerializationInfo,
	context As StreamingContext
)
```

### Parameters

*info* 

Type: [System.Runtime.Serialization.SerializationInfo](http://msdn.microsoft.com/en-us/library/a9b6042e)

The [SerializationInfo](http://msdn.microsoft.com/en-us/library/a9b6042e) that holds the serialized object data about the exception being thrown.

*context*  

Type: [System.Runtime.Serialization.StreamingContext](http://msdn.microsoft.com/en-us/library/t16abws5)

The [StreamingContext](http://msdn.microsoft.com/en-us/library/t16abws5) that contains contextual information about the source or destination.

## See Also

[ModularityException Class](/patterns-practices/reference/modularityexception-class-mspp-modularity)  
[ModularityException Members](/patterns-practices/reference/modularityexception-members-mspp-modularity)  
ModularityException Overload  
[Microsoft.Practices.Prism.Modularity Namespace](/patterns-practices/reference/mspp-modularity-namespace)  