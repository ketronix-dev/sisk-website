<!--

Copyrights 2023 Sisk Framework - CypherPotato
Published under MIT license

!!! DO NOT EDIT THIS FILE !!!
This file was generated by a tool in the Sisk package. To edit the information in this documentation,
edit the XML documentation present in the Sisk source code.

-->

# ExceptionErrorCallback delegate
Assembly: Sisk.Core

Namespace: Sisk.Core.Routing

Definition:

```cs
public delegate HttpResponse ExceptionErrorCallback(Exception ex, HttpContext context);
```

Represents the function that is called after the route callback threw an exception.
