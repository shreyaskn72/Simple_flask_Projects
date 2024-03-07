# Flask File Upload API

This Python Flask API allows you to upload files.

## Prerequisites

Before running this API, make sure you have the following installed:

- Python
- Flask

## Installation

1. Clone this repository:
```
git clone <repository_url>
```

2. Install the required dependencies:
```
pip install Flask
```

## Usage

1. Start the Flask server by running the following command:
```
python app.py
```

2. Send a POST request to the `/upload` endpoint with a file attached.

You can use tools like cURL or Postman to send the POST request.

### Example cURL command:

```bash
curl -X POST -F "file=@/path/to/your/file.txt" http://localhost:5000/upload
```

Replace /path/to/your/file.txt with the actual path to the file you want to upload.