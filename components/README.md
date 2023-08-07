![Image of Connected Factory Worker](/images/cfw_apps_255x115.png)

# Connected Factory Worker applications using the new PowerApps component feature for Canvas apps

This presents a set of custom controls built for Connected Factory Worker applications using the new PowerApps component feature for Canvas apps.
As a prerequisite, check out the following blog posts
* Yifie Wang’s Introducing Canvas components
* Mehdi Slaoui Andaloussi’s 10 Reusable Components: tab control, calendar, dialog box, map control and more
* Brian Dang’s Components: Start your Journey with Reusable Controls 
* Adam Toth’s PowerApps Design – Create a Digital Alarm Clock Display 

and docs
* Power Apps docs Create a component for canvas apps

-----------------

The Connected Factory Worker application is a set of application used by the factory operator addressing specific use cases to simplify their daily job to check, track and review standard operation using mobile device. 
 
![Image of Connected Factory Worker apps](../../images/Connected_Factory_Worker_application_overview.png)
 
The Connected Factory Worker Standard Components is a set of Power Apps Canvas components shared to the factor operators who can build now their specific standard operation app based on common UI pattern and Common Data Model exposed by the Common Data Services.

## CFW Home Screen
The Home Screen shares common UI pattern like application context (factory, service line center, line, machine center, user and date), operation navigation steps and system info (line and machine center). 

![Image of CFW Components Home Screen](../images/cfw_components_home_screen.png)

## CFW Map Tag to Line Layout image
To simplify factory operator’s navigation to find relevant tags (reported issues or non-adherence) within the factory, we introduced the concept of show factory layout image and map tags to the layout.
Two components are supporting the pattern to capture a position for a specify new tag and to view a list of tags linked using their relative position within the layout image.

View a list of tags linked using their relative position:

![Image of CFW Map Tag to Line Layout view](../images/cfw_components_map_position_view_screen.png)

Capture a position for a specify new tag linked to layout relative position:
 
![Image of CFW Map Tag to Line Layout map](../images/cfw_components_map_position_set_screen.png)

## CFW Header Control
Static control shows operators their factory context based on selected factory, service line center, line and machine center including visuals for line and machine center.

![Image of CFW Header Control](../images/cfw_components_header_control.png)

[Download package](https://teamrueggstorage.blob.core.windows.net/devops/CFWHeaderControl.zip)

Property | Description
------------ | ------------- 
Logo | Company logo image
AppName | Application name
SelectedFactory | Context factory name 
SeletcedSLC | Context service line center name
SelectedLine | Context line name
SelectedMachineCenter | Context machine center name
SelectedPackSize | Context pack size name
SelectedLineImage | Context layout image of the selected line
SelectedMachineCenterImage | Context image of the selected machine center
Color | Accent header background color
UserImage | Logged in user image (ex. User().Image)
UserName | Logged in username (ex. User().FullName)
UserAccount | Logged in user account name / email (ex. User().Email)

## CFW Nav Step Control
Simplified menu control reduced to show process step (screens) within the application context.

![Image of CFW Nav Step Control](../images/cfw_components_nav_step_control.png)

[Download package](https://teamrueggstorage.blob.core.windows.net/devops/CFWNavStepControl.zip)

Property | Description
------------ | ------------- 
Logo | Company logo image
AppName | Application name


## CFW Sys Info Control

![Image of CFW Sys Info Control](../images/cfw_components_sysinfo_control.png)

Property | Description
------------ | ------------- 
Logo | Company logo image
AppName | Application name

## CFW Map Position Set Control

![Image of CFW Map Position Set Control](../images/cfw_components_map_position_set_control.png)

Property | Description
------------ | ------------- 
SetX | Starting X coordinate (can be empty for new tag)
SetY | Starting Y coordinate (can be empty for new tag)
	

## CFW Map Position View Control

![Image of CFW Map Position View Control](../images/cfw_components_map_position_view_control.png)

Property | Description
------------ | ------------- 
Logo | Company logo image
AppName | Application name

[Download package](https://teamrueggstorage.blob.core.windows.net/devops/CFWMapPositionControls.zip)

## CFW Daily Tear Off Control

![Image of CFW Daily Tear Off Control](../images/cfw_components_daily_tear_off_control.png)

Property | Description
------------ | ------------- 
Logo | Company logo image
AppName | Application name



Give it a try !  We would love to hear your feedback. We have more open-source components on the PowerApps Tools github repository

* https://powerapps.microsoft.com/blog/components-available-in-preview/
* https://powerapps.microsoft.com/de-de/blog/components-available-in-preview/ 
* https://powerapps.microsoft.com/blog/components-start-your-journey-with-reusable-controls/


