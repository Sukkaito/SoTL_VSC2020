# SoTL_VSC2020

Code used in DREAM, the robot our team used at Vietnam STEAM Challenge 2020
![image](https://user-images.githubusercontent.com/40479420/214259286-970c4d97-ce05-4ca8-812c-f42ac0c8de7e.png)


## I. System Info:
- Raspberry Pi 3B+ with Raspbian.
- [K12 Maker](https://github.com/makerhanoi/k12maker) expansion circuit.
- Other components (Will be updated).
- NodeJS with `NODE_MODULE_VERSION = 72`
- Node-RED 1.x branch.


## II. Installation: (On Raspberry Pi)
- Install NodeJS.
- Install Node-RED: Check https://nodered.org/docs/getting-started/raspberrypi#installing-and-upgrading-node-red for details and customization.
- Install drivers (Will be updated).

## III. Running Node-RED:
- Start Node-RED:
```
node-red
```
You will get something like this:

![image](https://user-images.githubusercontent.com/40479420/214251992-17669267-b25e-48fd-bc6e-6a28c8ad3d0d.png)

- Open the server at `<address>` in your web browser and you're ready to go.
- Run in the background: https://nodered.org/docs/getting-started/raspberrypi#running-as-a-service
- Run with system: https://nodered.org/docs/getting-started/raspberrypi#autostart-on-boot
```
sudo systemctl enable nodered.service
```
