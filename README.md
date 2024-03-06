# Invoice Optical Character Recognition Project

## Project Overview
This project, developed in Python 3, aims to automatically identify and extract information from invoices using Optical Character Recognition technology. It is designed for finance, accounting, and any other fields that require extensive invoice processing, with the goal of increasing efficiency and reducing manual input errors.

## Features
- **Automated Text Recognition:** Utilizes OCR technology to automatically identify text on invoices, including but not limited to invoice numbers, dates, amounts, etc.
- **Supports Various Invoice Formats:** Capable of processing different formats and layouts of invoices, including digital and paper invoices.
- **Data Export:** Recognized data can be exported to CSV files or directly integrated into financial software.
- **User-friendly Interface:** An easy-to-use interface allows users to effortlessly upload and process invoices.

## Getting Started
The following steps will help you set up and run the project quickly.

### Prerequisites
- Python 3
- Other dependencies can be found in the `Pipfile` file.

### Installation
1. Clone the repository to your local machine.
   ```
   git clone https://github.com/dowdah/invoice_ocr.git
   ```
2. Navigate to the project directory and install the required dependencies.
   ```
   cd invoice_ocr
   pipenv install
   ```

### Usage
1. Run the main program.
   ```
   python main.py <path-to-invoice-picture>
   ```
2. The system will process the image and display the recognition results.
3. You may choose to export the results to a CSV file.

## Technical Architecture
- **OCR Engine:** The project uses [Tesseract](https://github.com/tesseract-ocr/tesseract) as the primary OCR engine.
- **Image Processing:** Uses [OpenCV](https://opencv.org/) for initial image processing to improve recognition accuracy.

## Contribution Guide
We welcome all forms of contribution, including but not limited to proposals for new features, bug fixes, documentation updates, etc. Please read `CONTRIBUTING.md` for how to get started.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact
For any questions or suggestions, please contact us through:
- Email: dowdah@sheldonwonderland.top
- GitHub Issues
