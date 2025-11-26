# The SwiftXML Project

The SwiftXML project provides a suite of packages implemented in the [Swift programming language](https://www.swift.org) that complement each other to enable the processing and transformation of XML documents.

See the documentation of the [SwiftXML](https://github.com/swiftxml/SwiftXML) repository and the sample application [SwiftXMLExample](https://github.com/swiftxml/SwiftXMLExample).

The sample application also uses the [Pipeline](https://github.com/swiftxml/Pipeline) framework which is part of the SwiftXML project and which can be used for constructing a pipeline to process a single work item.

The inventor and project lead of SwiftXML is [struktaris](https://struktaris.de). An important supporter and user of SwiftXML is the [German Institute for Standardization (DIN)](https://www.din.de/en), mainly by its subsidiary [DIN Solutions](https://dinsolutions.de).

Most project parts have previously been published on [another GitHub account](https://github.com/stefanspringer1) (their version numbers have been reset to 1.0.0 when initiating them here).

There is a [roadmap](https://github.com/swiftxml/Roadmap)) for things that should or could come for the SwiftXML project; it also includes a list of known issues.

The following repositories are part of the SwiftXML project:

## XML

1. [SwiftXMLInterfaces](https://github.com/swiftxml/SwiftXMLInterfaces): A libray for some interfaces to be useful in XML projects.
2. [SwiftXMLParser](https://github.com/swiftxml/SwiftXMLParser): A non-validating parser for XML files encoded in UTF-8.
3. [SwiftXML](https://github.com/swiftxml/SwiftXML): A library written in Swift to process XML.
4. [Libxml2Validation](https://github.com/swiftxml/Libxml2Validation): A small C project for the validation of XML documents using libxml2.

## Pipeline

5. [Localization](https://github.com/swiftxml/Localization): Tools for localization.
6. [Pipeline](https://github.com/swiftxml/Pipeline): A simple framework for constructing a pipeline to process a single work item.
7. [PipelineExtensionsForSwiftXML](https://github.com/swiftxml/PipelineExtensionsForSwiftXML): Extension of the Pipeline package for SwiftXML.

## Logging

8. [LoggingInterfaces](https://github.com/swiftxml/LoggingInterfaces): The interface to a common logger.
9. [PipelineLoggingBinding](https://github.com/swiftxml/PipelineLoggingBinding): A binding of the LoggingInterfaces to the Pipeline library.
10. [BasicLogging](https://github.com/swiftxml/BasicLogging): A small multi-platform logging library.
11. [PipelineBasicLogging](https://github.com/swiftxml/PipelineBasicLogging): Implements the use of BasicLogging for the Pipeline library.

## Tools

12. [LoopsOnOptionals](https://github.com/swiftxml/LoopsOnOptionals): Mini library to extend optional chains to include for-loops.

## Wrapper

13. [SwiftXMLComplete](https://github.com/swiftxml/SwiftXMLComplete): SwiftXML with common packages (but [LoopsOnOptionals](https://github.com/swiftxml/LoopsOnOptionals) would need to be added as a separate dependency).

## Example

14. [SwiftXMLExample](https://github.com/swiftxml/SwiftXMLExample): A sample project to show how to use SwiftXML and the Pipeline package.

## Planning

14. [Roadmap](https://github.com/swiftxml/Roadmap): A roadmap of things that should or could come for the SwiftXML project.
