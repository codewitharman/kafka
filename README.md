

**Project Description:**

This Kafka project is developed using **JDK 21** and **Spring Boot 3.2.0**. The ZIP file contains **three separate projects bundled together**.

To run the project:

1. Unzip the file.
2. Import all projects as **Maven projects** into your IDE.
3. Run the applications.

Once the applications are running, use **Postman** to send a POST request to:

`http://localhost:8081/api/orders`

**Request Body (JSON):**

```json
{
  "productName": "Laptop",
  "quantity": 1,
  "totalAmount": 999.99
}
```

The API will process the request and publish the data through Kafka.

