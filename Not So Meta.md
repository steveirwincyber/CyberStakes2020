# Not So Meta
# Points: 50
### Look, it's the flag! Oh wait...it looks like we need to take a closer look... not_so_meta.jpg
### [Solution]
    When running a hexedit on the file it appears that it has exif properties
    downloaded the exiftool and ran it against the photo with a stamp "Its The Flag" was the value "QUNJezI3Mjg0NDcxNjc4MjBiMDk0MWIwYWE4MDc0Zn0="
    This decoded using Base64 gave us the flag
    Flag:ACI{2728447167820b0941b0aa8074f}
