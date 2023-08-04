<!--

Copyrights 2023 Sisk Framework - CypherPotato
Published under MIT license

!!! DO NOT EDIT THIS FILE !!!
This file was generated by a tool in the Sisk package. To edit the information in this documentation,
edit the XML documentation present in the Sisk source code.

-->


# CreateRedirectResponse(string) method

Declaring type: [Sisk.Core.Http.HttpResponse](/read?q=/contents/spec/Sisk.Core.Http.HttpResponse.md) (from Sisk.Core)


Definition:

```cs
public static HttpResponse CreateRedirectResponse(string location)
```

Creates an new redirect <a href="/read?q=/contents/spec/Sisk.Core.Http.HttpResponse.md">HttpResponse</a> with given location header.


# Parameters

<table>
    <tbody>
<tr>
    <td width="33%">location</td>
    <td>The absolute or relative URL path which the client must be redirected to.</td>
</tr>
    </tbody>
</table>