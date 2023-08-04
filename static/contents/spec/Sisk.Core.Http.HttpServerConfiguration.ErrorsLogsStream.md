<!--

Copyrights 2023 Sisk Framework - CypherPotato
Published under MIT license

!!! DO NOT EDIT THIS FILE !!!
This file was generated by a tool in the Sisk package. To edit the information in this documentation,
edit the XML documentation present in the Sisk source code.

-->


# ErrorsLogsStream property

Declaring type: [Sisk.Core.Http.HttpServerConfiguration](/read?q=/contents/spec/Sisk.Core.Http.HttpServerConfiguration.md) (from Sisk.Core)


Definition:

```cs
public TextWriter? ErrorsLogsStream { get; set; }
```

Gets or sets the <a href="https://learn.microsoft.com/en-us/dotnet/api/System.IO.TextWriter">TextWriter</a> object which the HTTP server will write HTTP server error transcriptions to.

> **Remarks:**
>
> This stream can be empty if ThrowExceptions is true.