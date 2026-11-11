<!-- ================= HEADER ================= -->

<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com/?font=Righteous&size=36&center=true&vCenter=true&width=750&height=70&duration=3000&pause=1000&color=00F7FF&lines=Hi+👋+I'm+Srikar+Sanka;Full+Stack+Developer;Angular+%7C+Python+%7C+System+Design;AI+Integrated+Web+Applications;Future+Product+Engineer+🚀" />
</h1>

<h3 align="center">Building scalable web systems from Chennai IN</h3>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=SrikarSanka&label=Profile+Views&color=0e75b6&style=flat" />
  <img src="https://img.shields.io/github/followers/SrikarSanka?label=Followers&style=social" />
</p>

---

# 🧠 About Me

🔭 Working on **AI Powered Virtual Classroom**  
🌱 Learning **Angular Deep Dive + DSA + System Design**  
💡 Passionate about **AI-integrated scalable systems**  
🚀 Preparing for **Product & Startup Engineering Roles**

---

# 💼 Tech Arsenal

<p align="center">

<img src="https://skillicons.dev/icons?i=angular" width="45"/>
<img src="https://skillicons.dev/icons?i=typescript" width="45"/>
<img src="https://skillicons.dev/icons?i=javascript" width="45"/>
<img src="https://skillicons.dev/icons?i=python" width="45"/>
<img src="https://skillicons.dev/icons?i=nodejs" width="45"/>
<img src="https://skillicons.dev/icons?i=express" width="45"/>
<img src="https://skillicons.dev/icons?i=mongodb" width="45"/>
<img src="https://skillicons.dev/icons?i=git" width="45"/>
<img src="https://skillicons.dev/icons?i=github" width="45"/>
<img src="https://skillicons.dev/icons?i=vercel" width="45"/>

</p>

---

# 📊 Contribution Graph Animation

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=SrikarSanka&theme=tokyo-night&hide_border=true&radius=12" />
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/SrikarSanka/SrikarSanka/output/github-contribution-grid-snake.svg" />
</p>

---

# 📈 GitHub Analytics

<p align="center">
  <img width="400" src="https://github-readme-stats.vercel.app/api?username=SrikarSanka&show_icons=true&theme=tokyonight&hide_border=true" />
  <img width="400" src="https://github-readme-streak-stats.herokuapp.com/?user=SrikarSanka&theme=tokyonight&hide_border=true" />
</p>

<p align="center">
  <img width="350" src="https://github-readme-stats.vercel.app/api/top-langs/?username=SrikarSanka&layout=compact&theme=tokyonight&hide_border=true" />
</p>

---

# 🚀 Featured Projects

## 🎓 AI Powered Virtual Classroom

<p align="center">
  <img src="https://res.cloudinary.com/djha4r2ys/image/upload/v1774981405/orbit_zzz9h6.png" />
</p>

<p align="center">
  <!-- Replace this GIF with your own screen recording -->


🧠 **Tech Stack:** WebRTC • Socket.io • MongoDB • AI Face Detection  

✔ Real-time video streaming  
✔ Emotion-based engagement tracking  
✔ Automated attendance  
✔ Faculty & Student dashboards  

🔗 Repo: https://github.com/SrikarSanka/orbitai 
🌐 Live: https://orbit-zqsz.vercel.app/

---

## 🛍 Ubhaava – Handicraft E-Commerce

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:FF5722,100:FF9800&height=150&section=header&text=Ubhaava%20E-Commerce&fontSize=30&fontColor=ffffff" />
</p>

<p align="center">
  <!-- Replace with your own GIF -->
  <img src="https://res.cloudinary.com/djha4r2ys/image/upload/v1774981495/udbhava_mgtajf.png" width="700"/>
</p>

⚙ **Tech Stack:** Angular • Node.js • MongoDB • JWT  

✔ Dynamic cart engine  
✔ Category-based size logic  
✔ Auth + Wishlist  
✔ Heritage crafts showcase  

🔗 Repo: https://github.com/SrikarSanka/ubhaava  
🌐 Live: https://udbhava.onrender.com/

---

# 🎯 Current Engineering Focus

