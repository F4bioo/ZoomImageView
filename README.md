# ZoomImageView
This is a component class in Kotlin for Android projects that extends from ImageView to help implement zoom feature on images.

### Hou to use

- Copy the ZoomImageView.kt file to your Android project

- Create or copy the attrs.xml file to the value folder

```sh
<?xml version="1.0" encoding="utf-8"?>
<resources>
    <declare-styleable name="ZoomImageView">
        <attr name="setMaxZoom" format="float" />
    </declare-styleable>
</resources>
```
- Add ZoomImageView to your layout as usual 
```sh
<xxx.xxx.xxx.xxx.xxx.ZoomImageView <-- call ZoomImageView instead of ImageView
    android:id="@+id/image_photo"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:src="@drawable/dog_by_matthew_wiebe"
    app:setMaxZoom="10" /> <-- set the maximum zoom value (default is 3)
```

## Example
<img src="example.gif" width="30%"></img>
