# Markdowm Readme Tests
In this project I test some MARKDOWN syntax in GITHUB website. The idea is test (and take note) what works and what doesn't work.

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


 - Standard HTML with size tags
```markdown
<img width="150" height="150" src="https://avatars.githubusercontent.com/u/33596234?v=4"
     alt="URL image" />
```
<img width="150" height="150" src="https://avatars.githubusercontent.com/u/33596234?v=4" alt="URL image" />
     
     
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
    <img width="150" height="150" 
         src="https://avatars.githubusercontent.com/u/33596234?v=4" alt="URL image" />
</div>
```

<div style="text-align:center">
    <img width="150" height="150" src="https://avatars.githubusercontent.com/u/33596234?v=4" alt="URL image" />
</div>

```markdown
<img align="right" height="244" 
     src="https://avatars.githubusercontent.com/u/33596234?v=4" 
     alt="URL image" title="URL image">
```

<img align="right" height="244" src="https://avatars.githubusercontent.com/u/33596234?v=4" alt="URL image" title="URL image">


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


 - HTML with size tags
```markdown
<img width="150" height="150" src="assets/victor_roris.jpg"
     alt="URL image" />
```
<img width="150" height="150" src="assets/victor_roris.jpg"
     alt="URL image" />
 
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
<img width="150" height="150" src="src/assets/victor_roris.jpg"
     alt="URL image" />
```

<img width="150" height="150" src="src/assets/victor_roris.jpg"
     alt="URL image" />


```markdown

<img width="150" height="150" src="src/internal_module/assets/victor_roris.jpeg"
     alt="URL image" />
```
<img width="150" height="150" src="src/internal_module/assets/victor_roris.jpeg"
     alt="URL image" />


### Border in image


 - Plain markdown 
```markdown
<kbd>
  ![relative image](assets/victor_roris.jpg "Image title")
</kbd>
```
<kbd>
  ![relative image](assets/victor_roris.jpg "Image title")
</kbd>

 - HTML
```markdown
<kbd>
<img width="150" height="150" src="assets/victor_roris.jpg" alt="URL image" />
</kbd>
```
<kbd>
  <img width="150" height="150" src="assets/victor_roris.jpg" alt="URL image" />
</kbd>

### Clickable image

 - Markdown 
```markdown
[![clickable image](assets/victor_roris.jpg "Image Title")](https://www.linkedin.com/in/victor-roris/)
```
[![clickable image](assets/victor_roris.jpg "Image Title")](https://www.linkedin.com/in/victor-roris/)


 - HTML
```markdown
<a href="https://www.linkedin.com/in/victor-roris/"  target="_blank">
  <img width="150" height="150" align="center" src="assets/victor_roris.jpg" alt="URL image" />
</a>
```

<a href="https://www.linkedin.com/in/victor-roris/"  target="_blank">
  <img width="150" height="150" align="center" src="assets/victor_roris.jpg" alt="URL image" />
</a>

