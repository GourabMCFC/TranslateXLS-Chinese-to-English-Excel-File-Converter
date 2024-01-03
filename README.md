# TranslateXLS - 🌐 Chinese to English Excel File Converter

## Overview

TranslateXLS is a Python script designed to translate the content of a Chinese Excel file (in Traditional Chinese) to English. It utilizes the Google Translate API through the `deep-translator` library and is intended for use in a Google Colab environment.

## Features

-   **Excel Translation**: 📊 Translates the content of a Chinese Excel file to English.
-   **Column Name Translation**: 🏷️ Translates the column names to English.
-   **Handling NaN Values**: 🚫 Replaces NaN values with an empty string.
-   **Numeric String Handling**: 🔢 Avoids unnecessary translation for numeric strings.

## Prerequisites

-   Python 3.x
-   `deep-translator` library
-   Google Colab environment

## Installation

```bash
pip install -U deep-translator
```

## Usage

1. **Upload your Chinese Excel file in the Colab environment.**
2. **Run the provided Python script.**

## Code Structure

-   **File:** `Chinease_To_English_Excel_File_Converter.ipynb`
-   **Dependencies:**
    -   `pandas`
    -   `deep_translator`
    -   `time`
    -   `io`
    -   `google.colab`

## Performance

The script measures the time taken for translation and saving and prints the duration.

## Output

The translated Excel file is saved as **translated_sheet.xlsx**.

## Acknowledgments

-   This script uses the Google Translate API through the `deep-translator` library.
-   Original file: [Colab Notebook](https://colab.research.google.com/drive/1hLNNr2Esa0LC32GU7a9EFc7zKEhWfuyt)
