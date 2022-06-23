# matchy
matching participants randomly with each other


## general idea
- $something should be done for multiple rounds where participants interact with each other (e.g. dancing)
- there are three sets of participants (e.g. leading ppl, following ppl, and ppl that can do both)
- those should be randomly assigned to each other and to roles (e.g. to pairs of a leading person and a following person)
- the assignments are shown/told to the participants and one round of $something is performed
- for the next round an assigment of ppl should be calculated that does not include the already performed assigments

## defaults
By default numbers are aligned to the three types (see the settings that appear after clicking on 'more').
1-9 is assigned to left, 10-19 to right and 20-29 to the switches (i.e. participants that can/want to do both sides)

I planned to hand out numbers to ppl that want to participate in the corresponding group.
Then I wanted to inspect the numbers that are left over and remove them from the initial sets.

## does this even work
well ... it did for me ...
there are a couple of things I have not properly tested, like ... using names for participants instead of numbers :D 


## known limitations
the complete algoriths does NOT scale to too many participant (it works for 20 ppl, but starts calculating longer and longer if the number of participants is increased)

## coding idea
i want all data to be in one place (file)
so everybody can download that file and use it without having to setup a server, play around with cors headers and other black magic.


## ideas 
if you have some spare time and want to help: the following ideas could give you an idea to start for super simple an pretty daunting ones

- set values for "left" and "right" in the interface
- allow resizing of the boxes (to allow for 'names' instead of numbers)
- interface overhaul
- a server component (I might adapt another project to this) to allow ppl to use their phones as a diplay for their own number - websockets anyone?
- add the possibility to add custom attributes and preferences (e.g. attribute 'smoking' - and prerefence 'I don't want to dance with as smoking person' - or gender and gender preference)

