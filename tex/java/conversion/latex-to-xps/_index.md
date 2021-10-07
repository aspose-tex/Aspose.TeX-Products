---
title: Convert LATEX to XPS with Java 
description: Convert TeX files using Java API using On-premise Java library
url: /java/conversion/latex-to-xps/
family: tex
platformtag: java
feature: conversion
informat: LATEX
outformat: XPS
otherformats: PNG JPEG TIFF BMP
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convert LATEX to XPS via Java" h2="TeX to XPS, PNG, JPEG, PDF, TIFF & BMP conversion using On-premise Java library">}}
{{< blocks/products/pf/main-container >}}

{{% blocks/products/pf/agp/content h2="How to Convert LATEX to XPS Using Java" %}}

In order to render LATEX to XPS, we’ll use <a href="https://products.aspose.com/tex/java">Aspose.TeX for Java</a> API which is a feature-rich, powerful and easy to use conversion API for Java platform. You can download its latest version directly from <a href="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-tex">Maven</a> and install it within your Maven-based project by adding the following configurations to the pom.xml.

{{% blocks/products/pf/agp/code-block title="Repository" offSpacer="true" %}}

```cs
<repository>
    <id>snapshots</id>
    <name>repo</name>
    <url>http://repository.aspose.com/repo/</url>
</repository>
```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Dependency" offSpacer="true" %}}

```cs
<dependency>
    <groupId>com.aspose</groupId>
    <artifactId>aspose-tex</artifactId>
    <version>21.4</version>
</dependency>
```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="LATEX to XPS Conversion on Java" %}}
1. Initialize [TeXOptions](https://apireference.aspose.com/tex/java/com.aspose.tex/TeXOptions) to create conversion options for Object LaTeX format
2. In order to set space, or area, where the TeX output will be written, set system working directory for the output using [OutputWorkingDirectory](https://apireference.aspose.com/tex/java/com.aspose.tex/TeXOptions#getOutputWorkingDirectory--)
3. Initialize the options for saving in XPS format using [XpsSaveOptions](https://apireference.aspose.com/tex/java/com.aspose.tex.rendering/XpsSaveOptions)
4. Run LaTeX to XPS conversion using [TeXJob](https://apireference.aspose.com/tex/java/com.aspose.tex/TeXJob) method
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Requirements" %}}
{{% blocks/products/pf/agp/text %}}
Aspose.TeX for Java is supported on all major operating systems. Just make sure that you have the following prerequisites.
{{% /blocks/products/pf/agp/text %}}
- J2SE 8.0 (1.8) or above.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Java Code for LATEX to XPS Conversion" gistPath="" %}}
```cs
// Create conversion options for Object LaTeX format on Object TeX engine extension.
TeXOptions options = TeXOptions.consoleAppOptions(TeXConfig.objectLaTeX());
// Specify the file system working directory for the output.
options.setOutputWorkingDirectory(new OutputFileSystemDirectory("/output"));
// Initialize the options for saving in XPS format.
options.setSaveOptions(new XpsSaveOptions());
// Run LaTeX to XPS format conversion.
new TeXJob("hello-world.ltx", new ImageDevice(), options).run();
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}