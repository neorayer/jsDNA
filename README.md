

# jsDNA/SkyDNA
A commercial front-end UI/UX framework/lib for SkyMiracle software products. 

It's developed and used in production environment between 2005 to 2007. It is quite dated in today technology.
But during the times of IE6, the years chrome hasn't been borned, jsDNA represented the most advanced UX technology.

### core

- SkyDNA is a library of javascript. 
- The arm is providing a set of effectual functions(Classes) to implove the speed of UI/UX development.
- SkyDNA includes many useful components on building richUI.
- SkyDNA_core.js is the core of SkyDNA javascript library, all other SkyDNA libraries depend on it.
- @requires prototype.js
 
### elements
- SkyDNA_Element.js provide a set of 'rich' HTML element class. 
- all other complex SkyDNA elements libraries depend on it.
- AND, SkyDNA_Element.js provide a special functions in SkyDNA.Enhance name space. 
- These functions can enhance the effect of a COMMON html element. etc, 'drag move', 'shadow', 'dock'..
- @requires prototype.js
- @requires SkyDNA_core.js
 
### data binding 
- SkyDNA_Element_DS.js extends SkyDNA_Element.js, and provides a set of dynamic rich element class. 
- The essence of SkyDNA_Element_DS is 'DataSource' and 'DataStruct'.


A typical DataStruct example:
 
	var DataStruct = { 
		id: {title: "ID", isKey: true},
		username: {title: "User Name", isKey: true, validate: VF_username},
		password: {title: "Password", ftype: "Password", validate: VF_passwd},
		status:	{title: "Status", ftype: "Hash", optionMap: {"0": "Open", "1": "CLOSE"}},
		description: {title: "Description"},
		remark: {title: "Special memo"},
		type: {title: "Type", ftype: "Hash", optionMap: {"0": "SuperAdmin", "1": "DomainAdmin"}},
		createtime: {title: "Create Time"},
		modifytime: {title: "Modify Time"}
	}


- @requires prototype.js
- @requires SkyDNA_core.js
- @requires SkyDNA_Element.jS
 
 
