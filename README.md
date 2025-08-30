# Integrated Payment Gateway

This project exposes a simple `/welcome` endpoint returning a welcome message.

## Building and Testing

Ensure Maven can access the internet (proxy settings may be required).

```bash
mvn test
```

The test suite uses Spring Boot's `MockMvc` to verify the `/welcome` endpoint.
