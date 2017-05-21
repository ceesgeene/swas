# swas
An abstract sass framework.

## Considerations

* Ensure good DX
* Provide clear code structure
* Embrace BEM
* Prevent duplicate code
* Allow to reuse/share code over projects
* Embrace other existing well-established and/or popular libraries, standards and practices

## Design basics

When looking closely, you'll see that the design of almost every (modern, responsive) website or -application consists of the, more or less consistent and coherent, usage of the following basics:

* breakpoints
* rhythm
* colors
* typography
* layout
* icons
* spacing

## Design terminology

* Lanes
* Partials
* Lanesets

### Lane

Every area of a design covering the entire width of the viewport and ... is called a lane.

 * The width of a lane always equals 100vw
 * Lanes can be nested
 * Every design contains at least one lane
 
### Partial

A component that is placed into one or more designated regions of lanes is called a partial.

 * A partial is fluid
 * A partial can have a minimum and/or a maximum width (grid columns)
 
## Laneset

An area containing a set of adjoining lanes is called a laneset.

 * A laneset can control how the lanes visually adjoin/overlap/collapse.

# Structure

```
abstracts/
blocks/
config/
```
