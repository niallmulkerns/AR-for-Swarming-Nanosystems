# Augmented Reality for Swarming Nanosystems
Property of Niall Mulkerns, Guillermo Monge, Will MacAlester, Xinyi Ma - for research use at the Univeristy of Bristol within the Bristol Centre for Functional Nanomaterials. 

*Supervisors: 	Thomas Gorochowski (Biological Sciences) and Sabine Hauert (Mathematics).*

## Contents:

- [Project Briefing](#project-briefing)
- [Objectives](#objectives)
- [Initial Meeting Notes](#initial-meeting-notes)

## Project Briefing:

The ability to create emergent swarm behaviours at a microscopic scale would open many exciting avenues ranging from nanomedicine, to smart materials and synthetic biology [[1]](https://ac.els-cdn.com/S1748013213001138/1-s2.0-S1748013213001138-main.pdf?_tid=9c812716-a200-11e7-9124-00000aab0f26&acdnat=1506351096_a5decc7d2a13a12a911bfb301b2ab5e8).

Swarm behaviours emerge from the interaction of many simple agents (in our case nano- micro-particles) with each-other and their environment. Examples of swarming in nature include bird flocking, decision-making in bees, trail-formation in ants, morphogenesis in cellular populations, and quorum-sensing in bacteria [[2]](http://www.sciencedirect.com/science/article/pii/S0167779914001334).

By using swarm engineering approaches, inspired from our work in swarm robotics (http://hauertlab.com), we aim to systematically engineer swarm behaviours of nano- micro -particles under the microscope. Such systems could be useful in the field of nanomedicine, as outlined in the National Cancer Institute 5-year Cancer Nanotechnology Plan [[2]](http://www.sciencedirect.com/science/article/pii/S0167779914001334). Example applications include nanoparticles that amplify or synchronise the delivery of a treatment. nanoparticles that make decisions about the state of a tumour for diagnostics, and the creation of nanoparticle trails through tumours to improve our understanding of transport.

One key challenge in designing swarming particles is controlling the interactions between particles and each-other and their environment. To this end we propose to use a swam arena that can detect the behaviour of individual particles, and modify their local environment using light. Light patterns can in turn activate particles. This new form of "augmented reality" will allow us to design interactions suitable for the emergence of desired swarm behaviours before implementing them fully in particles.

The "augmented reality" system will be based on the "swarm arena" being designed in the Hauert and Gorochowski groups. The arena (shown in the figure) allows for the precise spatial-temporal control of environmental inputs such as light through a modified projector that emits patterns in the UV range. A camera connected to a raspberry pi is then interfaced with the microscope to capture the movement of the particles and process the resulting images that needs to be projected.

As an initial swarm behaviour, we will explore the creation of trails of microparticles from a source to an illuminated area of the swarm arena, a little bit like ants looking for a food source [[3]](https://link.springer.com/content/pdf/10.1007%2Fs11721-008-0013-5.pdf). 

## Objectives:

### September-December

- Investigation of off-the-shelf photo-responsive materials (nano- micro-particles) that can be used in the swarm arena.
- Characterisation of the purchased photo-responsive materials in the swarm arena.
- Design of an initial script that can track particles, and change the resulting light-patterns projected on the swarm arena.    

### January-March

- Design of a swarm experiment (possibly trail formation) given the selected photo-responsive material.
- Systematic exploration of the interaction space giving rise to the desired swarm behaviour.
- Demonstration of a fully autonomous swarm system using augmented reality.

## Initial Meeting Notes:


