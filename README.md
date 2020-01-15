# Veracode Python HMAC Example

A simple example of usage of the Veracode API signing library provided on the [Veracode Help Center](https://help.veracode.com/reader/LMv_dtSHyb7iIxAQznC~9w/cCoBmgWWxUM4hOY54dTqgA).

## Setup

Clone this repository:

    git clone https://github.com/veracode/veracode-python-hmac-example.git

Install dependencies:

    cd veracode-python-hmac-example
    pip install -r requirements.txt

(Optional) Save Veracode API credentials in `~/.veracode/credentials`

    [default]
    veracode_api_key_id = <YOUR_API_KEY_ID>
    veracode_api_key_secret = <YOUR_API_KEY_SECRET>

## Run

If you have saved credentials as above you can run:

    python example.py
    
Otherwise you will need to set environment variables before running `example.py`:

    export VERACODE_API_KEY_ID=<YOUR_API_KEY_ID>
    export VERACODE_API_KEY_SECRET=<YOUR_API_KEY_SECRET>
    python example.py
