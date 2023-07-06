```
                        _____      _                      _   _             _   _ _____   ___  
                       |_   _|    | |                    | | (_)           | \ | /  __ \ / _ \ 
                         | | _ __ | |_ ___ _ __ __ _  ___| |_ ___   _____  |  \| | /  \// /_\ \
                         | || '_ \| __/ _ \ '__/ _` |/ __| __| \ \ / / _ \ | . ` | |    |  _  |
                        _| || | | | ||  __/ | | (_| | (__| |_| |\ V /  __/ | |\  | \__/\| | | |
                        \___/_| |_|\__\___|_|  \__,_|\___|\__|_| \_/ \___| \_| \_/\____/\_| |_/                                                       
```
This organisation groups all the code and repositories used for our Bachelor thesis in Data Science (Spring 2023) at IT University of Copenhagen.
It contains three main repositories, **INCA library**, **NextJS Frontend** and a **FastAPI Backend**.

The system that the thesis proposes is illustrated below:
<p align="center">
<img src="https://github.com/Interactive-NCA/control-pcgnca/blob/main/assets/readme/training_overview_short.png" width="600">
</p>

### [control-pcgnca](https://github.com/Interactive-NCA/control-pcgnca/)
![Last commit](https://img.shields.io/github/last-commit/Interactive-NCA/control-pcgnca?style=flat-square)

This repository contains the code for the main **Interactive Neural Cellular Automata (INCA)** library. 

### [web-ui](https://github.com/Interactive-NCA/web-ui) 
[![Status](https://img.shields.io/website?style=flat-square&up_message=online&url=https%3A%2F%2Fwww.zeldalevelcraft.com)](https://www.zeldalevelcraft.com) 
![Last commit](https://img.shields.io/github/last-commit/Interactive-NCA/web-ui?style=flat-square)

Code for the interactive user interface developed as a qualitative experimentation platform to try our proposed system and compare and test the main experiments that we have conducted. The web application is being currently hosted at [www.zeldalevelcraft.com](https://www.zeldalevelcraft.com)

### [nca-backend](https://github.com/Interactive-NCA/nca-backend)
![Status](https://img.shields.io/website?style=flat-square&up_message=online&url=https%3A%2F%2Fnca-backend-rxv2teft2q-ew.a.run.app%2Fdocs) ![Last commit](https://img.shields.io/github/last-commit/Interactive-NCA/nca-backend?style=flat-square)

Uses the INCA library to define endpoints which the web UI depends on. This backend can be furthermore used as a general API for our INCA models
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










```
                                                        /@
                                         __        __   /\/
                                        /==\      /  \_/\/   
                                      /======\    \/\__ \__
                                    /==/\  /\==\    /\_|__ \
                                 /==/    ||    \=\ / / / /_/
                               /=/    /\ || /\   \=\/ /     
                            /===/   /   \||/   \   \===\
                          /===/   /_________________ \===\
                       /====/   / |                /  \====\
                     /====/   /   |  _________    /  \   \===\    THE LEGEND OF 
                     /==/   /     | /   /  \ / / /  __________\_____      ______       ___
                    |===| /       |/   /____/ / /   \   _____ |\   /      \   _ \      \  \
                     \==\             /\   / / /     | |  /= \| | |        | | \ \     / _ \
                     \===\__    \    /  \ / / /   /  | | /===/  | |        | |  \ \   / / \ \
                       \==\ \    \\ /____/   /_\ //  | |_____/| | |        | |   | | / /___\ \
                       \===\ \   \\\\\\\/   /////// /|  _____ | | |        | |   | | |  ___  |
                         \==\/     \\\\/ / //////   \| |/==/ \| | |        | |   | | | /   \ |
                         \==\     _ \\/ / /////    _ | |==/     | |        | |  / /  | |   | |
                           \==\  / \ / / ///      /|\| |_____/| | |_____/| | |_/ /   | |   | |
                           \==\ /   / / /________/ |/_________|/_________|/_____/   /___\ /___\
                             \==\  /               | /==/
                             \=\  /________________|/=/   
                               \==\     _____     /==/ 
                              / \===\   \   /   /===/
                             / / /\===\  \_/  /===/
                            / / /   \====\ /====/
                           / / /      \===|===/
                           |/_/         \===/
                                          =

```
