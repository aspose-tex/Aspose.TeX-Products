---
title: C++ TeX (LaTeX) Files Conversion
url: /cpp/conversion/
description: Convert LaTeX files to PDF, XPS and Images including PNG, JPEG, TIFF, BMP with few lines of C++ code.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="LaTeX Files Conversion Via C++" h2="Convert LaTeX Files to XPS, PDF and Images to build cross-platform applications." >}}

{{% blocks/products/pf/feature-page-summary %}}


Aspose.TeX is an API to the Object TeX system, for detail of Tex file, here is the [Tex introduction](https://docs.aspose.com/tex/net/what-is-tex/). Developers can easily convert TeX to PDF, XPS, PNG, JPG, BMP and TIFF formats by integrating the API. Below are few code samples that programmers can enhance and integrate within LaTex solutions.



{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Convert LaTeX to Images, XPS, PDF, SVG" %}}

To convert LaTeX files to Images, XPS or PDF, create instance of the [TeXOptions class](https://apireference.aspose.com/tex/net/aspose.tex/texoptions). 
Define the options with specific settings like the file system working directory for the output using 
[OutputWorkingDirectory](https://reference.aspose.com/tex/net/aspose.tex/texoptions/outputworkingdirectory/) 
and for the input using 
[InputWorkingDirectory](https://reference.aspose.com/tex/net/aspose.tex/texoptions/inputworkingdirectory/) 
and save options such as 
[PdfSaveOptions](https://apireference.aspose.com/tex/net/aspose.tex.presentation.pdf/pdfsaveoptions), 
[SvgSaveOptions](https://apireference.aspose.com/tex/net/aspose.tex.presentation.svg/svgsaveoptions), 
[BmpSaveOptions](https://apireference.aspose.com/tex/net/aspose.tex.presentation.image/bmpsaveoptions), 
[PngSaveOptions](https://apireference.aspose.com/tex/net/aspose.tex.presentation.image/pngsaveoptions), 
[TiffSaveOptions](https://apireference.aspose.com/tex/net/aspose.tex.presentation.image/tiffsaveoptions),
[JpegSaveOptions](https://apireference.aspose.com/tex/net/aspose.tex.presentation.image/jpegsaveoptions). 
[XpsSaveOptions](https://apireference.aspose.com/tex/net/aspose.tex.presentation.xps/xpssaveoptions) is default, not need to set.
And finally run conversion using TeXJob method.

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/agp/feature-section >}}
{{< app/tex/converter "C++ code example TeX to Images,XPS,PDF or SVG conversion" TeX PDF XPS SVG "JPEG|JPG" PNG TIFF BMP >}}
    // Create typesetting options for default ObjectTeX format on ObjectTeX engine extension.
    System::SharedPtr<TeXOptions> options = TeXOptions::ConsoleAppOptions(TeXConfig::ObjectTeX());

    // Specify a file system working directory for input and output.
    options->set_InputWorkingDirectory(System::MakeObject<InputFileSystemDirectory>(RunExamples::InputDirectory));
    options->set_OutputWorkingDirectory(System::MakeObject<OutputFileSystemDirectory>(RunExamples::OutputDirectory));

    // Initialize the options for saving in {{output upper}} format. 
    // Similary use relevant Image options for other image formats
    options->set_SaveOptions(System::MakeObject<{{output camel}}SaveOptions>());

    // Specify memory stream as output terminal, if you don't terminal output to be written to console.
    //options->set_TerminalOut(System::MakeObject<OutputMemoryTerminal>());

    // Run typesetting.
{{#if_output 'XPS' 'PDF' 'SVG'}}
    System::MakeObject<Aspose::TeX::TeXJob>(u"{{inputFile}}", System::MakeObject<{{output camel}}Device>(), options)->Run();
{{/if_output}}
{{#if_output 'BMP' 'JPEG' 'PNG' 'TIFF'}}
    System::MakeObject<Aspose::TeX::TeXJob>(u"{{inputFile}}", System::MakeObject<ImageDevice>(), options)->Run();
{{/if_output}}
{{< /app/tex/converter >}}
{{< /blocks/products/pf/agp/feature-section>}}
{{< /blocks/products/pf/main-wrap-class>}}


