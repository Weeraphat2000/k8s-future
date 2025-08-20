# k8s-future

# mount volume คือ ทำให้ container จัดเก็บข้อมูลลงใน container ได้

# stateless app คือ ตัว app เองจะไม่เก็บอะไรไว้เลย ถ้าจะมีการบันทึกข้อมูลอะไรจะบันทึกลง database ส่งออกไปข้างนอก app เผื่อเก็บข้อมูล

# kubectl delete -f . เพื่อลบ service, pod, deployment ออก

. ก็คืออ่านทุกไฟล์และลบออก ถ้าใส่เป็นทีละชื่อ file ก็ได้ มันจะค่อยๆลบ service, pod, deployment นั้นออก

# kubectl exec -it <pod-name> -- bash เพื่อเข้าไปที่ pod(container)

# exit คือออกจาก container
