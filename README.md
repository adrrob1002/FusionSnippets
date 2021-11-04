# FusionSnippets
A list of VSC Snippets for Elttob's Fusion

```lua
"Fusion Class": {
	"prefix": ["fusion-class", "fclass"],
	"body": [
		"local ${0:$TM_FILENAME_BASE} = {}",
		"${0:$TM_FILENAME_BASE}.__index = ${0:$TM_FILENAME_BASE}",
		"",
		"-- Fusion",
		"local Fusion = require(game:GetService(\"ReplicatedStorage\").Fusion)",
		"",
    "local New = Fusion.New",
		"local Children = Fusion.Children",
		"",
		"local State = Fusion.State",
		"local Computed = Fusion.Computed",
		"",
		"local OnEvent = Fusion.OnEvent",
		"",
		"local Spring = Fusion.Spring",
	  "",
		"-- Class",
		"function ${0:$TM_FILENAME_BASE}.new()",
		"\tlocal self = setmetatable({}, ${0:$TM_FILENAME_BASE})",
		"",
		"\tself.Component = New \"Frame\" {",
		"\t\t",
		"\t}",
		"\treturn self",
		"end",
		"",
		"",
		"function ${0:$TM_FILENAME_BASE}:Destroy()",
		"\t",
		"end",
		"",
		"",
		"return ${0:$TM_FILENAME_BASE}"
	]	
}
```
