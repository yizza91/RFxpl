# RFxpl
Random Forests eXplainer with SAT


### Usage:


* Print the Usage:

<code>$> ./RFxp.py -h </code>

* Train an RF model:

<code>$> ./RFxp.py -d 4 -n 100  -t ./datasets/iris/iris.csv </code>

* Compute an explanation:

<code>$> ./RFxp.py -X abd -x '5.4,3.0,4.5,1.5' ./Classifiers/iris/iris_nbestim_100_maxdepth_4.mod.pkl </code>


## Citations

Please cite the following paper when you use this work:

```
@inproceedings{ims-ijcai21,
  author       = {Yacine Izza and
                  Jo{\~{a}}o Marques{-}Silva},
  editor       = {Zhi{-}Hua Zhou},
  title        = {On Explaining Random Forests with {SAT}},
  booktitle    = {Proceedings of the Thirtieth International Joint Conference on Artificial
                  Intelligence, {IJCAI} 2021, Virtual Event / Montreal, Canada, 19-27
                  August 2021},
  pages        = {2584--2591},
  publisher    = {ijcai.org},
  year         = {2021},
  url          = {https://doi.org/10.24963/ijcai.2021/356},
  doi          = {10.24963/ijcai.2021/356},
  timestamp    = {Wed, 25 Aug 2021 17:11:16 +0200},
  biburl       = {https://dblp.org/rec/conf/ijcai/Izza021.bib},
  bibsource    = {dblp computer science bibliography, https://dblp.org}
}

```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.