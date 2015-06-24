
**Install customfont and its dependecy.**

http://fontcustom.com/

**on terminal**
 
    brew install fontforge --with-python
    brew install eot-utils
    gem install fontcustom

Clone this project

You can alter icon from icons.ai
export it to font/svg folder
font/svg folder contain three files

	index.htmml
	data.json
	iconstyle.css
	
leave them as it is

On terminal go to folder font/

	$cd font
	$fontcustom compile svg -t index.html data.json iconstyle.css -n "iconfont"


now your icon font is created at font/fontcustom