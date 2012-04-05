RobotStarlingLegs
=================

This is purely a simple plugin for Robotlegs 1.5x to help your projects handle both regulardisplay list projects
as well as starling display list projects. I personally have regular display list items in my starling projects
(menu screens etc) and if I am using Robotlegs I want to be able to have mediators for both my regular and
starling view components.

To use just swap out your mediatorMap and viewMaps in your application context:

            this.mediatorMap = new RobotMediatorMap(this.contextView, starling.stage, this.injector, this.reflector);
            this.viewMap = new RobotViewMap(this.contextView, starling.stage, this.injector);

Of course as you are referencing starling.stage here you will need to instantiate starling before this is done.