# LPTANDRO

### Description
LPTANDRO is a tool that automates the process of scanning and analyzing Android applications using AndroBugs and MobSF frameworks. It uploads the APK file to MobSF, extracts various security reports and outputs them into a selected folder.

### Prerequisites
- Python 2
- MobSF
- Androbug

### Installation
To install the script, simply clone or download the repository.

````
git clone https://github.com/SrirammananS/LPTANDRO.git
````

To run the script, make it executable and run it.

Make sure the script has execute permissions, if not you can run this command to give execute permissions to the file

````
cd LPTANDRO
chmod +x LPTANDRO 
./LPTANDRO
````

### Usage
Once you have run the script, it will do the following:

- Check if the required dependencies are installed.
- Prompt the user to select the APK file if no file path was provided.
- Extract the APK file and analyze it with AndroBugs.
- Start MobSF on the specified port and get the API key.
- Upload the APK file to MobSF.
- Analyze the APK file using MobSF API.
- Extract various security reports and save them in the selected folder.
 
### License
This project is licensed under the MIT License - see the [LICENSE](https://github.com/SrirammananS/LPTANDRO/blob/main/licence) file for details.
