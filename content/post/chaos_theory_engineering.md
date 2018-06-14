+++
title = 'Nietzsches Butterfly: An Introduction to Chaos Theory and Chaos Engineering'
image = 'images/maxresdefault.jpg'
slug = 'chaos-theory-and-engineering'
date = '2018-06-14'
description = 'Chaos theory was immortalized in fiction by "The Sound of Thunder," a short story that tells the tale of a contemporary presidential election being affected significantly by the death of a pre-historic butterfly.'
+++

Chaos theory was immortalized in fiction by "The Sound of Thunder," a short story that tells the tale of a contemporary presidential election being affected significantly by the death of a pre-historic butterfly. The chain of coincidences that led to this altered future seemed to be random and unpredictable, but when all the changes are tracked-a gargantuan, realistically impossible undertaking-order does emerge. The problem is, you have to accept the idea of chaos trumping simple cause and effect first, before you can see the inherent order at all.

Chaos theory falls into that category of scientific ideas that few actually understand but many have heard of, due to its expansive, epic-sounding principles and thoughts. Who wouldn't love to write a scientific paper entitled "If a butterfly flaps its wings in Brazil, does it cause a tornado in Texas?" Inherent to the theory is the idea that extremely small changes produce enormous effects, but ones that can only be described fully in retrospect. There are many great examples of this in nature, and climate change is one of them. Small atmospheric changes in one part of the globe can produce enormous effects years later in another region, thanks to the system feeding back changes into itself.

Does any of this ring bells when we compare the situations with modern day distributed systems in the age of internet where multitudes of services are being deployed every second across the system? Alright, let's take a humanly example:

The neurons in a human brain only fire in response to another electric signal firing at them. If each neuron represents a self-enclosed one-dimensional object-in a space with billions of one-dimensional objects-then your brain has a hypothetical billion dimensions within it. So when one neuron fires, the path may be initially deterministic, but the cascade of electrochemical transmissions rapidly becomes unpredictable. From ten billion neurons, or dimensions, a single thought generates a hypothetically infinite number of chaotic paths. However, this process is not random - it is merely chaotic.

If the electric signals in your heart show signs of chaos and unpredictability, this can lead to a heart attack. On the other hand, an epileptic seizure is nothing more than a pattern of abnormally periodical order in the electrochemical signals in your brain. Either way, understanding that systems are inherently chaotic, despite having simple deterministic variables, is important to coming up with conclusions as to how they will behave in the future.

So here's something very important to relate with the distributed systems, neurons and the electrochemical signals:

Consider a neuron as a single **service** from your system. Now, it is just a hypothetical scenario to consider billions of services in every distributed system. But, they're definitely not any less than our humanly example. Next, consider the electrochemical signals as the requests. So, what happens when the distributed system receives requests? Passing through all the services, communication between the services, the trajectory will quickly become unpredictable if you have a huge number of services.

Similarly, in case of your heart and the distributed system, the chaos is inherently there. One way or another, we cannot disagree to the fact the understanding the systems which are **inherently chaotic** in nature is important to make the system more reliable to handle the failures which might arise at any point in future.

So, how do we find the point of failures in such a complex world of neurons? This is where experimentations pitch in. We perform well thought experiments on our systems to find the point of failures, fix them before they turn into a disaster in future. This is called proactive approach. We act before something goes wrong. Chaos Engineering is not just another discipline where you’ll focus only on tools, it is a shift in culture and mindset as well.

In technical terms, as stated by [Principles of Chaos](https://principlesofchaos.org/):

> Chaos Engineering is the discipline of experimenting on a distributed system
in order to build confidence in the system’s capability
to withstand turbulent conditions in production.

Stay tuned for next steps of getting started with Chaos Engineering.

## References/Credits:

1. [nietzsches_butterfly](https://www.nature.com/scitable/blog/student-voices/nietzsches_butterfly_an_introduction_to)
2. [Principles of Chaos](https://principlesofchaos.org/)
