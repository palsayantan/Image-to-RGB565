# Image to RGB565 Converter

Convert JPG/PNG images to RGB565 `.h` header files for Arduino TFT displays.

## Live Demo

**[Open Converter](https://palsayantan.github.io/Image-to-RGB565/)**

## How to Use

1. Upload your image
2. Download the `.h` file
3. Include in Arduino: `#include "image_data.h"`
4. Display: `tft.pushImage(x, y, IMAGE_DATA_WIDTH, IMAGE_DATA_HEIGHT, image_data);`

## Troubleshooting

If colors look wrong, switch the byte order setting.

## License

MIT
