<h1>Dobot paste extruder</h1>

![logo.jpg](https://github.com/FabLab61/Dobot_Paste_Extruder/IMG_1055.JPG)

Dobot paste extruder is a project started at Fablab61 Winter school. 
Extruder prints 3d models using hot refined chocolate mass. The Extruder based on Dobot Magician Robo-arm. 
Paste extruder is an indispensable thing for confectioners, creative children and sweet-tooth humans. It is new kind of magic of Dobot Magician Robo-arm. Now you can create your own choco picture or card, or even statuette based on simple 3d stl model.

##Equipment and materials
1. Dobot Magician Robo-arm.
2. 3D Printer for creating pieces of extruder nozzle.
3. Syringe 20 ml volume.
3. Nema17 stepper driver (may be any small SD).
4. Stepper driver coupling (for Nema17 use 5-6 coupling).
5. Rolling bearing 6 mm inside.
3. М6 cotter pin ~15 sm length.
8. M5 cotter pin ~17 sm 2 pieces.
4. M6 nuts (10 pieces).
5. Heat-shrink tube for 6 mm diameter ~30 sm length.
10. Capton tape ~2 m lengh.
11. NiCr or steel wire ~2 m length.
12. Cable 0.5 mm^2 ~3 m length.
13. Controllable 12V Power input connectors for Dobot arm.
14. 12V fan.
15. Steel or glass sheet ~20x30 sm.
15. Couple of ice for cooling printing table and fan air.

##STL files for extruder nozzle

- [Syringe_pedestal.stl](http://my-files.ru/t19ojn) connects all nozzle with robo-arm and holds syringe up.
- [M6_housing.stl](http://my-files.ru/6xgr6z) is a middle-piece between syringe and stepper driver. It press syringe to extrude the choko paste.
- [Nema17_housing.stl](http://my-files.ru/4q1g3h) holds up a Nema17 stepper driver on the top of nozzle.

You need no print this stls at 3d printer. But if you want you might cut Nema17_housing out with laser razor.

##How does it works
First assembly the hardware pieces: glue rolling bearing up to Syringe pedestal, glue M6 nut up to M6 housing detail. Then fix  one tip of ~17 sm piece of M5 cotter pin to syringe pedestal at one d7 window, and do it with another ~17 sm piece of pin and another d7 window. 
Then cut heat-shrink tube in halves and put them around these two cotter pins.

Second connect stepper driver with M6 cotter pin using SD coupling. Fix it at stepper driver pedestal, then connect M6 pin with M6_housing.

Last hardware step is connecting all pieces and fix it with M5 nuts.

Then let's wrap syringe around with wire and fix it with capton tape. We need solder both tips to 12V dobot input. Then solder 12V fan to another Dobot input. Now you can try to load choko pieces to syringe and load small test stl model to you Dobot Magician robo-arm.
