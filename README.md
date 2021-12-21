# CryptoMe
We hope you find this little GTM utility useful. 

It allows you to create a custom event that passes an encrypted (SHA-256) value together with any other data points you need. 
Useful in creating a user id for google analytics as well as many other uses in identity resolution.

V1.2 : Released 21st Dec 2021
    Bug fix: Resolved issue where string returnd was in npt correctly encoded.

V1.1 : Released 20th May 2020
    Bug fix: resolved exception error thrown when no additional properties are added. 
    
UPDATE 08-09-2021 : We have come across an issue where the Google API for SHA256 is nto returnign a valid base64 encoded result. This means the returned hash is not valid. We will post an update as soon as Google get this fixed. THIS ISSUE IS NOW RESOLVED AS OF V1.2

120Feet | Digital Analytics Consultants | 120feet.com
