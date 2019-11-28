# identifier
Identify - [Face Recognition API](https://github.com/ageitgey/face_recognition) in Python, for identifying faces in an image.

## End Points
### Upload an image which returns an ID
Method=['POST']

Params: image -- Image File

Returns: image_id -- [id of the image]

`https://identifyapi.herokuapp.com/image/upload`
![Add](https://github.com/Md-Mudassir/identifier/blob/master/img/addimg.JPG)

### Add image data to image id
Method=['POST']

Header: Content-Type: application/json

Params: image_id -- [id of the image]

data -- data of the coressponding image

`https://identifyapi.herokuapp.com/image/data`
![Add Data](https://github.com/Md-Mudassir/identifier/blob/master/img/addimgdata.JPG)

### Query image
Method=['POST']

Params: image -- Image File

`https://identifyapi.herokuapp.com/image/query`
![query img](https://github.com/Md-Mudassir/identifier/blob/master/img/result.JPG)
