

![shell scripting](https://github.com/user-attachments/assets/3f7cb4c1-79d0-4916-a028-8028f43a70d3)

[root@ip-172-31-1-175 scripts]# cat task1.sh
#!/bin/bash

URL="https://www.guvi.in"

HTTP_CODE=$(curl -o /dev/null -s -w "%{http_code} \n" "$URL")

echo "HTTP Status Code: $HTTP_CODE"

if[ $HTTP_CODE -eq 200 ]

then
        echo "Success: the request was successful"
else
        echo "Failure: the request ws failed with error code $HTTP_CODE "
fi
[root@ip-172-31-1-175 scripts]# cat input.sh

ihello
this is
new script give and learing
give and welcome
give and learning
give and welcome

[root@ip-172-31-1-175 scripts]# cat task2.sh
#!/bin/bash
FILE="input.sh"

awk 'NR>=5 && /welcome/ {gsub(give/,"Learning")} {print}' "$FILE" > temp && mv temp "$FILE"
[root@ip-172-31-1-175 scripts]#

