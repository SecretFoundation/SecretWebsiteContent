---
layout: ~/layouts/MainPageLayout
---

<template v-slot:title>

## About Secret Network

</template>

<slim-column>

### What is Secret Network?

Secret Network is a first-of-its-kind, open-source blockchain that provides **data privacy by default.**

While blockchains have the promise to create a more open and sustainable Internet, they've been held back by one major flaw: they expose all your data to everyone. A better Internet must protect data privacy and give users and organizations control over how their data is used and shared. **Secret is a decentralized network that finally solves this problem of privacy,** helping to secure and scale the decentralized web.

As the first blockchain to support encrypted inputs, encrypted outputs, and encrypted state for smart contracts, Secret Network allows for new kinds of powerful decentralized applications to be built. This can unlock substantial value across multiple verticals and industries, including the following:

</slim-column>

<card-holder>

<card class="industry-card">

<template v-slot:header>

#### Decentralized<br>Finance

</template>

Support for privacy-preserving asset transfers, lending, and more.

</card>

<card class="industry-card">

<template v-slot:header>

#### Data<br>Sharing

</template>

Sharing and monetizing data while keeping it secure.

</card>

<card class="industry-card">

<template v-slot:header>

#### Machine<br>Learning

</template>

Discovering powerful insights while protecting underlying data.

</card>

<card class="industry-card">

<template v-slot:header>

#### Healthcare<br>Industry

</template>

Allowing research over encrypted data, driving innovation.

</card>

<card class="industry-card">

<template v-slot:header>

#### Gaming<br>Industry

</template>

Enabling more open and more usable gaming experiences.

</card>

<card class="know-other-keys">

<template v-slot:header>

#### Want to learn some other secrets?

</template>

<next-button tag="Read the FAQ" to="/about/about-secret-network/#frequently-asked-questions">

</next-button>

</card>

</card-holder>

<slim-column>

### How Secret Network Operates

Secret Network is a decentralized network of computers (secret nodes) that utilize trusted execution environments (TEEs) to enable secure, private computation over encrypted data. TEEs function like a “black box” for data processing, and they are utilized in all types of everyday platforms such as smartphones and video game consoles.

Secret Apps - powered by “secret”, privacy-preserving smart contracts - are built with CosmWasm smart contracts that are written in the Rust programming language and deployed on the Secret Network.

The Secret Network blockchain itself is based on Cosmos SDK / Tendermint, meaning the network has its own independent consensus, on-chain governance, and features like slashing and delegation. It is secured by the native coin Secret (SCRT), which must be staked by network validators and is used for transaction fees as well as governance.

<next-button tag="Read the Secret Network Gray Paper" location="move-left" to="/graypaper">

</next-button>

</slim-column>

<slim-column>

### Network Flow

The following process describes, step by step, how a contract is submitted and a computation performed on the Secret Network:

</slim-column>

<card-holder class="network-flow" columns="4">

<card>

<template v-slot:header>

<h4 class="orange">01</h4>

#### Writing

</template>

A developer writes "secret" smart contracts and deploys them to the Secret Network.

</card>

<card>

<template v-slot:header>

<h4 class="blue">02</h4>

#### Submission

</template>

Users submit encrypted data to Secret Network that can’t be read by anyone else — including the node doing the computation.

</card>

<card>

<template v-slot:header>

<h4 class="yellow">03</h4>

#### Computation

</template>

A "secret node" in the network performs the computation, and returns the result.

</card>

<card>

<template v-slot:header>

<h4 class="red">04</h4>

#### Verification

</template>

The work is verified as correct, and payment is released to the secret node that performed the work.

</card>

</card-holder>

<slim-column id="frequently-asked-questions" name="frequently-asked-questions">

## Frequently Asked Questions

<faq>

<template v-slot:header>

####  What is the Secret Network?

</template>

