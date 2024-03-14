# ARG Tech AIF Datasets
The repository containing links, descriptions and references for the datasets and shared tasts from ARG Tech group.

## Who are we ? 
The Centre for Argument Technology (ARG Tech) works in philosophical and linguistic theory of argument, in computational models of argument and their implementation in artificial intelligence systems, and in deploying argument technology solutions to large audiences. Our research has attracted £10m in funding in areas as diverse as law, defence and media, and we have partnered with organisations including IBM, the BBC and the UN. We have over 200 papers in print, and our freely available software, including argument annotation tool, OVA, has tens of thousands of users around the world. We host the largest extant public datasets of annotated argument and debate at aifdb.org, and our work with public engagement and the media has reached over 30 million people.


## Table of Contents  

##  Argument Interchange Format (AIF)

The AIF as a data format is constructed as a practical dataformat for Inference Anchoring Theory (IAT). The theory provides a theoretical toolkit to handle dialogue and argument structures, and the relations between them. We use IAT in order to represent and understand the arguments people offer, often on public platforms, in order to develop insight into complex debates.

<br> Simply speaking, AIF is a format for presenting text of a debate or an argument via the directed graph (see image below).

<br>
<br>
The base elements of the AIF are  argumentative discourse units (ADUs). ADUs can be further classified into L- and I-nodes. L-nodes (<b>locutions</b>) contain a unprocessed text with the information of the speaker included as well. I-nodes (<b>information</b>) contain a content of the ADUs. Keep in mind that the mapping of L and I nodes is not precise one to one.
<br>
<br>

Edges (incoming and outgoing) is the term used to describe the relations between the nodes.
IAT has three types of relations:

*  relations between locutions in a dialogue, called transitions (TAs);
*  relations between content (propositional content of locutions);
*  illocutionary connections that link locutions with their content.

These relations are collectively known as S-nodes (because they are governed by schemes) and they typically connect I-nodes.

![Alt text](aif-docs.png)

The top left proposition has two incoming edges (one from the rephrase and the other from the rhetorical questioning, whereas the bottom left proposition has one incoming (asserting) and one outgoing (Default Rephrase).
<br>

<b>Directionality</b>: TAs only point downwards; MA and CA only point up; RA can point both up or down depending on where the conclusion and premise are; YAs go from the right- to left-hand side.



## Available Datasets

| Year | Dataset Name | Description | Donwload Link | Reference | Contanct |
| --- | --- | --- |  --- | --- | --- |


## Scripts and Tutorials

## Overview of our Shared Tasks

## Overview of our Pre-Trained Models

## Scripts and Demos

## Useful Links and Contacts
