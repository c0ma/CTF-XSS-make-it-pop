```
<?php
    $id = preg_replace('/[\\\<>\'\/]/', '.', $_GET['id']);
    echo '<script>document.write(\'<div id='. $id .'>' . $id . ' </div>\');</script>';
?> 
```
