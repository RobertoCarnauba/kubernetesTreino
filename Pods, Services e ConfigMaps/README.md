# kubernetesTreino
## Criando o cluster 


## Criando e entendendo pods

Criar pod declárativo:
```
 kubectl apply -f .\nome-pod.yaml

```
Buscar os pod
```
 kubectl get pods
 
```
Descrever os pod
```
 kubectl  describler pod nome-arquivo.yaml 
 
```

Executar comandos internamente no pod
```
 Kubectl exec –it nome-pode  --  bash
 curl localhost
 
```

## Expondo pods com services 
 O SVC faz  a comunicação entre os pod no cluster e expõe o pod.  
 **Label** - Entiquetar os pods. 
Através de labels definidas no metadata e utilizando o campo selector no service, podemos saber 
quais pods devemos gerencia.

#### Tipods de SVC:
 * ClusterIP
 * NodePort
 * LoadBalancer
## Aplicando services ao projeto
## Definindo variáveis de ambiente 
