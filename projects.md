---
layout: page
title: Projects
permalink: /projects/
---

## Featured Projects

### fMRI-Guided TMS for Methamphetamine Use Disorders
<a href="/assets/images/project1.jpg" target="_blank"> 
  <img src="/assets/images/project1.jpg" alt="Personalized NIBS" width="200" style="border-radius: 10px; margin-bottom: 10px;"> 
</a>  
<p> 
  This project investigates how electric field modeling and individualized neuroimaging data can guide transcranial magnetic stimulation (TMS) interventions for substance use disorders. We collect structural and fMRI drug cue reactivity data prior to stimulation, and perform rapid analysis to define individualized targets based on functional connectivity between subcortical regions and the prefrontal cortex. Computational head models are then used to optimize coil orientation, and stimulation intensity is adjusted based on each participant’s scalp-to-cortex distance. 
  <br><br> 
  🧰 Please visit the <a href="https://github.com/SoleimaniGhazaleh/fmri-guided-TMS-GUI" target="_blank">GitHub repository</a> to access a user-friendly GUI for generating fMRI-guided TMS coordinates and running electric field simulations — from DICOM scans to ready-to-use targets. 
</p>

---

### Frontoparietal Dual-Site tACS-fMRI for Opioid Use Disorders
<a href="https://github.com/SoleimaniGhazaleh/Frontoparietal-tACS-OUD/tree/main" target="_blank" rel="noopener"> 
  <img src="/assets/images/project2.jpg" alt="Theta tACS" width="200" style="border-radius: 10px; margin-bottom: 10px;"> 
</a>  
<p> 
  A preregistered, randomized, triple-blind crossover clinical trial investigating the effects of theta-phase synchronized transcranial alternating current stimulation (tACS) on fMRI drug cue reactivity, functional connectivity, and behavioral performance. Sixty participants with opioid use disorder received 20 minutes of active or sham theta-band (6 Hz) tACS via 4×1 HD electrode montages targeting the frontoparietal network (F4 and P4). Structural MRI, resting-state fMRI, and drug cue reactivity scans were collected immediately before and after stimulation.
    <br><br> 
  🧰 Please visit the <a href="https://github.com/SoleimaniGhazaleh/Frontoparietal-tACS-OUD/tree/main" target="_blank" rel="noopener">GitHub Repository</a> to see more details. 
</p>

---

### Traveling Wave tACS-EEG for Working Memory
<a href="https://example.com/tacs-working-memory" target="_blank"> 
  <img src="/assets/images/project3.jpg" alt="Theta tACS" width="200" style="border-radius: 10px; margin-bottom: 10px;"> 
</a>  
<p> 
  Neural oscillations often propagate as traveling waves across the cortex, coordinating activity between distant brain regions. Transcranial alternating current stimulation (tACS) offers a promising method to modulate these dynamics noninvasively. In this study, we tested whether frontoparietal tACS, delivered with controlled frequency and phase offsets to simulate traveling waves in the theta band, could causally influence working memory performance and resting-state EEG activity. We conducted a randomized, triple-blind, sham-controlled crossover study in 29 healthy adults. Participants received four active tACS conditions—combining two frequencies (4 Hz, 7 Hz) and two phase offsets (45°, 315°)—and sham stimulation across two sessions. During stimulation, participants performed 2-back and 3-back working memory tasks. Resting-state EEG was recorded pre- and post-stimulation. 
  <br><br> 
  🧰 Please visit the <a href="https://github.com/SoleimaniGhazaleh/Traveling-Wave-tACS" target="_blank" rel="noopener">GitHub Repository</a> to see more details. 
</p>

---

### Closed-Loop TMS-EEG Task (MATLAB + Python) for Stimulant Use Disorders
<a href="https://github.com/SoleimaniGhazaleh/ClosedLoop_Task" target="_blank"> 
  <img src="/assets/images/project4.jpg" alt="Closed Loop Task" width="200" style="border-radius: 10px; margin-bottom: 10px;"> 
</a>  
<p> 
  A real-time task with TTL-triggered feedback designed to modulate and measure EEG states during neurostimulation. 
  <br> 
  🔗 <a href="https://github.com/SoleimaniGhazaleh/ClosedLoop_Task" target="_blank">View on GitHub</a> 
</p>

---

### Closed-Loop tACS–fMRI Frontoparietal Optimization
<a href="https://github.com/SoleimaniGhazaleh/closed-loop-tacs-fmri" target="_blank"> 
  <img src="/assets/images/project_closedloop_tacs_fmri.jpg" alt="Closed-Loop tACS-fMRI" width="200" style="border-radius: 10px; margin-bottom: 10px;"> 
