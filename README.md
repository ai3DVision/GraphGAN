## GraphGAN

- This is the implementation of [AAAI2018. GraphGAN](https://hwwang55.github.io/files/2018-AAAI-GraphGAN.pdf)



#### code structure

- data : includes the graph file

- pre_train : includes the pre_train embeddings file that generated by other methods, such as deepwalk, SDNE, LINE, since gan is difficult to be trained. 

- results : includes the evaluation results, you can see the results improving with the training progressing.

- src : includes the source codes

  ​

#### requirements:

- tensorflow
- tqdm(display the running progress)


#### data

undirected graph whose file format is as follows(from 0 to N(number of nodes)):

0	1

3	2

...

#### Run

```cd src/GraphGAN```

```python graph_gan.py```

