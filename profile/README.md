# Interactive Neural Cellular Automata for Game Level Generation 🎮

This organisation groups all the code and repositories used for our Bachelor thesis in Data Science (Spring 2023) at IT University of Copenhagen.

It contains three main repositories:

- (control_pcgnca)[https://github.com/Interactive-NCA/control-pcgnca/tree/main/pcgnca/evo]
This repository represent the main Interactive Neural Cellular Automata (INCA) library. 

- (Web UI Frontend)[https://github.com/Interactive-NCA/web-ui]
Code for the interactive user interface developed as a qualitative experimentation platform to try our proposed system and compare and test the main experiments that we have conducted. The web application is being currently hosted at (www.zeldalevelcraft.com)[https://www.zeldalevelcraft.com)

- (Backend)[https://github.com/Interactive-NCA/nca-backend]
Uses the INCA library to define endpoints which the web UI depends on. This backend can be furthermore used as a general API for NCA models
and can be used to develop similar interfaces as the one proposed in our work.

## Abstract 

In this work we investigate the application of Interactive Neural Cellular Automata
(INCA) in the context of Mixed-Initiative Content Creation (MI-CC), specifically fo-
cusing on automating game level design for The Legend of Zelda. Procedural Content
Generation (PCG) methods based on Cellular Automata often restrict users to limited
control over the generated content. To overcome this limitation, we have developed a
system that empowers users with the ability to fix certain tiles to specific types while
the rest of the level is grown through an evolved Neural Cellular Automata (NCA)
model. Furthermore, the system enables users to select a model from a trained archive
of NCA models. This innovative system produces a diverse range of specialized level
generators capable of creating engaging game levels that consider both the specific
level characteristics and the fixed tiles set by the user. Our experiments demonstrate
that models trained on specific fixed tiles substantially outperform a baseline model
trained with no user input in mind. However, the task of training models to handle a
mix of fixed tile types remains a challenge, underscoring the need for further improve-
ments in our proposed model training strategies. Apart from the proposed system, we
have also developed an experimental platform for testing the approach. We hope that
this work can serve as a useful basis for researchers working with INCAs and provide
a good starting point for future work in further research using NCAs for MI-CC.
1
