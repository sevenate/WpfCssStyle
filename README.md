# WPF Styles in CSS way

Example of mixing **WPF** styles in a CSS-like format by using custom markup extension:

```xml
<Label Content="Inline: size16 + bold + italic + red"
       Style="{WPF:CssStyle Names='size24 bold italic green red'}" />
```

Key code is in [CssStyleExtension.cs](CssStyleExtension.cs).

For more examples see [App.xaml](App.xaml) and [MainWindow.xaml](MainWindow.xaml).

## Design mode in Visual Studio 2017

<img align="right" src="https://github.com/sevenate/WpfCssStyle/blob/master/screenshot-vs2017.gif">

## Design mode in Blend for Visual Studio S2017

<img align="right" src="https://github.com/sevenate/WpfCssStyle/blob/master/screenshot-blend2017.gif">