# Humble Helper
 This helper library fetches HTTPOnly cookies from a .NET WebBrowser object.

****

## How do I use it?
Include this library in your project. It can be used in various .NET languagues by including, importing, or the like. Included are two samples, one for Visual Basic .NET, and C# .NET

### Visual Basic .NET

```
Imports Humble Helper
Public Sub ExtractHTTPOnlyCookies()
  WebHelper.GetGlobalCookies(WebBrowser1.Url.AbsoluteUri)
End Sub
```

### Visual C# .NET

```
using HumbleHelper;

public void ExtractHTTPOnlyCookies(){
  WebHelper.GetGlobalCookies(WebBrowser1.Url.AbsoluteUri);
}
```
