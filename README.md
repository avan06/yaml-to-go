# yaml-to-go

Parse `yaml string to js object`(used [jeremyfa/yaml.js](https://github.com/jeremyfa/yaml.js)) and `convert to Go struct`(reference by [json-to-go](https://github.com/mholt/json-to-go)).

[Check example in jsfiddle](https://jsfiddle.net/s2zcm0jb/show/)

___

## Getting started

***Include yaml and yaml-to-go on your page：***

*yaml can download from [jeremyfa/yaml.js](https://github.com/jeremyfa/yaml.js/blob/develop/dist/yaml.min.js) or here `/example/lib/yaml.min.js`*

```html
<script type="text/javascript" src="/Path/To/yaml.min.js"></script>
<script type="text/javascript" src="/Path/To/yaml-to-go.js"></script>
```


***Parse yaml string：***

```javascript
var result = yamlToGo(iEditor.getValue());
if (result.error) {
	console.log(result.error);
} else {
	console.log(result.go);
}
```

___

## Reference：

* [mholt/json-to-go](https://github.com/mholt/json-to-go)
* [jeremyfa/yaml.js](https://github.com/jeremyfa/yaml.js)
* [go-yaml/yaml](https://github.com/go-yaml/yaml)

___

![yamlToGO](https://raw.githubusercontent.com/avan06/yaml-to-go/master/example/yamlToGO.png)
