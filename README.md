# Step 1
- ## If you want to store images in the repository :
  - Upload the image to the repository (You can use your current project's repository or create a new public repository for storing the image). 
  - Click on the uploaded image, press the three dots in the right corner, and choose the "Copy permalink" option. In this way, you can access the image whenever you want.

- ## If you don't want to store images :
  - Enter the README.MD edit page. Then upload your image by drag and drop. 
  - Right after the image is uploaded, you will see a URL. Copy the URL.

# Step 2 (common) :
*Fill the code and paste it to the "README.md" ;*
```
<a href="URL that you want to be redirected to when clicked (optional)" >
   <img  src="URL of your image uploaded to GitHub" width="130" height="30"> 
</a>
```
- Remove width and height sections for the original image size. <br>
- Remove href section for the redirect to the image's full-size view. <br>
- Replace ```<a> </a>``` sections with ```<picture> </picture>``` for make the image non-clickable.
- Add ```<div align="center">``` before ```<a>```, ```</div>``` after ```</a>``` for make the image centered.

# Examples :

*Non-clickable :*                                                    
<picture> > <img src="https://github.com/ccemerdem/badges/blob/d7206826c5580e8c94ef94887d7058b49892fc64/v1.3.png" width="130" height="30" > </picture>
```
<picture> 
   <img src="https://github.com/ccemerdem/badges/blob/d7208268987d70892fc64/v1.2.png" width="130" height="30" >
</picture>
```
*Clickable (redirects to a custom link) :*                     
<a href="https://github.com" >
    <img  src="https://github.com/ccemerdem/badges/blob/d7206826c5580e8c94ef94887d7058b49892fc64/v1.3.png" width="130" height="30" > </a>
```
<a href="https://github.com" >
   <img src="https://github.com/ccemerdem/badges/blob/d7208268987d70892fc64/v1.2.png" width="130" height="30" >
</a>
```
*Clickable (redirects to the image's full size)  :*            
<a>
    <img src="https://github.com/ccemerdem/badges/blob/d7206826c5580e8c94ef94887d7058b49892fc64/v1.3.png" width="130" height="30" > </a>
```
<a>
   <img src="https://github.com/ccemerdem/badges/blob/d7208268987d70892fc64/v1.2.png" width="130" height="30" >
</a>
```







# Reference Images :

<a  href="https://codescene.com/" >
    <img  src="https://github.com/ccemerdem/badges/blob/d7206826c5580e8c94ef94887d7058b49892fc64/v1.1.png"width="399" height="92" > </a>

<a  href="https://codescene.com/" >
    <img  src="https://github.com/ccemerdem/badges/blob/d7206826c5580e8c94ef94887d7058b49892fc64/v2.1.png"width="399" height="92" > </a><br>   

<a  href="https://codescene.com/" >
    <img  src="https://github.com/ccemerdem/badges/blob/d7206826c5580e8c94ef94887d7058b49892fc64/v1.2.png" width="130" height="30" > </a>

<a  href="https://codescene.com/" >
    <img  src="https://github.com/ccemerdem/badges/blob/d7206826c5580e8c94ef94887d7058b49892fc64/v1.3.png" width="130" height="30" > </a>

<a  href="https://codescene.com/" >
    <img  src="https://github.com/ccemerdem/badges/blob/d7206826c5580e8c94ef94887d7058b49892fc64/v1.4.png" width="130" height="30" > </a>

<a  href="https://codescene.com/" >
    <img  src="https://github.com/ccemerdem/badges/blob/d7206826c5580e8c94ef94887d7058b49892fc64/v2.2.png " width="130" height="30" > </a>

<a  href="https://codescene.com/" >
    <img  src="https://github.com/ccemerdem/badges/blob/d7206826c5580e8c94ef94887d7058b49892fc64/v2.3.png " width="130" height="30" > </a>

<a  href="https://codescene.com/" >
    <img  src="https://github.com/ccemerdem/badges/blob/d7206826c5580e8c94ef94887d7058b49892fc64/v2.4.png " width="130" height="30" > </a> 

