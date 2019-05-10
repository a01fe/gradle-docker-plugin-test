# gradle-docker-plugin-test

Test project to help debug registryCredentials when tasks reference two different registries.

The `dockerBuildImage` task builds an image and references an image in the public Docker registry.

The `dockerPushImage` task pushes the built image to a private registry.
