# monkey android test
* python3 
* Statistical performance cpu,men,fps,battery,flow(wifi,gprs)
* Statistics crash info.
* muilt android
 


## monkey.ini setting

``` 

cmd=monkey -p ola.com.user --throttle 500 --ignore-timeouts --ignore-crashes   --monitor-native-crashes -v -v -v 200 >
package_name=ola.com.user
activity = ola.com.user.app.main.activity.WelcomeActivity
net = wifi 
```

- throttle Each event waits for 500 milliseconds
- net gprs or wifi


![monkey���](img/analysis.jpg  "monkey���")

![monkey���](img/monitor.png  "monkey���")

![monkey���](img/crash.PNG  "monkey���")

# other
* [Chinese](Chinese.md)







# monkey-test
# monkey-test
# monkey-test
# monkey-test
# monkey-test
