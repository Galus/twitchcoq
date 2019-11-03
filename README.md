# twitchcoq

Reimplementing a subset of Coq in Python

Just kidding, Coq is too complex. We implemented metamath instead.

# random notes

First order logic:

<pre>
Theorem test : exists x : nat, x + 2 = 4.
Theorem test2 : forall y : nat, (exists x : nat, x = y).
</pre>

Second order logic (quantifing over first order logic statements):

<pre>
forall y : (fun x : nat -> nat)
</pre>

Higher order logic...so on and so forth

