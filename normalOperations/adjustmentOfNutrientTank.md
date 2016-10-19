#normalOperations/adjustmentOfNutrientTank.md
##Synopsis.
Describes the process of periodic adjustment of the nutrient solution in the [nutrient tank](Valve diagram).  
As the plants grow, they drink water and eat the nutrients, so, every few days the nutrient tank needs to be adjusted. The need is indicated by the nutrient level dropping by a few inches. The nutrient solution level needs to be brought back up and nutrients components added in the right proportions to bring the total ppm to the [target level](Grow guidelines). Also, ph of the nutrient solution must be adjusted within acceptable range of 5.0-6.0ph as described in [grow guidelines](Grow guidelines)

##What to do.
* Top the [nutrient tank](Valve diagram) to the [target level](Grow guidelines) from the [RO tank](Valve diagram) using [transfer from RO to Nutrient tank procedure](Transfer from RO to Nutrient tank).  
    Note the amount of RO water added to the nutrient tank by observing tick marks on the tank.
* Turn mixing pump on by plugging it into one of [utility power strips](Wiring diagram) outlets.
* Calculate the amount of each nutrient component to be added as described below.
* Measure and add each component to the nutrient tank. Make sure to rinse the measuring cup with RO water for each component. There is a reason why they are in separate bottles.
* Wait a few minutes until the ppm reading stabilizes.
* Read the ph reading.
* Adjust ph of the nutrient tank if needed as described in [grow guidelines](Grow guidelines)
* Again, wait until ph reading stabilizes between each ph adjustment. Avoid the phup/phdown swing cycle. Use them very sparingly or not at all.

##How to calculate nutrient adjustments.
First, you need to know per gallon rate of each nutrient component for the target total ppm. As described in [grow guidelines](Grow guidelines), it should'v been calculated when you nuted the tank at the start of the grow. The target ppm level will be changing thru the grow, so, you should adjust per gallon rate proportionally. Example:
> Lets say, you started with 100gal tank and it took 1600ml of GH Bloom and 800ml of GH Grow to bring total ppm to 1300ppm. That makes 16ml/gal and 8ml/gal for grow and bloom components.
However, at this point in the grow, your target ppm is 1500. So, the adjusted per gallon rate is 16x1500/1300=18ml/gal for bloom and 8x1500/1300=9ml/gal for grow.


Now, for each nutrient component, calculate adjustment by this formula:

    //Calculate ppm adjustment factor as ratio of current ppm to the target ppm
    ppmAdjustmentFactor=ppmCurrent/ppmTarget

    //Calculate how much of the nutrient component (ml) in the tank right now
    //  currentWater (gal) - the reading of the water level you see on the tank right now
    //  targetComponentRate (ml/gal)- per gallon rate of the nut component to rich target total ppm (measured at the start of grow as described above)
    currentComponent=targetComponentRate x ppmAdjustmentFactor x currentWater

    //Calculate how much of the nutrient component (ml) is needed for target ppm
    targetComponent=targetComponentRate x currentWater
    
    //Calculate how much nut component to add (ml)
    componentToAdd=targetComponent - currentComponent

    
        