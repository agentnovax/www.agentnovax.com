# AgentNovaX Assets

This directory (`assets/`) is designated for storing all public assets related to the AgentNovaX project. These assets are used across the project for branding, marketing, and UI/UX purposes.

## Folder Structure

To maintain organization and ensure quick access, the `assets/` folder is divided into the following subdirectories:

### 1. `logos/`
- **Purpose**: Contains all logo files used for branding.

### 2. `banners/`
- **Purpose**: Includes banners used for the website, blog, and social media.

### 3. `videos/`
- **Purpose**: Stores video files for promotional or tutorial purposes.

### 4. `icons/`
- **Purpose**: Contains icons used throughout the application UI.

### 5. `og-images/`
- **Purpose**: Stores Open Graph (OG) images for social media sharing.

### 6. `misc/`
- **Purpose**: Holds miscellaneous assets that do not fit into the other categories.

## Guidelines for Adding Assets

1. **File Naming**:
   - Use clear and descriptive names.
   - Use lowercase letters and separate words with hyphens (e.g., `feature-video-preview.mp4`).
   
2. **File Formats**:
   - Use SVG for scalable vector graphics when possible.
   - Use PNG or JPEG for high-quality raster images.
   - Use MP4 for videos.

3. **Storage Location**:
   - Place the asset in the appropriate subdirectory based on its type and purpose.

4. **Versioning**:
   - Append version numbers to filenames if multiple versions exist (e.g., `homepage-banner-v2.jpg`).

## Recommended Practices

- **Optimize Assets**:
  Use tools to compress images and videos before adding them to reduce loading times.

- **Keep Licensing Information**:
  If an asset requires attribution or is under a specific license, include the details in a text file within the same subdirectory (e.g., `icons/LICENSE.txt`).

- **Centralized Reference**:
  Always refer to assets using relative paths in the project to ensure portability and consistency.

## Example Usage

### HTML Example
```html
<img src="/assets/logos/agentnovax-logo.svg" alt="AgentNovaX Logo" />
```

### CSS Example
```css
.banner {
  background-image: url('/assets/banners/homepage-banner.jpg');
}
```

## Contribution

If you are adding or modifying an asset, please ensure:
- You follow the naming conventions and guidelines above.
- You update this README if new categories or rules are introduced.

## Contact
For any questions or suggestions, reach out to the project maintainer.

## License
License: Creative Commons Attribution 4.0 International (CC BY 4.0)
