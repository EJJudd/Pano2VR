### Modify the video properties

The video properties will automatically appear in the Properties panel when the video is selected. There are several properties which can be viewed and/or modified:

- **ID**: Each video element is given a unique ID. The default is *Element01*. The number will increase with each added element.

    !!! warning "Follow along"
        Rename the ID to: *Video01*.

- **File**: This shows the path to and filename of the video. The video can be swapped out at anytime for another video by clicking on the **folder** icon (![Folder Icon](assets/images/FolderIcon.png){width="25"})

- **Alternative File(s)**: Since not all browers support all video file formats, this field can be used to add (up to three) additional file formats of the video. If the first file is not supported by the browser, the Alternative File(s) will be used. To add an alternative file, click on the **folder** icon (![Folder Icon](assets/images/FolderIcon.png){width="25"}) and select the alternative files(s).

    !!! warning "Follow along"
        Since MP4 files are supported by all major browsers, this step can be skipped for now. However, this is useful to consider if working with less common formats.

- **Mode**: This field refers to the sound mode. There are six sound modes:
    
    - **Static**: the audio will play uniformly in all directions.<br><br>
    - **Surround**: the audio will play in all directions, but the sound channels will automatically adjust to match the perspective.<br><br>
    - ![Directional Rectangular Mode](assets/images/ModeDirectionalRectangular.png){width=50%, align=right}**Directional Rectangular** (*default mode*): the audio will play at maximum level when centred on the field (green rectangle) and gradually fade out following the rectangular sound field (yellow). 
    
        The *Horizontal*, *Vertical*, and *Field* sizes can also be adjusted in the Properties panel.

    - **Directional Circular**: the audio behaves the same as in the **Directional Rectangular** mode but uses a circular sound field.<br><br>
    - **Effect Rectangular**: the audio will only play within the rectangular sound field (green rectangle).<br><br>
    - **Effect Circular**: the audio will only play within the circular sound field (green circle).


- **Level**: This field refers to the audio volume of the video, where 0 (i.e., 0%) is muted and 1 (i.e., 100%) is maximum volume. By default the volume is set to 1.

- **Loop**: This field can be modified to change the number of times the video repeats its playback. There are four options:
    - **-1**: the video will not play until it is activated by a click (or another action specified in the Skin Editor)
    - **0**: the video will play on a continuous loop
    - **1** (*default loop*): the video will play once
    - **Any other positive integar**: the video will play that many times (e.g., if 4 is selected, the video will play four times)
        !!! warning "Follow along"
        Change the *Loop* value to **-1**, which will require the video playback to be activated by a click.    

- **Auto-start** – If the browser is preventing the video from auto-playing, and Start muted is selected, the video will play back but the audio will be muted.

Horizontal Size – Determines the horizontal size of the center (green section) sound field. Available for the Effect and Directional modes only.

Vertical Size – Determines the vertical size of the center (green section) sound field. Available for the Effect and Directional Rectangular modes only.

Field Size – Determines the overall size of the sound field. Available for the Direction modes only.

Click Mode – Choose what will happen when a user clicks on the video from the following options:

None – Nothing happens.

Play/Pause – Clicking on the video will toggle playback and pausing.

Pop out normal – Clicking will cause the video to move forward (animate) from its pinned position and will enlarge to its original dimensions. The video will start to play once the player is loaded.

Pop out 100% – Clicking will cause the video to move forward (animate) from its pinned position and will enlarge to fit the player window. The video will start to play on start up.

Pop Back These options are available when Pop out normal or Pop out 100% are selected. This determines the video’s state when the video pops back to the panorama.

Stop – The video will stop playing when popped back.
Keep Playing – The video will keep playing when popped back.
Keep Playing Muted – The video will keep playing but will be muted when popped back.
Hand Cursor – Select enable to have the mouse cursor turn into a hand cursor when it hovers over a pinned video in the output.

Position – Select Lock to lock the video’s position in place.

X Rotation – Changes the element’s rotation on the X axis. Units are in degrees. Correlates to the top arrow in the preview image.

Y Rotation – Changes the element’s rotation on the Y axis. Units are in degrees. Correlates to the left arrow in the preview image.

Z Rotation – Changes the element’s rotation on the Z axis. Units are in degrees. Correlates to the center arrow in the preview image.

FoV – This is the horizontal field of view that the video covers. A smaller angle will decrease the overall size; larger angle increases the size or how much the video covers the field of view.

Vertical Stretch – This will stretch the vertical dimension of the video. This is used to help assist in exact fitting of a space (like a TV Screen). Anything beyond 100% will be vertically extended and therefore distort the video. Anything below 100% will will squeeze the picture horizontally.

For more information, see the Pano2VR [video properties](https://ggnome.com/doc/pano2vr/workspace/viewer-modes/videos-props/) documentation.