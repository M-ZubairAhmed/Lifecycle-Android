## Activity Lifecycle Explained
![Activity lifecycle](https://i.imgur.com/tMdSvj4.png)
<br>
*courtesy : google*

### Case 1
#### Activity 1 starting for first time

Activity 1 :
- onCreate()
- onStart()
- onResume()

### Case 2
#### Activity 1 resuming from home screen

Activity 1:
- onRestart()  [*optional*]
- onStart()
- onResume()