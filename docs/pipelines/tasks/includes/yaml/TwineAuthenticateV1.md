---
ms.topic: include
ms.date: 08/02/2019
author: steved0x
ms.author: sdanie
ms.prod: devops
ms.technology: devops-cicd-tasks
---

```YAML
# Python twine upload authenticate V1
# Authenticate for uploading Python distributions using twine. Add '-r FeedName/EndpointName --config-file $(PYPIRC_PATH)' to your twine upload command. For feed present in this organization, use the feed name as the repository (-r). Otherwise, use the endpoint name defined in the service connection.
- task: TwineAuthenticate@1
  inputs:
    #artifactFeed: MyTestFeed # Optional
    #pythonUploadServiceConnection: OtherOrganizationFeed # Optional
```
