# EuropresseScraper

Exploits a vulnerability in Europresse that allows access to content without logging in.
Scrap the day's newspaper frame by frame, puts them in a PDF and sends it by email.

## Installation

Clone this repository and install dependencies :
```bash
pip install pillow fpdf
```

## Usage

Put your information in the file send_mail.py :
```python
    sender_email = "sender_email"
    receiver_email = "receiver_email"
    password = "sender_password"
```
Run it !

```python
python main.py
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[GPLv3](https://choosealicense.com/licenses/gpl-3.0/)