# maui-numericentry-samples
Contains samples for .NET MAUI Numeric Entry
## Getting started with Numeric Entry control
The .NET MAUI NumericEntry control is designed to provide a user-friendly and advanced input experience for numeric values. It supports a wide range of numeric formats, including currency, percentages, decimals, and more. With its key features, it enables enhanced user experience and facilitates input validation.

Documentation: https://help.syncfusion.com/maui/numericentry/getting-started

## Adding the .NET MAUI NumericEntry 
Step 1: Add the NuGet to the project and add the namespace as shown in the following code sample:

**[XAML]**
```
xmlns:editors="clr-namespace:Syncfusion.Maui.Inputs;assembly=Syncfusion.Maui.Inputs"
```
**[C#]**
```
    using Syncfusion.Maui.Inputs;
```

Step 2: Set the NumericEntry control to content in `ContentPage.`
```
<editors:SfNumericEntry x:Name="numericEntry" />
```
**[C#]**
``` 
SfNumericEntry sfNumericEntry = new SfNumericEntry();
```
## Project pre-requisites

Make sure that you have the compatible versions of Visual Studio with .NET MAUI workloads and .NET SDK version in your machine before starting to work on this project. Refer to [System Requirements for .NET MAUI](https://help.syncfusion.com/maui/system-requirements).

## How to run this application?

To run this application, you need to first clone the maui-numericentry-samples repository and then open it in Visual Studio 2022. Now, simply build and run your project to view the output.

## <a name="troubleshooting"></a>Troubleshooting ##
### Path too long exception
If you are facing a path too long exception when building this example project, close Visual Studio rename the repository to short, and build the project.

## License

Syncfusion has no liability for any damage or consequence that may arise by using or viewing the samples. The samples are for demonstrative purposes, and if you choose to use or access the samples, you agree to not hold Syncfusion liable, in any form, for any damage that is related to use, for accessing, or viewing the samples. By accessing, viewing, or seeing the samples, you acknowledge and agree Syncfusion’s samples will not allow you seek injunctive relief in any form for any claim related to the sample. If you do not agree to this, do not view, access, utilize, or otherwise do anything with Syncfusion’s samples.