# Veracode Python HMAC Example

A simple example of usage of the Veracode Python API signing library provided in the [Veracode Documentation](https://docs.veracode.com/r/c_hmac_signing_example_python).

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

## Note

By default the example works for customers in the Veracode US Commercial Region (login page is https://analysiscenter.veracode.com). For customers in other regions, please comment out line 6 and uncomment either line 7 or line 8. For an example of code that automatically switches to the correct region, see the project [Veracode-api-py](https://github.com/veracode/veracode-api-py).
