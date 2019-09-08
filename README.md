# Graph-Attention-Networks-GAT
This is a Tensorflow 2.0 implementation of the Graph Attention Network (GAT) model by Veličković et al. (2017, [[arXiv link]](https://arxiv.org/abs/1710.10903)).

## Acknowledgements
I have no affiliation with the authors of the paper and I am implementing this code for non-commercial, educational purposes.  
The authors published their [reference Tensorflow implementation here](https://github.com/PetarV-/GAT), so check it out for something that is guaranteed to work as intended. 

You should cite the paper if you use any of this code for your research:
```
@article{
  velickovic2018graph,
  title="{Graph Attention Networks}",
  author={Veli{\v{c}}kovi{\'{c}}, Petar and Cucurull, Guillem and Casanova, Arantxa and Romero, Adriana and Li{\`{o}}, Pietro and Bengio, Yoshua},
  journal={International Conference on Learning Representations},
  year={2018},
  url={https://openreview.net/forum?id=rJXMpikCZ},
  note={Accepted as poster},
}
```

I also copied the code in `utils.py` almost verbatim from [this repo by Thomas Kipf](https://github.com/tkipf/gcn), who I thank sincerely for sharing his work on GCNs and GAEs.

## Disclaimer
I do not own any rights to the datasets distributed with this code, but they are publicly available at the following links:

- CORA: [https://relational.fit.cvut.cz/dataset/CORA](https://relational.fit.cvut.cz/dataset/CORA)
- PubMed: [https://catalog.data.gov/dataset/pubmed](https://catalog.data.gov/dataset/pubmed)
- CiteSeer: [http://csxstatic.ist.psu.edu/about/data](http://csxstatic.ist.psu.edu/about/data)

## Previewing
Run Tensorflow_2_0_Graph_Attention_Networks_(GAT).ipynb

In the colab sheet, you can choose to run different datasets and modify the training properties of the Graph Attention Networks
