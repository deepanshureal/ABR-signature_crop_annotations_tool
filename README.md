# Signature Crop Annotations Tool

A web-based tool for annotating JPG images with text and date/time metadata, creating JSON files for each annotation.

## Features

- 📁 **Folder-based workflow**: Select a folder containing JPG images
- 🖼️ **Image viewer**: Browse through images with Previous/Next navigation
- ⌨️ **Keyboard shortcuts**: 
  - `P` - Previous image
  - `N` - Next image
  - `Enter` - Save annotation
- 📝 **Dual text inputs**: Add text content and date/time for each image
- 💾 **JSON output**: Saves annotations as JSON files in the same folder
- ✅ **Progress tracking**: Visual indicators for processed/unprocessed images
- 📊 **Statistics sidebar**: Track overall progress and completion percentage
- 🔄 **Edit capability**: Load and modify existing annotations

## Requirements

- Modern web browser (Chrome or Edge recommended for full functionality)
- File System Access API support for direct folder operations

## Usage

1. Open `index.html` in Chrome or Edge browser
2. Click "Load All Images" or "Load Unannotated Only"
3. Select the folder containing your JPG images
4. Navigate through images using buttons or keyboard shortcuts
5. Enter text and date/time information
6. Press Enter or click "Save & Mark Complete" to save the annotation
7. JSON files are saved directly in the same folder as the images

## JSON Format

Each annotation creates a JSON file with the same name as the image:

```json
{
    "text": "Your text content here",
    "date": "MM/DD/YYYY HH:MM AM/PM"
}
```

## Browser Compatibility

- **Full functionality**: Chrome, Edge (Chromium-based browsers)
- **Limited functionality**: Firefox, Safari (downloads files instead of direct folder save)

## Development

This is a client-side only application with no server requirements. Simply open the HTML file in a supported browser to use.

## License

Proprietary - ABR Internal Use Only