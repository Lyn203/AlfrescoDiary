## Access Map
```
<#list msg?keys as key>
	${key} = ${msg[key]}
</#list>
```

## Access Object
```
<#list students as student>
	${student.getName()}
	${student.getAge()}
</#list>
```
