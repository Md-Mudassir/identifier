# identifier
Identify Face Recognition API in Python

## End Points
#### Upload an image which returns an ID

Params: image -- Image File

Returns: image_id -- [id of the image]

`https://identifyapi.herokuapp.com/image/upload`

### Add image data to image id
Header: Content-Type: application/json
Params: image_id -- [id of the image]
data -- data of the coressponding image
`https://identifyapi.herokuapp.com/image/data`
