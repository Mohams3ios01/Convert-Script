# Convert-Script

This is a script that can be used to convert pre-trained machine learning models to CoreML compatible models that can be used by Xcode 9 and Swift 4 to develop iOS and macOS tools and apps. 

Simply change whatever needed in the script (file name, path, and other data variables) to your desired scenario and then run `python convert-script.py`. Process can take a while depending on the initial model size.

In this case, it is a caffe model that is being converted. The script is using the coremltools package (installed using pip) to do that conversion.

##### Based on using Python 2.7. You may need to use pip3 or python3 in the terminal to use Python 3.6+ if installed on your machine.
