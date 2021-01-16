# Simulink_Fuzzy-PID

This is a simulink model of Fuzzy-PID controlled Inverted Pendulum. Simscape pendulum model was used[1], and Fuzzy-PID controllers created.

In the first alternative; to control pendulum angle and cart position, two Fuzzy-PID blocks were implemented. According to error signal, fuzzy controllers calculated parameters for both of PID respectively. Then PID controller calculated output signals and applied to the Pendulum. Fuzzy controllers have two different inputs. These are rate of change error and error signal.

In the second alternative; a Fuzzy-PID controller was created to control pendulum angle and a Fuzzy controller was created to control cart position. Fuzzy-PID to control pendulum angle works same as in the first alternative. To control cart position a single fuzzy block was used. The single fuzzy block has two different inputs. One of them is cart position error, the other is rate of change error in pendulum angle.

[1] SimScape model of pendulum is cited here; https://ctms.engin.umich.edu/CTMS/index.php?example=InvertedPendulum&section=SimulinkModeling
