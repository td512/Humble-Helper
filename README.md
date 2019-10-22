# Humble Helper
 This helper library fetches HTTPOnly cookies from a .NET WebBrowser object.

****

## How do I use it?
Include this library in your project. It can be used in various .NET languagues by including, importing, or the like. Included are two samples, one for Visual Basic .NET, and C# .NET

### Visual Basic .NET

```
Imports HumbleHelper
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

****

## Where is this used?
It's used in the [Humble Trove Downloader](https://github.com/td512/Humble-Trove-Downloader)

## Where do I get the library?
From either [here](https://github.com/td512/Humble-Helper/blob/master/Humble%20Helper/bin/Release/) or by visiting the [releases](https://github.com/td512/Humble-Helper/releases) page

****

## I've found a bug!
Great! Please file an issue over [here](https://github.com/td512/Humble-Helper/issues), or if you think you can solve it, a pull request!
