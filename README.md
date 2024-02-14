# Machine-learning-based models in particle-in-cell codes for advanced physics extensions

Author of this repository: [Óscar Amaro](https://github.com/OsAmaro) (Feb 2024)

Authors of paper: [Chiara Badiali](https://github.com/chiarabadiali), [Pablo J. Bilbao](https://github.com/pabilbado), [Fábio Cruz](https://github.com/fabiocruz), Luis O. Silva

Link to paper: https://www.cambridge.org/core/journals/journal-of-plasma-physics/article/abs/machinelearningbased-models-in-particleincell-codes-for-advanced-physics-extensions/9D34BB83508AF220EC60EF892079D053

Pre-print: https://arxiv.org/abs/2206.02937

Abstract: _In this paper we propose a methodology for the efficient implementation of Machine Learning (ML)-based methods in particle-in-cell (PIC) codes, with a focus on Monte-Carlo or statistical extensions to the PIC algorithm. The presented approach allows for neural networks to be developed in a Python environment, where advanced ML tools are readily available to proficiently train and test them. Those models are then efficiently deployed within highly-scalable and fully parallelized PIC simulations during runtime. We demonstrate this methodology with a proof-of-concept implementation within the PIC code OSIRIS, where a fully-connected neural network is used to replace a section of a Compton scattering module. We demonstrate that the ML-based method reproduces the results obtained with the conventional method and achieves better computational performance. These results offer a promising avenue for future applications of ML-based methods in PIC, particularly for physics extensions where an ML-based approach can provide a higher performance increase._

Notes:

- OSIRIS simulations shown here were run with the Compton-ML branch described in this [paper](https://www.cambridge.org/core/journals/journal-of-plasma-physics/article/abs/machinelearningbased-models-in-particleincell-codes-for-advanced-physics-extensions/9D34BB83508AF220EC60EF892079D053
). To know more about the Osiris Consortium see [here](https://epp.tecnico.ulisboa.pt/osiris/)

- OSIRIS simulation data shown in the notebooks can be downloaded [here](https://ulisboa-my.sharepoint.com/:u:/r/personal/ist187343_tecnico_ulisboa_pt/Documents/RePlasmaShare/BadialiBilbao2022JPP_osiris_data.zip?csf=1&web=1&e=giceI2) (~240Mb compressed, ~920Mb uncompressed)
