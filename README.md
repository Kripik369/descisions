задание 1)

<img width="2516" height="1369" alt="image" src="https://github.com/user-attachments/assets/b76b3fb6-13ac-4d4b-8b77-eabbc4cf006a" />

kubectl describe pods data-exchange

<img width="1602" height="384" alt="image" src="https://github.com/user-attachments/assets/1e716aa9-a0f8-424f-92ff-613a461ddbce" />


запись и считывание каждые 5 секунд

манифест для задания 1
containers-data-exchange.yaml

задание 2)

<img width="1827" height="202" alt="image" src="https://github.com/user-attachments/assets/3e4274b8-70c5-426e-a462-916ed7ba7646" />

установлены pv, pvc

 <img width="1616" height="446" alt="image" src="https://github.com/user-attachments/assets/60176adb-0821-449b-aa5d-7cdc29661147" />

контейнеры пишут и считывают в них

<img width="942" height="594" alt="image" src="https://github.com/user-attachments/assets/c524d052-723e-4184-9513-5b2fe604f0d3" />

после удаления pvc pv остался так как там был retain
