# tektontask
# sample pipeline to build from.
# The pipeline performs the following tasks for the back-end application pipelines-vote-api and front-end application pipelines-vote-ui:
# Clones the source code of the application from the Git repository by referring to the git-url and git-revision parameters.
# Builds the container image using the buildah cluster task.
# Pushes the image to the OpenShift image registry by referring to the image parameter.
# Deploys the new image on OpenShift Container Platform by using the apply-manifests and update-deployment tasks.