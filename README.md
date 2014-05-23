This is a demo of constraint-based layouts with [GSS](http://gridstylesheets.org/). As you size the window, the solver will attempt to solve all of the constraints defined in [structure.gss](structure.gss).

Required:

* Fill window with container, with 50px margin
* Fill entire container with photo (like css `cover`)

Preferred:

* Keep face within container
* Keep face in same position as original composition
* Don't scale image smaller than 75% of original

Todo:

* User-defined area of interest
* Hook into [noflo-ccv](https://github.com/noflo/noflo-ccv) to find binding rectangle of faces with any photo