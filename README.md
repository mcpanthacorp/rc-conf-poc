# rc-conf-poc

## Build all
mvn clean install

## Running config server
mvn springboot:run -Dspring.profiles.active=[dev,localdev,ci,stage,prod]

## Running Test App
mvn springboot:run -Dspring.profiles.active=[dev,localdev,ci,stage,prod]

## Testing

curl http://localhost:PORT/message


