---
tagline: push-buttons
---

## `require'winapi.buttonclass'`

This module implements the `Button` class for creating buttons.

## Button

### Hierarchy

* [Object][winapi.object]
	* [VObject][winapi.vobject]
		* [BaseWindow][winapi.basewindowclass]
			* [Control][winapi.controlclass]
				* [BaseButton][winapi.basebuttonclass]
					* Button

### Initial fields and properties

<div class=small>

__NOTE:__ the table below `i` means initial field, `r` means read-only property,
`rw` means read-write property.

----------------------- -------- ----------------------------------------- -------------- ---------------------
__field/property__		__irw__	__description__									__default__		__reference__
text																								'&OK'
w											width													100
h											height												24
text_margin								applied when autosize == true					{20,5}
autosize																							false
text_margin
pushed
----------------------- -------- ----------------------------------------- -------------- ---------------------
</div>

### Events

<div class=small>
-------------------------------- -------------------------------------------- ----------------------
__event__								__description__										__reference__
----------------------- --------	-------------------------------------------- ---------------------
</div>