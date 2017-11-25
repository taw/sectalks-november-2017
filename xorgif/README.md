To create challenge:

    $ ./xor_image "password" source.gif encrypted.gif

As xor encryption is same as decription, you can decrypt it same way:

    $ ./xor_image "password" encrypted.gif plaintext.gif

The script isn't specific to GIFs, it's going to work just as well for any file type.
For easy challenges, best if it has well defined magic header. If there's a lot of zeroes, it might even be too easy.
