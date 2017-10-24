
# CNC



CNC router (or Computer Numerical Control router) is a computer-controlled cutting machine related to hand held router used for cutting various hard materials,such as wood,composites,aluminum,steel,plastics and foams.  



![cnc milling](https://user-images.githubusercontent.com/32705189/31944677-b6fe66de-b881-11e7-8225-bcff10b5876b.jpg)




Almost all machines accepts "gcode"file for operations.Similarly the ShopBot also accepts the"gcode"file for PCB milling.Hence the circuit design inany of the format must be converted to"gcode" format.Thus we use fabmodules.org


## Steps for the generating "gcode"file



*Open fabmodules.org.




*Now select the input,either as image(.png or jpeg),drawing or mesh etc...




*Now select the output format.Here we selected the ".sbp" format.




*Finally the process need to be selected.Here we selected "Foam(rough cut 1/8)".





![cns measures](https://user-images.githubusercontent.com/32705189/31945791-07b773a6-b885-11e7-897b-599a77745035.png)




Once the "gcode"file is obtained,go for the machine adjustments.





## Steps for PCB milling


*First stick the material onto the sacrificial layer using a two side tape.



*Now we need to set the Zero point.For setting the Zero point do the following:



1.First move the bit to the appropriate position.




2.Now move the bit down and set the bit in such a position that it just touches the surface.Use a paper sheet to ensure this.




3.Once this is done select"Zero axis"and check all the three axis.(Refer the image)