The Secret Network is a decentralized network of computers (which we call "secret nodes") that use hardware-based and software-based privacy technologies to enable **secure computation.** On top of this network, developers can build **Secret Apps** - unstoppable, permissionless applications that can utilize encrypted data without ever exposing the data itself, even to the nodes in the network performing computations.

</faq>

<faq>

<template v-slot:header>

####  What's so special about Secret<br>Network?

</template>

Secret Network combines the best features of decentralized, open-source networks and blockchains with the benefits of data privacy and improved usability. These improvements are critical for achieving mass adoption.

We want to enjoy the benefits of [smart contracts](https://en.wikipedia.org/wiki/Smart_contract) and decentralized applications (or dApps): they are robust, unstoppable, censor-resistant and transparent. But blockchains, and by extension smart contracts, have one glaring problem that is often overlooked — all data stored on them is public. In that sense, blockchains are worse than anything that came before them when it comes to privacy. Instead of trusting your data with a single organization (e.g., as is the case with Facebook, Google, your bank, etc), you now have to trust _everyone._ Secret contracts and Secret Apps combine these benefits of dApps but add the ability to keep data private, helping remove one of the biggest barriers to mass adoption of the decentralized web.

</faq>

<faq>

<template v-slot:header>

####  Why call it Secret?

</template>

A secret is something that you don’t want to share with _everyone_, but still want to share with people you choose to trust. A secret is something that you want to keep protected - not because it’s something bad, but because it’s something _valuable_. We call this network “Secret” because it allows developers and users to protect valuable data while still enabling them to share and compute it when, how, and with whomever they choose. Secret Network is where these important concepts of _privacy, freedom, and consent_ coincide.

</faq>

<faq>

<template v-slot:header>

####  What are secret contracts and<br>Secret Apps?

</template>

"Secret contracts" are _privacy-preserving_ smart contracts built on Secret Network. Smart contracts (in this context) are essentially self-executing pieces of code that are managed on a blockchain. Secret contracts improve on regular smart contracts in that they not only solve for _correctness_, but also for _data privacy_. Secret contracts are written in the [Rust programming language](https://www.rust-lang.org) . Secret Apps utilize the capabilities of secret contracts to enable unique use cases that empower users and increase opportunities for growth and impact.

> Learn more on the [Protocol](../developers/protocol/components) page or visit our [full documentation](../developers/introduction/overview) .

</faq>

<faq>

<template v-slot:header>

####  Why privacy?

</template>

Members of our community, including secret node operators and Secret App developers, believe that **privacy is a fundamental human right and a public good.** Privacy needs to be protected and supported by the technologies we use in daily life. However, an overly centralized internet and large data monopolies have put our privacy, our security, and our society at risk. That's why we are dedicated to building solutions with privacy at their core, empowering users to take and keep control of their valuable information. Privacy makes the applications we rely on more usable and more secure - and when privacy is not protected, neither are we.

</faq>

<faq>

<template v-slot:header>

####  Why blockchain?

</template>

By using blockchain, a decentralized network of computers can reach consensus on the state of the network while remaining open and permissionless. Secret Network is built on [Cosmos SDK / Tendermint](https://tendermint.com/sdk) , a popular blockchain framework, allowing for a wide variety of organizations and individuals to participate in our community and network. The only way to build a sustainable foundation for privacy-first applications is by creating an open, diverse, and transparent culture, united by the purpose of data dignity for all!

</faq>

<faq>

<template v-slot:header>

####  What is programmable privacy?

</template>

Secret Network is focused on achieving _[programmable privacy](https://blog.scrt.network/programmable-privacy/)_ . Most privacy solutions in the blockchain space today concentrate only on _transactional privacy_, specifically obscuring data on senders or receivers of transactions. Programmable privacy is a much more expansive vision, as a transaction is just one (trivial) type of computation. Secret Network allows applications to use encrypted inputs, encrypted outputs, and encrypted state, meaning we can enable groundbreaking new use cases for smart contracts and decentralized applications.

</faq>

<faq>

<template v-slot:header>

####  What does Secret Network help solve?

</template>

Everything! Which applications would you use every day if they could not protect you or your data? When you use blockchains today for any purpose, you are forced to compromise on privacy. Any decentralized applications built on Secret Network benefit from its privacy protections. Our community is primarily focused on use cases that help us achieve our stated mission: to advance privacy as a human right and a public good; to empower individuals through development and use of decentralized technologies; and to protect freedom and create more valuable systems by eliminating data monopolies.

_Sample use cases include:_ privacy-preserving credit scoring and lending; private on-chain auctions for cryptoart and other digital collectibles; decentralized access control; secret voting for collective decision-making; privacy-preserving machine learning; and many more applications in the fields of decentralized finance, gaming, healthcare, and dozens of other industries.

</faq>

<faq>

<template v-slot:header>

####  What is SCRT?

</template>

SCRT (pronounced "Secret") is the native coin of the Secret Network. This means SCRT is used to pay fees and transfer value on the network. Secret nodes must stake SCRT in order to operate on the network, and in return they receive fees and network rewards in SCRT. When nodes go offline, they can be "slashed" and lose a portion of their SCRT stake. Holders of SCRT who are not operating nodes may "bond" their stake to a specific node in order to become a _delegator_. Delegators have an opportunity to earn a share of fees and network rewards by supporting a particular set of validators.

Another utility for SCRT is governance of the network. Secret nodes can create and vote on governance proposals using SCRT, allowing for decentralized control of the network.

> Learn more on the [Network](/about/about-the-network) page or visit our [full documentation](../developers/node-operators/validators/validators).

</faq>


<faq>

<template v-slot:header>

####  What are Trusted Execution<br>Environments, and why do we use<br>them?

</template>

[Trusted Execution Environments](https://en.wikipedia.org/wiki/Trusted_execution_environment) (TEEs) are special enclaves inside a computer that function like a "black box", allowing computations to occur _confidentially_ inside of them. They are utilized in a broad range of everyday hardware, including the fingerprint readers in smartphones. Secret nodes in the network use these secure enclaves to protect the data used by secret contracts.

While our community is constantly exploring other innovative privacy solutions (such as multi-party computing, homomorphic encryption, private set intersection, etc.), they are simply not practical to use in production for applications today. There are always tradeoffs between scalability, performance, and security, and today secure enclaves provide the best option for protecting data privacy in a decentralized network. We continue to explore and research other solutions!

</faq>

<faq>

<template v-slot:header>

####  What is the relationship between<br>Enigma and Secret Network?

</template>

[Enigma MPC](https://www.enigma.co) is a development company that is one of the core contributors to [Secret Network](https://scrt.network) . Their work is critical to the Secret ecosystem as they contribute to both protocol-level functionality (such as [secret contracts](https://blog.scrt.network/secret-contracts-update-milestone-3-of-3-is-complete/) ) and key applications for the network. There are currently dozens of companies and individual contributors currently supporting Secret Network and its ecosystem, whether it is through development work, node operation, education, or many other means!

</faq>

<faq>

<template v-slot:header>

####  What is Cosmos, and why are you<br>using their technologies?

</template>

[Cosmos](https://cosmos.network/) represents a standard approach to developing scalable and interoperable blockchain applications. We believe the Cosmos SDK, Tendermint and Inter-Blockchain Communication Protocol (IBC) are groundbreaking since they are looking ahead to a future of many interconnected, app-specific blockchains. We're excited to see how Secret Network can bring more privacy solutions to the Cosmos ecosystem. [Learn more about this on our blog.](https://blog.scrt.network/secret-hub/)

</faq>

<faq>

<template v-slot:header>

####  Is Secret Network a "Layer One" or<br>"Layer Two" solution?

</template>

Secret Network has its own consensus and provides privacy for smart contracts deployed on the network, without Secret Network needing to interoperate with any other blockchain. We have often referred to this as "blockchain independence", but based on this description, others would call Secret Network a "Layer One" blockchain. However, part of our vision has always been bringing privacy to _every_ blockchain. This means our community is continuing to explore key "Layer Two" functionality for Secret Network, such as by utilizing [IBC](https://cosmos.network/ibc) / Cosmos interoperability, building an Ethereum bridge, or other means.

_Interested in helping expand this guide? You can [contribute to this page!](https://github.com/SecretFoundation/SecretWiki)_

</faq>

</slim-column>

<style lang="scss">
#frequently-asked-questions {
  margin-bottom: $gutter-xxlarge;
}
.industry-card {
  border: 1px solid var(--theme-fg) !important;
  border-radius: 10px !important;
  .card__header {
    .separator {
      display: none;
    }
  }
  .card__body {
    padding: 0;
  }
  .card__footer {
    display: none;
  }
}
.know-other-keys {
  border: 0 !important;
  .card__header {
    .separator {
      display: none;
    }
  }
  .card__body {
    padding: 0 16px 16px 16px;
    .next-button {
      display: inline-block !important;
      width: auto !important;
      padding: 10px $gutter !important;
      background-color: transparent !important;
      @include theme(dark dark-colored) {
        color: $secondary-turquoise-color;
      }
      @include theme(light light-colored) {
        color: $primary-blue-color;
      }
      &:hover {
        transition: 0.5s ease;
        -webkit-transition: 0.5s ease;
        @include theme(dark dark-colored) {
          background-color: $secondary-turquoise-color !important;
          color: var(--theme-bg);
          .themed-image {
            img {
              filter: brightness(0);
            }
          }
        }
        @include theme(light light-colored) {
          background-color: $primary-blue-color !important;
          color: var(--theme-bg);
          .themed-image {
            img {
              filter: brightness(0) invert(1);
            }
          }
        }
      }
    }
  }
  .card__footer {
    display: none;
  }
}
.network-flow {
  .grid {
    @include respond-to("large and up") {
      grid-column-gap: rem(56px);
    }
    @include respond-to("small and down") {
      grid-column-gap: unset;
      grid-row-gap: rem(56px);
    }
    .card {
      border: 1px solid var(--theme-fg) !important;
      border-radius: 10px !important;
      position: relative;
      grid-template-rows: rem(76px) auto;
      grid-row-gap: $gutter;
      &__header {
          .separator {
            display: none;
          }
          h4 {
          &.orange {
            color: $primary-orange-color;
          }
          &.blue {
            color: $primary-blue-color;
          }
          &.yellow {
            color: #EDC92B;
          }
          &.red {
            color: $primary-red-color;
          }
          &:nth-child(2) {
            margin-bottom: 0;
          }
        }
      }
      &__body{
        padding: 0 0 $gutter 0;
      }
      &__footer {
        display: none;
      }
      &:after {
        position: absolute;
        top: 45%;
        right: rem(-40px);
        @include theme(dark dark-colored) {
          content: url('../../src/assets/arrow-right-white.svg');
        }
        @include theme(light light-colored) {
          content: url('../../src/assets/arrow-right-black.svg');
        }
      }
      &:last-child {
        &:after {
          @include theme(dark dark-colored) {
            content: ' ';
          }
          @include theme(light light-colored) {
            content: ' ';
          }
        }
      }
      @media (min-width: 768px) and (max-width: 1007px) {
        &:after {
          @include theme(dark dark-colored) {
            content: ' ';
          }
          @include theme(light light-colored) {
            content: ' ';
          }
        }
      }
      @include respond-to("small and down") {
        &:after {
          top: unset;
          bottom: rem(-42px);
          right: unset;
          left: 47%;
          @include theme(dark dark-colored) {
            content: url('../../src/assets/arrow-down-white.svg');
          }
          @include theme(light light-colored) {
            content: url('../../src/assets/arrow-down-black.svg');
          }
        }
      }
    } 
  }
}
</style>
