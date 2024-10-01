# Combo-Chain: Towards a Hierarchical Attribute-Based Access Control System for IoT with Smart Contract and Sharding Technique

The Internet of Things (IoT) provides a collaborative environment among different entities (i.e., users, IoT devices, sensors, applications, etc.) to access resources. Despite the benefits that IoT technology brings to individuals, society, and industry, it faces a critical challenge in controlling access to various resources in IoT environments. To address this challenge, we propose Combo-Chain, a blockchain-based access control system deeply rooted in the concepts of the Attribute-Based Access Control (ABAC) model, smart contracts, and sharding. Combo-Chain introduces the concept of hierarchy for both subject attributes and object attributes to enhance flexibility and dynamism when specifying ABAC policies, thereby simplifying policy and attribute management. It not only manages access policies but also attributes by deploying a set of smart contracts. Furthermore, Combo-Chain utilizes sharding techniques to distribute the overhead associated with storing and managing both access policies and attributes. Sharding also helps Combo-Chain to distribute the computational overhead when evaluating access requests among two groups of nodes, addressing the issues of low scalability and poor performance often associated with blockchain technology. Combo-Chain is implemented on a private Ethereum platform.

This repository presents the code for Combo-Chain, including the **APSC**, **SRMC**, **SAMC**,**OAMC**, **APMC**, **Oracle**, **JavaScript at the subject**, and **JavaScript at the object**.

## Steps to run the code:
1. setup three private Ethereum network.
2. Deploy the APSC and SRMC on chain1, SAMC and APMC on chain2, and OAMC and APMC on chain3.
3. Deploy oracle.
4. Register Subject and Object.
5. Add Subject/Object Attributes.
6. Add the required information for access control to the smart contracts, e.g., access control policies.

## Publication ##

Vahid Bakhtiary, Meghdad Mirabi, Afshin Salajegheh, Seyed Hossein Erfani. (2023). **Combo-Chain: Towards a Hierarchical Attribute-Based Access Control System for IoT with Smart Contract and Sharding Technique**. Internet of Things 25 (2024): 101080
<p dir="auto"><a href="https://www.sciencedirect.com/science/article/pii/S2542660524000222">The paper is available here.</a></p>

