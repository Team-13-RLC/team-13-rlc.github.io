---
title: "Week starting 2020-11-16"
date: 2020-11-21
draft: false
---
Meetings happened 2020-11-17, 2020-11-19

## Discussed in the meeting(s):
* Reviewing code:
    * Canvas - Done (for now) and merged
        * Canvas uses the LibGDX OrthographicCamera
    * Lanes - Done and merged
        * Lane class written in a way to make it easier later to detect collisions with lanes.
    * AIBoat still being worked on.

    * Boat sprites can be rendered
    * The background scrolls (to make it look like flowing water)
    * The Camera follows the boat
    * There needs to be a finish line, which can detect the end of the race.
        * Done and merged

    * The game needs multiple legs
        * Implemented, as a MainLoop singleton class, which creates (and disposes of) a Canvas fr each leg.

## The plan:
* Programming:
    * Create various obstacle classes, and a way to spawn them
* Other:
    * Starting various write-up tasks:
        * Requirements
        * Architecture
        * Method selection and planning
        * Risk assessment and mitigation
