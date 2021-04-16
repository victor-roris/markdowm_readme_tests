# Internal Markdowm Readme Tests

## Image tests

### Relative image 

 - Plain markdown 
 
   * Root asset
   
The filepath as it were the relative to the root of the project
```markdown
![relative image](assets/victor_roris.jpg "Image title")
```
![relative image](assets/victor_roris.jpg "Image title")


The absolute filepath as it were the root of the project
```markdown
![relative image](/assets/victor_roris.jpg "Image title")
```
![relative image](/assets/victor_roris.jpg "Image title")


The relative filepath as it were the root of the project
```markdown
![relative image](../../assets/victor_roris.jpg "Image title")
```
![relative image](../../assets/victor_roris.jpg "Image title")

   * Relative asset

The filepath start in the root of the project
```markdown
![relative image](/src/internal_module/assets/victor_roris.jpeg "Image title")
```
![relative image](/src/internal_module/assets/victor_roris.jpeg "Image title")


The filepath is relative to the current folder
```markdown
![relative image](./assets/victor_roris.jpeg "Image title")
```
![relative image](./assets/victor_roris.jpeg "Image title")


 - HTML
 
   * Root asset
 
The filepath as it were the relative to the root of the project
 ```markdown
 <img width="150" height="150" src="assets/victor_roris.jpg"
     alt="URL image" />
 ```

 <img width="150" height="150" src="assets/victor_roris.jpg"
     alt="URL image" />
     

The absolute filepath as it were the root of the project
```markdown
 <img width="150" height="150" src="/assets/victor_roris.jpg"
     alt="URL image" />
```
 <img width="150" height="150" src="/assets/victor_roris.jpg"
     alt="URL image" />


The relative filepath as it were the root of the project
```markdown
<img width="150" height="150" src="../../assets/victor_roris.jpg"
     alt="URL image" />
```
<img width="150" height="150" src="../../assets/victor_roris.jpg"
     alt="URL image" />


   * Relative asset

The filepath start in the root of the project
```markdown
<img width="150" height="150" src="/src/internal_module/assets/victor_roris.jpeg"
     alt="URL image" />
```
<img width="150" height="150" src="/src/internal_module/assets/victor_roris.jpeg"
     alt="URL image" />


The filepath is relative to the current folder
```markdown
<img width="150" height="150" src="./assets/victor_roris.jpeg"
     alt="URL image" />
```
<img width="150" height="150" src="./assets/victor_roris.jpeg"
     alt="URL image" />