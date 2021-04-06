# jetsonindustry
Jetson nano in industry
Combining Artificial Intelligence and Automation are a key product for the industry 4.0 which combines digital platforms, hyperautomotion, 5G, robotics, machine Learning and Others.
In this project we combined many branches of knowledge, including, electronic, electrica engineering, PLC programming, Neumatics, Python, PyQT5, etc.

The project was designed to segregate the product OK and the product NOK.
https://www.youtube.com/watch?v=fL3EmgYhG80
The process is as follow:
- Using the jetson nano and a camera check if there is a product NOK.
If the product is NOK the neumatic cilinder will open a gate.
The NOK product will go off and an inductive sensor will check if the product is gone.
Once product went to scrap the gate will close again for the OK pieces.
Cycle every time.
So we adapted a Jetson Nano Hat to use relays and send the 24V which is the standard voltage in the industry, the Jetson nano GPIO will send the signal to the Relay and the relay is connected to a power supply.

We found a case also which is good foor cooling and a cabinet also good.

Cabinet for jetson nano and PLC
So the client asked for an interface where the user is capable to reset the counter so he can know how many pieces are NOK and put that on his production log.
In the next image you can see how the interface is done, we used pyqt5 to create the interface which was very easy to do.

Interface for the jetson nano
In this project we put also password for admin to edit the parameters. The can be scalated using deep learning for image classification or Image segementation but we concluded that it was not necessary because we are only seeking a color pattern but we know that we can scalate this project further more.
Conclusion:
Artificial Intelligence and Industry is a beautiful combination which can do many things to help the operators in tasks where they cannot keep an eye the whole time, adding quality to their products and better client satisfaction.
