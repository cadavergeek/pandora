# pandora
A gallery that allow image browsing by exif tags.

Pandora uses a python dictionary and stores it in the ImageDescription exif tag.
This dictionary allows the user to specify:

Description - Description of the picture
Comment - Personal comment
Rating - Picture rating
Person - Person(s) in the picture
Keywords - Keywords
Series - Sets where the picture belongs to
Also has an extra field:
md5sum - Original md5sum hash before the dictionary were added to it used to find duplicates.

