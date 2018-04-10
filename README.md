# pact-provider-verifier

## how to run tests
The following variables need to be provided to get the tests running.

`PACT_PROVIDER_HOST`  
`PACT_PROVIDER_PORT`  
`PACT_PROVIDER_PROTOCOL` (default: "http")  
`PACT_BROKER_URL`  
`PACT_PROVIDER_NAME`  

If your broker requires authentification you can additionally set the following variables:  
`PACT_BROKER_USERNAME`  
`PACT_BROKER_PASSWORD`

If you want to publish results back to broker your gradle build should contain the 'VERSION_NUMBER' environment variable:
`VERSION_NUMBER` (default: "0.7.local")
