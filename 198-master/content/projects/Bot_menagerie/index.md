+++
    #this is the "front matter" of the template of a project. It's the variables associated with the file
    #this portion is written in TOML (Tom's Obvious Minimal Language)
    
    title = "Bot Menagerie"
    #replace takes the filename and replaces all hyphens with spaces so that when it appears on your page, it's using spaces. The filename is used in the URL and URLs can't have spaces so use hyphen in the filename.
    #title converts to title-case (using capital letters for principal words only)
    
    date = 2019-05-29T16:52:12-07:00 #the date the file was created

    
    shortDescription = "AI that hides in other objects"
    projectVideo = ""
    #Project video is just the unique part of the URL  
    # For example, if the link is https://vimeo.com/285189099 then the unique part is  285189099
    projectVideoType = ""
    #Enter "youtube" or "vimeo". You can add other video types as well by editing single.html 
    projectImage = "project_3.JPG"

    itch = ""
    #Enter the filename only. For example, "metropolis_album.jpg" 
    #This image should be saved in the project folder with the name of your project 
    projectImageAltText = ""
    #Alt text is the text that gets read by screenreaders for accessibility (typically for the visually impaired) 

+++

This an artificial intelligence script that controls a simple diamond shaped object to convey a particular emotion: surprise. The rhombus is black to convey the ghostly qualities of this object along with the usage of black smoke effects when it vanishes and appears. The object hides in other objects and pounces on the player when they get within a certain range. Inspired by the mimics from Prey.

