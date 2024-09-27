# lec-resources

## lec-06 routing note
You can extract the URI and http method using this code:
```
$uri = parse_url($_SERVER['REQUEST_URI'])['path'];
$method = $_SERVER['REQUEST_METHOD'];
```
