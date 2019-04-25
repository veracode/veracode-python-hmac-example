# Veracode Python HMAC Example

A simple example of usage of the Veracode API signing library provided on the [Veracode Help Center](https://help.veracode.com/reader/LMv_dtSHyb7iIxAQznC~9w/cCoBmgWWxUM4hOY54dTqgA).

## Setup

Clone this repository:

    git clone https://github.com/ctcampbell/veracode-python-hmac-example.git

Install dependencies:

    cd veracode-python-hmac-example
    pip install -r requirements.txt

Save Veracode API credentials in `~/.veracode/credentials`

    [default]
    veracode_api_key_id = <YOUR_API_KEY_ID>
    veracode_api_key_secret = <YOUR_API_KEY_SECRET>

## Run

    python example.py
