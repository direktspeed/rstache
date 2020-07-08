# Rstache
Rstache is a ECMAScript library for building Reactive HTML based user interfaces that work on any Device or Browser.

Rstache is drived from can-stache and is 100% Compatible to the DoneJS and CanJS Frameworks while it maintance his own Opinions on How to Develop Applications.
It is a Drop in Replacement of React while it Keeps Compatibility to Incremental Adopt it or Interop with it. This makes Rstache simply the better react framework.
It solves many common react component lifecycle hooks and other react bugs by providing a statemanagment system that is fully automated. 

# What it Solves?
- It replaces JSX and all it's problems and also solves the raw-html Issues.
- It is a newer Fresher DoneJS that keeps feature parity while it is more up to date.
- It replaces next.js react framework via it's own dev and production server.
- It massiv reduces code complexity and code needed to write while avoiding most common React Component bugs.
- It has a Automated Lifecycle Managment that saves you tons of code.
- Adds new and Legacy Features to the Current CanJS Framework via its ecosystem. So it is ideal for all those of you who want to use can-component and stuff like can-component, can-react-component.
- new build philosophie for DoneJS via Rollup droped Steal as it was designed Befor the es6 standard arrived we now Code es6+ and use rollup to transpil to SystemJs only if needed. While Steal would transpil everything to es5 always.

## Contributing Guide
As This is based on the canjs/ecosystem.mjs build it would be nice if we could land as much contribution directly in the bitovi or canjs projects.
but we are able to transform rewrite if needed to do not get blocked by that dependency we are ready to hardfork if needed.

The main Part here is the build.js file which uses our rollup tool chain to Create the rstache dist files that get published to npm 

## DIREKTSPEED Internal Info
Out of the Stealify Project we decided to do React related Marketing for the Project via Rstache which is a distribution of Stealify Cross Platform UI Research.
While Stealify UI Research comes to the Conclusion that SSR is best done via Rust and ActiX Rstache offers still the best Solution for NodeJS and Deno and GraalJS which Replaces RINO in the Java World there exists also VertX a GraalJS Class Factory. Also the DoneJS Project drives into a wrong direction via making Essential stuff Legacy or Deprecated as they view it from a diffrent perspective then we do. In Our Opinion this is the successor to DoneJS which was a inspiring Project for the last decade of Years!

### The Other Players
We Can work in all the Scenarios and even open our own 
- DoneJS serves via StealJS render function that returns html
- next.js serves via webpack React Components which are render functions that return a react component
- harp serveres via filestructure based pre compiler tool chain diffrent formarts it is its own bundler
- deno serves using parcel 
- open-webcomponents serves via dev-es6-server pre compiler tool chain
- rollup+serve can be maybe invented
