# room-wordpress-theme

## 1. change img path
- about.php
- assess.php
- join.php

Using
```php=
<?php echo get_template_directory_uri(); ?>
```
找到主題所在資料夾路徑後再確定圖片路徑
```htmlembedded=
<img src="<?php echo get_template_directory_uri(); ?>/assets/img/..."
```

## 2. 在 assess.php 增加 div
```htmlembedded=
<div>
    original assess.php code
</div>
```
