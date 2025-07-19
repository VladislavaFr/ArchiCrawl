# ArchiCrawl

ArchiCrawl is an image collection tool designed for the automated gathering of interior design images by style and room type. It helps create high-quality datasets for machine learning and deep learning applications in architecture and interior design.

## Features

- Smart keyword generation (e.g., boho living room, minimalist kitchen, etc.)
- Automatic folder structure creation by style and room type
- Configurable number of images per class
- Throttle control to prevent IP blocking
- Fully customizable and extensible


## Folder Structure Example
```
data/
├── boho/
│   ├── bedroom/
│   ├── kitchen/
│   └── living_room/
├── minimalist/
│   ├── bedroom/
│   ├── kitchen/
│   └── living_room/
...
```
## Installation

1. Clone the repository:
```
git clone https://github.com/VladislavaFr/archicrawl.git
cd archicrawl
```
2. Create a virtual environment and activate it:
```
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```
4. Install the dependencies:
```
pip install -r requirements.txt
```
## Usage

To start crawling images:
```
python archicrawl.py
```
You can configure keywords, number of images, and folder structure inside config.py.

## Disclaimer

> This tool is intended for educational and non-commercial use only. It does not store or distribute any copyrighted materials.
> Source websites are not named or referenced in the codebase.
> Use responsibly and respect the terms of service of any platform you access.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
