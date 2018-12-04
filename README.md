[![Build status](https://ci.appveyor.com/api/projects/status/c83f94dp4uk8rcms?svg=true)](https://ci.appveyor.com/project/sevenate/wpfcssstyle)

# WPF Styles in CSS way

Example of mixing **WPF** styles in a CSS-like format by using custom markup extension:

```xml
<Label Content="Some warning here" Style="{WPF:CssStyle Names='size16 bold red'}" />
```

Key code is in [CssStyleExtension.cs](CssStyleExtension.cs)

For more examples see [App.xaml](App.xaml) and [MainWindow.xaml](MainWindow.xaml)

## Design mode support

### Visual Studio 2017 

<img align="right" src="https://github.com/sevenate/WpfCssStyle/blob/master/screenshot-vs2017.gif" />  
  
  
  
### Blend for Visual Studio S2017

<img align="right" src="https://github.com/sevenate/WpfCssStyle/blob/master/screenshot-blend2017.gif" />