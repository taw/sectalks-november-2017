To generate the challenge:

    $ ./gen_image "theanswer" "encryptionkey"

It will generate `image.bmp.aes128ecb`, encrypted with key "encryptionkey" with text "The answer is theanswer" on the image.

The script requires ImageMagick and openssl installed.
