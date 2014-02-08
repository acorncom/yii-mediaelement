yii-mediaelement
================
This ext allow you to add HTML5 audio and video player using mediaElement JS library to you Yii project.

Its using latest code from http://mediaelementjs.com/.
Requirements

Yii 1.1 or above
Usage

Just use the widget anywhere in your view code.

$this->widget ( 'ext.mediaElement.MediaElementPortlet',
    array ( 
    'url' => 'http://www.toxsl.com/test/bunny.mp4',
// or you can set the model and attributes
    //'model' => $model,
    //'attribute' => 'url'
// its required and so you have to set correctly
    // 'mimeType' =>'audio/mp3',
 
    ));

Resources

demo: http://www.iseetv.biz/media/2?title=Radio+Gabbar
