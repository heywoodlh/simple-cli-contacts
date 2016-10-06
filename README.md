# simple-cli-contacts
Super simple BASH based contact viewer, which easily searches all contacts in vcard file. 

Contact Prompt Description:
GUI application that lists all contacts within the .vcf file and copies cell phone numbers to clipboard. Can be set as a hotkey for easy access.

Dependencies:
rofi
xclip

Compatible only with vcard .vcf files. 


To get a .vcf file from Google Contacts:
Go to https://www.google.com/contacts/ and export desired contacts in a vcard format (for importing into Apple Address Book or another application).

To use contact-prompt:
1. Move .vcf file to ~/.contacts.vcf
2. Execute contact-prompt

Optional: 
1. Place contact-prompt in $PATH to make it a command
