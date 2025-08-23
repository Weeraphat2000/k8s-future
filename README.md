# k8s-future

# mount volume คือ ทำให้ container จัดเก็บข้อมูลลงใน container ได้

# stateless app คือ ตัว app เองจะไม่เก็บอะไรไว้เลย ถ้าจะมีการบันทึกข้อมูลอะไรจะบันทึกลง database ส่งออกไปข้างนอก app เผื่อเก็บข้อมูล

# kubectl delete -f . เพื่อลบ service, pod, deployment ออก

. ก็คืออ่านทุกไฟล์และลบออก ถ้าใส่เป็นทีละชื่อ file ก็ได้ มันจะค่อยๆลบ service, pod, deployment นั้นออก

# kubectl exec -it <pod-name> -- bash เพื่อเข้าไปที่ pod(container)

# exit คือออกจาก container

# curl -LO https://get.helm.sh/helm-v3.4.1-darwin-amd64.tar.gz ดาวห์โหลด helm จะได้เป็น file zip มา (helm-v3.4.1-darwin-amd64.tar.gz )

# tar -xvf helm-v3.4.1-darwin-amd64.tar.gz เพื่อแตกไฟล์ zip เข้าไปให้เจอ file helm-v3.4.1-darwin-amd64.tar.gz ให้เจอ directory ก่อนนะ

# helm install -f rb-values.yml reabbitmq bitnami/rabbitmq ลง service ของ rabbitmq => service, pod

# Prometheus

# helm repo add prometheus-community https://prometheus-community.github.io/helm-charts

# helm repo update

# helm install prometheus prometheus-community/kube-prometheus-stack

# kubectl edit service <service-name> เข้าไปแก้ service

# kubectl edit service prometheus-kube-prometheus-prometheus

แก้จาก clusterIp เป็น NodePort
