# Prey-Predator-Ecosystem
A requirement in CMPLXSY using NetLogo to create a prey-predator model. Made in NetLogo.

**Group 5**
- Enriquez, Janielle Shane
- Mangoba, Michael Jhullian
- Rafanan, Clyla
- Sze, Gelson
- Tiongquico, Erik

## Model
The model is a prey-predator model where the prey are the fish and the predator are the fishermen. The source of food for fish are the plankton in the patches (noted by the greenish color).

<p align="center"><a href="https://github.com/erik-lance/Prey-Predator-Ecosystem/blob/master/img/pp_model.gif"><img src="https://github.com/erik-lance/Prey-Predator-Ecosystem/blob/master/img/pp_model.gif" width=50% height=50%></a></p>

## Agents

The fishermen are the turtles with boat sprites. They have slow turn rate compared to fish as it's harder to turn a boat, but they're faster at moving than fish. They move randomly, but if there's a fish turtle in the patch they're in, they catch them in order to refill their energy. However, if they do not catch any after a while, they will simply disappear.

Similarly, the fish are the turtles with fish sprites. They can turn better than boats but move slower. They also move randomly, but if there's a plankton in the patch they're in, they will eat it to refill their energ.y However, if they do not catch any after a while, they will simply disappear.