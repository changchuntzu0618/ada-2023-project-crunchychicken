# How to get the data
All the raw data should go in `./data/`.

To get the data:

    1. Delete the content of the data folder (keep the folder and `data/.gitkeep`)
    1. Download the raw data from the Google [Drive folder](https://drive.google.com/drive/folders/1xeeJxvuIyu738Bd2ev_Ex49Af8lDv9pw?usp=sharing).
    2. Put the compressed file in the root directory.
    2. Decompress the file using `$ tar -xvf data.tar.gz data/`

# How to update the data
To change the data folder:

    1. Do the changes on your local folder
    2. Compress the folder using `$ tar -cvf data.tar.gz data/`
    3. Delete the old compressed file from the drive
    4. Upload the compressed file to the drive
    5. Notify the others
