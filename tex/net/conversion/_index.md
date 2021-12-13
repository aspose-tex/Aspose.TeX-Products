---
title: C# TeX (LaTeX) Files Conversion
url: /net/conversion/
description: Convert LaTeX files to PDF, XPS and Images including PNG, JPEG, TIFF, BMP with few lines of C# code via .NET library.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="LaTeX Files Conversion Via C#" h2="Convert LaTeX Files to XPS, PDF and Images to build cross-platform .NET applications." >}}

{{% blocks/products/pf/feature-page-summary %}}


Aspose.TeX is an API to the Object TeX system, for detail of Tex file, here is the [Tex introduction](https://docs.aspose.com/tex/net/what-is-tex/). Developers can easily convert TeX to PDF, XPS, PNG, JPG, BMP and TIFF formats by integrating the API. Below are few code samples that programmers can enhance and integrate within LaTex solutions.



{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Convert LaTeX to Images" %}}

To convert LaTeX files to Images, Process is, create instance of the [TeXOptions class](https://apireference.aspose.com/tex/net/aspose.tex/texoptions). Define the options with specific settings like the file system working directory for the output using OutputWorkingDirectory and image save options such as [BmpSaveOptions](https://apireference.aspose.com/tex/net/aspose.tex.presentation.image/bmpsaveoptions), [PngSaveOptions](https://apireference.aspose.com/tex/net/aspose.tex.presentation.image/pngsaveoptions), [TiffSaveOptions](https://apireference.aspose.com/tex/net/aspose.tex.presentation.image/tiffsaveoptions). And finally run run LaTeX to Image conversion using TeXJob method.

{{% blocks/products/pf/feature-page-code h3="C# Code for LaTeX to Image Conversion" %}}

{{< gist "aspose-com-gists" "62ad6f22e48994af877bc847d83573a1" "convert-latex-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="latex-to-png latex-to-bmp latex-to-tiff latex-to-jpeg" >}}

{{% blocks/products/pf/feature-page-section  h2="LaTeX to PDF Conversion" %}}

Process of converting LaTeX to PDF is same as images, except that API provides [PdfSaveOptions](https://apireference.aspose.com/tex/net/aspose.tex.presentation.pdf/pdfsaveoptions) for setting specific PDF options. 


{{% blocks/products/pf/feature-page-code h3="C# Code for LaTeX to PDF Conversion" %}}

{{< gist "aspose-com-gists" "62ad6f22e48994af877bc847d83573a1" "convert-latex-to-pdf.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert LaTeX to XPS" %}}

Here is the way for converting TeX (LaTeX) to XPS Programmatically. Firstly create typesetting options TeXOptions on ObjectTeX engine extension and define the file system working folder for input / output. Run Typesetting with [XpsDevice](https://apireference.aspose.com/tex/net/aspose.tex.presentation.xps/xpsdevice) for TeX to XPS conversion programmatically.

{{% blocks/products/pf/feature-page-code h3="C# Code for XPS to Image Conversion" %}}

{{< gist "aspose-com-gists" "b6ff8a0d32ac7353678b69d23db6e8c6" "convert-TeX-to-XPS.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}