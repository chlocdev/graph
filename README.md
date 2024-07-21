# graph data

# guides

- Check if PyTorch is installed with CUDA support:

        python -c "import torch; print(torch.cuda.is_available())"
        >>> True

- Verify that nvcc is accessible from terminal:

        nvcc --version
        >>> 11.8

- Ensure that PyTorch and system CUDA versions match:

        python -c "import torch; print(torch.version.cuda)"
        >>> 11.8

        nvcc --version
        >>> 11.8

# references

https://networkx.org/

https://pytorch-geometric.readthedocs.io/en/latest/

https://pytorch-geometric.readthedocs.io/en/latest/get_started/colabs.html#official-examples

https://github.com/pyg-team/pytorch_geometric/tree/master

https://sites.math.rutgers.edu/~ajl213/CLRS/CLRS.html

[Stanford CS224W: Machine Learning with Graphs | 2021](https://www.youtube.com/watch?v=JAB_plj2rbA&list=PLoROMvodv4rOP-ImU-O1rYRg2RFxomvFp)

https://github.com/luciusssss/CS224W-Colab/tree/main

https://microsoft.github.io/graphrag/posts/get_started/

https://neo4j.com/docs/getting-started/