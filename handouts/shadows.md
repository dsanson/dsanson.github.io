---
author:
  - name: David Sanson
    affiliation: 
      - name: Illinois State University
course: Philosophy Club
date:  2018-04-17
title: Notes on Shadows 
bibliography: "bib.yml"
filters:
  - ../pandoc-labeled-lists.lua
  - diagram
nocite: |
  @aranyosi2010a, @westphal2011a, @sorensen2006a, @sorensen2008a, @lewis1970a, @tours1995a
format:
  html: default
  # pdf:
  #   pdf-engine: lualatex
  #   font-size: 10pt
  #   mainfont: Minion Pro
  #   sansfont: Myriad Pro
  #   mainfontfallback: 
  #     - "Linux Libertine:"
  #     - "Gentium:"
  #   sansfontfallback:
  #     - "Arial:"
  #   papersize: letter
  #   geometry: margin=1in
  #   italicquotes: true
  #   pdfstandard: 
  #     - ua-2
  #     - a-4f
---

Shadows and Materialism
=======================

*Materialism* is the view that there are only material things. Here is
an argument against materialism:

@p1.  There are shadows.
@p2.  Shadows are not material things.
@c.   Therefore, not all things are material.

What to make of this argument?

## Premise (@p1): Why Think There Are Shadows?

Maybe you want to deny (@p1). You might argue that 

@.  A shadow is not a *positive* thing; it is the absence of a positive 
    thing, namely, light. 

But (@p1) does not say that shadows are positive things; it just says that there
are shadows. (Other putative examples of *negative* things: holes, ugliness,
evil.) Here are some reasons for thinking there are shadows:

@.  We can see shadows, and you can't see things that don't exist.
@.  We can feel shadows, and you can't feel things that don't exist.
@.  Shadows are located in specific places ("the shadows were over the deep"),
    and things that don't exist aren't located anywhere.

## Premise (@p2): Why Think Shadows Are Not Material Things?

Here is an argument for (@p2):

@.  A material thing has to be made of something (its matter).
@.  A shadow is not made of light: its presence requires the *absence*
    of light.
@.  A shadow is not made of any other kind of matter.
@.  So shadows are not material things. 

## Are Shadows Dependent Things?

Even if shadows are not material things, it seems that in some sense they
*depend* on material things (think of the way that a hole depends on its host). But it is not quite right to say that a shadow
depends for its existence on the object that casts it and on the object upon
which it is cast. Light takes time to travel, so a shadow can outlast the
object that casts it. (Can it also exist before the object upon which it is
cast? What if it is being cast through fog or dust?)

## Where are Shadows?

Options:

@.  The shadow is on the surface of the object upon which it is cast.
@.  The shadow is on the surface of the dark side of the object that casts it.
@.  The shadow is the entire three-dimensional region of darkness that extends
    between the object that casts it and the surface upon which it is cast.


The Eclipse Riddle
==================

It is not immediately obvious what this puzzle has to do with shadows.
Instead, it seems to be about what you see when you
see a backlit object. It is due to @sorensen2008a.

``` tikz
\begin{tikzpicture}[scale=1]
\draw (-5,0) circle (1);
\node (sun) at (-5,0) {Sun};
\draw (-2,0) circle (.7);
\node (far) at (-2,0) {Far};
\draw (1,0) circle (.4);
\node (near) at (1,0) {Near};
\draw (-5,1) -- (5,0);
\draw (-5,-1) -- (5,0);
\node (eye) at (5.5,0) {Me};
\end{tikzpicture}
```

What do I see? Some suggestions:

@.  I don't see Far, because Near is in the way.
@.  I don't see Near, because Near does nothing to causally affect the light that reaches my
eye.
@.  I don't see Far, since, if Far were removed, everything would look the same to me.
@.  I don't see Near, since, if Near were removed, everything would look the same to me.

Causal Theory of Perception
:   When you see something, what you see is the thing that causally affects the light
    that reaches your eye.

An argument:

@.  The only thing that causally affects the light that reaches my eye is the far surface of Far.
@.  So, I see the far surface of Far.

This generalizes to all backlit objects: when you see a front-lit object, you
see the surface near to you; but when you see a backlit object, you see the
surface far from you. This is the view defended by
@sorensen2008a: he calls the far surface of a backlit object its "silhouette." 

@westphal2011a suggests instead that 

@.   What I see is *the shadow* cast by Far.

Ordinarily, when you see a shadow cast by an object, you see it on the surface
of some other object. But in this case, he says, you are seeing the shadow "end on".
He agrees with Sorenson that the far side of Far is the thing that causally affects the light
that reaches your eye. So he agrees that it is what *casts*
the shadow. But he argues that what you see is not the cause of the shadow,
but the shadow itself. (He also suggests that it is the shadow that
is properly called the "silhouette", not the far surface of the backlit object.)

Is this consistent with the Causal Theory of Perception?

Moving Shadows and Spinning Shadows
===================================

Shadows can move and change shape. As the sun crosses the sky, the shadow cast
by a flagpole moves across the lawn. As a cloud crosses the sun, the shadow it
casts moves along the ground. As a pinwheel spins, the shadow it casts on the
ground spins. Imagine a disc that casts a circular shadow. When the disc
rotates, does the shadow rotate too?

The Yale Shadow Puzzle
======================

This is so-called because it was the topic of lunchtime conversations within
the Yale Philosophy Department in the late 60s. 

@f.  If something casts a shadow, then there is light falling directly on it. 
@o.  Nothing can cast a shadow through an opaque object.
@s.  Every shadow is cast by something.

Consider a bird flying in the shadow of a barn. What casts the shadow
beneath the bird? Given (@f), not the bird. Given (@o), not the barn.

Variant 1: Suppose the two objects are sized just right so that each, absent the
other, would cast exactly the same shape and size of shadow. (So, Near and Far.)

Variant 2: Also suppose that Far is spinning clockwise, and Near
counterclockwise. Which direction is the shadow spinning?

Variant 3: Suppose an object casts a shadow on the surface of the Earth. Suppose
that, beneath the Earth, there is a dark cave. Does the object also cast a
shadow into the cave?

What is a Shadow?
=================

Shadows involve the absence of light, but not every absence of light involves
a shadow. A shadow involves an absence of light that is the result of one
object blocking light from hitting another. But not every absence of light
that involves one object blocking light from hitting another involves a shadow
(see the cave example). So, under what conditions, exactly, is it correct to
say that a shadow exists?

Further Reading {.unnumbered}
===============
