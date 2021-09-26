# ZoomImageView

### Hou to use
Create an attrs.xml file in the value folder

```sh
<?xml version="1.0" encoding="utf-8"?>
<resources>
    <declare-styleable name="ZoomImageView">
        <attr name="setMaxZoom" format="float" />
    </declare-styleable>
</resources>
```
Add ZoomImageView to your layout as usual 
```sh
<xxx.xxx.xxx.xxx.xxx.ZoomImageView <-- call ZoomImageView itend of ImageView
    android:id="@+id/image_photo"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:src="@drawable/dog_by_matthew_wiebe"
    app:setMaxZoom="10" /> <-- set the maximum zoom value (default is 3)
```

## Example
<img src="example.gif" width="30%"></img>