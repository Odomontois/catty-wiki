# Category Theory


## Monoidal

### Cospan\Hypergraph

##### The Algebra of Open and Interconnected Systems

https://golem.ph.utexas.edu/category/2018/02/hypergraph_categories_of_cospa.html
https://arxiv.org/abs/1609.05382 

**Brendan Fong**  
(Submitted on 17 Sep 2016)

> Herein we develop category-theoretic tools for understanding network-style diagrammatic languages. The archetypal network-style diagrammatic language is that of electric circuits; other examples include signal flow graphs, Markov processes, automata, Petri nets, chemical reaction networks, and so on. The key feature is that the language is comprised of a number of components with multiple (input/output) terminals, each possibly labelled with some type, that may then be connected together along these terminals to form a larger network. The components form hyperedges between labelled vertices, and so a diagram in this language forms a hypergraph. We formalise the compositional structure by introducing the notion of a hypergraph category. Network-style diagrammatic languages and their semantics thus form hypergraph categories, and semantic interpretation gives a hypergraph functor.
The first part of this thesis develops the theory of hypergraph categories. In particular, we introduce the tools of decorated cospans and corelations. Decorated cospans allow straightforward construction of hypergraph categories from diagrammatic languages: the inputs, outputs, and their composition are modelled by the cospans, while the 'decorations' specify the components themselves. Not all hypergraph categories can be constructed, however, through decorated cospans. Decorated corelations are a more powerful version that permits construction of all hypergraph categories and hypergraph functors. These are often useful for constructing the semantic categories of diagrammatic languages and functors from diagrams to the semantics. To illustrate these principles, the second part of this thesis details applications to linear time-invariant dynamical systems and passive linear networks. 

-----
#### Decorated Cospans
https://golem.ph.utexas.edu/category/2016/01/decorated_cospans.html
https://arxiv.org/abs/1502.00872 

**Brendan Fong**  
(Submitted on 3 Feb 2015 (v1), last revised 11 Aug 2015 (this version, v3))

> Let C be a category with finite colimits, writing its coproduct +, and let (D,⊗) be a braided monoidal category. We describe a method of producing a symmetric monoidal category from a lax braided monoidal functor F:(C,+)→(D,⊗), and of producing a strong monoidal functor between such categories from a monoidal natural transformation between such functors. The objects of these categories, our so-called `decorated cospan categories', are simply the objects of C, while the morphisms are pairs comprising a cospan X→N←Y in C together with an element 1→FN in D. Moreover, decorated cospan categories are multigraph categories---each object is equipped with a special commutative Frobenius monoid---and their functors preserve this structure. 


