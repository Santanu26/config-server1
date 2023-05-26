```
eureka.client.registerWithEureka=false
```
This line disables the registration of the Eureka server itself with the Eureka
service registry. By setting it to 'false', the Eureka server will not attempt
to register itself as a client.

```
eureka.client.fetchRegistry=false
```
This line disables the fetching of the registry information from the Eureka service registry.
By setting it to 'false', the Eureka server will not retrieve registry information from other Eureka client.
