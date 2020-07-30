# Xamarin.Forms.PinchZoomImage

Zoom in on the image with the pinch of your fingers.

A simple way to zoom in and zoom out on your images with Xamarin.Forms.

 ###### This is the component, works on iOS, Android
 
 **NuGet**

|Name|Info|Contributors|
| ------------------- | ------------------- | ------------------- |
|Xamarin.Forms.PinchZoomImage|[![NuGet](https://buildstats.info/nuget/Xamarin.Forms.PinchZoomImage)](https://www.nuget.org/packages/Xamarin.Forms.PinchZoomImage/)|[![GitHub contributors](https://img.shields.io/github/contributors/TBertuzzi/Xamarin.Forms.PinchZoomImage.svg)](https://github.com/TBertuzzi/Xamarin.Forms.PinchZoomImage/graphs/contributors)|

 
 **Platform Support**

PinchZoomImage is a .NET Standard 2.0 library.Its only dependency is the Xamarin.Forms

## Setup / Usage

Does not require additional configuration. Just install the package in the shared project and use.

You just need to add the reference in your xaml file.

```csharp
  xmlns:pinch="clr-namespace:Xamarin.Forms.PinchZoomImage;assembly=Xamarin.Forms.PinchZoomImage" 
```

Control

Use with the image control

```csharp
 <pinch:PinchZoom>
     <pinch:PinchZoom.Content>
         <Image Source="xxamarin.jpg" />
     </pinch:PinchZoom.Content>
 </pinch:PinchZoom>     
```

The complete example can be downloaded here: 
https://github.com/TBertuzzi/Xamarin.Forms.PinchZoomImage/tree/master/PinchZoomImageSample

Base on original docs : https://docs.microsoft.com/xamarin/xamarin-forms/app-fundamentals/gestures/pinch
