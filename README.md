# Machine Learning Reading List

## Bayesian Inference
### Monte Carlo methods
* MacKay, David JC. "Introduction to monte carlo methods." Learning in graphical models. Springer, Dordrecht, 1998. 175-204. [[pdf]](http://www.inference.org.uk/mackay/erice.pdf)
* Neal, Radford M. "Probabilistic inference using Markov chain Monte Carlo methods." (1993). [[pdf]](http://www.cs.toronto.edu/~radford/ftp/review.pdf)


## Topic Model
* pLSI - Hofmann, Thomas. "Probabilistic latent semantic analysis." Proceedings of the Fifteenth conference on Uncertainty in artificial intelligence. Morgan Kaufmann Publishers Inc., 1999. [[pdf]](https://arxiv.org/pdf/1301.6705.pdf)
* LDA - Blei, David M., Andrew Y. Ng, and Michael I. Jordan. "Latent dirichlet allocation." Journal of machine Learning research 3.Jan (2003): 993-1022. [[pdf]](http://www.jmlr.org/papers/volume3/blei03a/blei03a.pdf) [[code]](https://github.com/blei-lab/lda-c)
* DTM - Blei, David M., and John D. Lafferty. "Dynamic topic models." Proceedings of the 23rd international conference on Machine learning. ACM, 2006. [[pdf]](http://www.cs.columbia.edu/~blei/papers/BleiLafferty2006a.pdf) [[code]](https://github.com/blei-lab/dtm)

## Deep Learning
### General
* Bengio, Yoshua. "Learning deep architectures for AI." Foundations and trends® in Machine Learning 2.1 (2009): 1-127. [[pdf]](https://www.iro.umontreal.ca/~bengioy/papers/ftml_book.pdf)
* Glorot, Xavier, and Yoshua Bengio. "Understanding the difficulty of training deep feedforward neural networks." Proceedings of the thirteenth international conference on artificial intelligence and statistics. 2010. [[pdf]](http://proceedings.mlr.press/v9/glorot10a/glorot10a.pdf)
* Schmidhuber, Jürgen. "Deep learning in neural networks: An overview." Neural networks 61 (2015): 85-117. [[pdf]](https://arxiv.org/pdf/1404.7828.pdf)
### CNN
* CNN - LeCun, Yann, et al. "Gradient-based learning applied to document recognition." Proceedings of the IEEE 86.11 (1998): 2278-2324. [[pdf]](http://yann.lecun.com/exdb/publis/pdf/lecun-98.pdf)
* AlexNet - Krizhevsky, Alex, Ilya Sutskever, and Geoffrey E. Hinton. "Imagenet classification with deep convolutional neural networks." Advances in neural information processing systems. 2012. [[pdf]](https://papers.nips.cc/paper/4824-imagenet-classification-with-deep-convolutional-neural-networks)
* VGG-16 - Simonyan, Karen, and Andrew Zisserman. "Very deep convolutional networks for large-scale image recognition." arXiv preprint arXiv:1409.1556 (2014). [[pdf]](https://arxiv.org/pdf/1409.1556.pdf)
* ResNet - He, Kaiming, et al. "Deep residual learning for image recognition." Proceedings of the IEEE conference on computer vision and pattern recognition. 2016. [[pdf]](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)
* Inception - Szegedy, Christian, et al. "Going deeper with convolutions." Proceedings of the IEEE conference on computer vision and pattern recognition. 2015. [[pdf]](https://arxiv.org/pdf/1409.4842.pdf)
### RNN
* LSTM - Hochreiter, Sepp, and Jürgen Schmidhuber. "Long short-term memory." Neural computation 9.8 (1997): 1735-1780. [[pdf]](https://www.bioinf.jku.at/publications/older/2604.pdf)
* GRU - Cho, Kyunghyun, et al. "On the properties of neural machine translation: Encoder-decoder approaches." arXiv preprint arXiv:1409.1259 (2014). [[pdf]](https://arxiv.org/pdf/1409.1259.pdf)
* GRU - Chung, Junyoung, et al. "Empirical evaluation of gated recurrent neural networks on sequence modeling." arXiv preprint arXiv:1412.3555 (2014). [[pdf]](https://arxiv.org/pdf/1412.3555.pdf)
### Optimization
* Natural gradient - Amari, Shun-Ichi. "Natural gradient works efficiently in learning." Neural computation 10.2 (1998): 251-276.
* Nemirovski, Arkadi, et al. "Robust stochastic approximation approach to stochastic programming." SIAM Journal on optimization 19.4 (2009): 1574-1609. [[pdf]](https://www2.isye.gatech.edu/~nemirovs/SIOPT_RSA_2009.pdf)
* Xavier initialization - Glorot, Xavier, and Yoshua Bengio. "Understanding the difficulty of training deep feedforward neural networks." Proceedings of the thirteenth international conference on artificial intelligence and statistics. 2010. [[pdf]](http://proceedings.mlr.press/v9/glorot10a/glorot10a.pdf)
* Hessian free - Martens, James. "Deep learning via Hessian-free optimization." ICML. Vol. 27. 2010. [[pdf]](http://www.cs.toronto.edu/~jmartens/docs/Deep_HessianFree.pdf)
* Adagrad - Duchi, J., Hazan, E. and Singer, Y., 2011. Adaptive subgradient methods for online learning and stochastic optimization. Journal of Machine Learning Research, 12(Jul), pp.2121-2159. [[pdf]](http://www.jmlr.org/papers/volume12/duchi11a/duchi11a.pdf)
* Natural gradient - Pascanu, Razvan, and Yoshua Bengio. "Revisiting natural gradient for deep networks." arXiv preprint arXiv:1301.3584 (2013). [[pdf]](https://arxiv.org/pdf/1301.3584.pdf)
* He initialization - He, Kaiming, et al. "Delving deep into rectifiers: Surpassing human-level performance on imagenet classification." Proceedings of the IEEE international conference on computer vision. 2015. [[pdf]](https://arxiv.org/pdf/1502.01852.pdf)
* Kfac - Martens, James, and Roger Grosse. "Optimizing neural networks with kronecker-factored approximate curvature." International conference on machine learning. 2015. [[pdf]](https://arxiv.org/pdf/1503.05671.pdf)
* momentum - Sutskever, Ilya, et al. "On the importance of initialization and momentum in deep learning." International conference on machine learning (ICML). 2013. [[pdf]](http://www.jmlr.org/proceedings/papers/v28/sutskever13.pdf)[[supp]](http://proceedings.mlr.press/v28/sutskever13-supp.pdf)
* Adam - Kingma, Diederik P., and Jimmy Ba. "Adam: A method for stochastic optimization." arXiv preprint arXiv:1412.6980 (2014). [[pdf]](https://arxiv.org/pdf/1412.6980.pdf)
* dropout - Srivastava, Nitish, et al. "Dropout: a simple way to prevent neural networks from overfitting." The Journal of Machine Learning Research 15.1 (2014): 1929-1958. [[pdf]](http://jmlr.org/papers/volume15/srivastava14a/srivastava14a.pdf)
* Batch normalization - Ioffe, Sergey, and Christian Szegedy. "Batch normalization: Accelerating deep network training by reducing internal covariate shift." arXiv preprint arXiv:1502.03167 (2015).[[pdf]](https://arxiv.org/pdf/1502.03167.pdf)
* Bottou, Léon, Frank E. Curtis, and Jorge Nocedal. "Optimization methods for large-scale machine learning." SIAM Review 60.2 (2018): 223-311. [[pdf]](https://arxiv.org/pdf/1606.04838.pdf)
### Generative Model 
* CD - Carreira-Perpinan, Miguel A., and Geoffrey E. Hinton. "On contrastive divergence learning." Aistats. Vol. 10. 2005. [[pdf]](http://www.cs.toronto.edu/~fritz/absps/cdmiguel.pdf)
* CD-k - Hinton, Geoffrey E. "Training products of experts by minimizing contrastive divergence." Neural computation 14.8 (2002): 1771-1800. [[pdf]](http://www.cs.toronto.edu/~fritz/absps/tr00-004.pdf)
* Deep belief nets - Hinton, Geoffrey E., Simon Osindero, and Yee-Whye Teh. "A fast learning algorithm for deep belief nets." Neural computation 18.7 (2006): 1527-1554. [[pdf]](https://www.cs.toronto.edu/~hinton/absps/fastnc.pdf)
* Tieleman, Tijmen. "Training restricted Boltzmann machines using approximations to the likelihood gradient." Proceedings of the 25th international conference on Machine learning. ACM, 2008. [[pdf]](http://icml2008.cs.helsinki.fi/papers/638.pdf)
* DBM - Salakhutdinov, R. & Hinton, G.. (2009). Deep Boltzmann Machines. Proceedings of the Twelth International Conference on Artificial Intelligence and Statistics, in PMLR 5:448-455 [[pdf]](http://proceedings.mlr.press/v5/salakhutdinov09a/salakhutdinov09a.pdf)
* Rep SoftMax - Hinton, G.E. and Salakhutdinov, R.R., 2009. Replicated softmax: an undirected topic model. In Advances in neural information processing systems (pp. 1607-1614). [[pdf]](http://www.cs.toronto.edu/~fritz/absps/repsoft.pdf)
* Variational Autoencoder (VAE) - Kingma, Diederik P., and Max Welling. "Auto-encoding variational bayes." arXiv preprint arXiv:1312.6114 (2013). [[pdf]](https://arxiv.org/pdf/1312.6114.pdf)
* GANs - Goodfellow, Ian, et al. "Generative adversarial nets." Advances in neural information processing systems. 2014. [[pdf]](https://papers.nips.cc/paper/5423-generative-adversarial-nets.pdf) [[code]](https://github.com/goodfeli/adversarial)
* Salakhutdinov, R. (2015). Learning deep generative models. Annual Review of Statistics and Its Application, 2, 361-385. [[pdf]](https://www.cs.cmu.edu/~rsalakhu/papers/annrev.pdf)
## NLP
### Word Embedding
* Bengio, Yoshua, et al. "A neural probabilistic language model." Journal of machine learning research 3.Feb (2003): 1137-1155. [[pdf]](http://www.jmlr.org/papers/volume3/bengio03a/bengio03a.pdf)
* t-SNE - Maaten, Laurens van der, and Geoffrey Hinton. "Visualizing data using t-SNE." Journal of machine learning research 9.Nov (2008): 2579-2605. [[pdf]](http://www.jmlr.org/papers/volume9/vandermaaten08a/vandermaaten08a.pdf)
* word2vec - Mikolov, Tomas, et al. "Efficient estimation of word representations in vector space." arXiv preprint arXiv:1301.3781 (2013). [[pdf]](https://arxiv.org/pdf/1301.3781.pdf)
* word2vec - Mikolov, Tomas, et al. "Distributed representations of words and phrases and their compositionality." Advances in neural information processing systems. 2013. [[pdf]](https://papers.nips.cc/paper/5021-distributed-representations-of-words-and-phrases-and-their-compositionality.pdf)
* doc2vec - Le, Quoc, and Tomas Mikolov. "Distributed representations of sentences and documents." International Conference on Machine Learning. 2014. [[pdf]](https://arxiv.org/pdf/1405.4053v2.pdf)
* GloVe - Pennington, Jeffrey, Richard Socher, and Christopher Manning. "Glove: Global vectors for word representation." Proceedings of the 2014 conference on empirical methods in natural language processing (EMNLP). 2014. [[pdf]](https://nlp.stanford.edu/pubs/glove.pdf) [[code]](https://github.com/stanfordnlp/GloVe)

### Machine Translation
* Attention - Bahdanau, Dzmitry, Kyunghyun Cho, and Yoshua Bengio. "Neural machine translation by jointly learning to align and translate." arXiv preprint arXiv:1409.0473 (2014). [[pdf]](https://arxiv.org/pdf/1409.0473.pdf)
* BERT - Devlin, J., Chang, M.W., Lee, K. and Toutanova, K., 2018. Bert: Pre-training of deep bidirectional transformers for language understanding. arXiv preprint arXiv:1810.04805. [[pdf]](https://arxiv.org/pdf/1810.04805.pdf)[[code]](https://github.com/google-research/bert)

## Recommendation System
* RBM - Salakhutdinov, Ruslan, Andriy Mnih, and Geoffrey Hinton. "Restricted Boltzmann machines for collaborative filtering." Proceedings of the 24th international conference on Machine learning. ACM, 2007. [[pdf]](https://www.cs.toronto.edu/~rsalakhu/papers/rbmcf.pdf)
* PMF - Mnih, Andriy, and Ruslan R. Salakhutdinov. "Probabilistic matrix factorization." Advances in neural information processing systems. 2008. [[pdf]](https://papers.nips.cc/paper/3208-probabilistic-matrix-factorization.pdf)
