# window._promise
promise

```
_promise(function(resolve 成功, reject 错误){
	...
	})
	.then(function(返回值){
	...
	}) 成功后执行
	.wait(等待秒数) 等待
	.fail(function(错误值){
	...
	}) 错误后执行
	.always(function(){
	...
	}) 无论成功或错误都要执行
	
_promise.when(function(resolve, reject){
	...
	}, string, ...) 参数无限制
	.done(function(返回值){
	...
	}) 成功后执行
	.fail(function(错误值){
	...
	}) 错误后执行
```
