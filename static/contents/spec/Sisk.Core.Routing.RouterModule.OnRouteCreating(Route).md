<!--

Copyrights 2023 Sisk Framework - CypherPotato
Published under MIT license

!!! DO NOT EDIT THIS FILE !!!
This file was generated by a tool in the Sisk package. To edit the information in this documentation,
edit the XML documentation present in the Sisk source code.

-->


# OnRouteCreating(Route) method

Declaring type: [Sisk.Core.Routing.RouterModule](/read?q=/contents/spec/Sisk.Core.Routing.RouterModule.md) (from Sisk.Core)


Definition:

```cs
public virtual void OnRouteCreating(Route configuringRoute)
```

This method is called before a route is defined in the router and after it is created in this class, so its attributes and parameters can be modified. This method must be overloaded in the extending class and must not be called directly.


# Parameters

<table>
    <tbody>
<tr>
    <td width="33%">configuringRoute</td>
    <td>The route being defined on the router.</td>
</tr>
    </tbody>
</table>