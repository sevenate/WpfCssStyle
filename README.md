# WPF Styles in CSS way

Example of mixing **WPF** styles in a CSS-like format by using custom markup extension:

```xml
<Label Content="Some warning here" Style="{WPF:CssStyle Names='size16 bold red'}" />
```

Key code is in [CssStyleExtension.cs](CssStyleExtension.cs)

For more examples see [App.xaml](App.xaml) and [MainWindow.xaml](MainWindow.xaml)

## Design mode works in both Visual Studio 2017 and Blend for Visual Studio S2017

<img align="right" src="https://github.com/sevenate/WpfCssStyle/blob/master/screenshot-vs2017.gif">



<img align="right" src="https://github.com/sevenate/WpfCssStyle/blob/master/screenshot-blend2017.gif">