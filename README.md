# photo-sorter-bash
## Photo sorter CLI
Simple bash script for automatic photo sorting into a clear directory structure based on the year and month of creation.

## How does it work
Script loads EXIF metadata from files in the source directory and automatically moves them to the target directory in the following structure: `Target_directory/YEAR/MONTH/photo.ext`.

> **Note on ExifTool:** I am aware that `exiftool` natively supports file organization via its built-in `-Directory` flags. However, I wrote this script intentionally as a hands-on exercise to practice Bash scripting, recursion, error handling, and working with UNIX CLI utilities.

## Requirements
* **Bash**
* **exiftool**
  
## How to use
Script is executed in terminal with two arguments: source directory and target directory.

```bash
chmod +x sort_photos.sh
./sort_photos.sh /path/to/source /path/to/target