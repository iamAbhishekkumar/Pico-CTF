# Information

## Steps

* wget the provided [file](https://mercury.picoctf.net/static/149ab4b27d16922142a1e8381677d76f/cat.jpg)

* got a cat.jpg
* tried "41_ff_rrrrrrrrfffmmm_MDY02_EPI_6037" as flag but failed.
* tried to get meta data from image magic but found nothing
* tried to get extarct metadata from "exiftool", got a License.
* thought taht it is hex, but it is not.
* considering as base 64 encoding, found the flag after decoding that.

Got the flag : picoCTF{the_m3tadata_1s_modified}