# Supermarket Promotion Extractor

This project extracts structured product information (names, prices, discounts) from supermarket promotion advertisement images using **PaddleOCR** and classic **image processing techniques**.

## Features

- OCR extraction using [PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR)
- Image pre-processing (masking, contour detection, thresholding) to isolate regions of interest
- Converts unstructured ad images into structured datasets (CSV/JSON)

## Output

Each ad image is processed to extract:
- Product names
- Prices
- Discounts

## How to Run

1. Clone the repo
2. Install requirements (see notebook)
3. Run the provided **Jupyter notebook** to process sample images

```bash
jupyter notebook supermarket_promo_ocr.ipynb
