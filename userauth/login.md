Description and examples for /v2/userauth/login to follow...
The first step in your API usage: login to retrieve a //session token//.
  * Examples:
    * http://api.gpsinsight.com/v2/UserAuth/login?username=X&password=X
    * http://api.gpsinsight.com/v2/UserAuth/login?username=X&app_token=X
  * Response:

    head: { ... },
    data: { 
        token: "XXXX" 
    }
