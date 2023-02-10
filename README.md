# Cloud Computing - Microservices

## Students

- Mpoki MWAISELA - mail: mpoki.mwaisela@grenoble-inp.org - GitHub ID: TODO
- Almo CUCI - mail: almo.cuci@grenoble-inp.org - GitHub ID: cucialmo
- Josquin IMBERT - mail: josquin.imbert@etu.univ-grenoble-alpes.fr - GitHub ID: JosquinIMBERT

## First Manual Deployment

### Registry and Gateway

Manually started the JHipster registry:

![JHipster Registry Started](./microservice_jhipster_registry_running.JPG "JHipster Registry Manual Start")

Manually started the gateway:

![Gateway Started](gateway_running.JPG "Gateway Manual Start")

Browse the application:

![Application](./microservice_app.JPG "Application")

Browse the service registry console:

![JHipster Registry 1](./jhipster_registry_1.JPG "JHipster Registry 1")
![JHipster Registry 2](./jhipster_registry_2.JPG "JHipster Registry 2")


### Microservices

We were able to generate the new application schema and to manually start the microservices.

Once we did these steps, we were able to browse the application:

![Application Loaded](./loaded_product_order_microservice.JPG "Application Loaded")

And to see the microservices in the registry's web interface:

![Registered Microservices](./jhipster_registry_services_up.JPG "Registered Microservices")



## Docker generation

We generated the docker images for our microservices:

![Docker Images](./docker_images.JPG "Docker Images")

And we generated the docker-compose files and scaled the invoice service up to 2 replicas:

![Docker Compose](./docker_compose_scale_up.JPG "Docker Compose")

We were able to observe the two invoice replicas in the JHipster Registry:

![Invoice Replicas](./scaling_up_registry.JPG "Invoice Replicas")



## Monitoring

We were able to browse JHipster metrics, health-checks and logs:

![JHipster Metrics](./jhipster_metrics.JPG "JHipster Metrics")
![JHipster Health Checks](./jhipster_health_checks.JPG "JHipster Health Checks")
![JHipster Logs](./jhipster_logs.JPG "JHipster Logs")

We also started Grafana, added a Prometheus source to it, and ran a CPU usage query:

![Grafana Prometheus](./grafana_prometheus.JPG "Grafana Prometheus")

