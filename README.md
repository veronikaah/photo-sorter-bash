# photo-sorter-bash
## Photo sorter CLI
Simple bash script for automatic photo sorting into synoptical structure of directories based on year and month of creation.

## How does it work
Script loads EXIF data from source directory and automatically moves it in target directory in following structure: Target_directory/YEAR/MONTH/photo.jpg
# Requirements
* **Bash**
* **exiftool**
  
# How to use
Script is executed in terminal with two arguments: source directory and target directory.

```bash
chmod +x sort_photos.sh
./sort_photos /source /target
```

# Technologies
* Bash
* UNIX CLI & ExifTool
