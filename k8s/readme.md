����� �������� ���������� �� ���� ����� ����� ���������� mysql �� helm:

- �������� �����������:

`helm repo add stable https://kubernetes-charts.storage.googleapis.com/`

`helm repo update`

- ���������� ���� mysql: 

`helm install mysqldb --set mysqlUser=myuser,mysqlPassword=mypasswd,mysqlDatabase=myapp_v2 stable/mysql`