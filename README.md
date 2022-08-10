Dual Dory 
================
**Abstract**: A linkable ring signature allows a user to sign anonymously on behalf of a group while guaranteeing that multiple signatures from the same user can be detected.

For applications such as privacy-preserving e-voting and e-cash, linkable ring signatures can significantly improve privacy and anonymity guarantees. To scale to systems involving large numbers of users, we need short signatures with fast verification.

Concretely efficient ring signatures currently rely on a trusted authority maintaining a master secret, or follow an accumulator-based approach that requires a trusted group setup. 

In this work, we construct the first linkable ring signature with both logarithmic signature size and verification that does not require any trusted mechanism. Our scheme, which relies on discrete-log type assumptions and a bilinear map, improves upon a recent concise ring signature called DualRing by integrating improved preprocessing arguments to reduce the verification time from linear to logarithmic in the size of the ring. 

Our ring signature allows signatures to be linked based on what message is signed, ranging from linking signatures on any message to only signatures on the same message. 

We provide benchmarks for our scheme and prove its security under standard assumptions. The proposed linkable ring signature is particularly relevant to use cases that require privacy-preserving enforcement of threshold policies in a fully decentralized context and e-voting. 

Full paper
------------
Our full paper can be found [here](https://raw.githubusercontent.com/DualDory/DualDory.github.io/main/DualDory-full.pdf)

Implementation
---------------
Our implementation can be found [here](https://github.com/yacovm/DualDory)


