## How to use low level websocket in spring framework with stomp wire protocol


There are some ways to use websocket of spring framework, such as low level or hight level.

- Use low level api with implements `WebSocketHandler` interface or abstract class `AbstractWebSocketHandler`.
- Use high level api with `@MessageMapping`.

## STOMP 

Stomp is a wire protocol that is text-based, but it can also support binary data transport. 
