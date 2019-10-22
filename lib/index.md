# API
## Matiral app
  The MaterialApp configures the top-level Navigator to search for routes in the following order:
    For the / route, the home property, if non-null, is used.
    Otherwise, the routes table is used, if it has an entry for the route.
    Otherwise, onGenerateRoute is called, if provided. It should return a non-null value for any valid route not handled by home and routes.
    Finally if all else fails onUnknownRoute is called.
## Tween
  A linear interpolation between a beginning and ending value.
  
## AnimatedWidger
 Flutter has a set of widgets extending AnimatedWidget that rebuild themselves when the value of the animation changes.
 
## Curve 
 Flutter provides a selection of easing curves that adjust the rate of the animation over time. The Curves class provides a predefined set of commonly used curves. For example, Curves.easeOut will make the animation start quickly and end slowly.

## chain 
  To combine the tweens, use chain():