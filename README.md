# imgremap

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A web-based tool for correcting perspective and remapping images using a four-point transformation.

## Demo

https://code4fukui.github.io/imgremap/

The tool presents a two-panel interface. The left panel displays the source image where you select four points, and the right panel shows the real-time result of the transformation.

## Features

-   **Interactive Point Selection:** Click on the source image to define four corner points.
-   **Perspective Correction:** Remaps the quadrilateral area defined by the four points into a rectangular output.
-   **Coordinate-based Fine-tuning:** Manually adjust the X/Y coordinates for each point for precise control.
-   **Custom Output Size:** Specify the exact width and height of the resulting image.
-   **Live Preview:** The transformed image updates instantly as you adjust points or dimensions.
-   **Drag & Drop:** Easily load your own images by dragging them onto the page.

## Usage

1.  **Load an Image:** Drag and drop your image file onto the application window, or use the pre-loaded sample image.
2.  **Select Four Points:** Click on the source image (left canvas) to select four points in the following order:
    -   `p0`: Top-Left
    -   `p1`: Top-Right
    -   `p2`: Bottom-Right
    -   `p3`: Bottom-Left
3.  **Adjust and Refine:**
    -   Fine-tune the coordinates using the `p0` through `p3` input fields.
    -   Set the desired output `width` and `height` in the fields below the right canvas.
4.  **View Result:** The remapped image is automatically generated and displayed on the right canvas.

## Related Project

https://github.com/code4fukui/imgrotate/

## License

MIT License