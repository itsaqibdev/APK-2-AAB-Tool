# APK to AAB Converter

A professional desktop application to convert Android APK files to Android App Bundle (AAB) format and vice versa. This tool provides a user-friendly interface and supports both Windows and macOS platforms.

![APK2AAB Converter](screenshots/app.png)

## Features

- 🔄 Convert APK to AAB format
- 🔄 Convert AAB back to APK format
- 🖥️ Cross-platform support (Windows & macOS)
- 🎨 Modern and intuitive user interface
- 📝 Detailed conversion logs
- ⚡ Fast and efficient processing

## Requirements

- Java 11 or later installed on your system
- Minimum 4GB RAM recommended
- At least 1GB free disk space

## Installation

### Windows
1. Download `APK2AAB-Universal.zip`
2. Extract the ZIP file to your desired location
3. Double-click `APK2AAB.bat` to run the application

### macOS
1. Download `APK2AAB-Universal.zip`
2. Extract the ZIP file
3. Open Terminal in the extracted directory
4. Make the launcher executable:
   ```bash
   chmod +x APK2AAB.sh
   ```
5. Run the application:
   ```bash
   ./APK2AAB.sh
   ```

## Usage

### Converting APK to AAB
1. Launch the application
2. Select "APK to AAB" from the dropdown menu
3. Click "Browse" next to "Input File" and select your APK file
4. Click "Browse" next to "Output File" to choose where to save the AAB file
   - The output location will be automatically suggested based on the input file
5. Click "Convert" to start the conversion process
6. Monitor the progress in the log area
7. Once complete, you'll find your AAB file in the specified location

### Converting AAB to APK
1. Launch the application
2. Select "AAB to APK" from the dropdown menu
3. Click "Browse" next to "Input File" and select your AAB file
4. Click "Browse" next to "Output File" to choose where to save the APK file
5. Click "Convert" to start the conversion process
6. Monitor the progress in the log area
7. Once complete, you'll find your APK file in the specified location

## Troubleshooting

### Common Issues

1. **Java Not Found**
   - Error: "java is not recognized as an internal or external command"
   - Solution: Install Java 11 or later from [Oracle's website](https://www.oracle.com/java/technologies/downloads/)

2. **Permission Denied (macOS)**
   - Error: "Permission denied" when running APK2AAB.sh
   - Solution: Run `chmod +x APK2AAB.sh` in Terminal

3. **Invalid Input File**
   - Error: "Invalid input file format"
   - Solution: Ensure you're using a valid APK or AAB file

4. **Tools Not Found**
   - Error: "aapt2 not found" or "bundletool not found"
   - Solution: Ensure the `tools` directory is in the same folder as the JAR file

### Still Having Issues?
- Check if Java is properly installed by running `java -version` in Terminal/Command Prompt
- Verify that all files from the ZIP package are extracted to the same directory
- Make sure you have write permissions in the output directory
- Check the log area for detailed error messages

## Technical Details

The application uses the following tools and libraries:
- AAPT2 (Android Asset Packaging Tool 2)
- Bundletool
- Java Swing for the user interface
- Apache Commons IO for file operations

## Contributing

Feel free to submit issues and enhancement requests!

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Developer

Developed with ❤️ by Muhammad Saqib (iTSaqibdev)

- 🌐 [Fiverr](https://fiverr.com/itsaqibdev)
- 💻 [GitHub](https://github.com/itsaqibdev)

## Version History

- v1.0 (2025-01-15)
  - Initial release
  - Cross-platform support
  - Modern UI
  - Bidirectional conversion support
