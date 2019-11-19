# Scene Boundary Extraction Tool
This tool extracts the point where the transition happens, which will be easier for developer to extract the main 
image (shot) from each scene for further analysis. I have used [TransNet: A deep network for fast detection of common shot transitions.](https://arxiv.org/abs/1906.03363)
, and I have added automatic threshold detection algorithm for more convenient usage. 

You can open up test.ipynb and see how it actually works.


# Citing
    @article{soucek2019transnet,
        title={TransNet: A deep network for fast detection of common shot transitions},
        author={Sou{\v{c}}ek, Tom{\'a}{\v{s}} and Moravec, Jaroslav and Loko{\v{c}}, Jakub},
        journal={arXiv preprint arXiv:1906.03363},
        year={2019}
    }
    
