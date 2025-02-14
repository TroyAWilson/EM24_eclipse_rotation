# Eclipse Rotation

This is a Jupyter Notebook project and so a Jupyter enviornment will need to be setup before running the files.

This project does not contain the images themselves to keep the file size of the upload small but the following "observatorys" response IDs were used:

- R_3q1mNwx9K1zxvSU
- R_7jGQA5ayN3PAhaf
- R_5dhtl8su64RaocV
- R_7k6XR4OEpKYEnDH
- R_5lFYtlCG2wujlAl
- R_5L5JBcvfy565rah
- R_32LU6pKyipqNvLD
- R_2eJ8rlmbu9gZfGx
- R_2eJITUgec9aZ3tT
- R_5DdR4Wt0OJop3EJ
- R_7Pc9Yj1CmydXAMu
- R_1Jbdw0E8TUxdKWM
- R_1zdrnQVQUkXDHOV
- R_7MlFvQlgFdmd7bE
- R_2L07kIwcnXtVMd6
- R_6hy6qqKQPq05yc0
- R_2S2dEePywJi8GwM
- R_7ZJcSLE1ZxoMGtP
- R_5SzojpZwnCWabx7
- R_3rZCcwsix3oIlBH
- R_6YucibykX0bINI5
- R_2rVr5UeXwodCGdR
- R_39nNvR4eAMvamwA
- R_1opy0w14H2UMh1p
- R_3QJppz1FmWGTrJV

## Folders
- JPGs:
    - Landing for JPGs created by toJPG.ipynb
- test_exif: 
    - Folder that contains exiftool as well as a notebook that executes exiftool to programmatically obtain the time for the images.

## Files
- big_loop.ipynb: 
    - The primary file that runs the rotational code originally built in SN.ipynb on all files
- data.csv
    - Used as input to exif.ipynb for setting up data_w_times.csv in the exif folder
- out_final.csv:
    - final product that contains the name of the jpg and associated offset angle
- out_new.csv
    - output of big_loop contains folder name, file name, and offset angle.
- out_new.csv.backup
    - backup of out_new
- requirements.txt
    - packages that are required to run this notebook
- SN.ipynb
    - The singular version of big_loop, there may be some functions here that are out of date.
- toJPG.ipynb
    - Takes the results of big_loop and converts all the images into JPGs (was useful for the students working on the data)