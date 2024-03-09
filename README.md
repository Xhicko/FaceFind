# FaceFind

FaceFind is a Python project that integrates OpenCV for facial recognition and SendGrid for email notifications. With this project, you can detect faces within datasets and receive immediate email alerts upon recognition.

## Features

- Utilizes OpenCV for robust facial recognition.
- Integrates SendGrid for seamless email notification delivery.
- Easily configurable for various datasets and email settings.
- Ideal for security systems and experimentation.

## Getting Started

To get started with FaceFind, follow these steps:

1. Clone the repository to your local machine.
2. Install the necessary dependencies by running `pip install -r requirements.txt`.
3. Configure the dataset and email settings according to your requirements.
4. Run the `facefind.py` script to start detecting faces and receiving email alerts.

## Usage

```bash
python facefind.py
```

## Configuration

Modify the `config.py` file to adjust the dataset path and email settings:

```python
# Dataset path
DATASET_PATH = 'path/to/your/dataset'

# SendGrid API key
SENDGRID_API_KEY = 'your_sendgrid_api_key'

# Sender and recipient email addresses
SENDER_EMAIL = 'sender@example.com'
RECIPIENT_EMAIL = 'recipient@example.com'
```

## Dependencies

- OpenCV
- SendGrid

## Contributing

Contributions are welcome! Feel free to submit pull requests or open issues if you encounter any problems.
