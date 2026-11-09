Milestone status: What did you complete for the beta from your original plan? What did you not complete? What did you do that was not part of your original plan?


Surprises and challenges: What challenges and surprises did you encounter that affected your ability to progress according to plan?
- One challenge we encountered was that the resonators were initially sounding too pitched like tones instead of rock resonances. We found that adding more modes closer together in frequency counteracted this and produced a more natural sound, because the partials blurred together rather than standing out individually.

Design and concept changes: Has your work thus far caused you to reassess any of your original concept, goals, deliverables, etc.? If so, explain what has changed and why.
- While adjusting parameters of the brittle resonator to get closer to the sound we wanted, we added some sliders for attack, decay, and cutoff frequency. We're thinking about expanding this approach so that users could control the entire patch through UI elements, with more options for parameters in addition to depth.

Technical changes: Has your work thus far caused you to reassess any elements of your technical toolset? If so, explain what has changed and why.
- For the brittle resonator, we switched from Pd’s bandpass filter to a biquad filter which let us set each mode's decay directly through its pole radius, independent of frequency. This required calculating the filter coefficients, for which we used an abstraction. We also normalize these coefficients to keep mode levels consistent.

Remaining work: What are your "must-complete" tasks between now and the final version? What are your "stretch" goals that you will complete if time allows? Which group member is taking the lead on each item?
- A stretch goal could be incorporating additional control parameters to allow the user to shape the sound in more ways.

  
Collaboration: Have you encountered any challenges in working effectively as a group? Has everyone in the group made equal contributions? Explain any challenges, as well as any discrepancies in level of contribution from group members.
