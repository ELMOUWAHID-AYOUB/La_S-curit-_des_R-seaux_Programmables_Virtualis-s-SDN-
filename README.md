Voici la version corrigée de votre texte :

# SDN Network DDoS Detection Using Machine Learning

## Requirements

To run this project, you need the following:

- Dataset: `ML/FlowStatsfile.csv`
- Ryu Controller VM
- Mininet VM

## Steps

1. Import the virtual machines into VirtualBox.
2. Change the IP address of the Ryu controller in the source code.
3. On the Ryu controller, run:
   ```bash
   ryu-manager DT_controller.py
   ```
4. On Mininet, run:
   ```bash
   sudo python topology.py
   ```

## Created by
- EL MOUWAHID Ayoub
- Errahimi Oussama
- Laaouibi Mohammed
