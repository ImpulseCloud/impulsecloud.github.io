---
layout: post
title: DNA-puzzle
---

I'm starting to work on an Explorable Explanation relating to DNA transcription/translation, centering on the function of the Ribosome, but including functional explorations of what happens before and after. The first thing I'm going to make is a 'puzzle' game where the player has to construct DNA via molecular puzzle-pieces, arranging the sugar backbone with phosphate groups and adding nucleotides at the correct places.

I'm cloning Nicky Case's 'Loopy' so I have a scaffold to modify instead of starting from scratch. I intend to change the behavior of the Node-grabbing to have a group-behavior with multiple nodes to create a 'molecule' object. I'll remove the signal-propagation subsystem, unless I need it to verify that the pieces are correctly placed around each other. Then I'll need to make an "attachment" system to recognize correct proximity and orientation when a molecule is placed next to another.
