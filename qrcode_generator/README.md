## Run this command in terminal/powershell/anaconda powershell prompt to install require packages:

pip3 install -r requirements.txt

## Generate QR code in specific image's name:

python generate_qrcode.py words_want_to_generate_qr_code image_name.png

## Generate QR code with static data define in variable data::String in generate_qrcode_with_control.py to site_inverse.png

python generate_qrcode_with_control.py

## If you want to read a QR code, run read_qrcode.py.

For instance, if you want to read a QR code from a file named anything.png, you can run:

python read_qrcode.py anything.png

## If you want to read QR codes live using your cam, just run -> but may cause some error:

python read_qrcode_live.py
