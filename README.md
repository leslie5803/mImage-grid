# mImage-grid
It's a jQuery plugin, can preview images on mobile. And it's based on [images-grid](https://github.com/taras-d/images-grid).

## How to use ?

- Step 1

```
<link rel="stylesheet" type="text/css" href="images-grid.css">
<script type="text/javascript" src="images-grid.js"></script>
```

- Step 2

```
<script type="text/javascript">
$('#images-grid').imagesGrid({
	images: ['1.png', '2.png', '3.png'],
	cells: 3, //default 5
	align: true, //default false
});
</script>
```