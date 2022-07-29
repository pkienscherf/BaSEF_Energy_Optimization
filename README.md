# BaSEF Summer School
## Mathematical Optimization and Applications in Energy Economics
Hands-on examples for the BaSEF Summer School

### Background
The aim of the summer school within the university cooperation BaSEF (Building a Sustainable Energy Future) is to bring together renowned scientists and young researchers in the field of energy and environmental economics to discuss research advances and relevant policy issues. The program emphasizes cross-cultural scientific interaction and exchange of ideas. It operates at the intersection of methodological knowledge transfer and applied research to equip participants with the essential skills they need for a successful energy transition to sustainability. We cover a broad range of topics to paint a holistic picture of current global challenges in the energy sector, with a particular focus on the energy transition in Germany and the opportunities and challenges for North Africa, especially Egypt. In this way, we want to stimulate new research ideas and give young researchers the opportunity to build a global network.

To ensure continuity in joint research between Egypt and Germany, another Winter School will be held in Egypt in the winter semester 2022/2023.

### This course
This repository complements a lecture on the basics of mathemetical optimization held during the summer school. To bring that theory into application, we will use the discussed techniques to address questions coming up in in typical energy economics settings. 

### What you will need
We will use the Julia programming language (open-source, available here: https://julialang.org/downloads/) and the open-source HiGHS solver (will be downloaded automatically, but for further information look here: https://highs.dev/), alongside some other packages (mainly for data manipulation). We assume that most (if not all) of you are new to Julia, we will therefore give a brief introduction on the basics of the programming language. If you have familiarity with any scripting language (Python, R, Matlab, etc.) and/or have worked with Jupyter notebooks before, you should have no problems at all. If not, we will try our best to provide you an intuition of how programming techniques may complemenent your skillset to address a broader set of research questions.

#### Installing Julia
Please follow the instructions here: https://julialang.org/downloads/ to download the latest stable release of Julia. If there are any issues with the installation, please familiarize yourself with the help provided for your operating system. After installation, you should be able to start Julia for the first time, looking something like this:

![image](https://user-images.githubusercontent.com/44019953/181731459-5bc807a6-d4dc-4b8e-be26-e9d928c80e43.png)

What you are seeing is the so-called REPL (read–eval–print loop), sort of an interactive session for very quick prototyping (you may try to type in `5+5` and return, to see what happens?). As working in such environment does not yield reproducible results, we will use a slightly more advanced programming environment.

#### Juypter Notebooks
Jupyter notebooks (see https://jupyter.org/, ignore installation instructions) are an development environment suitable for quick prototyping and steap learning curves -- so they are perfect for us! To use them, we have to install a package to our Julia 
