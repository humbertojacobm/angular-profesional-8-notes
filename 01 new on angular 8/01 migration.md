if you want to migrate you need to use this page.

https://update.angular.io/

you can choose if you are using angular material, because that is adding more steps.

if you wants to control all de flow you can choose "advanced" to see all the details.

following the example we can do this.

```bash
  npm i -g @angular/cli@latest
```
With this, we are installing the lastest angularcli, no in the current folder.
the reason is because we will use this angularcli to migrate.

```bash
  ng update
```
we can see the instructiosn to migrate, so we can follow this order 


```bash
  ng update @angular/cli @angular/core
```

this is taking the angular dependencies to the 8th version.

You can see for the ViewChild, we will use {static:true}.

```bash
  ng i @angular/cdk@8.1.4 @angular/material@8.1.4 --save
```

we can mix between ng update and ng i

remember that angular move all the files.