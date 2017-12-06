# Med-Dev.io Software Roadmap
-----------------------

This document outlines the development plan from a high level and will be updated as progress is made toward version 1.0. It should be noted that this roadmap applies only to the basic services needed for the blockchain to begin tracking of devices and billing teams for FDA regulated type 1 and type 2 devices. Seperate road maps will be issued to cover other regulatory regimes when the regimes have finalized their requirements.

The plan was created by Origin Tracker Limited, based on their experience of writing tracking software, webistes and apps for the tracking on uniquley labelled phyiscal items. The exact use of EOS.io architecture is not yet fully understood and so may lead to material changes in the order and design of the below

***Everything contained in this document is in draft form and subject to change at any time and provided for information purposes only. Origin Tracker Ltd does not guarantee the accuracy of the information contained in this roadmap and the information is provided “as is” with no representations or warranties, express or implied.***

# Phase 1 - Minimal Viable Testing Environment

Learn how to interface with EOS.io when test bed is available (hence flexible start date)

##Simple contracting node
Create a simple contracting node to send a unique identifying code and check it's format with

##Simple verification node
Create a simple verification node to receive a unique identifying code and check it's format against static data

##Full Node
Create a Full node to record transactions

# Phase 2 - Assess EOS.io as a viable system
Is it possible to create the simple Blockchain above on EOS.io yet? Yes/no
If no:
  - Option A - Hold; EOS.io looks promising but needs work... we'll wait it out
  - Option B - Switch; Change to alternative providers or make our own
  
If Yes:

# Phase 3 - Tag Creation and integration

##Tag nodes

Generate the parent codes that represent every item being tracked.

##Tag integration

Simple nodes and verfication nodes will perform actions and report back by using contracts that identify both the individual and the Tag being used.

# Phase 4 - Complex data

##Simple verification node rules

Add rules to check data formats and routing information to Tags based on the code structure

##Simple contracting node - complex data

Allow simple contracting node to represent scanning handsets. Data becomes dynamic and unpredictable.

# Phase 4 - Permissioned Actions, Tokens and Teams

##Permissioned Actions

Allow contracts to dictate what different user types can take which action with this Tag.

##Tokens

Allow the purchase of Tokens to unlock sharing capabilities with contracts.

##Teams

Create team management and billing, to allow users to group and share their data.
Create permissioned teams that can verify their identity against the FDA's GUDID

##FDA Oracle

Create two interfaces into the FDA
  - Realtime; instant checking for individual users who are about to operate
  - Bulk download; storing full product data for disection and distribution to nodes
  
##Integrate FDA checking 

Take directions from simple verification node to allow sysetm to check with FDA. Later this will allow direction to different oracle nodes - eg manufacturer catalogues, other regulators, or external blockchains if the code is not recognized

# Phase 5 - Beta testing, blockchain integrity, open source docmentation

Is the transaction log accurate? Tools and testing to prove med-dev.io blockchain with live data

Hpw to plug in, full details on contract formats, third party integration.

SDC

- ends -
