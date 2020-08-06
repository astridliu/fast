# Flyout

## Overview

Flyout is a floating container that shows over a pages content and displays UI related to what the user is doing. Similar to a Dialog, but not blocking (can be dismissed easily) and no specific action is required, a Flyout can be used to reveal a secondary control or show more detail about an item.

### Background

A Flyout can be less intrusive to the user experience than a Dialog and should be used instead of a Dialog when action is not required, such as in the case of an error, user agreement, or item purchase.
Having a Flyout will cover use cases for non-urgent/required information or actions, such as collection of additional info before an action, displaying information that is only relevant some of the time, or displaying more information.

### Use Cases

- As a Dropdown (TODO: get pic) for a menu, navigation bar, etc.
- As a context menu(???).
- As a popup showing additional info of an item on the page.
- To display a larger image of a thumbnail image in a photo gallery.
- 

### Non-goals

*A list of use cases, features, or functionality which are **not** goals for the component*
  
### Features

*A list of the key features unique to this component.*
- Start Section
- End Section
- Placement Logic
- Sizing Logic

### Risks and Challenges

*Notable risks or challenges associated with implementing the component. Would we need to make any breaking changes in order to achieve this component's goals?*

### Prior Art/Examples

- toast
- material ui?
- fluent ui?
- msoft docs

---

## Design

*Describe the design of the component, thinking through several perspectives:*

- *A customer using the component on a web page.*
- *A developer building an app with the component and interacting through HTML/CSS/JavaScript.*
- *A designer customizing the component.*

### API

*The key elements of the component's public API surface:*

- *Component Name*
- *Props/Attrs*
- *Methods*
- *Events*

*Consider high and low-level APIs. Attempt to design a powerful and extensible low-level API with a high-level API for developer/designer ergonomics and simplicity.*

### Anatomy and Appearance

*Screenshots and/or description of the basic appearance of the component. Outline its structure with a diagram of its visual tree (shadow dom). Enumerate key areas of visual customization, such as:*

- *Slot Names*
- *Host Classes*
- *Slotted Content/Slotted Classes*
- *CSS Parts*

---

## Implementation

*Important aspects of the planned implementation with careful consideration of web standards and integration.*

### States

*Key component states, valid state transitions, and how interactions trigger a state transition.*

### Accessibility

*Consider the accessibility of the component, including:*

- *Keyboard Navigation and Focus*
- *Form Input*
- *Use with Assistive Technology*
  - e.g. The implications shadow dom might have on how roles and attributes are presented to the AT. Components which delegate focus require all global aria-* attributes to be enumerated.

### Globalization

*Consider whether the component has any special globalization needs such as:*

- *Special RTL handling*
- *Swapping of internal icons/visuals*
- *Localization*

### Security

*Are there any security implications surrounding the component?*

### Performance

*Are there any performance pitfalls or challenges with implementing the component?*

### Test Plan

*What is the plan for testing the component, if different from the normal path?*

### Tooling

*Are there any special considerations for tooling? Will tooling changes need to be made? Is there a special way to light up this component in our tooling that would be compelling for developers/designers?*

### Documentation

*What additions or changes are needed for user documentation and demos? Are there any architectural/engineering docs we should create as well, perhaps due to some interesting technical challenge or design decisions related to this component?*

---

## Resources

*Any related resource links such as web standards, discussion threads, diagrams, etc.*
[Dialogs and Flyouts](https://docs.microsoft.com/en-us/windows/uwp/design/controls-and-patterns/dialogs-and-flyouts/#:~:text=A%20flyout%20is%20a%20lightweight%20contextual%20popup%20that,control%20or%20show%20more%20detail%20about%20an%20item.)

## Next Steps

*What next steps, if any, are there? Is there some functionality that would be a nice-to-have or a common feature in other implementations that could be added but is not considered part of the MVP?*
