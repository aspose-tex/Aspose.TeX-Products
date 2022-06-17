---
title: C# TeX (LaTeX) Files Conversion
url: /net/conversion/
description: TeX and LaTeX conversion functionality. Convert TeX / LaTeX files to PDF, SVG, XPS, and image formats including PNG, JPEG, TIFF, and BMP using this .NET API solution.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="TeX / LaTeX Files Conversion Via C#" h2="Convert TeX / LaTeX Files to XPS, SVG, PDF and Images to build cross-platform .NET applications." >}}

{{% blocks/products/pf/feature-page-summary %}}


Aspose.TeX is an API to the Object TeX system, for detail of Tex file, here is the [Tex introduction](https://docs.aspose.com/tex/net/what-is-tex/). Developers can easily convert TeX to PDF, XPS, PNG, JPG, BMP and TIFF formats by integrating the API. Below are few code sample that programmers can enhance and integrate within TeX solutions.



{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Convert TeX to Images or Pdf, Svg, Xps formats." %}}

To convert TeX files to Images, Pdf, Xps or Svg process next steps. Create instance of the [TeXOptions class](https://apireference.aspose.com/tex/net/aspose.tex/texoptions). 
Define the options with specific settings like the file system working directory for the output/input using [OutputWorkingDirectory](https://reference.aspose.com/tex/net/aspose.tex/texoptions/outputworkingdirectory) 
 / [InputWorkingDirectory](https://reference.aspose.com/tex/net/aspose.tex/texoptions/inputworkingdirectory) 
and image save options such as [BmpSaveOptions](https://apireference.aspose.com/tex/net/aspose.tex.presentation.image/bmpsaveoptions), 
[PngSaveOptions](https://apireference.aspose.com/tex/net/aspose.tex.presentation.image/pngsaveoptions), 
[TiffSaveOptions](https://apireference.aspose.com/tex/net/aspose.tex.presentation.image/tiffsaveoptions),
[JpegSaveOptions](https://reference.aspose.com/tex/net/aspose.tex.presentation.image/jpegsaveoptions/)
 or [PDfSaveOptions](https://apireference.aspose.com/tex/net/aspose.tex.presentation.pdf/pdfsaveoptions), 
[SvgSaveOptions](https://apireference.aspose.com/tex/net/aspose.tex.presentation.svg/svgsaveoptions), 
[XpsSaveOptions](https://apireference.aspose.com/tex/net/aspose.tex.presentation.xps/xpssaveoptions), which is default, not need to set. And finally run TeX to Image or Pdf, Svg, Xps conversion using
[Run](https://reference.aspose.com/tex/net/aspose.tex/texjob/run) method of [TeXJob](https://reference.aspose.com/tex/net/aspose.tex/texjob) for [ImageDevice](https://apireference.aspose.com/tex/net/aspose.tex.presentation.image/imagedevice) or
[PdfDevice](https://reference.aspose.com/tex/net/aspose.tex.presentation.pdf/pdfdevice),
[SvgDevice](https://reference.aspose.com/tex/net/aspose.tex.presentation.svg/svgdevice),
[XpsDevice](https://reference.aspose.com/tex/net/aspose.tex.presentation.xps/xpsdevice).

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/agp/feature-section >}}
{{< app/tex/converter "C++ code example TeX to Images,XPS,PDF or SVG conversion" TeX PDF XPS SVG "JPEG|JPG" PNG TIFF BMP >}}
// Create conversion options for Object TeX format on Object TeX engine extension.
TeXOptions options = TeXOptions.ConsoleAppOptions(TeXConfig.ObjectTeX);

// Specify the file system working directory for the output.
options.OutputWorkingDirectory = new OutputFileSystemDirectory(RunExamples.OutputDirectory);

// Initialize the options for saving in {{output upper}} format.
options.SaveOptions = new {{output camel}}SaveOptions();

// Run TeX to {{output upper}} conversion.
{{#if_output 'XPS' 'PDF' 'SVG'}}
new TeXJob(Path.Combine(RunExamples.InputDirectory, "{{inputFile}}"), new {{output camel}}Device(), options).Run();
{{/if_output}}
{{#if_output 'BMP' 'JPEG' 'PNG' 'TIFF'}}
new TeXJob(Path.Combine(RunExamples.InputDirectory, "{{inputFile}}"), new ImageDevice(), options).Run();
{{/if_output}}
{{< /app/tex/converter >}}
{{< /blocks/products/pf/agp/feature-section>}}
{{< /blocks/products/pf/main-wrap-class>}}

