## 3.6.2+6
* Katex Web improvements.

## 3.6.2+5
* Minor improvements.

## 3.6.2+4
* Minor improvements.

## 3.6.2+3
* Web support fixes.

## 3.6.2+2
* iOS rendering bug fixed.

## 3.6.2+1
* Minor bug fixed.

## 3.6.2
* Minor API Changes
* `TeXViewTeX` replaced by `TeXViewDocument`
* `TeXViewContainer` children replaced by a single child.
* `TeXViewWidget`, `TeXViewImage`, `TeXViewColumn` and `TeXViewInkWell` added.
* `onTap` will only work with `TeXViewInkwell`.
  
## 3.6.1+3
* `&` sign encoding issue solved.

## 3.6.1+2
* Sockets removed.

## 3.6.1+1
* Rendering issue for lower android APIs solved.
* Multiple TeXView on same page issue solved.

## 3.6.1
* Minor API Changes for `TeXViewBorder` `TeXViewMargin` `TeXViewPadding` and `TeXViewBorderRadius`.
* Height corrections.
* Styling corrections

## 3.6.0+1
* `TeXViewMargin.zeroAuto()` added.

## 3.6.0
* Major API Changes
* `TeXViewChild` removed, `TeXViewContainer` child of `TeXView` added and `TeXViewTeX` child of `TeXViewChild` added which holds `TeX` data styling.
* `onTap` callback has been added for each view.

## 3.5.2
* Minor API Changes
* `RenderingEngine` has been replaced with `TeXViewRenderingEngine`
* Katex Configurations added.
* Katex rendered height issue has been resolved.

## 3.5.1
* Extra margin at bottom issue resolved.
* Transition in styling has been removed as it was causing problems while calculating height.
* Multiple TeXView at same page are possible.

## 3.5.0+2
* Minor rendering fixes.

## 3.5.0+1
* Katex page height issue fixed.
* Minor fix in styling.

## 3.5.0
*  Heavy API Changes.
* `teXHTML` removed from API
* `children` has been added, where you can pass List of `TeXViewChild`.
* `TeXViewStyles` added where you can easily customise TeXView Widget.
* `onTap` callback support for each individual child.

## 3.1.4+1
* FlutterWeb rendering Bug fixed.

## 3.1.4
* `onTap` method added.
* **Api Usage** added in `Reade.md`.

## 3.1.3+5
* Minor Fix.

## 3.1.3+4
* Minor Fix.

## 3.1.3+3
* Minor Fix.

## 3.1.3+2
* Example updated.

## 3.1.3+1
* Size reduced.

## 3.1.3
* Exampled updated.

## 3.1.2
* dependencies upgraded.

## 3.1.1
* Katex Chemistry equations problem solved.

## 3.1.0
* Solved the issue of showing raw TeX before rendering

## 3.0.0
* Speed Optimizations by adding Katex support, much faster than MathJax.

## 2.0.0
* Flutter Web Support added (Beta).

## 1.0.15
* Broken Screenshots fixed.

## 1.0.14
* Rendered formula outline removed.

## 1.0.13
* New Example added.
* Now we you can set custom height of TeXView.

## 1.0.12
* Performance optimizations.
* Rendering Flashes fixed.
* Rendering Indicator Widget added.

## 1.0.11
* Performance optimizations.

## 1.0.10
* TeXView Renders again and again issue resolved.

## 1.0.9
* Fonts size issue resolved.

## 1.0.8
* Now you can refresh TeXView with new data on setState().

## 1.0.5
* Performance improvements

## 1.0.4
* Optimised performance by removing server.

## 1.0.3

* TeXView can be used in ListView for multiple time on same page.

## 1.0.2

* `onRenderFinished` callback added with calculated height of WebView.

## 1.0.1

* `onPageFinished` callback added.

## 1.0.0

* Stable Release
