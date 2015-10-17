# CoreData+POOCO

## What is it?
CoreData+POOCO is a XCode file template to generate CoreData classes as POOCOs (plain old objective c objects :) ).

## Motivation
I was using RestKit + CoreData for a project but after a 2nd thought i saw that any persistance is rather overhead, instead of a business requirement. 
Instead of recreating the whole model in plain objects i decided at least to keep the xcdatamodel, but get rid of everything else CoreData related. mogenerator (TODO link here) was an overkill for this task, hence - just a simple file template did the job

## Installation

Put this inside ~/Library/Developer/Xcode/Templates/File Templates/
Benefit

### N.B.
remember to tick "use primitive types" or you may get nil NSNumber's from RestKit's RKObjectMapper if json says 0

