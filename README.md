# internship-Assignment-
2. Build a wrapper service for interact.sh [ https://github.com/projectdiscovery/interactsh ] , exposing two APIs for the service.
    1. APIs: 
        1. api/getURL → This will give the URL of the testing server being used for the current session in interact.sh
        2. api/getInteractions → This api will take the url of the testing server and send the information about its interactions [ caller ip and timestamp ]. [ Optional: this can also take timestamp limits to only give the information about the given timestamp ]
        3. e.g. The data in red is expected for the `api/getURL` API and the data in green is expected for `api/getInteractions` API.
