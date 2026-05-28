---
weight: 1
params:
  bookFlatSection: true
---

# Controller

Controller and Gamepad input uses the [web standard canonical layout](https://www.w3.org/TR/gamepad/#remapping).
Axis input is not supported at this time. The following values are valid:

	RightBottom
	RightRight
	RightLeft
	RightTop
	FrontTopLeft
	FrontTopRight
	FrontBottomLeft
	FrontBottomRight
	CenterLeft
	CenterRight
	LeftStick
	RightStick
	LeftTop
	LeftBottom
	LeftLeft
	LeftRight
	CenterCenter

The config file uses these quoted values in a comma separated list.
The settings ui uses these value, not quoted, in a comma separated line.

