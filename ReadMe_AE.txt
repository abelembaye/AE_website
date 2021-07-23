
- The "config/_default/menus.yaml" determines which folders will be in the navigation pane at the top
e.g., name: Bio  #the name in the navigation pane
      url: '#about' 
   The url is the page you get when you click the Bio; now if '#about' the link to the page is in the content/home/about.md 
   folder and it will be displayed on the first page of the homepage. But, if under the url: we put "about", then the link 
  is taken from content/about. Unfortunately,
   there is no folder "about" immediately under content; so the page wont be displayed when we click bio

- note that all url call with # will be displayed in the first page; if you want them to be in a separate page use 'about/'
      
- The files in "home" folder when their yaml is set to 'active: true' are the files that gives us the items in navigation pane--
 however it is the title: 'title name' in these files and not the file name that determines what the name of the page will be. 