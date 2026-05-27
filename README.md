# Jak 1: The JET-Board Legacy

This mod attempts to faithfully port the jetboard (from Jak 3) to Jak 1. In addition to all of the default jetboard behavior, there are also some completely new interactions with the different eco powers and things like launchers.

Ever since I decompiled the jetboard code for Jak II in 2022, making this mod has been a dream of mine and I've made numerous attempts since then, but our tooling capabilities for OpenGOAL were simply too lacking at the time (no custom actors, no animation import/export, no model import, etc.), so I put it on hold for a while. Over time, me and other OpenGOAL devs made various advancements towards this goal with custom actor support, custom animation import, etc., but the latest breakthrough came in April 2026 when I added support for exporting animations, which was the final missing piece of the puzzle.

It additionally serves as a proof of concept for some other new features that were created for this mod and will be added to vanilla OpenGOAL in the near future:

- Custom animations on existing character models (Jak, Daxter)
- Support for `align` bone in custom animations (used to modify an actor's velocity and rotation via animations, used extensively by Jak)
- Custom soundbanks

## TODOs

From a gameplay perspective, the mod should hopefully feel overall polished, but there's a couple of minor things I would still like to tackle in the future. Most notably, grinding is currently disabled on the initial release because the effort required for a faithful recreation of the system is currently a bit too high and I wanted to get this mod out a bit sooner so people can play around with it.

- [ ] Allow grinding
- [ ] Improve the models (Jak, Daxter, jetboard)
- [ ] Add a heat meter for the jetboard when used in Fire Canyon and Lava Tube
- [ ] Better position, scaling and rotation for the board when it's on Jak's back
- [ ] Better effects (improving some of the half-baked particle effects and adding the special "wave" effect on the timed double jump/when getting a boost)