</a>  
<p> 
This project integrates three complementary components: 
(1) a <strong>conceptual framework</strong> for real-time, network-guided neuromodulation (<a href="https://www.nature.com/articles/s41398-023-02565-5" target="_blank" rel="noopener">Read the paper</a>), 
(2) a <strong>safety and feasibility protocol</strong> for concurrent tACS–fMRI (<a href="https://onlinelibrary.wiley.com/doi/full/10.1002/brb3.2667" target="_blank" rel="noopener">Read the paper</a>), 
and (3) a <strong>randomized, double-arm closed-loop tACS–fMRI implementation</strong> for individualized, network-specific stimulation. 

In the closed-loop study, stimulation frequency and phase between the right dorsolateral prefrontal cortex (F4) and right inferior parietal cortex (P4) are iteratively optimized using real-time fMRI-based frontoparietal functional connectivity measured during a 2-back working memory task. A simplex optimization algorithm adapts stimulation parameters based on ongoing neural responses, enabling causal modulation of frontoparietal networks.
  <br><br>
  🧰 Please visit the <a href="https://github.com/SoleimaniGhazaleh/closed-loop-tacs-fmri" target="_blank" rel="noopener">GitHub repository</a> for the full analysis pipeline, optimization framework, and reproducible code.
</p>

---

### Meta-Modeling for Precision Neuromodulation in Substance Use Disorders

<a href="/assets/images/project5.jpg" target="_blank"> 
  <img src="/assets/images/project5.jpg" alt="Meta-Modeling for Precision Neuromodulation" width="200" style="border-radius: 10px; margin-bottom: 10px;"> 
</a>  
<p> 
  This project develops a <strong>meta-modeling framework for precision neuromodulation</strong> that extends conventional meta-analysis by integrating computational electric-field modeling with evidence synthesized across clinical brain stimulation studies. Rather than treating stimulation location and parameters simply as categorical study characteristics, this approach reconstructs the spatial distribution of stimulation across the brain and relates modeled brain exposure to therapeutic outcomes.

<br><br>
The framework has been applied to two major noninvasive brain stimulation modalities in substance use disorders: <strong>transcranial electrical stimulation (tES)</strong> and <strong>transcranial magnetic stimulation (TMS)</strong>. For electrical stimulation, computational head models are used to reconstruct electric-field distributions associated with published stimulation protocols and examine whether regional electric-field strength explains variability in clinical outcomes. For TMS, stimulation locations and protocol information are spatially modeled to characterize cortical electric-field exposure and identify brain regions where stimulation is associated with stronger therapeutic effects.

<br><br>
By transforming stimulation parameters reported across heterogeneous studies into <strong>quantitative, spatially resolved brain-level predictors</strong>, meta-modeling adds a mechanistic and spatial dimension to traditional evidence synthesis. This framework can help identify candidate therapeutic targets, investigate sources of between-study heterogeneity, compare stimulation strategies, and generate data-driven hypotheses for future precision neuromodulation trials.

<br><br>
📄 <strong>Electrical stimulation meta-modeling:</strong> <a href="https://www.sciencedirect.com/science/article/pii/S0149763426002150" target="_blank" rel="noopener">Read the paper</a> <br>
📄 <strong>TMS meta-modeling:</strong> <a href="https://www.sciencedirect.com/science/article/pii/S2451902226002090" target="_blank" rel="noopener">Read the paper</a>

</p>

---

### High School Students Summer Program (Step-by-Step Learning)
<a href="/divider-final-05.jpg" target="_blank"> 
  <img src="/divider-final-05.jpg" alt="High School Students Summer Program" width="200" style="border-radius: 10px; margin-bottom: 10px;"> 
</a>  
<p> 
  The High School Students Summer Program is a <strong>guided, step-by-step learning journey</strong>. Over the course of 6–8 weeks, participants move through carefully designed modules that build on one another. Each module provides clear goals, short tutorials, checklists, and small hands-on tasks. By the end of the program, students will have completed a mini-capstone neuroimaging-neuromodulation project and presented their work in a short talk and one-page summary. 
  <br><br> 
  🧰 <strong>Please visit the <a href="https://soleimanighazaleh.github.io/High-School-Students/" target="_blank" rel="noopener">program website</a> to access the whole package.</strong> 
</p>
