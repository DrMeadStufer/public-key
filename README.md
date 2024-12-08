This is my public key, which you can use to verify the authenticity of the files I send. 

To verify the files I send, you can use a program like Kleopatra, a free encryption and signing tool. Other similar tools can also be used, and the steps will be largely the same.

If you're downloading content from one of my GitHub repositories, GitHub will have already verified the files using my public key.

This guide assumes you're using Kleopatra, but the general process is similar with other tools.

Download and install Kleopatra. Then, download the .asc key file from this repository

Open Kleopatra.
---------------
![Annotation 2024-12-08 023316](https://github.com/user-attachments/assets/9293299a-608b-4f93-b628-414ee7727908)
Then, click 'Import' and select the .asc file you downloaded from this repository

Next, navigate to any content I've sent you. I always include a .sig certificate with the files.
------------------------------------------------------------------------------------------------
![image](https://github.com/user-attachments/assets/0e7f1298-994e-490f-84f4-f53ac7110204)
Double-click any .sig file. If prompted to select an application, choose Kleopatra. It will automatically verify the authenticity of the signature. A green confirmation means the file is verified. If you don’t see a green confirmation, the content was not sent by me.
