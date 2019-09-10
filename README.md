Install to `/usr/local/bin`

Setup bash alias like:

    alias awssh='/usr/local/bin/awsser.py -u ubuntu -i ~/.ssh/key.pem -d '

Use like

    # use default aws profile
    awssh servername

    # use another aws profile
    awssh -p work-profile servername