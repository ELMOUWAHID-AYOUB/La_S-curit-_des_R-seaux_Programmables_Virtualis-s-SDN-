SDN Network DDoS Detection Using Machine Learning
Requirements
To run this project, you need the following:

Dataset: ML/FlowStatsfile.csv
Ryu Controller VM
Mininet VM
Steps
Import the virtual machines into VirtualBox.
Change the IP address of the Ryu controller in the source code.
On the Ryu controller, run:
bash
Copier le code
ryu-manager DT_controller.py
On Mininet, run:
bash
Copier le code
sudo python topology.py
Created by
EL MOUWAHID Ayoub
Errahimi Oussama
Laaouibi Mohammed