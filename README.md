## DOX Notify
This is a fork from nd-notify which was a fork from mythic notify. All credit at this point goes to them. 

---NOT READY FOR CONSUMPTION YET---

## Features
- Nice Styling
- Police Notifications
- Framework agnostic
- FontAwesome Icons

## This clip shows a little preview
### [Click Me](https://streamable.com/m1diij)
---
## How to Use
```lua
-- Client Side
TriggerEvent('dox-notify:client:sendAlert', { 
    type = 'primary', -- Types = [primary, success, error, police]
    text = 'This is a test primary notification!',
    length = 3000,
    style = {['background-color'] = '#FFFFFF', ['color'] = '#000000' } -- This is optional
})
```

```lua
-- Server Side
TriggerClientEvent('dox-notify:client:sendAlert', source, { 
    type = 'primary', -- Types = [primary, success, error, police]
    text = 'This is a test primary notification!',
    length = 3000,
    style = {['background-color'] = '#FFFFFF', ['color'] = '#000000' } -- This is optional
})
```

## Todo
Replace ESX notifications.
