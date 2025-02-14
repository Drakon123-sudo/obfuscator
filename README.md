📜 Obfuscator Usage Instructions

🛠 STEP 0: File Preparation

Download the following 3 files into one folder:
— obfuscator.py
— script.py
— runner.py

🔐 STEP 1: Code Obfuscation

Run obfuscator.py → select option 1 (obfuscation).
Enter the name of your file without .py (for example, for test.py enter test).
After execution, the following will appear in the folder:
— test_obfuscated.py
— test_obfuscated_obfuscated.py
Run obfuscator.py again → select option 2 (creation of binaries with quantum encryption).
Enter the file name (e.g., test) → select file type by number 2 (this is test_obfuscated_obfuscated.py).
In the dumps folder, 3 binary files with encrypted code will be created.

📥 STEP 2: Loader Creation

Run script.py.
Specify runner.py.
Enter 3 links to your binaries (example):
— https://example.com/part_1.bin
— https://example.com/part_2.bin
— https://example.com/part_3.bin
Receive the ready-made loader.py file.

🚀 STEP 3: Launch or Build

You can:
— Install imports -> (bz2, secrets, math, random, marshal, requests, os, zlib, base64, tempfile)
— Run loader.py as a regular script from any folder.
— Build into .exe using tools like auto-py-to-exe, PyInstaller, etc.
— If you are going to build into .exe, specify these libraries:
(bz2, secrets, math, random, marshal, requests, os, zlib, base64, tempfile)
(command for pyinstaller --noconfirm --onefile --windowed --hidden-import=os --hidden-import=requests --hidden-import=base64 --hidden-import=tempfile --hidden-import=zlib --hidden-import=marshal --hidden-import=random --hidden-import=math --hidden-import=secrets --hidden-import=bz2 "C:\obf\loader.py")

ℹ Important Notes:

— All files for successful obfuscation must be in the same folder.
— For publication, upload the binaries (part_1.bin, part_2.bin, part_3.bin) to your hosting.
— If something went wrong, check if there are any typos in the file names.
— The file for obfuscation should not be small. It should contain at least a couple of methods for correct obfuscation.
— Python version MUST be 3.13.+
— Please - if the obfuscator doesn't work, write to me, I will try to fix it.
— This is not a complete version of the obfuscator, but in the future, dynamic loading of methods and many different features will be added.
