# :mag: Awesome Vector Database [![Awesome](https://cdn.jsdelivr.net/gh/sindresorhus/awesome@d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
A curated list of awesome works related to high dimensional structure/vector search &amp; database 

# Services
- [Google Vector Search (Vertex AI)](https://cloud.google.com/vertex-ai/docs/vector-search/overview)
- [Pinecone](https://www.pinecone.io/)
- [Weaviate](https://github.com/weaviate/weaviate) [[Beginner Guide](https://towardsdatascience.com/getting-started-with-weaviate-a-beginners-guide-to-search-with-vector-databases-14bbb9285839)]
- [Vespa](https://vespa.ai/)
- [txtai](https://github.com/neuml/txtai)
- [marqo](https://github.com/marqo-ai/marqo)
- [vectara](https://vectara.com)
- [Epsilla](https://epsilla.com/)
- [algolia](https://www.algolia.com/)
- [nucliadb](https://nuclia.com/vector-database/)
- [OpenSearch](https://opensearch.org/)
- [MyScale](https://myscale.com)
- [QdrantCloud](https://cloud.qdrant.io/)
- [zilliz](https://cloud.zilliz.com/signup)
- [OpenSearch's AlibabaCloud](https://www.alibabacloud.com/product/opensearch)
- [Typesense's Cloud](https://cloud.typesense.org)
- [MongoDB Atlas Vector Search](https://www.mongodb.com/products/platform/atlas-vector-search)
- [SuperDuperDB](https://github.com/SuperDuperDB/superduperdb)


## Comparisons
- [From Vespa](https://cloud.vespa.ai/feature-comparison.html)
- [Vector DB Comparison by VectorHub](https://vdbs.superlinked.com/)
  
# Libraries & Engines
## Multidimensional data / Vectors

- :star: 🥇 [Vector DB Feature Matrix](https://docs.google.com/spreadsheets/d/170HErOyOkLDjQfy3TJ6a3XXXM1rHvw_779Sit-KT7uc/edit#gid=0)
- :star: [Faiss](https://faiss.ai/) [Paper](https://arxiv.org/pdf/2401.08281.pdf)
- [Typesense](https://typesense.org/)
- [Qdrant](https://qdrant.tech/)
  - [Video tutorial](https://youtu.be/LRcZ9pbGnno), [Notebook](https://github.com/qdrant/examples/blob/master/qdrant_101_getting_started/getting_started.ipynb)
- [annoy](https://github.com/spotify/annoy)
- [NGT](https://github.com/yahoojapan/NGT)
- [pgvector](https://github.com/pgvector/pgvector)
- [Chroma](https://github.com/chroma-core/chroma)
- [LlamaIndex](https://github.com/jerryjliu/llama_index)
- [vectordb](https://github.com/epsilla-cloud/vectordb/tree/main)
- [jvector](https://github.com/jbellis/jvector)
- [RAFT](https://github.com/rapidsai/raft)
- [Vald](https://vald.vdaas.org/)
- [Voyager](https://github.com/spotify/voyager)
- [tinyvector](https://github.com/0hq/tinyvector)
- [USearch](https://github.com/unum-cloud/usearch)
- [vearch](https://vearch.github.io/)
- [MRPT](https://github.com/vioshyvo/mrpt)
- [milvus](https://milvus.io/)
- [infinity](https://github.com/infiniflow/infinity)
- [havenask](https://github.com/alibaba/havenask)

## Texts

- [PISA](https://github.com/pisa-engine/pisa)
- [Tantivy](https://github.com/quickwit-oss/tantivy)
- [sonic](https://github.com/valeriansaliou/sonic)

## Others
- [SimSIMD](https://github.com/ashvardanian/SimSIMD): Efficient Alternative to `scipy.spatial.distance` and `numpy.inner`

# Benchmarks & Databases

- [ANN Benchmarks](http://ann-benchmarks.com/) [[Paper](https://arxiv.org/pdf/1807.05614.pdf)].
- [Billion-scale ANNS Benchmarks](https://big-ann-benchmarks.com)
    - [2021 Result](https://proceedings.mlr.press/v176/simhadri22a/simhadri22a.pdf)
- [BEIR](https://github.com/beir-cellar/beir)
- [VectorDBBench - A Vector Database Benchmark Tool](https://zilliz.com/vector-database-benchmark-tool)
- [Qdrant's Vector Database Benchmarks](https://qdrant.tech/benchmarks/)
- [MyScale's Vector Database Benchmark](https://myscale.github.io/benchmark/#/benchmark)
- Li, Wen, et al. "[Approximate nearest neighbor search on high dimensional data—experiments, analyses, and improvement](https://arxiv.org/pdf/1610.02455.pdf)." IEEE Transactions on Knowledge and Data Engineering 32.8 (2019): 1475-1488.

# 📚 Books 
- [Foundations of Multidimensional and Metric Data Structures](https://www.amazon.com/Foundations-Multidimensional-Structures-Kaufmann-Computer/dp/0123694469/)
- [Introduction to Information Retrieval](https://nlp.stanford.edu/IR-book/information-retrieval-book.html)
- [Deep Learning for Search](https://www.manning.com/books/deep-learning-for-search)
- [Foundations of Vector Retrieval](https://arxiv.org/abs/2401.09350)

# Conferences & Workshops
- :star: [VLDB](https://vldb.org)
  - Tutorial:
    - New Trends in High-D Vector Similarity Search [[slides](https://vldb.org/2021/files/slides/tutorial/tutorial5.pdf), [video](https://www.youtube.com/watch?v=TFsrFwF0bC4&ab_channel=VLDB2021), [paper](https://echihabi.com/publications/tutorials/vldb2021-tutorial-summary.pdf)]
- :star: [Image Retrieval in the Wild (CVPR20)](https://matsui528.github.io/cvpr2020_tutorial_retrieval/) [[Video](https://www.youtube.com/watch?v=SKrHs03i08Q)]
- [Haystack](https://haystackconf.com)
- [Neural Search In Action](https://matsui528.github.io/cvpr2023_tutorial_neural_search/)
- ACM MM 2020: [Effective and Efficient: Toward Open-world Instance Re-identification](https://wangzwhu.github.io/home/acmmm2020_tutorial_reid.html)
  - Billion-scale Approximate Nearest Neighbor Search: [[Slides](https://wangzwhu.github.io/home/file/acmmm-t-part3-ann.pdf), [Video](https://www.youtube.com/watch?v=iI8e3kU11eU)]
  - Is instance search a solved problem? [[Slides](https://wangzwhu.github.io/home/file/acmmm-t-part4-ins.pdf), [Video](https://www.youtube.com/watch?v=cH256Zqt5Ms)]
- Retrieval Augmented Generation and Vespa [[Slides](https://docs.google.com/presentation/d/1LRAQfdT4UH69pgojNi_EMspSgsHn9YJVac_bbnhy038/edit#slide=id.p1)]
## Courses
- Long Term Memory in AI - Vector Search and Databases (COS 495 - Princeton) [[Class Notes](https://github.com/edoliberty/vector-search-class-notes)]

# Publications
## Survey
- :star: Pan, James Jie, Jianguo Wang, and Guoliang Li. "Survey of Vector Database Management Systems." arXiv preprint arXiv:2310.14021 (2023). [[Paper](https://arxiv.org/abs/2310.14021)]
- Nearest neighbor search: the old, the new, and the impossible. Andoni, Alexandr. [[Paper](https://dspace.mit.edu/bitstream/handle/1721.1/55090/587638612-MIT.pdf?sequence=2)]
## Quantization
![](https://raw.githubusercontent.com/wiki/facebookresearch/faiss/PQ_variants_Faiss_annotated.png)
Source: A survey of product quantization.

- :star: PQ: Product quantization for nearest neighbor search. Jegou, Herve, Matthijs Douze, and Cordelia Schmid. [[Paper](https://lear.inrialpes.fr/pubs/2011/JDS11/jegou_searching_with_quantization.pdf), [Code](https://github.com/facebookresearch/faiss), [Julia Code](https://github.com/una-dinosauria/Rayuela.jl), [nanopq](https://github.com/matsui528/nanopq)]
- :star: k-selection on GPU: Billion-scale similarity search with gpus. Johnson, Jeff, Matthijs Douze, and Hervé Jégou [[Paper](https://arxiv.org/pdf/1702.08734.pdf), [Code](https://github.com/facebookresearch/faiss)]
- :star: A survey of product quantization. Matsui, Yusuke, Yusuke Uchida, Hervé Jégou, and Shin'ichi Satoh [[Paper](https://www.jstage.jst.go.jp/article/mta/6/1/6_2/_pdf)]
- OPQ: Optimized Product Quantization. Ge, Tiezheng, Kaiming He, Qifa Ke, and Jian Sun [[Homepage](https://kaiminghe.github.io/cvpr13/index.html), [Paper](https://www.microsoft.com/en-us/research/wp-content/uploads/2013/11/pami13opq.pdf), [Code](https://kaiminghe.github.io/cvpr13/matlab_OPQ_release_v1.1.rar), [nanopq](https://github.com/matsui528/nanopq)]
- Quicker adc: Unlocking the hidden potential of product quantization with simd. André, Fabien, Anne-Marie Kermarrec, and Nicolas Le Scouarnec [[Paper](https://arxiv.org/pdf/1812.09162), [Code](https://github.com/technicolor-research/faiss-quickeradc)]
  - Accelerated nearest neighbor search with quick adc. André, Fabien, Anne-Marie Kermarrec, and Nicolas Le Scouarnec [[Paper](https://arxiv.org/pdf/1704.07355.pdf)].
  - Cache locality is not enough: High-performance nearest neighbor search with product quantization fast scan. Fabien André, Anne-Marie Kermarrec, Nicolas Le Scouarnec [[Paper](https://hal.inria.fr/hal-01239055/document)]
- ScaNN: Accelerating Large-Scale Inference with Anisotropic Vector Quantization. Guo, Ruiqi, Philip Sun, Erik Lindgren, Quan Geng, David Simcha, Felix Chern, and Sanjiv Kumar [[Paper](http://proceedings.mlr.press/v119/guo20h/guo20h.pdf), [Python/C++ Inference](https://github.com/google-research/google-research/tree/master/scann), [Julia Training/Inference](https://github.com/AxelvL/AHPQ.jl)]
- The inverted multi-index. Babenko, Artem, and Victor Lempitsky [[Paper](https://cmp.felk.cvut.cz/~toliageo/rg/papers/BabenkoLempitsky_PAMI2014_The%20Inverted%20Multi-Index.pdf), [Code](https://github.com/jatin7gupta/Product-Quantization)]
- Are We There Yet? Product Quantization and its Hardware Acceleration. Fernandez-Marques, Javier, Ahmed F. AbouElhamayed, Nicholas D. Lane, and Mohamed S. Abdelfattah. [[Paper](https://arxiv.org/pdf/2305.18334.pdf)]
- LibVQ: A Toolkit for Optimizing Vector Quantization and Efficient Neural Retrieval. Li, Chaofan, Zheng Liu, Shitao Xiao, Yingxia Shao, Defu Lian, and Zhao Cao. [[Paper](https://dl.acm.org/doi/10.1145/3539618.3591799), [Code](https://github.com/staoxiao/LibVQ/tree/demo)]
- Matsui, Yusuke, Ryota Hinami, and Shin'ichi Satoh. "Reconfigurable Inverted Index." Proceedings of the 26th ACM international conference on Multimedia. 2018. [[Paper](https://dl.acm.org/ft_gateway.cfm?id=3240630), [Project](https://yusukematsui.me/project/rii/), [Code](https://github.com/matsui528/rii)]
- Aguerrebere, Cecilia, et al. "[Similarity search in the blink of an eye with compressed indices.](https://arxiv.org/pdf/2304.04759.pdf)" arXiv preprint arXiv:2304.04759 (2023).
- Huijben, Iris, et al. "[Residual Quantization with Implicit Neural Codebooks](https://arxiv.org/pdf/2401.14732.pdf)." arXiv preprint arXiv:2401.14732 (2024). [[Code](https://github.com/facebookresearch/Qinco)]
- Rege, Aniket, et al. "[Adanns: A framework for adaptive semantic search](https://proceedings.neurips.cc/paper_files/paper/2023/file/f062da1973ac9ac61fc6d44dd7fa309f-Paper-Conference.pdf)." Advances in Neural Information Processing Systems 36 (2024).
- Amara, Kenza, et al. "[Nearest neighbor search with compact codes: A decoder perspective](https://arxiv.org/pdf/2112.09568)." Proceedings of the 2022 International Conference on Multimedia Retrieval. 2022.
- Krishnan, Aditya, and Edo Liberty. "[Projective Clustering Product Quantization](https://arxiv.org/pdf/2112.02179.pdf)." arXiv preprint arXiv:2112.02179 (2021).

## Graph-based Methods

- :star: Wang, Zeyu, et al. "[Graph-and Tree-based Indexes for High-dimensional Vector Similarity Search: Analyses, Comparisons, and Future Directions](https://helios2.mi.parisdescartes.fr/~themisp/publications/bulletin23.pdf)." Data Engineering (2023): 3-21.
- :star: A comprehensive survey and experimental comparison of graph-based approximate nearest neighbor search. Wang, Mengzhao, Xiaoliang Xu, Qiang Yue, and Yuxiang Wang. [[Paper](https://arxiv.org/pdf/2101.12631.pdf), [Code](https://github.com/Lsyhprum/WEAVESS)]
- :star: HNSW: Efficient and robust approximate nearest neighbor search using hierarchical navigable small world graphs. Malkov, Yu A., and Dmitry A. Yashunin. [[Paper](https://arxiv.org/pdf/1603.09320.pdf), [Code](https://github.com/nmslib/hnswlib)], [Rust Version](https://github.com/rust-cv/hnsw)
- Scaling Graph-Based ANNS Algorithms to Billion-Size Datasets: A Comparative Analysis. Dobson, Magdalen, Zheqi Shen, Guy E. Blelloch, Laxman Dhulipala, Yan Gu, Harsha Vardhan Simhadri, and Yihan Sun. [[Paper](https://arxiv.org/pdf/2305.04359.pdf)]
- FINGER: Fast Inference for Graph-based Approximate Nearest Neighbor Search. Chen, Patrick, Wei-Cheng Chang, Jyun-Yu Jiang, Hsiang-Fu Yu, Inderjit Dhillon, and Cho-Jui Hsieh [[Paper](https://dl.acm.org/doi/pdf/10.1145/3543507.3583318), [Video](https://www.youtube.com/watch?v=OsxZG2XfcZA)]
- NSG : Navigating Spread-out Graph For Approximate Nearest Neighbor Search. Fu, Cong, Chao Xiang, Changxu Wang, and Deng Cai. [[Paper](https://www.vldb.org/pvldb/vol12/p461-fu.pdf), [Code](https://github.com/ZJULearning/nsg)]
- EFANNA : Extremely Fast Approximate Nearest Neighbor Search Algorithm Based on kNN Graph. Cong Fu, Deng Cai. [[Paper](https://arxiv.org/abs/1609.07228), [Code](https://github.com/ZJULearning/efanna/tree/master)]
- Khan, Saim, et al. "[BANG: Billion-Scale Approximate Nearest Neighbor Search using a Single GPU.](https://arxiv.org/pdf/2401.11324.pdf)" arXiv preprint arXiv:2401.11324 (2024).
- Ootomo, Hiroyuki, et al. "[Cagra: Highly parallel graph construction and approximate nearest neighbor search for gpus.](https://arxiv.org/pdf/2308.15136.pdf)" arXiv preprint arXiv:2308.15136 (2023).
- Oguri, Yutaro, and Yusuke Matsui. "[Theoretical and Empirical Analysis of Adaptive Entry Point Selection for Graph-based Approximate Nearest Neighbor Search.](https://arxiv.org/pdf/2402.04713.pdf)" arXiv preprint arXiv:2402.04713 (2024).
- Oguri, Yutaro, and Yusuke Matsui. "[General and practical tuning method for off-the-shelf graph-based index: Sisap indexing challenge report by team utokyo.](https://arxiv.org/pdf/2309.00472.pdf)" International Conference on Similarity Search and Applications. Cham: Springer Nature Switzerland, 2023.
- Wang, Mengzhao, et al. "[Starling: An I/O-Efficient Disk-Resident Graph Index Framework for High-Dimensional Vector Similarity Search on Data Segment](https://arxiv.org/pdf/2401.02116.pdf)." arXiv preprint arXiv:2401.02116 (2024).
- Manohar, Magdalen Dobson, et al. "[ParlayANN: Scalable and Deterministic Parallel Graph-Based Approximate Nearest Neighbor Search Algorithms](https://dl.acm.org/doi/pdf/10.1145/3627535.3638475)." Proceedings of the 29th ACM SIGPLAN Annual Symposium on Principles and Practice of Parallel Programming. 2024. [[Code](https://github.com/cmuparlay/ParlayANN)]
- Wang, Mengzhao, et al. "[An Efficient and Robust Framework for Approximate Nearest Neighbor Search with Attribute Constraint](https://proceedings.neurips.cc/paper_files/paper/2023/file/32e41d6b0a51a63a9a90697da19d235d-Paper-Conference.pdf)." Advances in Neural Information Processing Systems 36 (2024).
- Yu, Shangdi, et al. "[Pecann: Parallel efficient clustering with graph-based approximate nearest neighbor search](https://arxiv.org/pdf/2312.03940.pdf)." arXiv preprint arXiv:2312.03940 (2023).
- Azizi, Ilias, Karima Echihabi, and Themis Palpanas. "[ELPIS: Graph-Based Similarity Search for Scalable Data Science](https://www.vldb.org/pvldb/vol16/p1548-azizi.pdf)." Proceedings of the VLDB Endowment 16.6 (2023): 1548-1559.
- Indyk, Piotr, and Haike Xu. "[Worst-case performance of popular approximate nearest neighbor search implementations: Guarantees and limitations](https://proceedings.neurips.cc/paper_files/paper/2023/file/d0ac28b79816b51124fcc804b2496a36-Paper-Conference.pdf)." Advances in Neural Information Processing Systems 36 (2024).
- Liu, Jun, et al. "[Optimizing Graph-based Approximate Nearest Neighbor Search: Stronger and Smarter.](https://nicsefc.ee.tsinghua.edu.cn/nics_file/pdf/dacb55cd-fe0a-4b00-9fa0-8f32e3243930.pdf)" 2022 23rd IEEE International Conference on Mobile Data Management (MDM). IEEE, 2022.
- Wang, Hui, Yong Wang, and Wan-Lei Zhao. "[Graph-based Approximate NN Search: A Revisit](https://arxiv.org/pdf/2204.00824.pdf)." arXiv preprint arXiv:2204.00824 (2022).
- Peng, Zhen, et al. "[Speed-ANN: Low-Latency and High-Accuracy Nearest Neighbor Search via Intra-Query Parallelism](https://arxiv.org/pdf/2201.13007.pdf)." arXiv preprint arXiv:2201.13007 (2022).
- Lu, Kejing, et al. "[HVS: hierarchical graph structure based on voronoi diagrams for solving approximate nearest neighbor search](https://www.vldb.org/pvldb/vol15/p246-lu.pdf)." Proceedings of the VLDB Endowment 15.2 (2021): 246-258. [[Code](https://github.com/chuanxiao1983/HVS)]
- Yingfan, Liu, Cheng Hong, and Cui Jiangtao. "[Revisiting $ k $-Nearest Neighbor Graph Construction on High-Dimensional Data: Experiments and Analyses](https://arxiv.org/pdf/2112.02234)." arXiv preprint arXiv:2112.02234 (2021).


## Tree-based Methods
- Diskann: Fast accurate billion-point nearest neighbor search on a single node. Jayaram Subramanya, Suhas, et al. [[Paper](https://proceedings.neurips.cc/paper_files/paper/2019/file/09853c7fb1d3f8ee67a61b6bf4a7f8e6-Paper.pdf), [Code](https://github.com/microsoft/DiskANN)]
- Li, Haitao, et al. "[Constructing Tree-based Index for Efficient and Effective Dense Retrieval.](https://arxiv.org/pdf/2304.11943.pdf)" arXiv preprint arXiv:2304.11943 (2023).
- Engels, Joshua, et al. "[Approximate Nearest Neighbor Search with Window Filters](https://arxiv.org/html/2402.00943v1)." arXiv preprint arXiv:2402.00943 (2024).

## Hashing
- :star: [Awesome Papers on Learning to Hash](https://learning2hash.github.io)
- :star: A survey on learning to hash. Wang, Jingdong, Ting Zhang, Nicu Sebe, and Heng Tao Shen [[Paper](https://arxiv.org/pdf/1606.00185.pdf)]
- :star: A survey on deep hashing methods. Luo, Xiao, Haixin Wang, Daqing Wu, Chong Chen, Minghua Deng, Jianqiang Huang, and Xian-Sheng Hua. [[Paper](https://dl.acm.org/doi/full/10.1145/3532624)]
- :star: Iterative quantization: A procrustean approach to learning binary codes for large-scale image retrieval. Gong, Yunchao, Svetlana Lazebnik, Albert Gordo, and Florent Perronnin [[Paper](https://slazebni.cs.illinois.edu/publications/ITQ.pdf), [Python code](https://github.com/twistedcubic/learn-to-hash/blob/master/itq.py), [Matlab code](https://github.com/dangkhoasdc/sah/tree/master/itq)]
- Gan, Yukang, et al. "[Binary Embedding-based Retrieval at Tencent](https://arxiv.org/pdf/2302.08714)." arXiv preprint arXiv:2302.08714 (2023).

## Systems

- Qin, An, et al. "[Maze: A Cost-Efficient Video Deduplication System at Web-scale](https://dl.acm.org/doi/pdf/10.1145/3503161.3548145)." Proceedings of the 30th ACM International Conference on Multimedia. 2022.

## Others
- [Search Optimization with Query Likelihood Boosting and Two-Level Approximate Search for Edge Devices](https://arxiv.org/abs/2312.07517)
- Gao, Jianyang, and Cheng Long. "[High-Dimensional Approximate Nearest Neighbor Search: with Reliable and Efficient Distance Comparison Operations.](https://dl.acm.org/doi/pdf/10.1145/3589282)" Proceedings of the ACM on Management of Data 1.2 (2023): 1-27.
- [Approximate Nearest Neighbor Search in Recommender Systems](https://big-ann-benchmarks.com/neurips23_slides/ANNS_for_recommendation_systems_Yury.pdf). Yury Malkov.
- [Accelerating vector search on the GPU with RAPIDS RAFT](https://big-ann-benchmarks.com/neurips23_slides/NVIDIA_Corey.pdf). Corey Nolet
- Gupta, Gaurav, et al. "[CAPS: A Practical Partition Index for Filtered Similarity Search](https://arxiv.org/pdf/2308.15014.pdf)." arXiv preprint arXiv:2308.15014 (2023).
- Zhu, Yuhao. "[RTNN: accelerating neighbor search using hardware ray tracing](https://arxiv.org/pdf/2201.01366.pdf)." Proceedings of the 27th ACM SIGPLAN Symposium on Principles and Practice of Parallel Programming. 2022. [[Code](https://github.com/horizon-research/rtnn)]


## Evaluation & Metrics
- Which BM25 do you mean? A large-scale reproducibility study of scoring variants. Kamphuis, Chris, Arjen P. de Vries, Leonid Boytsov, and Jimmy Lin [[Paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7148026/)]

## 📰 Articles & Talks
- [What is a Vector Database?](https://www.pinecone.io/learn/vector-database/)
- Vector databases (Part 1): [What makes each one different?](https://thedataquarry.com/posts/vector-db-1/)
- [eBay’s Blazingly Fast Billion-Scale Vector Similarity Engine](https://tech.ebayinc.com/engineering/ebays-blazingly-fast-billion-scale-vector-similarity-engine/)
- [Computer Vision Meetup: Computer Vision Applications at Scale with Vector Databases](https://www.youtube.com/watch?v=YTIDj7jeRbs)
- [How to choose your vector database in 2023?](https://www.sicara.fr/blog-technique/how-to-choose-your-vector-database-in-2023)
- [Do we really need a specialized vector database?](https://modelz.ai/blog/pgvector)
- [Vector database is not a separate database category](https://nextword.substack.com/p/vector-database-is-not-a-separate)
- [Vector Databases: A First-Principles Approach](https://docs.google.com/presentation/d/1qRv2nGVHjbFHXyUeUKK7bbvboj7Yal8UYcu_POEfWOQ/edit#slide=id.p)
- [Vector Search RAG Tutorial – Combine Your Data with LLMs with Advanced Search](https://www.youtube.com/watch?v=JEBDfGqrAUA&ab_channel=freeCodeCamp.org)
- [Efficient Vector Similarity Search in Recommender Workflows Using Milvus with NVIDIA Merlin](https://milvus.io/blog/efficient-vector-similarity-search-recommender-workflows-using-milvus-nvidia-merlin.md)
- [Vector Databases: A Beginner’s Guide!](https://medium.com/data-and-beyond/vector-databases-a-beginners-guide-b050cbbe9ca0)
- [Vector Database and Spring IA](https://dev.to/lucasnscr/vector-database-and-spring-ia-4dll)

