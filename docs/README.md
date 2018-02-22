# <Project Name> Project site

## Description

Provide support for runtime parameter value initializations upon user execution of parameterized elements.  

## Requirements

R.1 Launch configuration “Initializer dialog” shall be tree table based and include parameter children  
  R.1.1 The new initializer dialog shall support column data for all parameter type values  
  R.1.2 The new initializer dialog shall support editable column cells for all parameter types the are considered simple core values.  These are types of String, Boolean, Enumerator, Integer, Real.  UDTs that have core types of the aforementioned shall be editable.  
  R.1.3 The values shall be validated during entry.  Existing validation rules exist and shall be used.  
  R.1.4 The values shall be stored in the launch configuration and used on subsequent launches and edits.  
  R.1.5 Default values shall be used in the absence of any user configuration.  
R.2 The Execute Action shall be extended to present a table based dialog for configuring parameter values for the element to be launched.  
  R.2.1 All parameterized elements shall show the dialog and allow configuration as specified in R1.2 and R1.3.  
  R.2.2 No cancel shall be allowed, just Continue.  
  R.2.3 Default values shall be used in the absence of any user configuration.  
R.3  Values edited using support added for R.1 and R.2 shall be injected to Runtime Value instances prior to a launch.  
  R.3.1 The entire Runtime Value shall be created and configured before launch.  
R.4 All configured Runtime values from the support added in the preceding sections, R.1 - R.3, shall be injected into the runtime environment on launch.  
  R4.1 The Runtime Value instances shall be associated with the necessary Stack Frame(s).  
  R4.2 The Runtime Value instances shall be associated with the necessary Block data.  
  R4.3 The Runtime Value instances shall be associated with the necessary parameter instances, these can be one of the following: Function Parameter, Bridge Parameter, Signal Parameter, Interface Operation Parameter, and Operation Parameter.  
  

## Timeframe  

February 28th of 2018 

## Demonstration  

https://youtu.be/G-vg5m--i3s

## Pledging

The pledge goal is 12,000 USD.

### Pledge to this project
Send an e-mail to [FMAY](mailto:travis.london@gmail.com) to pledge.  

Pledge status:  

![progress](http://progressed.io/bar/0 "progress")
 
