---
title: Java TeX (LaTeX) Files Conversion
url: /java/conversion/
description: Convert LaTeX files to PDF, XPS and Images including PNG, JPEG, TIFF, BMP via Java library.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="LaTeX Files Conversion Via Java" h2="Convert LaTeX Files to Images, XPS and PDF to build cross-platform Java applications." >}}

{{% blocks/products/pf/feature-page-summary %}}


Aspose.TeX is an API to the Object TeX system, for detail of Tex file, here is the [Tex introduction](https://docs.aspose.com/tex/net/what-is-tex/). Developers can easily convert LaTeX to XPS, PDF and Images including PNG, JPG, BMP and TIFF formats by integrating the API within Java based solutions. Below are few code examples that programmers can integrate for LaTex conversion solutions.



{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Convert LaTeX to Images" %}}



To convert LaTeX files to Images, Process is, Initialize [TeXOptions](https://apireference.aspose.com/tex/java/com.aspose.tex/TeXOptions) for creating conversion options for Object LaTeX format. Specify system working directory for the output using [OutputWorkingDirectory](https://apireference.aspose.com/tex/java/com.aspose.tex/TeXOptions#getOutputWorkingDirectory--). Use the relevant [ImageSaveOptions](https://apireference.aspose.com/tex/java/com.aspose.tex.rendering/ImageSaveOptions) to initialize the options for saving in relevant format. Finally use TeXJob method for LaTeX to image conversion.


{{% blocks/products/pf/feature-page-code h3="C# Code for LaTeX to Image Conversion" %}}

{{< gist "aspose-com-gists" "a94cd0f5d4e008d2f9a334004e5a3743" "convert-latex-to-images.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="latex-to-png latex-to-bmp latex-to-tiff latex-to-jpeg" >}}

{{% blocks/products/pf/feature-page-section  h2="LaTeX to PDF Conversion" %}}

Process of LaTeX to PDF conversion is same as images, except that API provides [PdfSaveOptions](https://apireference.aspose.com/tex/java/com.aspose.tex.rendering/PdfSaveOptions) for setting specific PDF options. 


{{% blocks/products/pf/feature-page-code h3="C# Code for LaTeX to PDF Conversion" %}}

{{< gist "aspose-com-gists" "a94cd0f5d4e008d2f9a334004e5a3743" "latex-to-pdf-conversion.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convert LaTeX to XPS" %}}

Here is the way for converting TeX (LaTeX) to XPS Programmatically via Java. Firstly create [TeXOptions](https://apireference.aspose.com/tex/java/com.aspose.tex/TeXOptions) object to create conversion options for Object LaTeX format. Set system working directory for the output using [OutputWorkingDirectory](https://apireference.aspose.com/tex/java/com.aspose.tex/TeXOptions#getOutputWorkingDirectory--)
Specify XPS format options using [XpsSaveOptions](https://apireference.aspose.com/tex/java/com.aspose.tex.rendering/XpsSaveOptions) and run TeXJob method for LaTeX to XPS conversion.

{{% blocks/products/pf/feature-page-code h3="C# Code for Tex to XPS Conversion" %}}

{{< gist "aspose-com-gists" "a94cd0f5d4e008d2f9a334004e5a3743" "convert-latex-to-xps.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}