# orca-image 

>> TO RUN:

$> docker pull orca-image:latest
$> docker run -p 5001:5001 -p 8081:8080 -v /Users/michaellawson/orca/mongo:/data/db -v /Users/michaellawson/orca/elasticsearch:/var/lib/elasticsearch -v /Users/michaellawson/orca/config:/orca/config  orca-image:latest
