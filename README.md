# FLAAP
## Fair Lottery Autonomous Agent Provider (powered by Obyte)

## Use cases:
* Sent ticket price to AA;

## problems revealed in the first round lotteries:
* Using mc_unit as seed is bad idea because it can be manipulated with a previous specially craft unit.
* Letting the draw time be selected by a trigger is dangerous because harry can way the best moment for his odds to trigger.

## Workflow:
* When the buy period ends up, the buyer of the last ticket, trigger the pick of a 'random drawing time' and a 'random player' that player will be asked to trigger again the AA after the specific 'drawing time delay', this first randomness is generated based only on the attested addresses that entered the lottery so that is this difficult for harry to choose this value to be in his favor. 
* The selected player will have a chance to get a 0.5% reward of the lottery to trigger the real draw at the 'random drawing time' previously defined, this reward is paid thought an secondary AA that allows other parties to try to overtaken the player by getting the reward in his place by triggering before him (see AA entry THAANKS), so it insure that the drawing will be realized at the wanted time. 
* If the delay is too long, another drawing time and and other player are selected for later draw. 
* If a drawing is trigger at the randomly selected moment, the number of the winning player is drawn based only on a maximum of 'time variable data feeds' (in testnet, only, crypto prices and timestamp millisec, so there is no way to influence the draw as the draw-time was randomly fixed in the future and there was no way to predict those 'time variable data feeds'..

## remarks
* It could be made simplier by taking the taking the 'drawtime' = 'buy round time', and select random players and propose them a reward every time a attested player buy a ticket. But if not attested players around then nobody is asked to trigger the AA at the right time. and also the delay between the notifiation of available reward and the requested trigger time is longer.
* You can create lottery for any type of asset
   ▄▄▄▄▄▄▄ ▄▄▄▄▄  ▄▄ ▄ ▄ ▄▄▄▄▄▄▄  
   █ ▄▄▄ █ ▄ ▄▀ ▄  ▄ ▀ █ █ ▄▄▄ █  
   █ ███ █ ██    ▀ █ ▄   █ ███ █  
   █▄▄▄▄▄█ ▄▀▄ ▄▀█ ▄ ▄▀▄ █▄▄▄▄▄█  
   ▄▄▄▄  ▄ ▄▀ ▀▄ ▀▄█▀▄█▄▄  ▄▄▄ ▄  
     █ ▀█▄▄▄▀ █▀█▀▀▀▄▀▀   ██▀▄▄▀  
   ▀█ ▀▄█▄▀▄▄   ██▀  ▀ ▄▀▀ █ ▄██  
   ▄▀▄▀ █▄▀█▀█ ▄▄▀ █▄▀▄▄█▄▄▄▀▀██  
   ▀▀█▀█▀▄  ▄▄▄█▄▀▀▄ ▀▀▄█ █▀▄ ▀▀  
   ▄ ██▄█▄█▄▀▄▀  ▄▄  ▀▀█▄▀▀ ▀█    
    ▄▀ ▄ ▄▀ ▀███ ▄▄█▀▄█▄██▄█▀▀█▀  
   ▄▄▄▄▄▄▄ ▀▄▀█▀█ ▀█▄ ▀█ ▄ █▄▄█▀  
   █ ▄▄▄ █  ▄█ ▀██▄▄ ▀ █▄▄▄█▄ █   
   █ ███ █ ███ ▀▄▄▀ ▀▀ ▀▀▄█ ▄▄▀█  
   █▄▄▄▄▄█ █▄▄▀ ▄▀▀█  ▀██▀█▄▀▄█   
                                  
