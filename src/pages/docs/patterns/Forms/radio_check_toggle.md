---
title: "Checkbox, Radio button, Toggle"
description: "Checkbox, Radio button, Toggle patterns description"
layout: "guide"
weight: 2
---

# Checkbox

## Definition
TODO Textfield is 

## Usage

* Checkboxes should be used when more than one option can be selected.
* Better if they are stacked
* Mutually inclusive options
* Use it for a single binary option as unique entry
* Note that although we have visually defined the checkbox, we use the native checkbox as it is easier to identify by the end user using different web browsers.

### States

**Default**

![checkbox default state](../../../images/checkbox.png)

**Active**

![checkbox active state](../../../images/checkboxSelected.png)

**Disable**

![checkbox disable state](../../../images/checkboxDisabled.png)

# Radio button

## Definition
TODO Textfield is 

## Usage

* As a general rule of thumb, radio buttons should be used when there’s a range of options and only one option can be chosen.
* Better if they are stacked.
* Do not use for a single binary option.
* Note that although we have visually defined the radio button, we use the native radio button as it is easier to identify by the end user using different web browsers.


### States

**Default**

![radio button default state](../../../images/radiobuttonOff.png)

**Active**

![radio button active state](../../../images/radiobuttonOn.png)

**Disable**

![radio button disable state](../../../images/radiobuttonDisabled.png)

### Radio vs Dropdown Menu

It is a common case of doubt when to use radios or a dropdown menu instead when users need to choose one item out of a list of options. There is not a fixed rule for that but we propose this guidelines.

Radio buttons: 

* When the number of options is small
* When options need a long label to explain the differences of each option. 
* Radio buttons are always listed vertically. 

Dropdown menus: 

* When the number of options is large, or has the potential to become large. 
* Options should be of the same nature (e.g. a list of branches, or a list of people).



# Toggle

## Definition
A toogle is an interface element that by its activation or deactivation provokes a inmediate action in the screen.

## Usage

* Use a toggle to present the user mutually exclusive options that have an action that is possible to perceive inmediately.

**Use doubt cases**

* Use a radio button or drop down rather than an on/off switch if the two states in question are separate options.

* In confirmation messages use always a checkbox instead of a toggle as it is a single  binary option.

### States

**Default**

![switch default state](../../../images/switchOff.png)

**Active**

![switch active state](../../../images/switchOn.png)

**Disable**

![switch disable state](../../../images/switchDisabled.png)

