---
title: InputControlDesign type
description: Learn about the InputControlDesign type, which includes the alignItems, alignSelf, bindings, border, color, flexFlow, and other properties.
author: jasongre
ms.author: jasongre
ms.topic: how-to
ms.date: 12/31/2024
ms.reviewer: johnmichalak
ms.search.region: Global
ms.custom: 
  - bap-template
---

# InputControlDesign type

[!include [banner](../../../../includes/banner.md)]
[!include [mobile app deprecated](../../../../includes/mobile-app-deprecation-banner.md)]

Input control design.

### Hierarchy

[Design](view-model-ipage-idesign.md) <br>&nbsp;&nbsp;&nbsp;└─ InputControlDesign <br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└─ [FieldDesign](view-model-control-field-ifield-ifielddesign.md) <br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└─ [LookupDesign](view-model-control-lookup-ilookup-ilookupdesign.md) <br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└─ [MultiLookupDesign](view-model-control-lookup-imultilookup-imultilookupdesign.md) <br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└─ [ValueDesign](view-model-control-value-ivalue-ivaluedesign.md) <br>

## Index

### Properties

* [alignItems](view-model-control-basecontrol-iinputcontrol-iinputcontroldesign.md#alignitems)
* [alignSelf](view-model-control-basecontrol-iinputcontrol-iinputcontroldesign.md#alignself)
* [bindings](view-model-control-basecontrol-iinputcontrol-iinputcontroldesign.md#bindings)
* [border](view-model-control-basecontrol-iinputcontrol-iinputcontroldesign.md#border)
* [color](view-model-control-basecontrol-iinputcontrol-iinputcontroldesign.md#color)
* [flexFlow](view-model-control-basecontrol-iinputcontrol-iinputcontroldesign.md#flexflow)
* [flexSize](view-model-control-basecontrol-iinputcontrol-iinputcontroldesign.md#flexsize)
* [fontSize](view-model-control-basecontrol-iinputcontrol-iinputcontroldesign.md#fontsize)
* [fontWeight](view-model-control-basecontrol-iinputcontrol-iinputcontroldesign.md#fontweight)
* [justifyItems](view-model-control-basecontrol-iinputcontrol-iinputcontroldesign.md#justifyitems)
* [label](view-model-control-basecontrol-iinputcontrol-iinputcontroldesign.md#label)
* [labelPosition](view-model-control-basecontrol-iinputcontrol-iinputcontroldesign.md#labelposition)
* [name](view-model-control-basecontrol-iinputcontrol-iinputcontroldesign.md#name)
* [padding](view-model-control-basecontrol-iinputcontrol-iinputcontroldesign.md#padding)
* [type](view-model-control-basecontrol-iinputcontrol-iinputcontroldesign.md#type)

## Properties

### alignItems

alignItems: string (optional) 

This property is an alias for the CSS property "align-items".
Please refer to [this web page](https://css-tricks.com/snippets/css/a-guide-to-flexbox) for documentation on the "align-items" property.

> Inherited from [Design](view-model-ipage-idesign.md).[alignItems](view-model-ipage-idesign.md#alignitems)


### alignSelf

alignSelf: string (optional) 



> Inherited from [Design](view-model-ipage-idesign.md).[alignSelf](view-model-ipage-idesign.md#alignself)


### bindings

bindings: any (optional) 



> Inherited from [Design](view-model-ipage-idesign.md).[bindings](view-model-ipage-idesign.md#bindings)


### border

border: "none" &#124; "solid" &#124; "left" &#124; "right" &#124; "top" &#124; "bottom" (optional) 

The border behavior of a control. This property will not be inherited by the children.

> Inherited from [Design](view-model-ipage-idesign.md).[border](view-model-ipage-idesign.md#border)


### color

color: string (optional) 

The foreground color of the container.
This will modify the color of all headers, items, labels, and icons within the container.<br>
Consider setting the background color at the same time as necessary when setting this attribute.<br>
Note: if color is set to "theme", the theme color of the app will be used.<br>
The following colors are available: <br>
![sample image.](../../../media/colors.PNG)

> Inherited from [Design](view-model-ipage-idesign.md).[color](view-model-ipage-idesign.md#color)


### flexFlow

flexFlow: string (optional) 

Specifying this property makes the component a flex container component.
This property is an alias for the CSS property "flex-flow".
Please refer to [this web page](https://css-tricks.com/snippets/css/a-guide-to-flexbox) for documentation on the "flex-flow" property.

> Inherited from [Design](view-model-ipage-idesign.md).[flexFlow](view-model-ipage-idesign.md#flexflow)


### flexSize

flexSize: string (optional) 

One number or two numbers written as a string. For example, "(size to grow) [(size-to-shrink)]" to accommodate available space in the immediate flex container.
This property is an alias for the CSS property "flex". Please refer to
[this web page](https://css-tricks.com/snippets/css/a-guide-to-flexbox) for documentation on the "flex" property.

> Inherited from [Design](view-model-ipage-idesign.md).[flexSize](view-model-ipage-idesign.md#flexsize)


### fontSize

fontSize: "medium" &#124; "xx-small" &#124; "x-small" &#124; "small" &#124; "large" &#124; "x-large" &#124; "xx-large" (optional) 

The proportional text size

> Inherited from [Design](view-model-ipage-idesign.md).[fontSize](view-model-ipage-idesign.md#fontsize)


### fontWeight

fontWeight: "normal" &#124; "bold" (optional) 

Normal or bold text.

> Inherited from [Design](view-model-ipage-idesign.md).[fontWeight](view-model-ipage-idesign.md#fontweight)


### justifyItems

justifyItems: "flex-start" &#124; "flex-end" &#124; "center" &#124; "space-between" (optional) 

This property is an alias for the CSS property "justify-content".
Please refer to [this web page](https://css-tricks.com/snippets/css/a-guide-to-flexbox) for documentation on the "justify-content" property.

> Inherited from [Design](view-model-ipage-idesign.md).[justifyItems](view-model-ipage-idesign.md#justifyitems)


### label

label: string (optional) 



> Inherited from [Design](view-model-ipage-idesign.md).[label](view-model-ipage-idesign.md#label)


### labelPosition

labelPosition: "stacked" &#124; "hidden" &#124; "inline" (optional) 

Determines how a label is positioned, if at all. By default, labelPosition is set to stacked.

> Inherited from [Design](view-model-ipage-idesign.md).[labelPosition](view-model-ipage-idesign.md#labelposition)


### name

name: string (optional) 



> Inherited from [Design](view-model-ipage-idesign.md).[name](view-model-ipage-idesign.md#name)


### padding

padding: "none" &#124; "small" &#124; "std" (optional) 

Allows specifying the component's padding behavior.
A component will inherit the padding behavior specified by its parent container components.

> Inherited from [Design](view-model-ipage-idesign.md).[padding](view-model-ipage-idesign.md#padding)


### type

type: [ControlType](../modules/view-model-control-basecontrol-icontrol.md#controltype) (optional) 

The type of the control as a string.

> Inherited from [Design](view-model-ipage-idesign.md).[type](view-model-ipage-idesign.md#type)




[!INCLUDE[footer-include](../../../../../../includes/footer-banner.md)]
