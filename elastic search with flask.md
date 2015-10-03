
#Elastic Search with Python

## The official low level api is too cumbersome to use either use elasticsearch-dsl or use http requests


    1. Python `json.dumps(<python dict>)` adds additional quotes when doing something like this:

      `body={"doc":json.dumps(<python dict>)}` so take special care of those extra quotes


    2. Elastic search needs refresh parameter to recreate indexes after updation
