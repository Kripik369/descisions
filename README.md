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

<img width="641" height="74" alt="image" src="https://github.com/user-attachments/assets/064f183e-0cd2-4522-98ee-ee6f77182d8b" />

файл остался

после удаления pv тоже остался 

манифесты для задания 2
containers-data-exchange2.yaml
pv-pvc.yaml
pvc2.yaml

задание 3

<img width="1516" height="392" alt="image" src="https://github.com/user-attachments/assets/306103a1-995b-4ecb-a9df-2a8a2f7199aa" />

созданы pvc, sc, pod

<img width="1671" height="399" alt="image" src="https://github.com/user-attachments/assets/93e92aeb-0e6a-4e33-98ca-070144627284" />


контейнеры пишут и читают

манифесты для задания 3
containers-data-exchange3.yaml
sc.yml
pvc.yaml
