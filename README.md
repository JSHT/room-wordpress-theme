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

## 2. 在 assess.php .row 添加 m-auto
```htmlembedded=
<div class="row justify-content-center m-auto">...</div>
```

## 3. Others
- img name SHA256 hashed `[:10]`
- about.php add `px-5`

Before
![](https://i.imgur.com/azf4XnH.png)
After
![](https://i.imgur.com/mBCf5h2.png)
Whole
![](https://i.imgur.com/7nldOi6.jpg)