<p align="center">
  <img src="https://img.shields.io/badge/Angular_Deep_Dive-DD0031?style=for-the-badge&logo=angular&logoColor=white"/>
  <img src="https://img.shields.io/badge/NeetCode_DSA-000000?style=for-the-badge&logo=leetcode&logoColor=white"/>
  <img src="https://img.shields.io/badge/System_Design-0078D4?style=for-the-badge&logo=windowsterminal&logoColor=white"/>
  <img src="https://img.shields.io/badge/Scalable_Architecture-339933?style=for-the-badge&logo=node.js&logoColor=white"/>
</p>

---

# 🌐 Connect With Me

<p align="center">
  <a href="https://linkedin.com/in/srikar-sanka-987104294">
    <img src="https://img.icons8.com/fluency/48/linkedin.png" width="40"/>
  </a>
  <a href="mailto:srikarsanka@gmail.com">
    <img src="https://img.icons8.com/fluency/48/gmail.png" width="40"/>
  </a>
  <a href="https://portfolio-nine-gray-65.vercel.app/">
    <img src="https://img.icons8.com/fluency/48/domain.png" width="40"/>
  </a>
  <a href="https://github.com/SrikarSanka">
    <img src="https://img.icons8.com/fluency/48/github.png" width="40"/>
  </a>
</p>

---

<p align="center">
  <b>“I don’t just write code. I engineer systems.”</b> 🚀
</p>


Absolutely! 🔥 Kubernetes Volumes and Networking are two of the most important topics to understand if you want to work with real-world Kubernetes deployments.

Let's learn them from the basics to an intermediate/advanced level, with practical YAML examples, real-world scenarios, and interview questions.

# Part 1: Kubernetes Volumes

## 1. Why do we need volumes?

First, understand one important thing:

Containers are ephemeral (temporary).

Imagine you have a MySQL container running inside a Kubernetes Pod.

1. MySQL stores customer information inside the container.
2. Suddenly, the Pod crashes.
3. Kubernetes creates a new Pod.
4. The new container starts with a fresh filesystem.
5. Your previous data may be lost.

This is where Kubernetes Volumes come into the picture.

A Volume provides storage to containers inside a Pod, allowing data to survive container restarts and, depending on the storage type, Pod replacement.

