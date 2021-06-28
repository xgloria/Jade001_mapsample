# Project Kleutghen Jade001 Mapping Documentation

## Documents: 
**Code:** Jade001.ipnb

**Image Folder:** Jade001_Images

**Output file:** Jade001_SampleMap.html

**Webpage Styling:** _config.yml

**Web Content:** index.md

**Gemfile:** Prepared for possible further use on other web platforms.

### Notice
#### 1. The code is written in python. 
The [Folium](https://python-visualization.github.io/folium/) library in python provides a translational ability to write the leaflet.js from Javascript to Python.

Python Tutorial [Melanie Walsh's textbook](bookhttps://melaniewalsh.github.io/Intro-Cultural-Analytics/Python/Installation.html)

Step by step documentation is embedded in the markdown of the python code. Besides the minimap and mouse position, the visualization consists of a vector layer(written in in [5]) and location markers.

The **size deflator** def open_resize allows you to resize the images down to any size you want, so that the images fits the popup. 

The **Hetian marker** In [9]- In [11] provides a basic example of inserting one image (Tianshannanlu_6_Hetian.jpg) to the popup of the marker. 

The **Xinjiang marker** In [6] - In [8] provides the example of inserting four images with basic introduction to a popup.

Other markers from In[13] - In[16] provide examples of **bolded** plain text content. 

#### 2. The supplement images are in .jpg form.

The .tiff file in the Box folder is too large to use. 

Also, please pay attention to the size of the .jpg file, especially the historical map from the Xiyutuzhi, after the size conversion. Using a deflator at 2.5 works in the individual Hetian marker, but not for the Xinjiang marker(four images). So consider resizing them down or download smaller images from the Harvard mirador link.

In order to manage the code with images easily, the images should better be put in the same folder as the code. Ideally, as the folder Jade001_Images. The resized images will be generated in the same image folder as well (e.g. Jade001_NPMT_bottom.jpgxx). 

*Pay attention to the route of the image document in the code*

>ppp2 = open_resize('Jade001_Images/Jade001_NPMT_bottom.jpg',3.5)

While **Jade001_NPMT_bottom.jpg** is the image file name, **Jade001_Images** is the folder that holds it.

* Store the code, image folders, and output html file in one package folder together. 


#### 3. Before we publish the map package online, create a github repository.
basic tutorials:
https://www.youtube.com/watch?v=BA_c3bGQXlQ
https://www.youtube.com/watch?v=LT3wU4XAzWI

-In the Github Pages-->Theme Chooser, choose your favourite theme. (This page is shown in [minimal](https://github.com/pages-themes/minimal).) Then, _config.yml, and index.md will appear in your repository.

_config.yml controls the left area of the minimal style website,

and index.md controls the content, which is the right area of the minimal style website. 
 
**After that, we can start to commit and push the package folder from our computer.**
 
Method:use RStudio and Git for desktop (& Github desktop works in the same mechanism).

follow this tutorial step by step: https://www.youtube.com/watch?v=liMd1L8KDpc

download link for RStudio:  https://rstudio.com/products/rstudio/download/

**On your local computer:**
 
In RStudio, create a new project, choose the third option **Git**.

Copy the github respository's html link and create a github pages folder on your local computer.

Then, replicate the *package folder* and put it in the folder for the new project (You can drag them in directly or use the command line). 

In the upper right window, choose Git. Thenk click on the small boxes for all the files you've just added.

Click the commit button, add the commit message, and click the commit button.

Finally, push all the files to your github repository.

-------
 
When you find the folders in the github repository, open the index.md file. 
put the html file name in the iframe src, set the height and width as demanded. 
><iframe src="Jade001_SampleMap.html" height="500" width="600"></iframe>
 
 
go to the Settings of the Repository

roll down to Github Pages->Source->in Branch, select main branch(this may change upon need) "main/roots", and the link for the Github pages will appear on the screen. 
 
**Further notices**

In -_config.yml, you can put theme, title, description, logo, etc. in. You can even insert a map there(idk why to do so, but you see, it’s quite versatile...) And for the logo, pay attention to it route.
