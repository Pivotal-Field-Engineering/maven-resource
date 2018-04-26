# Maven Repository Manager Concourse Resource

This fork is no longer maintained. Please reference the main repo [nulldriver/maven-resource](https://github.com/nulldriver/maven-resource) and update your Concourse pipelines to use the updated Docker Hub location:

```yml
resource_types:
- name: maven-resource
  type: docker-image
  source:
    repository: nulldriver/maven-resource
    tag: latest
```
