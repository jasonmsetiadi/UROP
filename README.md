## UROP
In this project, I explored three different active learning methods ,namely Variance Minimization (V-Opt)[4], Error Bounds Minimization[5], and Sampling Theory for Graph Signals[6], on a semi-supervised learning framework[2][3][4] to see if they perform better than random sampling. We tested our experiments on a toy dataset of 8 gaussian clusters forming a circle. We discovered that active learning is indeed much better than random sampling because it chooses the most optimal points to label first which are the centers of the clusters. Therefore, active learning is worth trying on semi-supervised learning frameworks. However, I also encounter some difficulties when implementing Error Bounds Minimization because there is some mathematical derivation error on the paper that causes it to be similar to V-Opt. On the other hand, Sampling Theory for Graph Signals works but is not scalable for larger real-world datasets.

## References

[1] jwcalder, GraphLearning, (2020), GitHub repository, https://github.com/jwcalder/GraphLearning

[2] X. Zhu, Z. Ghahramani, and J. Lafferty, “Semi-supervised learning
using Gaussian fields and harmonic functions,” in Proceedings of the
Twentieth International Conference on International Conference on
Machine Learning, ser. ICML’03. AAAI Press, 2003, p. 912–919.

[3] J. Calder, B. Cook, M. Thorpe, and D. Slepˇcev, “Poisson learning:
Graph based semi-supervised learning at very low label rates,” in 37th
International Conference on Machine Learning, ICML 2020, ser. 37th
International Conference on Machine Learning, ICML 2020, H. Daume
and A. Singh, Eds. International Machine Learning Society (IMLS),
2020, pp. 1283–1293.

[4] M. Ji and J. Han, “A variance minimization criterion to active learning on graphs,” in Proceedings of the Fifteenth International Conference on Artificial Intelligence and Statistics, ser. Proceedings of Machine Learning Research, N. D. Lawrence and M. Girolami, Eds., vol. 22. La Palma, Canary Islands: PMLR, 21–23 Apr 2012, pp. 556–564. [Online]. Available: http://proceedings.mlr.press/v22/ji12.html

[5] Q. Gu and J. Han. Towards active learning on graphs: An error bound minimization approach. In 2012 IEEE 12th
International Conference on Data Mining, pages 882–887, 2012.

[6] A. Gadde, A. Anis, and A. Ortega. Active semi-supervised learning using sampling theory for graph signals. In Proceedings of the 20th ACM SIGKDD International Conference on Knowledge Discovery and Data Mining, page
492–501, New York, NY, USA, 2014. Association for Computing Machinery.

