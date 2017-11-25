To generate the challenge:

    ./rotword "key" <plaintext.txt >encrypted.txt

To then decrypt, run:

    ./decrypt "key" <encrypted.txt >decrypted.txt

The encryption process:

* strips diacritical marks
* forces letters to lower case
* forces all spacing to a single space
* removes all characters except letters, numbers, and spaces

So decrypted text won't be the same as input.
