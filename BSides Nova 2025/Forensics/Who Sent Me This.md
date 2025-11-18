# Who Sent Me This?
You received an [anonymous letter](https://metaproblems.com/8de8d2a81a7eff5506df9d966f158f82/anonymous_letter.pdf), with no sender information included ...

Can you use your PDF knowledge to figure out who wrote it?

# Solution
Downloaded this and due to the premise of the questions its probably in the details using exiftool which pulls metadata from files


Simply using exiftool I found the author, which is the flag
┌──(kali㉿kali)-[~/Desktop]
└─$ exiftool anonymous_letter.pdf      
ExifTool Version Number         : 13.25
File Name                       : anonymous_letter.pdf
Directory                       : .
File Size                       : 49 kB
File Modification Date/Time     : 2025:11:17 17:52:30-05:00
File Access Date/Time           : 2025:11:17 17:57:18-05:00
File Inode Change Date/Time     : 2025:11:17 17:57:18-05:00
File Permissions                : -rw-------
File Type                       : PDF
File Type Extension             : pdf
MIME Type                       : application/pdf
PDF Version                     : 1.7
Linearized                      : No
Language                        : en
Tagged PDF                      : Yes
XMP Toolkit                     : Adobe XMP Core 9.1-c001 79.675d0f7, 2023/06/11-19:21:16
Format                          : application/pdf
Creator                         : MetaCTF{look_you_were_able_to_find_me}
Creator Tool                    : Microsoft Word
Create Date                     : 2024:02:26 14:09:02Z
Modify Date                     : 2025:11:17 17:52:30-05:00
Metadata Date                   : 2025:11:17 17:52:30-05:00
Document ID                     : uuid:852D4F7C-3197-4A0D-B1C5-1412535F5C42
Instance ID                     : uuid:d4b4425e-e262-4934-83b3-165b2bb4888b
Page Count                      : 1
Author                          : MetaCTF{look_you_were_able_to_find_me}
