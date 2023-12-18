+++
title = 'Why Neural Networks'
date = 2023-12-18T12:10:05Z
draft = false
+++

# Why neural networks?
## *(an article I wrote back in 1996)*

***This is an article I wrote about neural networks, back in 1996, as part of a university project. The article was lost but I found it on the [wayback machine](http://web.archive.org/web/20141127065609/http://www.doc.ic.ac.uk/~nd/surprise_96/journal/vol1/ds12/article1.html) and I am republishing it since its content is still applicable today and the article was very popular in its day.***

For the last ten years Neural networks have attracted a great deal of attention. They offer an alternative approach to computing and to understanding of the human brain. This approach is not something new. The first artificial neuron was produced in 1943 by the neurophysiologist Warren McCulloch and the logician Walter Pits. During the sixties, for reasons that are out of the scope of this article, people turned away from neural networks and concentrated in the symbolic side of Artificial Intelligence. Only in the eighties scientists saw the real potential of neural networks.

Neural networks take a different approach to problem solving than that of conventional computers. Conventional computers use an algorithmic approach i.e. the computer follows a set of instructions in order to solve a problem. Unless the specific steps that the computer needs to follow are known, the computer cannot solve the problem. That restricts the problem solving capability of conventional computers to problems that we already understand and know how to solve. But computers would be so much more useful, if they could do things that we don’t exactly know how to do.

Neural networks process information in a similar way the human brain does. The network is composed of a large number of highly interconnected processing elements(neurons) working in parallel to solve a specific problem. Neural networks learn by example. They cannot be programmed to perform a specific task. The examples must be selected carefully otherwise useful time is wasted or even worse the network might be functioning incorrectly. The problem is that there is no way of knowing if the system is faulty or not, unless an error occurs.

The building block of a neural net is the neuron. An artificial neuron works much the same way the biological one does. It takes many inputs having different weightings and has one output which depends on the inputs. A biological neuron can either ‘fire’ or not ‘fire’(When a neuron fires, it outputs a pulse signal of a few hundred Hz). In an artificial neuron ‘firing’ is normally represented by a logical one and nor ‘firing’ by a logical zero.

> “Definition: Neural computing is the study of networks of adaptable nodes which, through a process of learning from task examples, store experiential knowledge and make it available for use.” Aleksander, I. and Morton, H.

Neural nets are widely used in pattern recognition because of their ability to generalise and to respond to unexpected inputs/patterns. During training, neurons are taught to recognise various specific patterns and whether to fire or not when that pattern is received. If a pattern is received during the execution stage that is not associated with an output, the neuron selects the output that corresponds to the pattern from the set of patterns that it has been taught of, that is least different from the input. This is called generalisation.

For example:
A 4-input neuron is trained to fire when the input is 1111 and not to fire when the input is 0000. After applying the generalisation rule the neuron will also fire when the input is 0111, 1011, 1101, 1110 or 1111 but will not fire when the input is 0000, 0001, 0010, 0100 or 1000. Any other inputs (like 0011) will produce a random output since they are equally distant from 0000 and 1111.

Highly complex pattern recognition can be achieved by using a network of neurons hence the name neural networks. The networks normally used for pattern recognition are called feed forward because they have no feedback. They simply associate inputs with outputs. Neural networks are now used successfully in speech, language, and image recognition. Of course, pattern recognition can be done successfully on conventional computers too, but writing the software is time consuming and the system will generally have a slower response.

Pattern reconstruction is much more complicated and something that on conventional computers is very difficult to do. For pattern reconstruction feed-forward networks are not enough. Feedback is needed in order to create a dynamic system that will produce the appropriate pattern. The output of each neuron is connected to the input of the neighbouring neurons. These kind of networks are called autoassociative networks.

An interesting experiment was carried out involving a neural network controlling a vehicle. The experiment was intended to compare human driving behaviour with neural network driving behaviour. The results showed an astonishing similarity between the two of them (Ref. 2). According to the results neural nets can approximate human driving behaviour with a maximum error of 5%.

Neural networks and conventional algorithmic computers are not in competition but complement each other. There are tasks that are more suited to an algorithmic approach like arithmetic operations and tasks that are more suited to neural networks. Even more, a large number of tasks require systems that use a combination of the two approaches (normally a conventional computer is used to supervise the neural network) in order to perform at maximum efficiency.

> *Neural networks do not perform miracles. But if used sensibly they can produce some amazing results.*

References:
1. An introduction to neural computing. Aleksander, I. and Morton, H. 2nd edition
2. Developments in autonomous vehicle navigation. Stefan Neuber, Jos Nijhuis, Lambert Spaanenburg. Institut fur Mikroelektronik Stuttgart, Allmandring 30A, 7000 Stuttgart-80
