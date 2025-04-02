# vRO-Package-Explorer-VS-Code-Plugin
A Visual Studio Code Plugin for VCF Orchestrator (vRO) Packages

## Key Features of This Extension

- File Extraction: Uses adm-zip to extract the .package file contents
- XML Detection: Recursively searches for XML files in the extracted structure
- XML Parsing: Basic parsing to show XML structure information
- User Interface: Clean WebView panel displaying all found XML files
- File Viewing: Ability to view the content of any discovered XML file
- Cleanup: Properly manages temporary files
- vRO Component Detection: Automatically identifies different types of vRO components by analyzing XML structure
- Rich Component Visualization: Organizes components by type in an accordion interface

### Component-Specific Views:

For Workflows: Shows inputs/outputs parameters and category path
For Actions: Shows script content, language, inputs/outputs
For Configurations: Shows properties and their values
For Resources: Shows MIME type and category
For Policies: Shows policy type


## How to Use the Enhanced Extension

- Install and launch the extension
- Run the "vRO Package Explorer: Open .package file" command
- Select a vRO package file (.package)
- Browse the extracted components organized by type
- Click on any component to view its parsed details

This implementation provides a much more convenient way to explore vRO packages than having to manually extract the package and navigate through raw XML files.
