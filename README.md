# Cyber-ANZ
This repository contains solutions to all the Tasks in Cyber@ANZ virtual internship provided by InsideSherpa

These documents and images were extracted from the pcap file provided using WireShark and HxD software.

My observations and Findings while extracting these files are:

1. Hex code for .jpg image file starts from ffd8 and ends with ffd9.

2. Steps to be followed for extracting PDF files from HTTP stream in WireShark:

Step 1). Open the pcap file and filter out the data packets to show only http stream. This can be done by simply writing http in the search bar after opening the pcap file.

Step 2). Look for the file you want to extract and find the packet it is communicating with. This van be done by clicking on the file to be extracted and seeing the GET description.

Step 3). Click on the GET file that was communicating with the file to be extracted and right click on "Media Type". This option will be available in the dialog box below the one showing HTTP stream. Then select "Export Packet Bytes" from the pull down menu and save the file with a proper extension (like .jpg/.png/.pdf/.doc etc)

Step 4). Now go the location where you saved the file and open it. You will be able to see the contents of the extracted document/image.

**PLEASE NOTE: All the Files uploaded here are geniune work of the auther and copying or duplication is NOT ALLOWED.**

**This Repository is only for your refrence and help. KEEP LEARNING :)**
