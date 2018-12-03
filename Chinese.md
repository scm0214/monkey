# monkey ѹ������android ��
* python3 
* ͳ��������Ϣcpu,men,fps,battery,flow
* ֧��wifi,gprsͳ��
* ͳ��crash��Ϣ
* ֧�ֶల׿�豸
 


## monkey.ini �����ļ�

``` 

cmd=monkey -p ola.com.user --throttle 500 --ignore-timeouts --ignore-crashes   --monitor-native-crashes -v -v -v 200 >
package_name=ola.com.user
activity = ola.com.user.app.main.activity.WelcomeActivity
net = wifi 
```

- throttle ÿ���¼��ȴ�500����
- net ֧��gprs��wifi


![monkey���](img/analysis.PNG  "monkey���")

![monkey���](img/monitor.png  "monkey���")

![monkey���](img/crash.PNG  "monkey���")







