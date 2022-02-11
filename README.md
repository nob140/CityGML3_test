# CityGML3_test

Input data: [Sample data](https://github.com/opengeospatial/CityGML-3.0Encodings/files/8046320/base_profile_example.zip) provided by @clausnagel during the [issue](https://github.com/opengeospatial/CityGML-3.0Encodings/issues/60)

Validation tool: VS Code with [XML Extension v0.18.3 by Red Hat](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-xml), and [FZKViewer 6.3 Build 2170](https://www.iai.kit.edu/downloads/Informatik%20f%c3%bcr%20die%20Energiesystemanalyse/FZKViewer-6.3_Build-2170.zip)

Validation results:
* VS Code with XML Extension: All errors are resolved using modified sample data [Building_CityGML3.0_LOD2_with_several_attributes.gml](https://github.com/nob140/CityGML3_test/blob/main/Building_CityGML3.0_LOD2_with_several_attributes.gml) by importing individual .xsd files and avoid uging CityGML.xsd, and describing namespace "core:" explicitly.

* FZKViewer: 204 errors are reported by XML Schema Validation function, and they are not resolved. FZKViewer couldn't save the log file of 204 errors, so only Log Message [Building_CityGML3.0_LOD2_with_several_attributes.logxml](https://github.com/nob140/CityGML3_test/blob/main/Building_CityGML3.0_LOD2_with_several_attributes.logxml) are saved for reference.
