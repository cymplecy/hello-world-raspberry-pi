# Node-RED

1. Open **Node-RED** from Programming in the main menu

1. Open **Chromium Web Browser** from Internet menu (or click icon at top)

1. Type `localhost:1880` into url address box

1. Drag a blue `Inject` node from the list of nodes on the left, into the main flow workspace area

1. Double-click on it and change `Payload` from timestamp to string and type in `Hello World` and then click `Done`

1. On the left pane, scroll down to green `Debug` and drag that out to the right of the Inject node

1. Double-click on it and click to enable node status -  press `Done`

1. Click and drag a wire from the output of the `Inject` node to the input of the `Debug` node.

1. Click `Deploy` in the top right of the window.

1. Click the button on the left of the `Inject` node to see Hello World appear beneath the `Debug` node (you can also see it if you click on the `Debug tab`)  
![capture](https://user-images.githubusercontent.com/2357428/37516101-f303dfd0-2904-11e8-9128-4e7d2f144b7f.PNG)

