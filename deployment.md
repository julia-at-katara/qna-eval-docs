#Deployment

To deploy the application, first ensure all environment variables are defined in the `.env` file. Then run `deploy.sh`, which builds the Docker image, pushes it to the container registry, and updates the Kubernetes deployment. Deployment typically completes within 5–10 minutes.

This process should only be run by users with deploy access rights, as it may overwrite the currently running production instance.
