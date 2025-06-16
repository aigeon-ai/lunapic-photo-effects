markdown
# LunaPic Photo Effects MCP Server

## Overview

LunaPic Photo Effects MCP Server provides powerful image editing capabilities directly through a set of well-defined tools. This server offers some of the best art effects from LunaPic.com, allowing users to apply various artistic filters to their images at a high resolution of up to 1500x1500 pixels. With the added feature of automatic background removal using object detection, users can seamlessly enhance their images with minimal effort.

## Key Features

- **High-Resolution Art Effects**: Apply LunaPic's renowned art filters to images, with support for resolutions up to 1500x1500 pixels.
- **Automatic Background Removal**: Utilize object detection to automatically remove backgrounds from images, simplifying the editing process.
- **Diverse Filter Options**: Access over 100 different art effects to customize your images.
  
## Tools Overview

The LunaPic Photo Effects MCP Server offers two main tools for processing images:

1. **Image Upload and Filter Application**:
   - **Function**: `/v2/api-post.php`
   - **Description**: Directly upload an image and apply a chosen filter.
   - **Usage**: Ideal for users who have image files ready for enhancement and wish to apply art effects directly.

2. **Image Processing via URL**:
   - **Function**: `/v2/api-call.php`
   - **Description**: Process an image from a given URL.
   - **Parameters**:
     - **Options**: Optional string parameters, e.g., `keepcolors`.
     - **URL**: String parameter for the image URL (note: max size is 1500x1500 pixels).
     - **Filter**: Specify which LunaPic image filter to use.

These tools enable users to either upload images directly or specify an image URL for processing. The wide range of filters ensures that users can achieve their desired artistic effects with ease.

## Usage

The LunaPic Photo Effects MCP Server is designed to be user-friendly and efficient, providing quick access to high-quality image transformations. With its comprehensive set of tools, users can enhance their photos with professional-grade effects without the need for advanced editing skills. Whether you are looking to add a simple filter or completely transform an image, this server offers the capabilities to meet your needs.

For a full list of available filters and effects, users can explore the tools provided by this server to discover the vast array of customization options available.

---