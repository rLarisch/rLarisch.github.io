---
title: "Combination of voltage-based STDP with symmetric iSTDP to learn V1 simple-cells"
collection: talks
type: "Poster"
permalink: /talks/2012-03-01-talk-1
venue: "Bernstein Conference, Berlin"
date: 2016-09-03
location: "Berlin, Germany"
---

Learning the receptive fields of V1 simple-­cells, given natural scene input, is a well studied setting. For this, several models based on spike­-timing dependent plasticity (STDP) have been published. However, these models have several limitations as they rely on rate­-based learning dynamics (referring to symmetric STDP), lack an inhibitory circuit, or have only been described in a single­-neuron setting. We implemented a spiking network consisting of 144 excitatory and 36 inhibitory recurrent connected neurons, receiving inputs from a population of Poisson neurons. Excitatory synapse strengths are learned using a homoeostatic voltage­-based triplet STDP rule, and inhibitory synapse strengths using symmetric inhibitory STDP. The network was stimulated with pre­-whitened natural scene patches and implemented with the neural simulator ANNarchy. The neurons in the network develop V1 simple like receptive fields. Further, excitatory and inhibitory neurons with similar tuning develop strong bidirectional synaptic weights. We observed that a state of balanced excitation and inhibition was virtually impossible to achieve using the pulse­like synaptic transmission used in the STDP model by Clopath et al., which led to strongly fluctuating excitatory and inhibitory synaptic currents with little temporal correlation in our setting. As a consequence, we employed longer synaptic time constants, which improved the representation acuity of the network in terms of the image reconstruction error. However, this also had effects on the learning dynamics, such as differences in the feed­-forward receptive field sizes and learning speed, presumably through compensatory effects of the homoeostatic mechanism of the excitatory learning rule on the inhibitory learning. Finally, the model’s coding performance compares favourably to existing models.
