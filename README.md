# Grafana Prometheus RabbitMQ Monitoring

This repository contains the configuration files and setup instructions for monitoring RabbitMQ using Prometheus and Grafana.

## Getting Started

To get started with monitoring RabbitMQ, follow these steps:

### Clone the Repository

Clone this repository to your local machine using the following command:

git clone https://github.com/mashhoudrajput/Grafana-prometheus-rabbitmq-monitoring
Run Docker Compose
Navigate to the cloned repository directory and run Docker Compose to start the monitoring environment:

cd Grafana-prometheus-rabbitmq-monitoring
docker-compose up -d

**Add Prometheus Data Source:**
Open a web browser and go to http://localhost:3000 to access Grafana.
Log in to Grafana using the default credentials (admin/admin).
Go to "Configuration" in the sidebar and select "Data Sources".
Click on "Add data source" and select "Prometheus".
In the URL field, enter http://localhost:9090 as the Prometheus URL.
Click "Save & Test" to add the data source.

**Use RabbitMQ Dashboard:**
Go to "Create" in the Grafana sidebar and select "Dashboard", then "Import".
Upload the RabbitMQ dashboard JSON file available in this repository.
Select the Prometheus data source added earlier.
Click "Import" to import the dashboard.
Now, you can explore the RabbitMQ dashboard in Grafana and monitor your RabbitMQ instance's metrics.

Contributing
If you encounter any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

Feel free to copy this content and paste it into your README.md file in your GitHub repository. Let me know if you need any further assistance!





