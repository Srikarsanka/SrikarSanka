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
today notes 

# Kubernetes In-Depth Notes: Ingress, ConfigMaps and Secrets

These three Kubernetes concepts solve different problems:

- Ingress: How external users access applications inside a Kubernetes cluster.
- ConfigMap: How applications receive non-sensitive configuration.
- Secret: How applications receive sensitive configuration such as passwords, tokens and credentials.

Let's understand each one from architecture to implementation, using your ShopKart application.

# 1. Ingress

## 1.1 What is Ingress?

Ingress is a Kubernetes API resource that manages external HTTP and HTTPS access to services running inside a Kubernetes cluster.

It allows us to define routing rules based on:

- Hostnames (domains).
- URL paths.
- HTTP and HTTPS traffic.

The main purpose of Ingress is to expose multiple applications through a common external entry point without requiring a separate external LoadBalancer for every application.

## 1.2 Why do we need Ingress?

Imagine your ShopKart application has three components:

- Frontend
- Backend
- Admin application

Each component runs in separate Pods and has its own Kubernetes Service.

Without Ingress, one option is to expose each Service through a LoadBalancer.

[Grundlagen des Netzwerkdesigns für Microservices-Architekturen](https://images.openai.com/static-rsc-4/zYlwPEcUJpcpANjuMzDvl84N8TDzp2jLM8T2hCzqMliOKLGCvkeu2ctuR1lzIH8LAda3V9S1fnCvWz6xecmzDiC29HQaueIgA9As3XtquLkw9ViPv4-o6uJq6tuKYqgUOIgXMsZR0qBg21LiC2R1n2sG_A2lfELrLFheMxDWHL8?purpose=inline)

[mad-summit.de](https://mad-summit.de/blog/grundlagen-des-netzwerkdesigns-fuer-microservices-architekturen/?utm_source=chatgpt.com)

This can result in:

- Multiple external IP addresses.
- Additional cloud load-balancer costs.
- More networking configuration.
- Difficulty managing HTTPS certificates across applications.

Instead, we can use Ingress to route traffic to multiple Services through a common entry point.

[Exposing Kubernetes services to the internet | Scaleway Documentation](https://images.openai.com/static-rsc-4/uhwEq13_pT5uz2RoOyLYPs7EsAY5FRZ2jxJimDIW_svr5jdeZjptTOWyBkETVttV5dDvdAwWsJgGRUJeoEDtnexKPCsevQIBnl7soSWvadcFrNE33V1pjhoKaqh2JQU7BUwMgH0wbFqxo10vmrG1WpU6l71XaBLVJjEC6bDFxJk?purpose=inline)

[scaleway.com](https://www.scaleway.com/en/docs/kubernetes/reference-content/exposing-services/?utm_source=chatgpt.com)

For example:

| Application | URL                  | Destination Service |
| ----------- | -------------------- | ------------------- |
| Frontend    | `shopkart.com/`      | shopkart-frontend   |
| Backend     | `shopkart.com/api`   | shopkart-backend    |
| Admin       | `shopkart.com/admin` | shopkart-admin      |

One external entry point can handle all three routes.

## 1.3 Important components of Ingress

There are two important components.

A. Ingress Resource

This is a Kubernetes object where we define routing rules.

For example:

```
shopkart.com/api  → backend Service
shopkart.com/     → frontend Service
```

It tells Kubernetes where incoming requests should go.

B. Ingress Controller

The Ingress Controller is responsible for implementing those routing rules.

Examples:

- NGINX Ingress Controller
- Traefik
- HAProxy Ingress Controller

An Ingress resource alone does not handle incoming traffic. We must install and configure an Ingress Controller.

## 1.4 Complete Ingress request workflow

[Inside the Cluster: Ingress in Focus — How External Traffic Reaches Your Services | by KELVI MANAVADARIA | Medium](https://images.openai.com/static-rsc-4/N3WoFxY-KKSDv4MP14jeEhC0jAwuoR8uIT3TU2c4maNw6d0dCJlkUwNEgEbInSSWJ_k1_Q_3kU4K64OgDCmvjSHQJeIBoGUns-1eG3WjA8YMIppVdb8bdmD-tdpThY0PQqXuExpvk6ReZxi3KlWsB1AsIuE9-dcsn97CPv70A6Q?purpose=inline)

[medium.com](https://medium.com/%40kelvi030117/inside-the-cluster-ingress-in-focus-how-external-traffic-reaches-your-services-95006bd8cdb4?utm_source=chatgpt.com)

Let's understand what happens when a user opens `https://shopkart.com/api/products`.

1. Browser: The user enters the URL.
2. DNS: DNS resolves `shopkart.com` to the external IP associated with the Ingress entry point.
3. External Load Balancer: If configured, it forwards traffic to the Ingress Controller.
4. Ingress Controller: Receives the HTTP/HTTPS request.
5. Ingress Rules: The controller evaluates the hostname and path.
6. Service: The request is routed to `shopkart-backend`.
7. EndpointSlices: Kubernetes maintains the eligible Pod endpoints associated with the Service.
8. Backend Pod: The selected backend Pod processes the request.
9. Response: The response travels back to the user.

Important: Ingress routes traffic to Services, not directly to Pods in the standard Ingress API model.

## 1.5 Types of Ingress routing

There are two commonly used routing methods.

### A. Host-based routing

Different applications use different domain names.

Example:

| Hostname             | Service  |
| -------------------- | -------- |
| `shopkart.com`       | frontend |
| `api.shopkart.com`   | backend  |
| `admin.shopkart.com` | admin    |

Example YAML:

```
apiVersion: networking.k8s.io/v1
kind: Ingress

metadata:
  name: shopkart-ingress

spec:
  ingressClassName: nginx

  rules:
    - host: shopkart.com
      http:
        paths:
          - path: /
            pathType: Prefix
            backend:
              service:
                name: shopkart-frontend
                port:
                  number: 80

    - host: api.shopkart.com
      http:
        paths:
          - path: /
            pathType: Prefix
            backend:
              service:
                name: shopkart-backend
                port:
                  number: 8080
```

Here, the Ingress Controller checks the hostname and forwards the request to the appropriate Service.

### B. Path-based routing

Different applications use different URL paths under the same domain.

Example:

```
shopkart.com/       → frontend
shopkart.com/api    → backend
shopkart.com/admin  → admin
```

Example YAML:

```
apiVersion: networking.k8s.io/v1
kind: Ingress

metadata:
  name: shopkart-ingress

spec:
  ingressClassName: nginx

  rules:
    - host: shopkart.com
      http:
        paths:

          - path: /api
            pathType: Prefix
            backend:
              service:
                name: shopkart-backend
                port:
                  number: 8080

          - path: /admin
            pathType: Prefix
            backend:
              service:
                name: shopkart-admin
                port:
                  number: 8080

          - path: /
            pathType: Prefix
            backend:
              service:
                name: shopkart-frontend
                port:
                  number: 80
```

The controller evaluates the paths, generally selecting the longest matching path.

For example:

```
shopkart.com/api/products
```

Matches `/api`, so the request goes to the backend Service.

Note that the `/api` prefix is not necessarily removed from the forwarded request. Path rewriting requires additional controller-specific configuration.

## 1.6 Understanding pathType

Ingress supports three path types.

| Path type              | Meaning                                             |
| ---------------------- | --------------------------------------------------- |
| Exact                  | Matches the exact path                              |
| Prefix                 | Matches the path prefix, based on URL path elements |
| ImplementationSpecific | Matching behavior depends on the controller         |

For example:

- `Exact /api` matches `/api`, not `/api/products`.
- `Prefix /api` matches `/api` and `/api/products`.
- `ImplementationSpecific` depends on the controller implementation.

## 1.7 What happens with HTTPS?

Normally, HTTP traffic is not encrypted.

We use TLS to secure communication between the client and the Ingress Controller.

Ingress can reference a Kubernetes TLS Secret containing a certificate and private key.

Example:

```
apiVersion: networking.k8s.io/v1
kind: Ingress

metadata:
  name: shopkart-ingress

spec:
  ingressClassName: nginx

  tls:
    - hosts:
        - shopkart.com
      secretName: shopkart-tls

  rules:
    - host: shopkart.com
      http:
        paths:
          - path: /
            pathType: Prefix
            backend:
              service:
                name: shopkart-frontend
                port:
                  number: 80
```

The Secret must be in the same namespace as the Ingress and normally has type `kubernetes.io/tls`.

The TLS certificate allows the Ingress Controller to establish HTTPS connections with clients.

## 1.8 Important Ingress commands

```
kubectl get ingress

kubectl describe ingress shopkart-ingress

kubectl get ingressclass

kubectl get pods -n ingress-nginx

kubectl get svc -n ingress-nginx
```

Remember: Creating an Ingress resource does not automatically create a cloud LoadBalancer. The networking infrastructure and Ingress Controller must also be configured.

# 2. ConfigMap

## 2.1 What is a ConfigMap?

A ConfigMap is a Kubernetes API object used to store non-sensitive configuration data separately from application code and Docker images.

It helps us maintain different configurations for different environments without rebuilding the Docker image.

## 2.2 Why do we need ConfigMaps?

Let's consider the ShopKart backend.

Our application needs database configuration:

```
DATABASE_HOST=shopkart-db
DATABASE_PORT=5432
DATABASE_NAME=shopkart
```

One approach is to hardcode these values inside our application.

But imagine:

- Development uses `dev-db`.
- Testing uses `test-db`.
- Production uses `prod-db`.

If we hardcode these values, we would need to modify our application code for every environment.

That is not a good deployment practice.

Instead, we separate configuration from the application.

Without ConfigMap

Docker image contains application code with environment-specific configuration hardcoded.

With ConfigMap

Docker image

Application code + dependencies

ConfigMap

Environment-specific configuration

Running container

## 2.3 How to create a ConfigMap?

There are multiple ways.

### Method 1: YAML manifest

```
apiVersion: v1
kind: ConfigMap

metadata:
  name: shopkart-config

data:
  DATABASE_HOST: shopkart-db
  DATABASE_PORT: "5432"
  DATABASE_NAME: shopkart
  APP_ENV: production
```

Apply it:

```
kubectl apply -f configmap.yaml
```

### Method 2: Using kubectl commands

```
kubectl create configmap shopkart-config \
  --from-literal=DATABASE_HOST=shopkart-db \
  --from-literal=DATABASE_PORT=5432 \
  --from-literal=APP_ENV=production
```

### Method 3: From a file

Suppose you have a configuration file:

`application.properties`

```
database.host=shopkart-db
database.port=5432
application.environment=production
```

Create a ConfigMap:

```
kubectl create configmap shopkart-config \
  --from-file=application.properties
```

Kubernetes stores the file contents under the key `application.properties`.

## 2.4 How does ConfigMap integrate with a container?

This is the most important part.

Kubernetes does not modify the Docker image to insert the ConfigMap values.

Instead, it provides those values when the container is created.

There are two major methods.

### Method 1: Environment variables

Consider this Deployment:

```
apiVersion: apps/v1
kind: Deployment

metadata:
  name: shopkart-backend

spec:
  replicas: 2

  selector:
    matchLabels:
      app: shopkart-backend

  template:
    metadata:
      labels:
        app: shopkart-backend

    spec:
      containers:
        - name: backend
          image: shopkart-backend:v1

          envFrom:
            - configMapRef:
                name: shopkart-config
```

Notice:

```
envFrom:
  - configMapRef:
      name: shopkart-config
```

This tells Kubernetes to expose all the ConfigMap key-value pairs as environment variables in the container.

For example:

```
DATABASE_HOST=shopkart-db
DATABASE_PORT=5432
DATABASE_NAME=shopkart
APP_ENV=production
```

Your application can access them.

Node.js:

```
const dbHost = process.env.DATABASE_HOST;
const dbPort = process.env.DATABASE_PORT;
```

Python:

```
import osdb_host = os.getenv("DATABASE_HOST")db_port = os.getenv("DATABASE_PORT")
```

### Method 2: Using individual environment variables

Sometimes we don't want to inject every ConfigMap entry.

We can select only the required values.

```
containers:
  - name: backend
    image: shopkart-backend:v1

    env:
      - name: DATABASE_HOST
        valueFrom:
          configMapKeyRef:
            name: shopkart-config
            key: DATABASE_HOST

      - name: DATABASE_PORT
        valueFrom:
          configMapKeyRef:
            name: shopkart-config
            key: DATABASE_PORT
```

Here:

- `configMapKeyRef` selects one particular key.
- `name` specifies the environment variable name inside the container.
- `key` specifies the key in the ConfigMap.

### Method 3: Mounting ConfigMap as a volume

We can also provide ConfigMap data as files.

Example:

```
apiVersion: apps/v1
kind: Deployment

metadata:
  name: shopkart-backend

spec:
  replicas: 1

  selector:
    matchLabels:
      app: shopkart-backend

  template:
    metadata:
      labels:
        app: shopkart-backend

    spec:
      containers:
        - name: backend
          image: shopkart-backend:v1

          volumeMounts:
            - name: config-volume
              mountPath: /app/config
              readOnly: true

      volumes:
        - name: config-volume
          configMap:
            name: shopkart-config
```

Inside the container:

```
/app/
  config/
    DATABASE_HOST
    DATABASE_PORT
    DATABASE_NAME
    APP_ENV
```

Each file contains its respective ConfigMap value.

For example, reading `/app/config/DATABASE_HOST` returns:

```
shopkart-db
```

## 2.5 How does Kubernetes internally provide ConfigMap values?

Let's understand the workflow:

1. We create a ConfigMap using `kubectl apply`.
2. The Kubernetes API server validates and stores the object.
3. The ConfigMap is persisted in etcd.
4. We create a Deployment that references the ConfigMap.
5. The Deployment controller creates a ReplicaSet, which creates Pods.
6. The scheduler assigns the Pods to worker nodes.
7. Kubelet obtains the Pod specification and required configuration.
8. Kubelet prepares the container configuration.
9. The container runtime starts the container with the requested environment variables or mounted files.

The application reads the values using its normal configuration mechanisms.

## 2.6 What happens when a ConfigMap changes?

This is an important interview question.

Suppose:

Initially:

```
DATABASE_HOST=dev-db
```

You change it to:

```
DATABASE_HOST=prod-db
```

What happens?

If using environment variables:

- Existing containers continue using their original environment values.
- Kubernetes does not automatically change environment variables in running containers.
- You need to restart the Pods to receive the updated values.

For example:

```
kubectl rollout restart deployment shopkart-backend
```

If using volume mounts:

- Kubernetes eventually updates the mounted ConfigMap files.
- The application must reread the files to use the new values.
- A `subPath` mount does not receive automatic updates.

## 2.7 ConfigMap limitations

- ConfigMaps are intended for non-sensitive information.
- They are namespace-scoped.
- Their total data size is limited to 1 MiB.
- They do not automatically update application environment variables.
- They should not be used to store passwords or private credentials.

## 2.8 Useful commands

```
kubectl get configmaps

kubectl describe configmap shopkart-config

kubectl get configmap shopkart-config -o yaml

kubectl delete configmap shopkart-config

kubectl get pods

kubectl exec -it <pod-name> -- printenv
```

# 3. Secrets

## 3.1 What is a Kubernetes Secret?

A Secret is a Kubernetes object designed to hold sensitive information such as:

- Database passwords.
- API tokens.
- Authentication credentials.
- TLS certificates.
- Private keys.

Secrets allow us to separate sensitive configuration from application code and Docker images.

## 3.2 Why do we need Secrets?

Consider your ShopKart backend.

It needs to connect to MongoDB.

The connection string might contain:

```
MONGO_URL=mongodb+srv://username:password@cluster.mongodb.net/shopkart
```

It may also need:

```
JWT_SECRET=some-private-key
PAYMENT_API_KEY=some-api-key
```

We should never hardcode these credentials in the application or push them to GitHub.

Instead, we store them in Kubernetes Secrets.

## 3.3 How to create a Secret?

### Method 1: Using YAML

```
apiVersion: v1
kind: Secret

metadata:
  name: shopkart-secret

type: Opaque

stringData:
  MONGO_URL: mongodb+srv://username:password@cluster.mongodb.net/shopkart
  JWT_SECRET: my-private-secret
  PAYMENT_API_KEY: my-api-key
```

Apply it:

```
kubectl apply -f secret.yaml
```

Here:

- `type: Opaque` represents a general-purpose Secret.
- `stringData` allows us to provide plain text values.
- Kubernetes converts the values to its Secret data representation.

### Method 2: Using kubectl

```
kubectl create secret generic shopkart-secret \
  --from-literal=JWT_SECRET=mysecret \
  --from-literal=PAYMENT_API_KEY=myapikey
```

### Method 3: From a file

Suppose we have a file containing a credential:

```
password.txt
```

Create the Secret:

```
kubectl create secret generic shopkart-secret \
  --from-file=password.txt
```

The file becomes a Secret key, with its contents as the value.

## 3.4 Secret integration with containers

Just like ConfigMaps, Secrets can be supplied through environment variables or mounted files.

### Method 1: Environment variables

```
apiVersion: apps/v1
kind: Deployment

metadata:
  name: shopkart-backend

spec:
  replicas: 2

  selector:
    matchLabels:
      app: shopkart-backend

  template:
    metadata:
      labels:
        app: shopkart-backend

    spec:
      containers:
        - name: backend
          image: shopkart-backend:v1

          env:
            - name: MONGO_URL
              valueFrom:
                secretKeyRef:
                  name: shopkart-secret
                  key: MONGO_URL

            - name: JWT_SECRET
              valueFrom:
                secretKeyRef:
                  name: shopkart-secret
                  key: JWT_SECRET
```

Now Kubernetes provides these values to the container.

Your application reads:

```
const mongoUrl = process.env.MONGO_URL;
const jwtSecret = process.env.JWT_SECRET;
```

The application does not need to know whether these values came from a `.env` file or a Kubernetes Secret.

### Method 2: Using envFrom

If you want to inject all Secret keys:

```
containers:
  - name: backend
    image: shopkart-backend:v1

    envFrom:
      - secretRef:
          name: shopkart-secret
```

This exposes all Secret entries as environment variables.

### Method 3: Mounting Secret as a volume

We can also mount Secret values as files.

```
apiVersion: apps/v1
kind: Deployment

metadata:
  name: shopkart-backend

spec:
  replicas: 1

  selector:
    matchLabels:
      app: shopkart-backend

  template:
    metadata:
      labels:
        app: shopkart-backend

    spec:
      containers:
        - name: backend
          image: shopkart-backend:v1

          volumeMounts:
            - name: secret-volume
              mountPath: /app/secrets
              readOnly: true

      volumes:
        - name: secret-volume
          secret:
            secretName: shopkart-secret
```

Inside the container:

```
/app/secrets/
    MONGO_URL
    JWT_SECRET
    PAYMENT_API_KEY
```

Each file contains its corresponding Secret value.

## 3.5 How are Secrets stored internally?

This is an important security topic.

When you create a Kubernetes Secret:

1. The request reaches the API server.
2. The API server validates the Secret.
3. The Secret is stored in etcd.
4. Authorized components can retrieve it.
5. Kubelet obtains the Secret when needed for the Pod.
6. The Secret is provided to the container as environment variables or mounted files.

Important security distinction:

Kubernetes Secrets are Base64 encoded by default, not encrypted by default.

For production environments, you should:

- Enable encryption at rest for Secrets in etcd.
- Configure appropriate RBAC permissions.
- Restrict access to Secret resources.
- Avoid printing Secret values in logs.
- Avoid committing real Secret manifests to GitHub.
- Consider external secret managers such as HashiCorp Vault or cloud secret-management services.

## 3.6 What happens when a Secret changes?

Suppose the password changes from:

```
old-password
```

to:

```
new-password
```

Environment variable method:

Existing containers continue using the old password.

You need to restart the Pods to load the updated environment variable.

```
kubectl rollout restart deployment shopkart-backend
```

Volume mount method:

Kubernetes eventually updates the mounted Secret files, but the application must reread them. A `subPath` mount does not receive automatic updates.

## 3.7 Types of Kubernetes Secrets

| Secret type                           | Purpose                                       |
| ------------------------------------- | --------------------------------------------- |
| `Opaque`                              | General-purpose credentials and configuration |
| `kubernetes.io/tls`                   | TLS certificate and private key               |
| `kubernetes.io/dockerconfigjson`      | Docker registry authentication                |
| `kubernetes.io/basic-auth`            | Basic authentication credentials              |
| `kubernetes.io/ssh-auth`              | SSH authentication credentials                |
| `kubernetes.io/service-account-token` | Service account token                         |

For ShopKart, the most common type will be `Opaque`.

For your Ingress TLS certificate, you may use `kubernetes.io/tls`.

For pulling private Docker images, Kubernetes can use a registry authentication Secret through `imagePullSecrets`.

## 3.8 Useful commands

```
kubectl get secrets

kubectl describe secret shopkart-secret

kubectl get secret shopkart-secret -o yaml

kubectl create secret generic shopkart-secret \
  --from-literal=JWT_SECRET=mysecret

kubectl delete secret shopkart-secret
```

Be careful: `kubectl get secret -o yaml` displays encoded Secret data. Anyone with permission to read the Secret can potentially retrieve its original values.

# 4. ConfigMap vs Secret – Complete comparison

| Feature                | ConfigMap                   | Secret                    |
| ---------------------- | --------------------------- | ------------------------- |
| Main purpose           | Non-sensitive configuration | Sensitive information     |
| Database hostname      | Yes                         | Possible, but unnecessary |
| Database password      | No                          | Yes                       |
| API endpoint           | Yes                         | Usually no                |
| API token              | No                          | Yes                       |
| Default representation | Plain text                  | Base64-encoded data       |
| Encryption at rest     | Not by default              | Not by default            |
| Environment variables  | Yes                         | Yes                       |
| Volume mounting        | Yes                         | Yes                       |
| Namespace-scoped       | Yes                         | Yes                       |
| Default size limit     | 1 MiB                       | 1 MiB                     |

# 5. Complete ShopKart architecture

Let's put everything together.

[Kubernetes for Absolute Beginners: Build and Run Your First Two-Pod App from Scratch | by Niran Peiris | Medium](https://images.openai.com/static-rsc-4/5XsKYch8tcNk35UiXCqaRll_R63UQxd7yCn6HjZF9T84t-T3b6SQeuK5DJACe74bs3EVx0gFdHr3yH3_Gy4zKwXMTnliXxlfwhVoGNdQMTJyixshYYrXzj_YuYYw0SV0Wj_Xb-mEGIBf4ZL6Yx_8H9rMFfXWbxjceCGGLC9LOeo?purpose=inline)

[medium.com](https://medium.com/%40niranpeiris/kubernetes-for-absolute-beginners-build-and-run-your-first-two-pod-app-from-scratch-4f11d42f84b9?utm_source=chatgpt.com)

Imagine your ShopKart application is deployed in Kubernetes.

External request workflow:

1. User accesses `shopkart.com`.
2. DNS resolves the domain.
3. Traffic reaches the Ingress Controller.
4. Ingress evaluates the hostname and path.
5. Traffic is forwarded to the frontend or backend Service.
6. Service forwards the request to the appropriate Pod.

Configuration workflow:

1. The Deployment specifies the Docker image.
2. The Deployment references the ConfigMap.
3. The Deployment references the Secret.
4. Kubelet prepares the container configuration.
5. The container runtime starts the container.
6. The application reads the supplied environment variables.
7. The backend uses its database credentials to connect to MongoDB.

## 6. Important concept: Build once, deploy many times

This is especially important for your Harness CI/CD project.

Suppose you have one Docker image:

```
shopkart-backend:v1
```

You deploy the same image in different environments.

| Environment | DATABASE_HOST | DATABASE_PASSWORD |
| ----------- | ------------- | ----------------- |
| Development | dev-db        | Dev Secret        |
| Testing     | test-db       | Test Secret       |
| Production  | prod-db       | Prod Secret       |

The application code remains unchanged.

You don't need three different Docker images.

You build once, push the image to Artifactory, and supply the appropriate configuration during deployment.

# 7. Quick interview revision

| Question                                                                      | Key answer                                                     |
| ----------------------------------------------------------------------------- | -------------------------------------------------------------- |
| Why do we need Ingress?                                                       | To manage external HTTP/HTTPS routing to Kubernetes Services.  |
| Does Ingress work without a controller?                                       | No, a controller is needed to implement the rules.             |
| Does Ingress directly route to Pods?                                          | Standard Ingress rules target Services.                        |
| Why do we need ConfigMaps?                                                    | To separate non-sensitive configuration from application code. |
| Why do we need Secrets?                                                       | To manage sensitive configuration separately.                  |
| Does ConfigMap modify the Docker image?                                       | No.                                                            |
| How does Kubernetes inject ConfigMap values?                                  | Environment variables or volume mounts.                        |
| How does an application read Secret values?                                   | Through environment variables or files.                        |
| Is Base64 encryption?                                                         | No.                                                            |
| Do updated environment variables automatically appear in existing containers? | No. Restart the containers/Pods.                               |
| Can the same Docker image run in multiple environments?                       | Yes, with different ConfigMaps and Secrets.                    |

Recommended next practical exercise: Create a ShopKart Ingress, ConfigMap and Secret in your local Kubernetes cluster, reference them from your existing Deployments, and verify the configuration inside the running Pods. This will connect all the theory to actual Kubernetes behavior.
