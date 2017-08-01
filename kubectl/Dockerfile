FROM gcr.io/cloud-builders/gcloud

COPY with-cluster.bash /builder/with-cluster.bash

ENTRYPOINT ["/builder/with-cluster.bash", "kubectl"]
