# pypassport

Read biometric passport data via NFC using Python 3.

[Forked from the original](https://github.com/roeften/pypassport)

## Howto

1. Download this code / clone this repo.
1. Install the requirements with `pip3 install -U setuptools PyCryptodome pyasn1 pyscard Pillow
1. Edit `scan.py` and add your passport's number, your date of birth, and your document's expiry date.
1. Plug in your NFC reader.
1. Place your passport on the NFC reader.
1. Run `python scan.py`
1. You will see some debug data.
1. The code will save a JPG of the photo, metadata about the photo, and data from the Machine Readable Zone.

## Further Reading

[Reading NFC Passport Chips in Linux](https://shkspr.mobi/blog/2025/06/reading-nfc-passport-chips-in-linux/)
