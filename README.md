# Google Drive Folder Copier

Copy folders and files between Google Drive accounts with size limits and filtering options.

## Features

- Copy files/folders from shared drive to personal drive
- Pagination support (start/end page selection)
- Maximum download size limit
- Exclude files/folders by keyword
- Real-time copy progress display

## Usage

Run in Google Colab and provide:
- Source folder link (shared drive)
- Destination folder link (your drive)
- Page range (optional)
- Max size in GB (default: 700)
- Exclusion keywords (optional)

## Requirements

- Google Colab
- `google-auth`, `google-api-python-client`, `ipywidgets`

## License

MIT License
