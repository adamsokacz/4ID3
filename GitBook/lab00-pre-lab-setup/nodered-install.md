# NodeRED Install

NodeRED will be installed by NPM. NPM is an acronym for Node Package Manager. When programming, sometimes different programs need to use to the same libraries or frameworks. A package manager ensures the same libraries are not installed twice, they remain up-to-date, and they have the correct dependencies installed for them to work properly. NPM will be used to install NodeRED.

The official install documentation can be found here:

[https://nodered.org/docs/getting-started/windows](https://nodered.org/docs/getting-started/windows)

&#x20;

Open Powershell.

Launch PowerShell as Administrator.

<figure><img src="../.gitbook/assets/image (5).png" alt=""><figcaption></figcaption></figure>

Use the following command to change the execution policy.

_Set-ExecutionPolicy -ExecutionPolicy RemoteSigned_        &#x20;

<figure><img src="../.gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

Next, re-open Powershell as a normal user.

<figure><img src="../.gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>

Check to ensure that NPM has been installed correctly.

_npm --version_

<figure><img src="../.gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

Install NodeRED using the following command:

_npm install -g --unsafe-perm node-red_

<figure><img src="../.gitbook/assets/image (8).png" alt=""><figcaption></figcaption></figure>

To start NodeRED, use the following command:

&#x20;

<figure><img src="../.gitbook/assets/image (7).png" alt=""><figcaption></figcaption></figure>

Notice the line Server now running at…

Type that IP address into your web browser. Do not close this terminal window until you are done using NodeRED. Ensure that you see the Welcome to Node-RED screen.

&#x20;

<figure><img src="../.gitbook/assets/image (9).png" alt=""><figcaption></figcaption></figure>

To safely close NodeRED, open the Powershell window and press CTRL + C.



