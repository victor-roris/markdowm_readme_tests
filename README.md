# Markdowm Readme Tests
In this project I test some MARKDOWN sitaxis in GITHUB website. 

## Image tests

### URL source 

 - Plain markdown 
```markdown
![url image](https://avatars.githubusercontent.com/u/33596234?v=4 "Image title")
```
![url image](https://avatars.githubusercontent.com/u/33596234?v=4 "Image title")


 - Standard HTML with style
```markdown
<img src="https://avatars.githubusercontent.com/u/33596234?v=4"
     alt="URL image"
     style="width: 150px; height: 150px; border: 1px solid black;" />
```
<img src="https://avatars.githubusercontent.com/u/33596234?v=4"
     alt="URL image"
     style="width: 150px; height: 150px; border: 1px solid black;" />

     
 - Wrapper HTML with style
```markdown
<div>
   <img src="https://avatars.githubusercontent.com/u/33596234?v=4"
     alt="URL image"
     style="width: 150px; height: 150px; border: 1px solid black;" />
</div>
```
<div>
   <img src="https://avatars.githubusercontent.com/u/33596234?v=4"
     alt="URL image"
     style="width: 150px; height: 150px; border: 1px solid black;" />
</div>
     
     
 - Centered HTML 
```markdown
<div style="text-align:center">
    <img src="https://avatars.githubusercontent.com/u/33596234?v=4"
         alt="URL image"
         style="width: 150px; height: 150px; border: 1px solid black;" />
</div>
```

<div style="text-align:center">
    <img src="https://avatars.githubusercontent.com/u/33596234?v=4"
         alt="URL image"
         style="width: 150px; height: 150px; border: 1px solid black;" />
</div>


### Relative image 

 - Plain markdown 
```markdown
![relative image](assets/victor_roris.jpg "Image title")
```
![relative image](assets/victor_roris.jpg "Image title")


 - Proprietary markdown 
```markdown
![relative image](assets/victor_roris.jpg  =150x100)
```
![relative image](assets/victor_roris.jpg  =60x60)


```markdown
![relative image](assets/victor_roris.jpg){: width=90 height=90 style="float:right; padding:16px"}
```
![relative image](assets/victor_roris.jpg){: width=90 height=90 style="float:right; padding:16px"}


```markdown
![relative image](assets/victor_roris.jpg){ width=50% }
```
![relative image](assets/victor_roris.jpg){ width=50% }


 - HTML Wrapper in markdown
```markdown
<div style="width:300px; height:300px">
  ![relative image](assets/victor_roris.jpg)
</div>
```
<div style="width:300px; height:300px">
  ![relative image](assets/victor_roris.jpg)
</div>


 - HTML 
```markdown
<div style="text-align:center">
    <img src="assets/victor_roris.jpg"
         alt="URL image"
         style="width: 150px; height: 150px; border: 1px solid black;" />
</div>
```

<div style="text-align:center">
    <img src="assets/victor_roris.jpg"
         alt="URL image"
         style="width: 150px; height: 150px; border: 1px solid black;" />
</div>
 
### Internal Relative image 

 - Plain markdown 
```markdown
![relative image](src/assets/victor_roris.jpg "Image title")
```
![relative image](src/assets/victor_roris.jpg "Image title")

```markdown
![relative image](src/internal_module/assets/victor_roris.jpeg "Image title")
```
![relative image](src/internal_module/assets/victor_roris.jpeg "Image title")


 - HTML 
```markdown
<div style="text-align:center">
    <img src="src/assets/victor_roris.jpg"
         alt="URL image"
         style="width: 150px; height: 150px; border: 1px solid black;" />
</div>
```
<div style="text-align:center">
    <img src="src/assets/victor_roris.jpg"
         alt="URL image"
         style="width: 150px; height: 150px; border: 1px solid black;" />
</div>


```markdown
<div style="text-align:center">
    <img src="src/internal_module/assets/victor_roris.jpeg"
         alt="URL image"
         style="width: 150px; height: 150px; border: 1px solid black;" />
</div>
```
<div style="text-align:center">
    <img src="src/internal_module/assets/victor_roris.jpeg"
         alt="URL image"
         style="width: 150px; height: 150px; border: 1px solid black;" />
</div>