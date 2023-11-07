# Trusting the Explainers

This repository is the official implementation of the LAK 2023 paper entitled ["Trusting the Explainers: XAI for Course Design"](https://arxiv.org/abs/2212.08955) written by [Vinitra Swamy](http://vinitra.github.io), [Skye (Sijia) Du](https://github.com/Skye-Du), [Mirko Marras](https://www.mirkomarras.com/), and [Tanja Käser](https://people.epfl.ch/tanja.kaeser/?lang=en).

Experiments are located in `scripts/`, corresponding directly to the experimental methodology mentioned in the paper. User study materials used to conduct the 26 semi-structured expert interviews with STEM professors are located in `study/`. 

## Project overview

Our goal is to validate explainers for student success prediction across controlled differences in online and blended learning course design. Our analyses cover five course pairs that differ in one educationally relevant aspect and two popular instance-based explainable AI methods (LIME and SHAP). We quantitatively compare the distances between the explanations across courses and methods, then validate the explanations of LIME and SHAP with 26 semi-structured interviews of university-level educators regarding which features they believe contribute most to student success, which explanations they trust most, and how they could transform these insights into actionable course design decisions. Our results show that quantitatively, explainers significantly disagree with each other about what is important, and qualitatively, experts themselves do not agree on which explanations are most trustworthy. 

This project started in the ML4ED laboratory at EPFL in February 2022 as a continuation of work from our EDM 2022 paper [Evaluating the Explainers](http://github.com/epfl-ml4ed/evaluating-explaienrs) and has recieved **a honorable mention** at [LAK 2023](https://www.solaresearch.org/events/lak/lak23/). 

## Contributing 

This code is provided for educational purposes and aims to facilitate reproduction of our results, and further research 
in this direction. We have done our best to document, refactor, and test the code before publication.

If you find any bugs or would like to contribute new models, training protocols, etc, please let us know. Feel free to file issues and pull requests on the repo and we will address them as we can.

## Citations
If you find this code useful in your work, please cite our paper:

```
Swamy, V., Du, S., Marras, M., Käser, T. (2023). 
Trusting the Explainers: Teacher Validation of Explainable Artificial Intelligence for Course Design. 
In: Proceedings of the 13th International Learning Analytics and Knowledge Conference (LAK 2023).
```

## License
This code is free software: you can redistribute it and/or modify it under the terms of the [MIT License](LICENSE).

This software is distributed in the hope that it will be useful, but without any warranty; without even the implied warranty of merchantability or fitness for a particular purpose. See the [MIT License](LICENSE) for details.
