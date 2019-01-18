# UCexo-EPOS_Linux_Library

We have used EPOS_Linux_Library to control three maxon motors placed in an exoskeleton of lower limbs.


EPOS_Linux_Library has installed within a Raspberry Pi 3 Model B. Through a CANbus network, we connected a Raspberry with 3 EPOS4 module 50/8 to control the exoskeleton joints, topology is depicted below.

            -----------       -------------       --------------       ---------------
           | Raspberry |     | EPOS4 - Hip |     | EPOS4 - Knee |     | EPOS4 - Ankle |
            -----------       -------------       --------------       ---------------
                 |                  |                    |                     |
                 ---------------------------------------------------------------
                                              CAN bus


