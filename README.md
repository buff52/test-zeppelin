# test-zeppelin
This repository hosts the Upgradeable variant of OpenZeppelin Contracts, meant for use in upgradeable contracts. This variant is available as separate package called @openzeppelin/contracts-upgradeable.

It follows all of the rules for Writing Upgradeable Contracts: constructors are replaced by initializer functions, state variables are initialized in initializer functions, and we additionally check for storage incompatibilities across minor versions.
