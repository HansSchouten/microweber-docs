##mw.modal

mw.modal - creates a modal window

##Summary

mw.modal(options); Parameters
```
mw.modal({
    content:   Required: String or Node Element or jquery Object
    width:     Optional: ex: 400, default 600
    height:    Optional: ex: 400, default 500
    overlay:   Optional: Boolean, default false
    title:     Optional: String for the title of the modal
    template:  Optional: String, default skins are "default", "simple", "basic"  
    id:        Optional: String: set this to protect from multiple instances
});
```
 
 
##Use modal
```
var modal = mw.modal({content: "test"})
$(modal.container).html("Some content")
modal.container.innerHTML = "some container"
modal.remove()
modal.hide()
modal.show()
``` 
 
 
##Remove modal
```
mw.tools.modal.get(this).remove()
```




