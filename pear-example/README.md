# Pear Example

### Quickstart for the Speedrunners

1. Open Two Terminals. Put this into the first one:
```bash
npm i -g pear
npm install hyperswarm hypercore-crypto b4a
pear run --dev .
```

2. Now put this in the second one:
```bash
pear run --dev .
```

3. Click "Create" in one of the terminals
4. Copy and Paste the topic string into the second terminal
5. Join
6. ????
7. Pear to Pear

### Why Fruit is So Nutritious 

Please watch [these videos](https://www.youtube.com/watch?v=y2G97xz78gU&list=PLEZwCXa1K8Q629mWmpcSYCVMDoi0s8hzI&pp=iAQB) to see the founders demonstrate their remarkable work
 
The code used here can be found documented [here](https://docs.pears.com/guides/making-a-pear-desktop-app)

Pear, originally called HolePunch, is a suite of open source tools built upon the [bare javascript runtime](https://docs.pears.com/bare-reference/overview). In their overview of bare, the Pear Team say:

> Bare is a small and modular JavaScript runtime for desktop and mobile. Like Node.js, it provides an asynchronous, event-driven architecture for writing applications in the lingua franca of modern software. Unlike Node.js, it makes embedding and cross-device support core use cases, aiming to run well on any system whether that is a phone or desktop. The result is a runtime ideal for networked, peer-to-peer applications that can run on a wide selection of hardware

This is javascript built with to be as bare and lightweight as possible. It is performant and can find itself on most devices you would care to find software on. Yet to truly live out this vision, we must test, build, and then imagine. This demo code is what the founders of pear have left us with to begin spreading our fig upon. We will find our fig spread from Pear to Pear.

Pear allows for testing, sharing, and shipping applications in every phase of their creation from the smallest scraps of processing to the most baroque endeavours. Though you read this on GitHub, we ship fig through pear and we simply stage the bare minimum you need to start spreading fig all throughout the pear toolchain. Pear can even be invoked from C. 

We Snails wish to integrate fig and pear with iron on rust. The inspired founders of Pear cherish Bitcoin, and should we not pay homage to the greats which have forged the world in which we find our lives played out? However, we snails want to go fast, simply put. Iron on Rust will iteratively like Newton's method spread rusty-kaspa Pear to Pear enabling rapid confirmation of hyperbolic silver at your fingertips. 

We start with snailmail which is a faithful fork of the pear you find in this directory. If I imagine what fig on pear will taste like, I come to see Holders of the KRC-20 token $FAST gaining the ability to sign their messages with their same private key that shows they are who they are on the Iron on Rust kaspa network. We snails will bring our slime to complex networks beyond the block while sublimating their structural principles towards new heights of sacchrine effervescence. May we transcend our old networks on the very same hardware that we could hitherto not imagine working otherwise. 

### Getting Started 

Let us obtain fig via the customary git symbolic invocation

```bash
git clone https://github.com/AccKaspa/fig.git
cd fig
```

If you do not have npm, please install it by doing a variation on the following to be found [here](https://nodejs.org/en/download/package-manager):

This should work for linux. 

For those who are new to this: welcome. Nvm is a version manager that we will use to install a package manager that we will use to get javascript code that others have been so kind to make available for us. Pear and Bare and all the rest are such treasures which we are so enriched to have at our disposal, surely. The node runtime comes along with it, but since we are building fig on pear, we wish to focus on bare as our runtime. The founders of Pear are very familiar with node and so if they have moved onto new horizons, we would be wise to follow suit.

```bash
# installs nvm (Node Version Manager)
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.0/install.sh | bash

# download and install Node.js (you may need to restart the terminal)
nvm install 22

# verifies the right Node.js version is in the environment
node -v # should print `v22.9.0`

# verifies the right npm version is in the environment
npm -v # should print `10.8.3`
```

For more information on installing pear [see](https://docs.pears.com/guides/getting-started)

In summary:

```bash
npm i -g pear
```

Because bare is built moduarly, you will often find yourself needing npm to install depenencies when building with Pear.

In order to run the project here, we shall necessarily invoke:

```bash
npm install hyperswarm hypercore-crypto b4a
``` 

At this point, we can now begin running our app. Before that, a word on just what is here. If you have watched the videos in the very first link of this README, you will know what is about to happen. If not: here is a very basic peer to peer chat app that creates a hash. A second client app using this pear can utilize that hash in order to join the chatroom. One should run the following command in two seperate terminal windows or with a friend on a lovely call to investigate with phenomenological satuaration. 

```bash
pear run --dev .
```
