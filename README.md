# snailpics
image hosting site im building as a java learning experience

Features:

  Ability to upload image.
  
  Able to view all uploaded images.
  
Design:

  Start
  
    button to upload image.
    
    Entire start page accept drop to upload.
    
    Link to gallery
    
  Gallery
  
    thumbnails of images in the gallery. pagination of ex 25 images per page.
    
    image is a link that leads to its own page.
    
  image
  
    the full image in the center.
    
  Database
  
    Mysql/Mongo
    
      stores images with:
      
        index
        
        url
        
        ip from uploader
        
        date of upload
        
  REST
  
    jersey
    
      GET images from the DB.
      
      PUSH add images to the DB.

Security:

Safe search https://cloud.google.com/vision/

upload captcha https://developers.google.com/recaptcha/

resource for connecting to db:

http://hnusfialovej.cz/2015/01/30/upload-file-to-mongodb-using-jersey-2/

setup mvn

mvn archetype:generate -DarchetypeArtifactId=jersey-quickstart-grizzly2 -DarchetypeGroupId=org.glassfish.jersey.archetypes -DinteractiveMode=false -DgroupId=com.example -DartifactId=simple-service -Dpackage=com.example -DarchetypeVersion=2.26

https://jersey.github.io/documentation/latest/getting-started.html

Check out thenewboston on youtube!