[Kubernetes Persistent Volume Claims: Tutorial & Top Tips](https://images.openai.com/static-rsc-4/FdqRGDRBpvaOZetDK2SjwSwstE39_owv9ddwUrCS0GybhGXjy9MEEhwy_2Y-o3x1KAqpTyfEleyWbb_DgmUtXBJuHl-vXMDO5ZESMt0ibV-O55v1mtSJ-zJPXDc46LGjET2vmV9id2IovnfT-BKUzZj3X_pP0C7KNBH0v329SuY?purpose=inline)

[groundcover.com](https://www.groundcover.com/blog/kubernetes-pvc?utm_source=chatgpt.com)

## 2. How Kubernetes Volumes work

Understand these three terms:

| Term        | Meaning                                                    |
| ----------- | ---------------------------------------------------------- |
| Volume      | Storage resource associated with a Pod                     |
| volumeMount | Specifies where storage is mounted inside a container      |
| mountPath   | Directory inside the container where storage is accessible |

The relationship looks like this:

Kubernetes Pod

Contains the storage definition

Volume: app-storage

Storage attached to the Pod

Container

volumeMount → /app/data

## 3. Types of Kubernetes Volumes

Let's understand the most important volume types.

### A. emptyDir

- Created when a Pod is assigned to a node.
- Shared between containers in the same Pod if they mount it.
- Data survives a container restart while the Pod remains alive.
- Data is deleted when the Pod is removed from the node.

Example use case: Temporary files, caching, shared files between containers.

YAML example:

```
apiVersion: v1
kind: Pod
metadata:
  name: volume-demo
spec:
  containers:
    - name: app
      image: nginx
      volumeMounts:
        - name: app-storage
          mountPath: /usr/share/nginx/html

  volumes:
    - name: app-storage
      emptyDir: {}
```

Here, Kubernetes creates an empty directory and mounts it inside the Nginx container.

### B. hostPath

- Mounts a directory from the worker node into a Pod.
- Data exists on the worker node even if the Pod is deleted.
- If the Pod moves to another worker node, it may not find the same data.

Example: Accessing node-level logs or files.

```
volumes:
  - name: node-storage
    hostPath:
      path: /data
      type: DirectoryOrCreate
```

Be careful: `hostPath` can introduce security and portability problems. It is not generally recommended for application data.

### C. PersistentVolume (PV)

A PersistentVolume is a storage resource available to the Kubernetes cluster.

Think of it as a storage disk that Kubernetes can allocate to applications.

### D. PersistentVolumeClaim (PVC)

A PersistentVolumeClaim is a request for storage made by an application.

For example:

- Application requests 5 GB storage.
- Kubernetes finds suitable storage.
- The PVC gets bound to a PersistentVolume.

[Learn About Kubernetes Concepts and Architecture](https://images.openai.com/static-rsc-4/P9YmS0y-BXvMZmiCAYsCp76sJ1XYIvR3LJXWyznfmdAuL2NVgGghP7aS3hBK77LTfmVnAzqdt0jPsmB9gP2tVXD_p5AcuCCcMOn1JbXtoPacrkLHryhUgz_7LckNskrLBHdsj7lFU4-0je_NeD3PEq6PAUopv6gj3wdNBKbFi5I?purpose=inline)

[platform9.com](https://platform9.com/blog/kubernetes-enterprise-chapter-2-kubernetes-architecture-concepts/?utm_source=chatgpt.com)

### PV vs PVC

| PersistentVolume                          | PersistentVolumeClaim              |
| ----------------------------------------- | ---------------------------------- |
| Actual storage resource                   | Request for storage                |
| Created by administrator or provisioner   | Created by developer               |
| Defines storage capacity and access modes | Requests capacity and access modes |
| Exists independently of a Pod             | Can be mounted by a Pod            |

### E. StorageClass

Now imagine you have 100 applications.

Do you want to manually create 100 PersistentVolumes?

No!

A StorageClass allows Kubernetes to dynamically provision storage when a PVC requests it.

For example:

- Application requests 10 GB.
- PVC references a StorageClass.
- Storage provisioner creates the required storage.
- PV is dynamically created and bound to the PVC.

This is called Dynamic Volume Provisioning.

### Complete PV + PVC + StorageClass example

First, create a PVC:

```
apiVersion: v1
kind: PersistentVolumeClaim
metadata:
  name: mysql-pvc
spec:
  accessModes:
    - ReadWriteOnce
  resources:
    requests:
      storage: 5Gi
  storageClassName: standard
```

Now create a Pod that uses the PVC:

```
apiVersion: v1
kind: Pod
metadata:
  name: mysql-pod
spec:
  containers:
    - name: mysql
      image: mysql:8
      volumeMounts:
        - name: mysql-storage
          mountPath: /var/lib/mysql

  volumes:
    - name: mysql-storage
      persistentVolumeClaim:
        claimName: mysql-pvc
```

What happens here?

1. PVC requests 5 GB of storage.
2. Kubernetes looks for a matching PV or dynamically provisions one through the StorageClass.
3. PVC becomes Bound to a PV.
4. The Pod references the PVC.
5. The storage is mounted at `/var/lib/mysql`.
6. If the Pod is deleted and recreated, the data can remain available through the same PVC.

### 4. Access Modes

Access modes determine how storage can be mounted by nodes.

| Access mode             | Meaning                               |
| ----------------------- | ------------------------------------- |
| ReadWriteOnce (RWO)     | Read/write mounting by one node       |
| ReadOnlyMany (ROX)      | Read-only mounting by multiple nodes  |
| ReadWriteMany (RWX)     | Read/write mounting by multiple nodes |
| ReadWriteOncePod (RWOP) | Read/write mounting by one Pod        |

Important: RWO means one node, not necessarily one Pod. Multiple Pods on the same node may use an RWO volume, subject to the storage driver's capabilities.

### 5. Reclaim Policies

What happens when you delete a PVC?

| Policy | Behavior                                             |
| ------ | ---------------------------------------------------- |
| Retain | Keeps the PV and underlying data for manual recovery |
| Delete | Deletes the PV and underlying storage, if supported  |

For important production data, understand your storage backend's reclaim behavior before deleting PVCs.

### 6. Important Kubernetes storage commands

```
# List PersistentVolumes
kubectl get pv

# List PersistentVolumeClaims
kubectl get pvc

# List StorageClasses
kubectl get storageclass

# Describe PVC
kubectl describe pvc mysql-pvc

# Check Pod volume mounts
kubectl describe pod mysql-pod
```

# Part 2: Kubernetes Networking

Now let's move to networking. This is particularly important because your application may have multiple Pods, Services, and worker nodes.

## 1. Why do we need Kubernetes networking?

Imagine you have a three-tier application:

- Angular frontend
- Spring Boot backend
- MySQL database

Each application runs in a separate Pod.

[Sample java web system on Kubernetes | by Dayan | Medium](https://images.openai.com/static-rsc-4/u1QzHEcuNHZzrFEW5iEHPSNIFI6oZPm3gbZGd2DS4V2RX7ijGXzkap5lTJ9yXNAhL7JDGj9cH1PQ96aKQe5NNKnmHGD5InZfytu85lnRSbxCqkg3LBzu4Y41qP45myVKpuxq8iMHQKa-LrOMHnDDTgMt5MzC8frJzna_ZK7VWhc?purpose=inline)

[medium.com](https://medium.com/%40dayan888/sample-java-web-system-on-kubernetes-e52069390916?utm_source=chatgpt.com)

Now think about these questions:

1. How does Angular communicate with Spring Boot?
2. How does Spring Boot communicate with MySQL?
3. How can users access the Angular application from outside the cluster?
4. What happens when a Pod gets deleted and a new Pod receives a different IP?

Kubernetes networking solves these problems.

## 2. The four main networking concepts

1\. Pod Networking

Communication between Pods using IP addresses.

2\. Service Networking

Stable networking endpoint for Pods.

3\. Ingress

HTTP/HTTPS routing from outside the cluster to Services.

4\. NetworkPolicy

Controls which Pods can communicate with other Pods.

## 3. Pod Networking

One of the fundamental Kubernetes networking rules is:

Every Pod gets its own IP address.

For example:

| Pod             | IP address |
| --------------- | ---------- |
| Angular Pod     | 10.244.1.5 |
| Spring Boot Pod | 10.244.1.6 |
| MySQL Pod       | 10.244.2.5 |

Pods can communicate with each other using their IP addresses, including Pods running on different worker nodes, assuming the cluster networking is correctly configured.

[Tracing pod to pod network traffic in Kubernetes - The Ops Community ⚙️](https://images.openai.com/static-rsc-4/idoD_vJ7UPZBEHcw4CJUQwxm_gJ_INJjzibwR7yyBR_dFQQGA_Id9hWbheWDCGD9tNtE9B97lc5YHKgcBloLOxz0-Ptpso4njwSOSgh9A-HGFGlLfO5K4tctTtb4qU8rpyDqLqaCbFjSSv-uJEoS77JjqGdOH93Ymqi7bzgRoXU?purpose=inline)

[community.ops.io](https://community.ops.io/danielepolencic/tracing-pod-to-pod-network-traffic-in-kubernetes-2g24?utm_source=chatgpt.com)

### What is CNI?

CNI stands for Container Network Interface.

It is a specification and ecosystem of plugins responsible for configuring container networking.

Examples:

- Calico
- Cilium
- Flannel

Think of CNI as the networking system that helps Pods communicate across the cluster.

Important: Kubernetes defines networking requirements, but a CNI plugin implements much of the actual Pod networking.

## 4. Kubernetes Services

Now here comes an important problem.

Imagine your Spring Boot application has three replicas:

```
backend-pod-1 → 10.244.1.5
backend-pod-2 → 10.244.1.6
backend-pod-3 → 10.244.2.5
```

What happens if backend-pod-1 crashes?

Kubernetes may create a replacement Pod with a different IP.

If Angular directly connects to the Pod IP, communication can break.

Solution: Kubernetes Service.

A Service provides a stable IP address and DNS name and routes traffic to its selected backend Pods.

[KAI Road of Kubernetes 03 — What a Service is, and why Pod IPs should not be your interface | LemonKAI](https://images.openai.com/static-rsc-4/20oClK_fQK1M0Ot-zH-W6EAMJJ-iSuPb6Zyg3Hrzi69c1DdDCZ4iKAivVzOFImoqzrY5F04P7aTR4OEPbjy-U6kDxuHeCPnQFvNrLspPz6Kebdh0tdLdXZxEo1wRad2S42lPzngQmE26hxNhwNrAL5dofR-QHp7Mtap9E2GU7D8?purpose=inline)

[lemonkai.github.io](https://lemonkai.github.io/blog/en/kai-k8s-road-03-service/?utm_source=chatgpt.com)

### How does a Service identify Pods?

Through labels and selectors.

Pod:

```
apiVersion: v1
kind: Pod
metadata:
  name: backend-pod
  labels:
    app: backend
spec:
  containers:
    - name: backend
      image: nginx
      ports:
        - containerPort: 8080
```

Service:

```
apiVersion: v1
kind: Service
metadata:
  name: backend-service
spec:
  selector:
    app: backend
  ports:
    - port: 80
      targetPort: 8080
  type: ClusterIP
```

Let's understand the important fields:

| Field      | Meaning                            |
| ---------- | ---------------------------------- |
| selector   | Finds Pods with matching labels    |
| port       | Port exposed by the Service        |
| targetPort | Port on the destination Pod        |
| type       | Defines how the Service is exposed |

For this example:

- Angular communicates with `backend-service:80`.
- The Service selects Pods with `app: backend`.
- Traffic is forwarded to port `8080` on selected Pods.

### 5. Types of Services

There are four commonly discussed Service types.

A. ClusterIP

Default type

[Kubernetes Networking: Pod and Service Networking](https://images.openai.com/static-rsc-4/vqn70lPz5IJSKpuNgw4-OlRcYX7lY1xzUBOwvkautTrRSwAmxIDnPTCKcpnd6YpT-ljMyoX-0gTeE-Hqp2HYwBY9KDX0hiY4i1vyWwuFfOxgfFKWtjoVJqXFY8e7k4YxIFnOIqls_Rep0xabCOoCvaYNwNP4TsAIM1hIoh__ysA?purpose=inline)

[thelearningjourney.co](https://thelearningjourney.co/kubernetes-networking-pod/?utm_source=chatgpt.com)

- Exposes the Service inside the cluster.
- Not directly accessible from outside the cluster.
- Used for backend-to-database and frontend-to-backend communication.

Example:

```
spec:
  type: ClusterIP
  selector:
    app: backend
  ports:
    - port: 80
      targetPort: 8080
```

B. NodePort

[PPT - Kubernetes PowerPoint Presentation, free download - ID:8801821](https://images.openai.com/static-rsc-4/FWujb3UMjCY1G4MoJU8d5c86AFwDePtgHN8RI8gwf6J4Wv1crnp-jv_VLJ95O0IXe9GdVQsm0XsQWlLQyaSGCCQwUfHuoLoXiAw5h17X72zupnl_YCL7lFNGjVGoF_mG_4cXeUXJb7QJ5_UyJlq3Y0EsQLZphnTqS-QiaO5eFdg?purpose=inline)

[slideserve.com](https://www.slideserve.com/ponton/kubernetes-powerpoint-ppt-presentation?utm_source=chatgpt.com)

- Opens a port on each worker node.
- Default NodePort range is 30000–32767.
- Traffic can enter through `NodeIP:NodePort`.

Example:

```
spec:
  type: NodePort
  ports:
    - port: 80
      targetPort: 8080
      nodePort: 30080
```

C. LoadBalancer

[Kubernetes Deployment Template](https://images.openai.com/static-rsc-4/5Y6iIvOw6HVRdLmF5Ldeu1Nu6mIDIKllNQqRSMwve7GqrpQSVS0DfTkQwOpdd5NYU6nJzOROs1P6V8kVyNOkenYQKaZZfsxZjygP9bF1DtdoZmRn_wYYwF49CNx5uAElsleUe2RDdN7OZpEmDOYk3JO21HakSgXkaqHP6OgUjtY?purpose=inline)

[template.mapadapalavra.ba.gov.br](https://template.mapadapalavra.ba.gov.br/en/kubernetes-deployment-template.html?utm_source=chatgpt.com)

- Requests an external load balancer through the infrastructure provider.
- Commonly used in cloud environments.
- External traffic is forwarded to the Service.

Example:

```
spec:
  type: LoadBalancer
  ports:
    - port: 80
      targetPort: 8080
```

D. ExternalName

- Maps a Kubernetes Service name to an external DNS name.
- Does not create a normal Pod endpoint or proxy traffic.

Example:

```
apiVersion: v1
kind: Service
metadata:
  name: external-db
spec:
  type: ExternalName
  externalName: database.example.com
```

## 6. Kubernetes DNS

This is another important concept.

Suppose your Spring Boot application needs to connect to MySQL.

You should not hardcode the MySQL Pod IP.

Instead, use the Service DNS name.

For example:

```
mysql-service
```

Within the same namespace, this is usually sufficient.

The full DNS name is:

```
mysql-service.default.svc.cluster.local
```

Breakdown:

| Part          | Meaning                      |
| ------------- | ---------------------------- |
| mysql-service | Service name                 |
| default       | Namespace                    |
| svc           | Kubernetes Service           |
| cluster.local | Cluster DNS domain (default) |

Kubernetes DNS is typically provided by CoreDNS.

Real-world example:

Your Spring Boot application's database URL could be:

```
spring.datasource.url=jdbc:mysql://mysql-service:3306/mydb
```

Even if the MySQL Pod IP changes, the Service DNS name remains stable.

## 7. Ingress

Now imagine users want to access your application.

You have:

```
frontend-service
backend-service
```

You could expose both through separate LoadBalancer Services, but that might be unnecessarily expensive.

Instead, you can use Ingress for HTTP/HTTPS routing.

Example:

```
https://myapp.com       → frontend-service
https://myapp.com/api   → backend-service
```

[Inside the Cluster: Ingress in Focus — How External Traffic Reaches Your Services | by KELVI MANAVADARIA | Medium](https://images.openai.com/static-rsc-4/N3WoFxY-KKSDv4MP14jeEhC0jAwuoR8uIT3TU2c4maNw6d0dCJlkUwNEgEbInSSWJ_k1_Q_3kU4K64OgDCmvjSHQJeIBoGUns-1eG3WjA8YMIppVdb8bdmD-tdpThY0PQqXuExpvk6ReZxi3KlWsB1AsIuE9-dcsn97CPv70A6Q?purpose=inline)

[medium.com](https://medium.com/%40kelvi030117/inside-the-cluster-ingress-in-focus-how-external-traffic-reaches-your-services-95006bd8cdb4?utm_source=chatgpt.com)

Ingress has two important components:

1. Ingress Resource: Defines routing rules.
2. Ingress Controller: Implements those rules and handles incoming traffic.

Example Ingress resource:

```
apiVersion: networking.k8s.io/v1
kind: Ingress
metadata:
  name: app-ingress
spec:
  rules:
    - host: myapp.com
      http:
        paths:
          - path: /
            pathType: Prefix
            backend:
              service:
                name: frontend-service
                port:
                  number: 80

          - path: /api
            pathType: Prefix
            backend:
              service:
                name: backend-service
                port:
                  number: 80
```

Important: Creating an Ingress resource alone does not make it work. You need an Ingress Controller installed and configured. The Kubernetes Gateway API is also an increasingly important option for newer deployments.

## 8. NetworkPolicy

Imagine your application has:

- Frontend
- Backend
- Database

You want:

- Frontend → Backend: Allowed
- Backend → Database: Allowed
- Frontend → Database: Blocked

This is where NetworkPolicy comes in.

[Exploring Kubernetes Networking (Part 4/6): Using Network Policies Effectively | by Salwan Mohamed | Medium](https://images.openai.com/static-rsc-4/np4dm-6u4Qb0NOka7M1Z0u9KSU9dtx0lMBXn2FW8VoucPCleEVZ6wiRq1Lrjf2Ojp6bXeG67Wa-1EIpObGmyk3F17u9LR0FZEVzjcsup9F1lQYvvTVRINFKZC9Y8c90LL5Mag4J5iEFX_w0JFCQY_MMYRfBEhzn8dBNxgjN-y-s?purpose=inline)

[medium.com](https://medium.com/%40salwan.mohamed/exploring-kubernetes-networking-part-4-6-using-network-policies-effectively-cb51b4d04693?utm_source=chatgpt.com)

Example:

```
apiVersion: networking.k8s.io/v1
kind: NetworkPolicy
metadata:
  name: allow-backend-to-db
spec:
  podSelector:
    matchLabels:
      app: mysql
  policyTypes:
    - Ingress
  ingress:
    - from:
        - podSelector:
            matchLabels:
              app: backend
      ports:
        - protocol: TCP
          port: 3306
```

This policy allows incoming traffic to MySQL Pods on port 3306 from backend Pods selected by their labels.

Important: Your CNI plugin must support NetworkPolicy enforcement. Also, policies are additive, and a policy selecting a Pod for ingress isolation changes its default ingress behavior.

# Part 3: How everything works together

Let's combine Volumes and Networking into one real-world application.

Imagine you are deploying an e-commerce application.

[Master CKAD with One Project — A Beginner-Friendly Guide with YAMLs and KillerCoda Playground | by Venkatesh Beeraka | Medium](https://images.openai.com/static-rsc-4/2Ikr1Zkmv9PNSyAuinVNUTBaWt2IsO5sXQ5mRjcixU_d6myXWmblEyFzlcekjllgfiwwWTik-bUjl-HE7CNNrnu7XL6oDgqEbdzreFmADfSKrR5XW6IYq74cC2Z-DKSRNv3o54QiapiDLFcAg69TxkvcbYAj6v2lUqrJsAuRmqg?purpose=inline)

[medium.com](https://medium.com/%40beerakavenkatesh1997/master-ckad-with-one-project-a-beginner-friendly-guide-with-yamls-and-killercoda-playground-f667f436e97a?utm_source=chatgpt.com)

The architecture:

```
                 INTERNET
                    |
                    v
              INGRESS
                    |
          +---------+---------+
          |                   |
          v                   v
   Frontend Service     Backend Service
          |                   |
          v                   v
    Angular Pods        Spring Boot Pods
                              |
                              v
                       MySQL Service
                              |
                              v
                         MySQL Pod
                              |
                              v
                         PVC / PV
                              |
                              v
                       Persistent Data
```

What each component does:

| Component     | Responsibility                       |
| ------------- | ------------------------------------ |
| Ingress       | External HTTP/HTTPS routing          |
| Service       | Stable networking endpoint           |
| Pod           | Runs application containers          |
| CNI           | Provides Pod networking              |
| NetworkPolicy | Controls network traffic             |
| PVC           | Requests persistent storage          |
| PV            | Represents available storage         |
| StorageClass  | Enables dynamic storage provisioning |

# Part 4: Important troubleshooting commands

These are commands you should practice.

### Networking

```
# List Services
kubectl get svc

# List Pods with IP addresses
kubectl get pods -o wide

# List Ingress resources
kubectl get ingress

# Describe a Service
kubectl describe svc backend-service

# Check EndpointSlices
kubectl get endpointslices

# Check DNS resolution inside a Pod
kubectl exec -it frontend-pod -- nslookup backend-service

# Test connectivity
kubectl exec -it frontend-pod -- curl http://backend-service
```

### Volumes

```
# Check PersistentVolumes
kubectl get pv

# Check PersistentVolumeClaims
kubectl get pvc

# Check StorageClasses
kubectl get sc

# Check volume details
kubectl describe pvc mysql-pvc

# Check Pod volume mounts
kubectl describe pod mysql-pod

# Check files inside mounted directory
kubectl exec -it mysql-pod -- ls /var/lib/mysql
```

# Part 5: Common interview questions

Try answering these without looking at the explanations.

Knowledge check

0/7 answered

1\. What happens to emptyDir data when a container restarts but the Pod remains alive?

Data is deleted

Data remains available

Data moves to another node

2\. What is the difference between PV and PVC?

Both are identical

PV is storage; PVC requests storage

PVC is a networking resource

3\. Why do we need Kubernetes Services?

To create Pods

To provide stable networking endpoints

To store application data

4\. Which Service type exposes an application through a cloud load balancer?

ClusterIP

ExternalName

LoadBalancer

5\. What is the responsibility of CNI?

Managing databases

Configuring container networking

Creating PersistentVolumes

6\. Does creating an Ingress resource automatically expose your application?

Yes, always

No, an Ingress Controller is needed

Only if you have a PVC

7\. Can two Pods on different worker nodes communicate?

No

Yes, with correctly configured cluster networking

Only using NodePort

Submit answers

# Part 6: What should you learn next?

My recommended learning order:

1. Volumes: PV, PVC, StorageClass, StatefulSets and dynamic provisioning.
2. Networking: Pod networking, CNI, Services, DNS and EndpointSlices.
3. Ingress: Ingress Controller, TLS and path-based routing.
4. Security: NetworkPolicy and traffic isolation.
5. Advanced: Gateway API, service meshes and persistent storage troubleshooting.

## Practical assignment

Build this architecture locally using Minikube or a Kubernetes cluster:

- Deploy an Angular frontend.
- Deploy a Spring Boot backend with two replicas.
- Deploy MySQL with persistent storage.
- Create ClusterIP Services for backend and MySQL.
- Expose the frontend using Ingress.
- Verify backend-to-database communication.
- Delete and recreate the MySQL Pod and verify that your data persists.

One important challenge: Delete one backend Pod while sending requests to the backend Service. Observe how Kubernetes continues routing traffic to the available Pods.

That exercise will help you understand how these concepts work together in a real production-style deployment. 🚀

