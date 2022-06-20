---
title: Convert TEX to TIFF with C++ 
description: TeX to TIFF conversion functionality. Integrate this on-premise C++ library into your project or use cross-platform applications to convert TeX to TIFF.
url: /cpp/conversion/tex-to-tiff/
family: tex
platformtag: cpp
feature: conversion
informat: TEX
outformat: TIFF
otherformats: BMP PNG JPEG PDF SVG XPS
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convert TEX to TIFF via C#" h2="Convert TeX files to XPS, PDF & Image formats like BMP on Windows, macOS & Linux">}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="TEX to TIFF Conversion on C++" %}}
1. Initialize [TeXOptions](https://reference.aspose.com/tex/cpp/class/aspose.te_x.te_x_options)
2. Specify the file system working directory for the output using [OutputWorkingDirectory](https://reference.aspose.com/tex/cpp/class/aspose.te_x.te_x_options#aa4f4ea6dab7db5ba1b40800495f16f63)
3. Initialize the options for saving in TIFF format using [TiffSaveOptions](https://reference.aspose.com/tex/cpp/class/aspose.te_x.presentation.image.tiff_save_options)
4. Run TeX to TIFF conversion using [TeXJob](https://reference.aspose.com/tex/cpp/class/aspose.te_x.te_x_job) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Get Started with C++ TeX API" %}}
Install from command line as ```nuget install Aspose.TeX.Cpp``` or via Package Manager Console of Visual Studio with ```Install-Package Aspose.TeX.Cpp```.

Alternatively, get the offline MSI installer or DLLs in a ZIP file from [downloads](https://downloads.aspose.com/tex/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/agp/feature-section >}}
{{< app/tex/converter "C++ code example TeX to Images,XPS,PDF or SVG conversion" TEX TIFF BMP PNG JPEG>}}
TeXOptions options = TeXOptions.ConsoleAppOptions(TeXConfig.ObjectTeX);
options.OutputWorkingDirectory = new OutputFileSystemDirectory(RunExamples.OutputDirectory);
options.SaveOptions = new {{output camel}}SaveOptions();
new TeXJob(Path.Combine(RunExamples.InputDirectory, "{{inputFile}}"), new ImageDevice(), options).Run();
{{< /app/tex/converter >}}
{{< /blocks/products/pf/agp/feature-section>}}
{{< /blocks/products/pf/main-wrap-class>}}

{{< blocks/products/pf/agp/about-file-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}

