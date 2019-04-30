# 4 STEP ADD PROPS #
-----------------
###1. Parent###
 ```
data: {
  key : value
}
```
###2. Parent###
 ```
<tag :propsname='key'>
```
###3. Chidren###
```
props: ['propsname']
```
###4. Chidren###
```
<tag>{{ propsname }}</tag>
```
