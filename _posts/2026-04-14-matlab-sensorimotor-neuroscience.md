---
layout: post
title: "MATLAB & Sensorimotor Neuroscience"
date: 2026-04-14
order: 2
categories: [MATLAB, Neuroscience]
tags: [matlab, sensorimotor, neuroscience, data analysis]
---

In KNES 464 (Advanced Topics in Sensorimotor Neuroscience) at the University of Calgary, I used MATLAB to analyze electromyography (EMG) signals and study how the nervous system controls muscle activity. Below is some of the figures I generated.

---

## The Tendon Vibration Reflex

In this experiment, a wearable tendon vibrator was applied to the Achilles tendon while surface EMG was recorded from the right soleus muscle. The vibrator was equipped with an accelerometer to capture its movement. The goal was to characterize the **muscle stretch reflex** — the automatic muscle contraction that occurs in response to tendon stretch.

**Figure 1** Raw acceleration signal from the Achilles tendon vibrator and rectified right soleus electromyography recorded during a 2-second segment of tendon vibration stimulation.

![Tendon Vibration and Soleus EMG time series](/assets/img/matlab_1.png)

**Figure 2** Power spectral density of the tendon vibration acceleration signal (ACC; left) and right soleus electromyography (RSOL; right) across their respective frequency ranges.

![Power Spectral Density - Tendon Vibration](/assets/img/matlab_2.png)

The cross-correlation between the two signals revealed a peak response latency of approximately **80 ms** — consistent with the known conduction time of the stretch reflex arc in the lower limb.

---

## The Vestibular Reflex

In this experiment, **Stochastic Vestibular Stimulation (SVS)** — a form of electrical vestibular stimulation using band-pass filtered (1–25 Hz) noise — was applied over the mastoid processes while EMG was recorded from the right medial gastrocnemius (RMG) muscle. The goal was to probe the neural pathway connecting the vestibular system to lower-limb muscles, which is critical for balance and postural control.

**Figure 3** Stochastic vestibular stimulation current waveform (SVS; top) and rectified right medial gastrocnemius electromyography (RMG; bottom) recorded during a 2-second segment of electrical vestibular stimulation.

![SVS and RMG EMG time series](/assets/img/matlab_3.png)

**Figure 4** Power spectral density of the stochastic vestibular stimulation input (SVS; left) and right medial gastrocnemius electromyography output (RMG; right) within the 1–25 Hz stimulation bandwidth.

![Power Spectral Density - Vestibular](/assets/img/matlab_4.png)

---

## Key Takeaways

Working with real physiological data in MATLAB gave me hands-on experience with signal processing techniques that are directly applicable to clinical and research settings, giving me a deeper understanding on how to extract meaningful information from noisy biological signals.