# pandora
A gallery that allow image browsing by exif tags.

Pandora uses a python dictionary and stores it in the ImageDescription exif tag.
This dictionary allows the user to specify:

Description - Description of the picture<br>
Comment - Personal comment<br>
Rating - Picture rating<br>
Person - Person(s) in the picture<br>
Keywords - Keywords<br>
Series - Sets where the picture belongs to<br>
Also has an extra field:<br>
md5sum - Original md5sum hash before the dictionary were added to it used to find duplicates.<br>

