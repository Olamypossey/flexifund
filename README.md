# CrowdFlex Smart Contract

CrowdFlex is a Clarity smart contract for decentralized crowdfunding on the Stacks blockchain. It allows anyone to create, manage, and contribute to fundraising campaigns with flexible controls for both creators and contributors.

## Features

- **Create Campaigns:** Start a campaign with a funding goal and deadline.
- **Contribute:** Send STX to active campaigns before their deadline.
- **Claim Funds:** Campaign creators can claim funds if the goal is met.
- **Refunds:** Contributors can claim refunds if the campaign fails.
- **Cancel & Force Cancel:** Creators and admins can cancel campaigns.
- **Extend Deadline & Update Goal:** Creators can extend deadlines or update goals (if no funds raised).
- **Admin Controls:** Admin can remove campaigns, force cancel, and transfer admin rights.
- **Read-Only Views:** Query campaign details, contributions, and campaign status.

## Usage

1. **Deploy** the contract to the Stacks blockchain.
2. **Interact** using the public functions to create campaigns, contribute, claim funds, or request refunds.
3. **Query** campaign and contribution data using the read-only functions.

