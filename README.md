# flickrRandom
# May have bugs,vulnerabilities
Gets random image URLs from flickr  


First run InitFlickrRandom(subject, apikey, license <optional>);  
Use license to filter the images look up the number. https://www.flickr.com/services/api/flickr.photos.licenses.getInfo.html
  
Then you can create the event Listener for onFlickrImage  
window.addEventListener("onFlickrImage", function(event){  
alert([event.detail.url]);  
});  
  
  
Events have both detail.url and detail.credit