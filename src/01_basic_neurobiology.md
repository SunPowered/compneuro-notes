Introduction
============

Three types of computational models covered.  

1.  Descriptive models

*   How do neurons respond to external stimuli nd how do we describe this quantitatively with a neural encoding model
*   How can we extract information from neurons

2.  Mechanistic Models

*   How can we simulate the behaviour of a single neuron on a computer?
*   How do we simulate a network of neurons?
    i.e. The Human Brain Project

3.  Interpretive or Normative Models of the Brain

*   Why do brains operate the way they do?
*   What are the computational principles underlying their operation?


Recommended Texts
------------------

*   Theoretical Neuroscience: Computational and Mathematical Modeling of Neural Systems
    by P.Dayan and L.Abbot
*   Tutorial on Neural Systems Modelling
    by T. Anastasio

Software Required
-------------------

Use MATLAB or the open source Octave <http://www.gnu.org/software/octave>

Some Goals

1.  Quantitatively describe what a biological neuron or network of neurons is doing given experimental data
2.  Simulate on a computer the behaviour of neurons and networks.
3.  Formulate computational principles underlying the operation of neurons and networks in the brain.

What is Computational Neuroscience?
====================================

To explain how brains generate behaviours?
Characterizing what nervous systems do, determining how they function and understanding why they function

Receptive Fields
------------------

In the 60's, researchers planted electrodes into an area of the cats brains.  They were able to record
electrical signals of specific brain cells.  In order to get the cells to respond, various stimuli were 
presented to the cat.  Visual cortical brain cells.  The neurons would fire only when there was a thin bar 
of light oriented 45 deg horizontally. More importantly the frequency of the response was dependent on the 
orientation, 45 degree in one direction produced a higher frequency response than 45 deg in the other direction
and no change in frequency for perfectly horizontal bars.

A receptive field is a set of cells that respond to a specific input stimuli.

### Descriptive model of receptive field ###

The retina behind the eye captures an image.  The retinal ganglion cells transmit this image as signals to 
cells in the Lateral Geniculate Nucleus (LGN) and then onwards to the primary visual cortex (V1).  It has been found that certain cells repond when a point of light is directed
onto the center of the retina and off when the light is in the surrounding region.  Alternatively, there
are cells which respond when light is on the surrounding area of the retina, and off when light is on the 
center.  These are dubbed respectively, _On-Center/Off-Surround_, and _Off-Center/On-Surround_.  

ecording Cells from *V1* shows various receptive fields.  The exepriment with the cat demonstrated oriented
receptive field. If many cells are measured in the *V1*, one finds many different oriented receptive fields, 
which can be characterized using reverse correlation.

Q: How are the oriented receptive fields obtained from the center receptive fields?
