<img width="512" height="512" alt="Foundation Node" src="https://github.com/user-attachments/assets/920cc0c8-3b04-4f6a-bfff-7386aa0072e5" /> <br />
The **Foundation Node** is a [UNet](https://github.com/Tyson-Shannon/UNet) to [TNet](https://github.com/Tyson-Shannon/TNet) data validation border node. This node will validate and sign UNet data so TNet can trust and store it.

## Goal
This code will be run by admin on a private device to ensure the security of TNet. This code will ensure malicious data can't be uploaded to the public IPFS storage network.

## The Network
<img width="581" height="570" alt="529012917-a48d2560-fb83-4023-9078-5758ea63d8df" src="https://github.com/user-attachments/assets/4775b5e8-94ae-4311-b193-2b9d39a4d2d0" />

## Why
Despite UNet/TNet being decentralized this one centralized node is essential to maintain security without an expensive, slow, and often confusing blockchain. Without the Foundation Node's data signing anyone would be able to upload anything to TNet's IPFS gossip network, allowing for garbage and malicious data to overwhelm connected devices. This is a simple and secure solution to maintain network integrety while sacrificing a bit of decentralization. <br /><br />

It should be noted however, if the Foundation Node where to fail the decentralized network should continue to operate with only data upload funtionalities being impacted.
