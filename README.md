# On the Foundation of Neural Computation

[download paper.pdf](paper.pdf?raw=true). 

## Abstract

The paper postulates that neuron firings, an all-or-none event, are the equivalent of particles travelling in space, and the propagation of neural signals over a neural network follows the same rule as the propagation of particle waves, more specifically, Feynman’s path integral formulation as described in his *A Space-Time Approach of Non-Relativistic Quantum Mechanics[1]* (Eq 18):  

![Feynman's Rule](images/feynmans_rule.png?raw=true)

From this postulate, we can deduce that neural circuits are the basic storage and processing units. The information is stored in its frequency domain representation by circling signals around. Neural circuits are analogous to strings with both ends fixed on a music instrument. Each circuit has its unique natural frequency that’s determined by the time and energy required for signals to circle around the circuit. The dendrites and axons attached to neural circuits function as the antennas receiving and transmitting neural signals, respectively. The communication between circuits and the recall of memory are done through the resonance of natural frequencies.

The paper discusses how a sufficiently large and deep neural network can approximate the transform function between two arbitrary input and output signals using basic building blocks of neural computation. It provides a simple mechanism of how a network can and will spontaneously develop the capability of recognizing spatial and temporal patterns. Such a mechanism explains why the learning behavior of biological brains differs from the current ML system, e.g. no explicit objective function, no backpropagation, one-shot learning, the learned behavior is reversible, etc. The paper makes both qualitative and quantitative predictions on the behavior of individual and collective minds that can be observed and tested objectively. It proposes the design of physical devices that can accomplish common tasks such as spectral analysis and solving the shortest path problem in O(1) time. Finally, it explores the nature of consciousness and the limitations of the human logic imposed by the physical law of the universe.

In summary, biological brains are neural computers built on neural circuits (not logic gates). The information is encoded, stored, and processed as frequencies in the form of circling signals (not as bits in genetic or digital information). The computation is carried out through the propagation of neuron signals (not by flipping bits). The evolution of neural networks is driven by the principle of least action (objective function) and manifests itself in the process of evolution by natural selection. Neural computation offers a new paradigm of computing that’s very different from the current classical and quantum computers, and a simple interpretation of quantum mechanics that’s compatible with everyday experience.

Please see details at [paper.pdf](paper.pdf?raw=true). 

## Neural Circuits in a Nutshell

Suppose that a neural circuit receives upstream signals via a neuron (purple) and connects to the downstream network via another (orange).  It takes 1s for neural signals to circle around the circuit. Let us also assume that the upstream signals consist of two frequencies: one is firing every 1s (1Hz, as shown in red arrow), and the other firing every 1.1 ms (~0.9Hz, as shown in green arrow). The neuron firing is illustrated as the following diagram where a small block is the equivalent of 100 ms. We can visualize the signal propagation by dragging the signals toward the arrow of the time. The signal propagation along the circuit can be visualized as rotating the circuit. 

![Signal Processing and Natural Frequency](images/natural_frequency.png?raw=true)

When the input signal lasts, the circuit largely relays the signal to the downstream network. The firings resonating with the circuit’s frequency (red arrows) always hit the same block (#7 red) while the firings of non-resonating signals (green arrows) spread around the circuit. If we represent the signal circling around the circuit by a probability density function (PDF) by counting the number of neuron firings per unit of time, i.e. 100ms, we will see the 1Hz signal stands out and the non-resonating signal (0.9Hz) becomes background noises. The area under the PDF corresponds to the total number of neuron firings around the circuit, which is powered by the neurons around the circuit and remains largely a constant. Over the time, the circuit will capture and store the signal resonating with its frequency (1Hz). It’s the neural basis for read/write memory. 

![Signal Circling Around a Circuit](images/neural_signal.png?raw=true)

There are ~100B neurons in the human brain. With an average branching factor of ~10,000, the number of unique paths starting from a neuron is in the order of 10<sup>4000</sup> after 1000 hops. Even if a miniscule amount of the paths loop back and form circuits, the number of circuits could be more than the number of atoms in the universe. An arbitrarily complex signal, namely, the intensity of neuron firings as a function of time, can be expressed as a Fourier series of different frequencies and stored in a cluster of neural circuits. The same neural structures can transform the signals from its frequency domain representation back to its time domain representation. This simple neural structure solves the encoding, storage, and processing of the information.

![Basic Storage and Processing Units](images/processing_unit.png?raw=true)

If the upstream signal stops, the neuron firings of the 1Hz signal continue circling around the circuit. When the signal arrives at the orange neuron,it will propage to both the next neuron of the circuit and the downstream network. However, the frequency of the signal will be 1Hz and no longer contains other frequencies in the original upstream signals. So, a neural circuit can not only remember the signal strength of its inputs, but also become a source broadcasting the signal of a specific frequency for the downstream circuits.

![Circuits as the Source of Neural Signals](images/signal_source.png?raw=true)

If a weak signal with resonating frequency arrives at the circuit and coincides with the circling signal, it will hit the hyper-sensitive area and trigger a strong frequency response. The frequency response of neural circuits are the neural basis for why we can utter one word at a time even though the muscle memories of all words are simultaneously wired to the muscle cells of the vocal cords.

![Frequency Response](images/frequency_response.png?raw=true)


## Personal Note

In the pursuit of a basic understanding of my own consciousness, I’ve destroyed everything that I once held dearly in my life: emotion, dream, love, free will, and self-awareness. It feels too cold to live a life full of illusions. When the temperature drops outside, I see water molecules cuddling together and forming these beautiful snowflakes. I see the colors of the rainbow reflected by their ephemeral existence. I think to myself what a beautiful sight! It’s a miracle for a snowflake to even contemplate the meaning of life.

After a day of mundane life, it’s become a pastime for me to watch Feynman’s lectures online. His path integral formulation of quantum mechanics gives me an intuitive understanding of the inner workings of the universe. Feynman once remarked after reflecting on the intellectual journey of developing his theory:

>*So what happened to the old theory that I fell in love with as a youth? Well, I would say it’s become an old lady that has very little attractive left in her and the young today will not have their hearts pound anymore when they look at her. But, we can say the best we can for any old woman, that she has been a very good mother and she has given birth to some very good children.*

Well, at least one young today looks at the old lady. His heart starts to pound and his mind cannot help but ponder the secret of life and nature. Hope the sparklings from one tiny snowflake add a bit of color to your understanding of life and nature, too. 
