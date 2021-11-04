# Cardano Acropolis Academy

This is the Cardano Acropolis Academy for the Cardano blockchain.

`Create <> Build <> Educate`

Be sure to check out the `praxis` directory if you are just getting
started.

## Anthropocentric Introduction

### "Who owns what?"

The complexity of the smart contract is in the definitions for those
three words of the following clause: "who owns what?" 

Naively, we start with signatures. The eUTxO ledger rules state that
you may sign some value to a public key. That value is transferred if
and only if the private key corresponding to that public key signs it
to another public key. Vis a vis, it is whoever posesses the private
key who owns all value signed to its corresponding public key. In the
simplest case, the ``who'' is the posessor of the private key.

Likewise, the definition of "owns" is that rule: that the posessor of
the private key may sign those funds to a new public key. Having the
right to spend a value is the definition of owning that value. Thus,
to "own" is to "be able to sign" and, by extension, "to be able to
spend".

The "what" as we have been referring as some "value" is a UTxO. This
is some arbitrary quantity of the ledger currency. In our case, this
is Ada. It is a number represented by string of bytes stored in the
blockchain. It has a signature attached and a value attached. When it
is spent, the sum of the outputs must be equal to the sum of the
inputs. Thus, the value of a UTxO may be divided and signed to
multiple other parties, but the total value of all of the UTxOs in the
system can never be altered by a transaction (escept in as much as it
must be verified and minted into a block, but this is a completely
separate mechanism.)

In the enlightened case, "who", "owns", and "what" are modified to
have much broader definitions. In fact, they can be programmed to
represent anything that falls within the scope of [that which can be
computed](https://plato.stanford.edu/entries/computability/) --
anything *computable*.

Before, a "who" was a the owner of a signing key. However, now a
script can sign a transaction according to arbitrary logic (but only
when told to do so by an input). Thus, any entity that can provide the
correct input to a script to induce that script to sign the
transaction can be said to be the "who". This could be individuals,
groups of individuals, autonomous machines, oracles, or space aliens
with no concept of numbers. The "who" is extended to be any input that
fulfils the arbitrary criteria provided by the "business logic" of a
"smart contract", or, simply put, a "script".

The definition of "owns" is likewise changed. Before, we needed only
sign a transaction to another public key. Now we can sign it to a
script that allows some particular entity to sign it but if and only
if they perform some other arbitrary action. Thus, to "own" is the
same as before but with the possibility of arbitrary constraints. This
is why the "smart contract" is described as a "contract": because each
party may only own that which the smart contract contains if and only
if they satisfy whatever other criteria the script and therefore the
definition of "own" dictates. To "own" is thus conditional upon
cooperation. The bedrock of coopoeration in a trustless environment is
so updated by our updated in the definition of ownership.

The final piece is to extend the definition of "what" to be
anything. This means that we must be able to specify a value not just
in arbitrary ledger units or "ada" but in any object. Where there was
no description before, we must include a description so as to
reference something that exists and so differentiate it from all other
things that exist. We do this by creating a minimal transfer of ledger
value but attach to it a description of that thing which we actually
wish to transfer. Futhermore, we can provide a number of that thing or
"value". This latter point, in which we can take the description and
hash it into the identity of a new object that also has a value is
what is meant by "native asset". We can govern the nature of that
asset by changing its minting logic specifying how much is allowed to
be created and under what circumstances and so too as it can be
destroyed. Thus it can be a copy with no original or it can be used to
represent something that exists in the real world and follow the same
rules as that object which it describes. Thus, by updating "what" to
include metadata and minting rules that define a particular asset, now
anything can be the "what".

So, in summary, the former definition of "who owns what" is the base
UTxO model. The latter definition is the eUTxO model in place as of
the Alonzo era. You can define "who," "owns," and "what" to be
anything you can imagine. So now only two questions remain: what can
you imagine, and how do we build it?

### Ethics and Law

## Mathematical Underpinnings

### Blocks of equations in formal specs.

## Algorithmic Underpinnings

### Haskell walkthrough

## Homework and Collaboration

### Further reading

### Practical Collaboration's
