### kubernetes Task ☸️

#### Kubernetes project that shows price of BitCoin and displays the latest news from Ynet:    


## Run the project

```bash
  git clone https://github.com/waheeb96/kubernetes-task.git
```
```bash
  cd kubernetes-task
```

```bash
  minikube start
```

```bash
  minikube addons enable ingress
```
```bash
  kubectl apply -f .
```

```bash
  minikube tunnel
```

Run in browser:  
● http://localhost/bitcoin
● http://localhost/news-parser

## Close project
```bash
  minikube delete -f .
```
```bash
  minikube delete
```
