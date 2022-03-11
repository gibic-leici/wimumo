# WIMUMO Pulse

WIMUMO is a wireless device capable of measuring electrical signals from the body. The most well-known electrophysiological or biopotential signal is the electrocardiogram (ECG) that almost everyone has experiences at a doctor's office at some point. But other biopotentials can also be measured, such as those coming from the muscles (called electromyogram or EMG), brain (EEG) or eyes (EOG).

![An ECG](/images/ecg-2.png)

WIMUMO measures these signals, transmits them wirelessly over Wi-Fi, and uses them for a variety of applications such as music generation, games, and learning about the signals themselves. Technically we call it Multi-Modal acquisition platform, and hence its name (WIreless MUlti MOdal aqcuisition platform).

![Photo of the first WIMUMO prototype](/images/ALV0753-01-01-1024x483.jpg)

WIMUMO is not intended only to be used by the engineers who developed it, but one of its objectives is to provide simple and friendly access to the signals produced in the human body. The motivating power of biopotential signals together with easy access enables the generation of multiple applications for teaching, artistic performances, entertainment, assistance devices for people with disabilities and many others.

That is why WIMUMO makes the signals, applications and configuration tools available through a web page. In the case of artistic performances, the already processed signals are transmitted to generate music and images with standard programs that musicians and multimedia designers usually use, using the OSC protocol.


## The body's electrical signals, or “biopotentials”

In order for us to contract a muscle, a chain of events is necessary that begins with our conscious decision, or an unconscious command, which is triggered in the brain, in some of our neurons. That "spark" is transmitted through our nervous system in the form of an electrical impulse called an "action potential" that travels to the muscles. The electrical signal spreads through the muscles as they contract, and if we need to exert more force, more and more of these potentials are sent.

The heart is a big muscle and has its own “pacemaker” that generates these action potentials at the rhythm of the beat and gives the ECG that particular shape. The electromyogram (EMG), on the other hand, which comes from the process described above when moving or trying to move the muscles, is less well known and its shape is more strange. It is made up of the superposition of many action potentials that run through nerves and muscle fibers, and therefore looks like a set of "spikes" that grows as we exert more effort. The muscles of the arms, legs, face, etc., receive these signals according to our will and move the body. All this keeps us alive and allows us to work, eat, play, dance.

![Image of an electromyogram (EMG) signal](/images/emg-300x93.png)

An “active” electrode placed on the forearm to measure signals from the muscles that move the fingers
When biopotentials are very strong or pass very close to the skin, they can be captured by placing electrodes resting on the skin surface. The electrodes "translate" the biopotentials inside the body into electronic signals that can be measured with precision electronic instruments. Precisely the GIBIC group of the LEICI Institute (depending on the UNLP and CONICET) works on the investigation of these electronic instruments that measure biopotentials, an area where electronic and computer engineering contribute to biomedical engineering.

## From the measurement of biopotentials to music

To use biopotentials in performance or artistic works of any kind, WIMUMO measures muscle and heart signals, and digitally processes them to obtain the "average activity" observed in each signal, known as the envelope. This envelope is a clear indication of the force exerted with one or several muscles. WIMUMO sends it to music or video generation programs and can then, for example, be used to raise or lower the volume of a musical note. In this way, when a person in a performance moves, or, being immobile, makes an effort with his muscles, she can create different sounds.
