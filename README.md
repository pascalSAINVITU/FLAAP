# FLAAP
## Fair Lotto Autonomous Agent Provider (for Obyte)


## Use cases:
* Sent ticket price with a hash of your secret (that could be ask later) to enter the round;
* Be the first to trigger the next step for a free ticket in the next round;
* Reply with your secret when asked by the AA for a free ticket in the next round;

## problems revealed in the first round lottery:
* Using mc_unit as seed is bad idea because it can be manipulated with a previous specially craft unit.
* Letting the draw time be selected by a trigger is dangerous because harry can way the best moment for his odds to trigger.

## Workflow:
When the buy period ends up, the buyer of the last ticket, trigger the pick of a 'random drawing time' and a 'random player' that will be asked to trigger again the AA after the specific 'drawing time delay', this first randomness is generated based only on the attested addresses that entered the lottery so that is this difficult for harry to choose this value to be in his favor. The selected player will have a chance to get a 0.5% reward of the lottery to trigger the real draw at the 'random drawing time' previously defined, this reward is payd thought an secondary AA that allows other parties to try to overtaken the player by getting the reward in his place by triggering before him, so it insure that the drawing will be realized at the wanted time. if the delay is too big another drawing time and and other player are selected for later draw. If a drawing is trigger at the randomly selected moment, the number of the winner player is drawn based only on different 'time variable data feeds', so there is no way to influence the draw as the draw-time was randomly fixed in the futur and there was no way to predict those variable in the first place.
