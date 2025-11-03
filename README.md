# busybox_pod_lab4

## Komenda tworząca szablon yaml
```
kubectl run loop --image=busybox:1.36.1 --dry-run=client -o yaml > loop.yaml
```
<img width="806" height="52" alt="image" src="https://github.com/user-attachments/assets/8d5726d7-c3c5-4a97-bd68-68b0e2d4db5e" />


## Szablon yaml
<img width="908" height="501" alt="image" src="https://github.com/user-attachments/assets/54f682c1-d444-49c8-8162-70f6bbc05e31" />

## Uruchomienie poda
```
kubectl apply -f loop.yaml
```
<img width="301" height="61" alt="image" src="https://github.com/user-attachments/assets/36790b3a-b900-4a6a-ac5f-64806da0becb" />


## Status poda po uruchomieniu
```
kubectl get pods
```
<img width="536" height="90" alt="image" src="https://github.com/user-attachments/assets/5d31f643-c093-4329-8977-2995bdcfe5e5" />

## Logi minikube
```
kubectl logs loo
```
<img width="302" height="163" alt="image" src="https://github.com/user-attachments/assets/cf45ca19-6d7c-4927-9497-21ad7c9b33ad" />

## Modyfikacja .yaml (dodanie nieskończonej pętli)
<img width="967" height="502" alt="image" src="https://github.com/user-attachments/assets/782109e8-632d-4635-b624-17f9d29c5b30" />

## Wynik działania kubectl get pods
<img width="967" height="93" alt="image" src="https://github.com/user-attachments/assets/71eee610-c970-486a-9a21-e766c58bd6cc" />
