---
author: jess-johnson-msft
ms.author: jejohn
ms.topic: include
ms.date: 01/25/2022
ms.service: app-service
ms.role: developer
ms.devlang: python
ms.azure.devx-azure-tooling: ['azure-portal']
ms.custom: devx-track-python
---

**Step 1.** In the browser window or tab for the web app:

* Select **SSH**, under **Development Tools** in the left resource menu.
* Then **Go** to open an SSH console on the web app server. (It may take a minute to connect for the first time as the web app container needs to start.)

> [!IMPORTANT]
> If the `ls` command shows only one file named *hostingstart.html*, then the deployment hasn't yet completed from the previous step. Check the **Actions** in your GitHub repository for status. Once the build is complete, the `ls` command should show the app's files, especially *manage.py*.
