# workaround-dynamic-ip
Workaround buying a static ip and setting up a local web server. I did not wanted to pay for static ip to ISP so this is the procedure I followed to setup a local site that is acessable over internet. I wanted to setup solr for testing and its not possible on aws fre tire so I setup a local server for testing and devaloping.

setup aws account

buy domain name

setup re-direct site as index page,
       write js to pick up redirect ip address from file

setup web site on apache server on local machine,
       change port from 80,
       block traffic to all other ports,

setup corn job to update public ip in S3 bucket,
        write bash script to get public ip,
        use awscli to write public ip to S3,
Site is setup. 

