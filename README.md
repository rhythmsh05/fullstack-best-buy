# fullstack-best-buy

For an online electronics company, the Best Buy Demo Application is a cloud-native solution that demonstrates a scalable and reliable microservices architecture. The following elements make up the architecture:

Store-Front: A customer-facing application allowing users to browse products and place orders.

Store-Admin: An employee-facing application for managing products and viewing orders.

Order-Service: Handles the creation of orders and sends data to Azure Service Bus for processing.

Product-Service: Manages CRUD operations for product data.

Makeline-Service: Processes and completes orders by reading messages from Azure Service Bus.

AI-Service: Utilizes GPT-4 and DALL-E to generate product descriptions and images dynamically.

