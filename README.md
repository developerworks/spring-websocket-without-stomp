## How to use low level websocket in spring framework with stomp wire protocol


There are some ways to use websocket of spring framework, such as low level or hight level.

- Use low level api with implements `WebSocketHandler` interface or abstract class `AbstractWebSocketHandler`.
- Use high level api with `@MessageMapping`.

## STOMP 

Stomp is a wire protocol that is text-based, but it can also support binary data transport. 


## References

- http://www.devglan.com/spring-boot/spring-websocket-integration-example-without-stomp
- https://stackoverflow.com/questions/35618039/how-to-send-binary-with-spring-boot-websocket
- https://spring.io/blog/2015/03/22/using-google-protocol-buffers-with-spring-mvc-based-rest-services
- http://jmesnil.net/stomp-websocket/doc/
- https://stomp.github.io/stomp-specification-1.2.html
