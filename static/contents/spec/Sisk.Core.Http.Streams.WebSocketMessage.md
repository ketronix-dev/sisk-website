<!--

Copyrights 2023 Sisk Framework - CypherPotato
Published under MIT license

!!! DO NOT EDIT THIS FILE !!!
This file was generated by a tool in the Sisk package. To edit the information in this documentation,
edit the XML documentation present in the Sisk source code.

-->

# WebSocketMessage class
Assembly: Sisk.Core

Namespace: Sisk.Core.Http.Streams

Definition:

```cs
public sealed class WebSocketMessage
```

Represents an websocket request message received by an websocket server.

# Property list
<table>
    <tbody>
<tr>
    <td width="33%">
        <img class="icon" src="/assets/img/icons/property.svg">
        <a href="/read?q=/contents/spec/Sisk.Core.Http.Streams.WebSocketMessage.IsClose.md">
            IsClose
        </a>
    </td>
    <td>
        Gets an boolean indicating that this message is an remote closing message.
    <td>
</tr>
<tr>
    <td width="33%">
        <img class="icon" src="/assets/img/icons/property.svg">
        <a href="/read?q=/contents/spec/Sisk.Core.Http.Streams.WebSocketMessage.IsEnd.md">
            IsEnd
        </a>
    </td>
    <td>
        Gets an boolean indicating that this message is the last chunk of the message.
    <td>
</tr>
<tr>
    <td width="33%">
        <img class="icon" src="/assets/img/icons/property.svg">
        <a href="/read?q=/contents/spec/Sisk.Core.Http.Streams.WebSocketMessage.Length.md">
            Length
        </a>
    </td>
    <td>
        Gets the message length in byte count.
    <td>
</tr>
<tr>
    <td width="33%">
        <img class="icon" src="/assets/img/icons/property.svg">
        <a href="/read?q=/contents/spec/Sisk.Core.Http.Streams.WebSocketMessage.MessageBytes.md">
            MessageBytes
        </a>
    </td>
    <td>
        Gets an byte array with the message contents.
    <td>
</tr>
<tr>
    <td width="33%">
        <img class="icon" src="/assets/img/icons/property.svg">
        <a href="/read?q=/contents/spec/Sisk.Core.Http.Streams.WebSocketMessage.Sender.md">
            Sender
        </a>
    </td>
    <td>
        Gets the sender <a href="/read?q=/contents/spec/Sisk.Core.Http.Streams.HttpWebSocket.md">HttpWebSocket</a> object instance which received this message.
    <td>
</tr>
    </tbody>
</table>
# Method list
<table>
    <tbody>
<tr>
    <td width="33%">
        <img class="icon" src="/assets/img/icons/method.svg">
        <a href="/read?q=/contents/spec/Sisk.Core.Http.Streams.WebSocketMessage.GetString().md">
            GetString()
        </a>
    </td>
    <td>
        Reads the message bytes as string using the UTF-8 text encoding.
    <td>
</tr>
<tr>
    <td width="33%">
        <img class="icon" src="/assets/img/icons/method.svg">
        <a href="/read?q=/contents/spec/Sisk.Core.Http.Streams.WebSocketMessage.GetString(Encoding).md">
            GetString(Encoding)
        </a>
    </td>
    <td>
        Reads the message bytes as string using the specified encoding.
    <td>
</tr>
    </tbody>
</table>