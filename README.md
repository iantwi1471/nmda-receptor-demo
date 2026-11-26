# NMDA receptor: a coincidence detector

An interactive, single-page demo of how the NMDA receptor works as a coincidence detector at the synapse.

The channel lets calcium in only when two things are true at the same time:

1. **Glutamate is bound.** The presynaptic (sending) neuron has just fired.
2. **The postsynaptic membrane is depolarized.** This pushes out the magnesium ion (Mg²⁺) that normally plugs the pore.

When both happen together, Ca²⁺ flows in. In real neurons, that calcium signal triggers long-term potentiation (LTP), a key mechanism of learning and memory.

## Try it

- **Live demo:** https://iantwi1471.github.io/nmda-receptor-demo/
- **Locally:** download `index.html` and open it in any browser. Nothing to install.

## Things to try

- Fire the presynaptic neuron alone. Glutamate binds, but the magnesium block holds.
- Depolarize the postsynaptic membrane alone. Magnesium leaves, but the gate stays shut.
- Fire, wait until the glutamate bar is nearly empty, then depolarize. Calcium enters only during the overlap.

## Caveats

This is a simplified teaching model. Timings are not to scale, the receptor is drawn as two subunits rather than four, and the co-agonist (glycine or D-serine) is assumed to be present.

## License

MIT
