# identifier
Identify - [Face Recognition API](https://github.com/ageitgey/face_recognition) in Python, for identifying faces in an image.

## End Points
### Upload an image which returns an ID

Params: image -- Image File

Returns: image_id -- [id of the image]

`https://identifyapi.herokuapp.com/image/upload`

### Add image data to image id

Header: Content-Type: application/json

Params: image_id -- [id of the image]

data -- data of the coressponding image

`https://identifyapi.herokuapp.com/image/data`

### Query image

Params: image -- Image File

`https://identifyapi.herokuapp.com/image/query`
