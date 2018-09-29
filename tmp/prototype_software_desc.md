# Introduction

Meal vouchers are redeemable tickets given by an employer to its employee as a form of benefit. Vouchers have a fixed value, cannot have change and have to be spent in their entirety, thus making payments problematic when cost and voucher value do not match. 

The purpose of this software (ExChange) is to provide a platform for payments in which vouchers are a form of credit that can be used to seamlessly execute transactions between parties. The platform can tokenize fixed values credits such as vouchers or pool credits from multiple buyers to solve the issue of fixed values credits and change. (Forse conviene lasciare il resto in surplus dai ticket -> debito rimanente da un party?)

The sections here presented describe the necessary requirements to fullfill the functional requirements of the system previously mentioned, in the form of simplified diagrams according to agile methodologies.

# System model

### Actors:

* Generic user: A generic user is a user that has in his account a certain amount of credits. A generic user can either receive or transfer his credits as part of a transaction. Contemplated transactions involve selling or buying goods - hence a generic user can be either a buyer or a seller.
* Company: A company is a legal entity made up of an association of people. A company might represent a seller or a conglomeration of buyers pooling their credits together.
* ExChange system: The system acts whenever a new user joins the system or a transaction takes place. Every transaction aspect is automatized by the system through the Corda architecture.

### List of use cases:

* Generic user use cases:
    * Charging credits
    * Buying a good
    * Selling a good
* Company use cases:
    * Pooling credits
    * Buying a good
    * Selling a good
* ExChange use cases:
    * 
    * 