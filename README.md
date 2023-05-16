# Icon Extractor
Icon Extractor is a dynamic-link library (DLL) for extracting icons from files using the Shell32.dll library. It provides developers with a convenient way to retrieve icons of various sizes from specified files, such as 16x16, 32x32, 64x64, and 128x128 pixels.
## Features
- Extract icons from files using Shell32.dll
- Retrieve icons of different sizes (16x16, 32x32, 64x64, 128x128)
- Simplify working with icons in applications
- Easy integration into your C# projects
## Usage
1. Include the libIconExtractor.dll in your C# project.
2. Use the provided `ShellIconExtractor` class to extract icons from files.
3. Specify the file path and icon index to retrieve the desired icon.
4. Call the `GetIcon` method with the desired size parameter to obtain the icon as an `Icon` object.
```csharp
ShellIconExtractor iconExtractor = new ShellIconExtractor(filePath, iconIndex);
Icon icon = iconExtractor.GetIcon(32); // Retrieve a 32x32 icon
```
## Dependencies
- Shell32.dll
## Build
To build the libIconExtractor.dll from source, follow these steps:
1.  Clone this repository.
2.  Open the solution file in your preferred C# development environment.
3.  Build the solution to generate the libIconExtractor.dll file.
## Contribution Rules
Contributions to Icon Extractor are welcome! If you would like to contribute to the project, please adhere to the following guidelines:
-   Fork the repository and create a new branch for your contribution.
-   Make your changes and ensure they are well-tested.
-   Submit a pull request describing the changes you have made.
-   Ensure your code adheres to the project's coding standards and best practices.
-   Provide clear and concise commit messages and documentation for your changes.
## License
This project is licensed under the [MIT License](https://github.com/korayustundag/IconExtractor/blob/main/LICENSE).

Feel free to contribute, open issues, and submit pull requests to help improve the library.
