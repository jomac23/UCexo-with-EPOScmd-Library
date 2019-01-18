# UCexo-EPOS_Linux_Library


Here you can find a C++ code that we used to control an exoskeleton for lower limbs. Each joint uses a maxon EC motor with an EPOS4 module 50/8. The code implements functions of the EPOS_Linux_Library which allow send frames with information to every EPOS4 and generate a normal walking trajectory on the exoskeleton.


EPOS_Linux_Library has installed within a Raspberry Pi 3 Model B. Through a CANbus network, we connected a Raspberry with 3 EPOS4 to control the exoskeleton joints, topology is depicted below.

            -----------       -------------       --------------       ---------------
           | Raspberry |     | EPOS4 - Hip |     | EPOS4 - Knee |     | EPOS4 - Ankle |
            -----------       -------------       --------------       ---------------
                 |                  |                    |                     |
                 ---------------------------------------------------------------
                                              CAN bus
                  
Information of each function implemented in EPOS_Linux_Library are in "EPOS Command Library.pdf". You can obtain this document after to install EPOS Studio in your computer (https://www.maxonmotor.com/maxon/view/content/epos-detailsite). With these functions, we can send CAN frames to each EPOS4 through a Raspberry Pi. 



hghh
