# File Types

## Steps:

- wget the file
- found out it is shell archive text
- check for any malicous code.
- extract using shar utils -> got a ar file
- extarct using ar -> got a cpio archive(used to create .tar files)
- extracted cpio file -> got bzip2 file(uses burrown-sheeler compresssion and huffomn compression instead of using convetional lz compression)

I thought this will end here. :|

- Extarcted bzip2 file, got a gzip file(uses lz compression)
- Extracted gzip file -> got a lzip file.(.zip ext.)
- Extracted lzip file -> got a lz4 cpmpressed file.(Fast lossless compression algo)

Now, this is getting annoying.....

- Extracted, got a LZMA compressed data.
- Extracted, got a lzop compressed data.
- Extarcted, again got a lzip file.
- Extarcted again got a XZ file.
- Extarcted, finally got a ASCII text.
- It looks like hex, converted it to ASCII. 

Got the key > picoCTF{f1len@m3_m@n1pul@t10n_f0r_0b2cur17y_3c79c5ba}





