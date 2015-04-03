---
title: OnClientApplicationMenuItemClicked
page_title: OnClientApplicationMenuItemClicked | UI for ASP.NET AJAX Documentation
description: OnClientApplicationMenuItemClicked
slug: ribbonbar/client-side-programming/events/onclientapplicationmenuitemclicked
tags: onclientapplicationmenuitemclicked
published: True
position: 17
---

# OnClientApplicationMenuItemClicked



## 

The __OnClientApplicationMenuItemClicked__ client-side event occurs after an ApplicationMenu items is clicked.

The event handler receives two parameters:

1. The instance of the ribbonbar firing the event.

1. An eventArgs parameter containing the following methods:

* __get_applicationMenu()__ returns a reference to the ribbonbar application menu.

* __get_item()__ returns a reference to the clicked application menu item.

* __get_domEvent()__ returns the DOM event object.

# See Also

 * [Overview]({%slug ribbonbar/client-side-programming/overview%})

 * [Application Menu]({%slug ribbonbar/radribbonbar-items/application-menu%})

 * [Overview]({%slug ribbonbar/client-side-programming/events/overview%})