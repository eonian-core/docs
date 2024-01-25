# Assets Recovery

One integral part of any wallet is the private key. But there exists a hard problem where to save it. If the key is stored only locally on the device, it guarantees increased security and a lower risk of hack. But if the device is lost, access is lost with it. On the other hand, it is possible to save a key on the server or encrypt and store it on another chain. Some wallets even provide this solution directly. But all of them introduce the risk of private keys being stolen on the server or unencrypted on the chain. And give access to some middleman who can accidentally lose or use this key.

We allow the user to store their key locally on the device. But in case the user loses the device, he is still able to recover access to assets in our protocol by creating a new wallet and then contacting us through the receiver's email. This email works as a 2FA channel, which will be used to target us on which wallet we must move user assets to give access back to these assets.

In the future, we will introduce additional channels, like messengers and phones, to make this recovery process even more convenient. But even one email paired with a wallet can provide a higher level of safety and reliability than a hardware wallet.
