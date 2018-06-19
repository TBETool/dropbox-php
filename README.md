# Dropbox upload
Upload to dropbox

### Install
```
composer require tbetool/dropbox-php
```

### Initialize
```
$dropbox = new Dropbox($access_token);
```

### Uploading
```
$response = $dropbox->upload('/file/path', 'title');
```

##### Response
response will contain
```
[
    'id' => 'upload_id',
    'file_name' => 'uploaded file name'
]
```
