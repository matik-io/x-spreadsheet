This is a fork of x-data-spreadsheet

We will rely on uploading a packaged file to our s3 bucket: matik-forked-repo-storage
----------------
✅ Zip & Upload Your Fork to GitHub Releases or S3

# After all changes are ready
yarn pack

This will create a file like:

    x-data-spreadsheet-v1.1.8.tgz

    Upload this .tgz file to:

        A GitHub release (on your fork), or

        S3 or another static URL you control

    In your main project package.json:

"x-data-spreadsheet": "https://your-host/x-data-spreadsheet-v1.1.8.tgz"

    Then:

yarn install
