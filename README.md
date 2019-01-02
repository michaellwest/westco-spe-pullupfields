# Pull Up Fields for SPE

## Getting Started

* Ensure that Sitecore PowerShell Extensions 4.7 or later is installed.
* Install the Pull Up Fields package found in the repo.

## Using the Module

The module provides a context menu for manipulating the template fields.

### Context Menu

![image](https://user-images.githubusercontent.com/933163/40794268-47aa4fc4-64c4-11e8-952e-4b7c68cf20ed.png)

#### Pull Up Dialog

![image](https://user-images.githubusercontent.com/933163/40794327-7416126e-64c4-11e8-8de7-bbd35d64bdcd.png)

## Use Cases

### Move fields to a new template

Let's say you have a template called _Landing Page_ and would like to move a field to a new template called _Corporate Landing Page_. The new template will inherit from _Landing Page_. Following the wizard you would make these selections:

* Select the fields that no longer belong to the _Landing Page_ template. For example, you could have a **Corporate Tag Line** that should move up to a new template.
* Enter a new template name called _Corporate Landing Page_.
* Specify the parent location for the new template such as _Templates/User Defined_.

### Move fields into a base template

Let's say you have a template called _Corporate Landing Page_ and would like to move a field to another template called _Landing Page_. The template losing the field will inherit from _Landing Page_. Following the wizard you would make these selections:

* Select the fields that no longer belond to the _Corporate Landing Page_ template.
* Specify the existing base template such as _Templates/User Defined/Landing Page_.

## Credit

I found inspiration for this from Mike Reynolds. Check out his post [here](https://sitecorejunkie.com/2013/04/04/reuse-sitecore-data-template-fields-by-pulling-them-up-into-a-base-template/).