# IGX Portable
### Pure Data patches for microtonal and algorithmic composition.

Patches are created in a Linux version of PD-Extended and 
should work in extended versions of all platforms.

Module patches are divided more or less into five categories:

* **main-** modules include tuning systems and metronomes. All other modules require at least one main module to be open to work.
* **seq-** modules include various note generators and sequencers, some have synthesizers too.
* **synth-**  modules are sound generators from synthesizers to samplers that get their input from seq and main modules.
* **drummer-** modules have algorithmic beat sequencers and sample players that get their input from main modules.
* **instrument**- modules are sound generators which get their input from external midi messages.

Modules connect more or less to each other with [s xxx] and [r xxx] lines.  
Most modules with audio outputs are designed to have pd in multiple output mode (using Jack).   
