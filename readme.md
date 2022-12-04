# S3 Folder Backup

Have capacity to back up your server files and folders to AWS S3

<code>

    config =
      {
        "DIR": "",# your server/folder dir
        "AWS_ACCESS_KEY_ID": "", #aws access key
        "AWS_SECRET_ACCESS_KEY": "",#aws secret key
        "DELETE_LOCAL": "" #want to delete backup file from local system
      }

    s3_folder_backup(config).upload()

</code>

You can easily upload folders with it.
