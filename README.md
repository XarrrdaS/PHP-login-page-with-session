
# Login panel with session

Default login is: $\color{red}{admin}$<br>
Default password is: $\color{red}{admin}$<br><br>
To change login or password, you need to use this:<br>


```diff
<?php
  echo password_hash(`Word you want to hash`, PASSWORD_BCRYPT);
?>
```
Generated hash, copy and paste to <i>`hash.php`</i> file<br><br>
