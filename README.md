## Activity Lifecycle Explained
<p align="center">
  <img src="https://i.imgur.com/tMdSvj4.png" alt="Activity Lifecycle by Google developers docs"/>
</p>

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