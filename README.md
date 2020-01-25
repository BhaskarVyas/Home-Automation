# Home-Automation
Home automation refers to the ability of your home to make its own decisions depending on the
environmental conditions and give you the option to control it from a remote location. In this project,
we primarily aim to control appliances in two ways: automatic control and User control.
We detect human presence and count the number of people in a particular part of the house and
check if additional lighting is required based on the light intensity already present in the room. The
user also has control over the light through his phone or any google home device.
We will also work on fan control in the same way, using LM35 sensors for automatic control.

We plan to implement this on NodeMCU. PIR and LDR sensors will be interfaced with the NodeMCU
to read the data, which then processes the information and sends the output to the appliance
connected to it via a relay. For user control, we plan to use Google Assistant to input data, which then
transfers the data to the Adafruit feed via IFTTT. NodeMCU which continuously monitors the Adafruit
dashboard receives the information and controls the appliance accordingly.
