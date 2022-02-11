# CityGML3_test

Input data: [Sample data](https://github.com/opengeospatial/CityGML-3.0Encodings/files/8046320/base_profile_example.zip) provided by @clausnagel during the [issue](https://github.com/opengeospatial/CityGML-3.0Encodings/issues/60)

Validation tool: VS Code with [XML Extension v0.18.3 by Red Hat](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-xml), and [FZKViewer 6.3 Build 2170](https://www.iai.kit.edu/downloads/Informatik%20f%c3%bcr%20die%20Energiesystemanalyse/FZKViewer-6.3_Build-2170.zip)

Validation result of VS Code with XML Extension: All errors are resolved using modified sample data by importing individual .xsd files and avoid uging CityGML.xsd, and describing namespace "core:"

Validation result of FZKViewer: 204 errors are reported by XML Schema Validation function, and they still remain (not resolved)
