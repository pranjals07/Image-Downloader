# Google Image Downloader

This project is a Python-based script to download images from Google automatically. It allows users to fetch images based on parameters like the number of images, type, and other customizations.

---

## Prerequisites

To run this project, ensure you have the following installed:

1. **Python 3.x**
2. Required Python packages (listed in `requirements.txt`):
   - `requests`
   - `beautifulsoup4`
   - Any other dependencies required by the script.

Install dependencies with:
```bash
pip install -r requirements.txt
```

---

## Setup

1. Clone or download the repository:
   ```bash
   git clone https://github.com/yourusername/google-image-downloader.git
   cd google-image-downloader
   ```

2. Create a `.env` file with your environment variables, if required. For example, add proxy settings or Google API keys (if applicable).

---

## Usage

To download images, run the script `google_image.py` with the required parameters:

```bash
python google_image.py --query "your search term" --limit 50
```

### Parameters:

- `--query`: The search term or keywords for the image search (**required**).
- `--limit`: Number of images to download (**default**: 10).

### Example:

To download 20 images of puppies:
```bash
python google_image.py --query "puppies" --limit 20
```

---

## Features

- **Customizable Search**: Specify the search term and number of images.
- **Automated Fetching**: Downloads images automatically based on user-defined parameters.
- **Flexible Settings**: Supports proxy and API key configuration via `.env` file.

---

## File Structure

- `google_image.py`: Main script to download images.
- `README.md`: This file.

---

