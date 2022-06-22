# API Endpoints #
### http://54.89.168.46/ ###
- POST
- body = {url : <long_url> }

### http://54.89.168.46/auth/signup ###
- POST
- body = { user_id : xyz@, password: xyz@#, name: xyz, address: Mumbai }

### http://54.89.168.46/auth/signin ###
- POST
- body = { user_id : xyz@, password: xyz@# }


### http://54.89.168.46/auth/ ###
- GET
- headers:<br>
    name = Authorization<br>
    value = Token
