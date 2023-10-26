# Run API and UI on kubernetes



**Create a Kubernets yaml mainfests for the application by the use of dekorate**


<img width="745" alt="image" src="https://github.com/eswarganesan/kaiburr-k8/assets/104221146/693754a5-1f53-41f9-ab0f-967c754fe4c8">


<img width="383" alt="image" src="https://github.com/eswarganesan/kaiburr-k8/assets/104221146/8933c52f-de6d-4788-a8f8-5210c314a7ba">


**skaffold yaml file creation**


<img width="557" alt="1" src="https://github.com/eswarganesan/kaiburr-k8/assets/104221146/a463c430-afaa-4e16-959f-c5349ce7389d">


**skaffold build**


<img width="549" alt="2" src="https://github.com/eswarganesan/kaiburr-k8/assets/104221146/f1292376-5e48-4baa-86e1-b689cb8ffec3">

<img width="960" alt="3" src="https://github.com/eswarganesan/kaiburr-k8/assets/104221146/f80a4ee7-69a9-47d8-acf1-f3ff78eb21c7">

<img width="754" alt="4" src="https://github.com/eswarganesan/kaiburr-k8/assets/104221146/5d731e3f-6894-467a-aa41-ea506e2b9d06">


**skaffold run - added kubernet files**


<img width="572" alt="5" src="https://github.com/eswarganesan/kaiburr-k8/assets/104221146/f1dbb6c7-1a2e-4ae0-9c71-093efc36f70f">

<img width="787" alt="6" src="https://github.com/eswarganesan/kaiburr-k8/assets/104221146/5fb67aab-984e-4260-b2cc-2207d693f405">


**kubectl get all**

**Created Services, Pod - 4 , Replicas - 4, and Deployment - 4**

<img width="576" alt="7" src="https://github.com/eswarganesan/kaiburr-k8/assets/104221146/5445a35d-9e48-493f-a8e6-2ea759301490">


**Created mongodb deployment and sevice yaml file**


<img width="960" alt="mongo 8" src="https://github.com/eswarganesan/kaiburr-k8/assets/104221146/e669a667-6814-4a69-b19e-d733dc86f6d8">


**Created Pod for Mongodb**

<img width="563" alt="9" src="https://github.com/eswarganesan/kaiburr-k8/assets/104221146/fda02aa8-af14-41f9-94c8-39ca5c1d5333">


**Deploy the application by skaffold dev --pod-forward**

<img width="551" alt="11" src="https://github.com/eswarganesan/kaiburr-k8/assets/104221146/d81ad041-e458-45ee-a7c3-d733b77fea43">


**Port forwarding service/server-services in namespace default, remote port 8089 -> http://127.0.0.1:8089**

<img width="686" alt="12" src="https://github.com/eswarganesan/kaiburr-k8/assets/104221146/3439d7ea-52ee-41a8-a1d8-b4b922f9719b">


**Website**

<img width="475" alt="10" src="https://github.com/eswarganesan/kaiburr-k8/assets/104221146/6cc39f0f-e1eb-489e-95b2-1ec9e2209959">

