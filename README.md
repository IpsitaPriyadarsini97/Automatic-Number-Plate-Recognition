# Automatic Number Plate Recognition (ANPR)

An Automatic Number Plate Recognition system built using YOLOv8 and EasyOCR.

## Features

- Detects vehicle license plates from images
- Reads registration-number text using OCR
- Draws a bounding box around the detected plate
- Uses image preprocessing to improve OCR output

## Technologies Used

- Python
- Google Colab
- YOLOv8 (Ultralytics)
- EasyOCR
- OpenCV
- Roboflow Dataset

## Workflow

1. Upload a vehicle image.
2. YOLOv8 detects the license plate.
3. The detected plate region is cropped.
4. EasyOCR extracts the plate number.
5. The final output displays the bounding box and plate text.

## Files

- `Automatic_Number_Plate_Recognition.ipynb` — complete project notebook
- `best.pt` — trained YOLOv8 model
- `anpr_result.jpg` — sample output image

## How to Run

1. Open the notebook in Google Colab.
2. Run all cells in order.
3. Upload or select a vehicle image.
4. The model will detect and read the number plate.

## Dataset

The license plate dataset was obtained from Roboflow in YOLOv8 format.
