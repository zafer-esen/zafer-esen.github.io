---
layout: page
title: "Publications and Talks"
permalink: /publications/
icon: fas fa-file-alt
order: 2
last_modified_at: 2025-06-18
---

### <i class="fas fa-book"></i>  Theses

<ul>
  <li>
    <span class="badge bg-secondary float-end">2025</span>
    <strong>Transformations for Verifying Programs with Heap-Allocated Data Structures</strong><br>
    <em>Zafer Esen</em>. PhD Thesis, Uppsala University.
    <div class="mt-2 mb-3">
      <a href="https://urn.kb.se/resolve?urn=urn:nbn:se:uu:diva-554456" class="btn btn-sm btn-secondary" target="_blank" rel="noopener">URL</a>
      <a href="https://uu.diva-portal.org/smash/get/diva2:1952212/FULLTEXT01.pdf" class="btn btn-sm btn-secondary" target="_blank" rel="noopener">PDF</a>
      <button class="btn btn-sm btn-secondary" type="button" data-bs-toggle="collapse" data-bs-target="#abs-esen2025phd">Abstract</button>
      <button class="btn btn-sm btn-secondary" type="button" data-bs-toggle="collapse" data-bs-target="#bib-esen2025phd">BibTeX</button>
    </div>
    <div class="collapse" id="abs-esen2025phd"><div class="card card-body bg-light text-dark p-3"><em>Verifying programs that manipulate heap-allocated data structures is a long-standing challenge in software verification. This thesis summarises a series of five papers that advance the state of the art in automated verification of such programs through transformation-based approaches. The contributions include the development of a formal SMT-LIB theory of heaps to represent heap operations, the implementation of this theory in an automated verification tool for C programs, and novel invariant-based encodings that simplify reasoning about heap structures. The thesis further presents methods for automatically instrumenting programs to simplify verification tasks involving quantified properties and aggregations. All proposed techniques are fully automated and do not rely on user-provided annotations, enabling verification of heap-manipulating programs with quantified invariants that previously posed significant challenges to automated verification tools.</em></div></div>
    <div class="collapse" id="bib-esen2025phd">
      <pre class="card card-body bg-light text-dark p-3">{% raw %}﻿@phdthesis{EsenPhD,
   author = {Esen, Zafer},
   institution = {Uppsala University, Computer Systems},
   pages = {55},
   school = {Uppsala UniversityUppsala University, Computer Systems, Division of Computer Systems},
   title = {Transformations for Verifying Programs with Heap-Allocated Data Structures},
   series = {Digital Comprehensive Summaries of Uppsala Dissertations from the Faculty of Science and Technology},
   ISSN = {1651-6214},
   number = {2541},
   ISBN = {978-91-513-2484-5},
   year = {2025}
}{% endraw %}</pre>
    </div>
  </li>
  <li>
    <span class="badge bg-secondary float-end">2019</span>
    <strong>Extension of the Eldarica C model checker with heap memory</strong><br>
    <em>Zafer Esen</em>. MSc Thesis, Uppsala University.
    <div class="mt-2 mb-3">
      <a href="http://urn.kb.se/resolve?urn=urn:nbn:se:uu:diva-397812" class="btn btn-sm btn-secondary" target="_blank" rel="noopener">URL</a>
      <a href="https://uu.diva-portal.org/smash/get/diva2:1373067/FULLTEXT01.pdf" class="btn btn-sm btn-secondary" target="_blank" rel="noopener">PDF</a>
      <button class="btn btn-sm btn-secondary" type="button" data-bs-toggle="collapse" data-bs-target="#abs-esen2019msc">Abstract</button>
      <button class="btn btn-sm btn-secondary" type="button" data-bs-toggle="collapse" data-bs-target="#bib-esen2019msc">BibTeX</button>
    </div>
    <div class="collapse" id="abs-esen2019msc"><div class="card card-body bg-light text-dark p-3"><em>Model checking is a verification method which is used to detect bugs which would be extremely hard to detect using traditional testing, and ELDARICA is a state-of-the-art model checker which accepts a variety of formats as its input, including programs written in a fragment of the C language. This thesis aims to improve the C front-end of ELDARICA to a point where it can automatically model and verify C programs which contain pointers, heap memory interactions and structs, which are currently not supported. This work models the heap in a similar way to how it was done in JayHorn, a model checker for Java, by automatically finding quantified invariants which summarize the states of data structures that are on the heap. Support for structs is added by modeling them as algebraic data types, and limited support for stack pointers is added with some constraints on how they are declared and used. The initial experimental results are promising. The extended tool can now parse programs written in a larger fragment of the C language, with acceptable precision and performance in comparison to similar tools.</em></div></div>
    <div class="collapse" id="bib-esen2019msc">
      <pre class="card card-body bg-light text-dark p-3">{% raw %}﻿@mastersthesis{EsenMSc,
   author = {Esen, Zafer},
   institution = {Uppsala University, Department of Information Technology},
   pages = {70},
   school = {Uppsala University, Department of Information Technology},
   title = {Extension of the ELDARICA C model checker with heap memory},
   series = {IT},
   number = {19078},
   year = {2019}
}{% endraw %}</pre>
    </div>
  </li>
</ul>

### <i class="fas fa-file-alt"></i>  Peer-Reviewed Publications

<ul>
  <li>
    <span class="badge bg-secondary float-end">2025</span>
    <span class="badge bg-success float-end me-1">To Appear</span>
    <strong>Arithmetizing Shape Analysis</strong><br>
    <em>S. Wolff, E. Gupta, Z. Esen, H. Hojjat, P. Rümmer, T. Wies</em>. In: International Conference on Computer-Aided Verification (<a href="#" target="_blank" rel="noopener">CAV 2025</a>).
    <div class="mt-2 mb-3">
      <a href="https://arxiv.org/pdf/2408.09037" class="btn btn-sm btn-secondary" target="_blank" rel="noopener">URL (preprint)</a>
      <a href="https://arxiv.org/pdf/2408.09037" class="btn btn-sm btn-secondary" target="_blank" rel="noopener">PDF (preprint)</a>
      <button class="btn btn-sm btn-secondary" type="button" data-bs-toggle="collapse" data-bs-target="#abs-wolff2025">Abstract</button>
      <button class="btn btn-sm btn-secondary" type="button" data-bs-toggle="collapse" data-bs-target="#bib-wolff2025">BibTeX</button>
    </div>
    <div class="collapse" id="abs-wolff2025"><div class="card card-body bg-light text-dark p-3"><em>Memory safety is an essential correctness property of software systems. For programs operating on linked heap-allocated data structures, the problem of proving memory safety boils down to analyzing the possible shapes of data structures, leading to the field of shape analysis. This paper presents a novel reduction-based approach to memory safety analysis that relies on two forms of abstraction: flow abstraction, representing global properties of the heap graph through local flow equations; and view abstraction, which enable verification tools to reason symbolically about an unbounded number of heap objects. In combination, the two abstractions make it possible to reduce memory-safety proofs to proofs about heap-less imperative programs that can be discharged using off-the-shelf software verification tools without built-in support for heap reasoning. Using an empirical evaluation on a broad range of programs, the paper shows that the reduction approach can effectively verify memory safety for sequential and concurrent programs operating on different kinds of linked data structures, including singly-linked, doubly-linked, and nested lists as well as trees. </em></div></div>
    <div class="collapse" id="bib-wolff2025"><pre class="card card-body bg-light text-dark p-3">{% raw %}@inproceedings{WolffEtAl2025Arithmetizing,
  title     = {Arithmetizing Shape Analysis},
  author    = {Sebastian Wolff and Ekanshdeep Gupta and Zafer Esen and Hossein Hojjat and Philipp R{\"u}mmer and Thomas Wies},
  booktitle = {CAV},
  year      = {2025},
  note      = {To appear}
}{% endraw %}</pre></div>
  </li>
  <li>
    <span class="badge bg-secondary float-end">2025</span>
    <strong>Finding Universally Quantified Heap Invariants by Horn Clause Transformations</strong><br>
    <em>Zafer Esen, Philipp Rümmer, Tjark Weber</em>. In: International Conference on Fundamentals of Software Engineering (<a href="#" target="_blank" rel="noopener">FSEN 2025</a>).
    <div class="mt-2 mb-3">
      <a href="https://link.springer.com/chapter/10.1007/978-3-031-87054-5_4" class="btn btn-sm btn-secondary" target="_blank" rel="noopener">URL</a>
      <button class="btn btn-sm btn-secondary" type="button" data-bs-toggle="collapse" data-bs-target="#abs-esen2025finding">Abstract</button>
      <button class="btn btn-sm btn-secondary" type="button" data-bs-toggle="collapse" data-bs-target="#bib-esen2025finding">BibTeX</button>
    </div>
    <div class="collapse" id="abs-esen2025finding"><div class="card card-body bg-light text-dark p-3"><em>A common approach in software verification is to encode a program as a set of Constrained Horn Clauses (CHCs), which are then processed and solved automatically by a CHC solver. To streamline this verification approach for the case of programs operating on mutable linked data-structures, we have in earlier work proposed a theory of heaps, defined within the SMT-LIB framework, which enables us to represent programs as CHCs with minimal loss of structural information. By preserving high-level program information in the encoding, the theory of heaps enables CHC solvers to apply various internal techniques for handling program heap; among others, to encode the heap further using the theory of arrays, to apply shape analysis, or to translate to a heap-less program with the help of invariants. This paper explores the third option, developing transformation rules that rewrite a set of CHCs into an equisatisfiable set of CHCs with additional predicates representing heap invariants. The proposed method generalises the notion of space invariants, which were previously introduced for verifying Java programs, by lifting the entire transformation process to the CHC level. The paper defines the transformation rules, provides detailed correctness proofs, and discusses the strengths and limitations of the approach. We also outline possible extensions of the method.</em></div></div>
    <div class="collapse" id="bib-esen2025finding"><pre class="card card-body bg-light text-dark p-3">{% raw %}@InProceedings{10.1007/978-3-031-87054-5_4,
author="Esen, Zafer
and R{\"u}mmer, Philipp
and Weber, Tjark",
editor="Hojjat, Hossein
and Caltais, Georgiana",
title="Finding Universally Quantified Heap Invariants by Horn Clause Transformations",
booktitle="Fundamentals of Software Engineering",
year="2025",
publisher="Springer Nature Switzerland",
address="Cham",
pages="42--60",
isbn="978-3-031-87054-5"
}
{% endraw %}</pre></div>
  </li>
  <li>
    <span class="badge bg-secondary float-end">2024</span>      
    <span class="badge bg-info text-dark float-end me-1">Book Chapter</span>
    <strong>An Exercise in Mind Reading: Automatic Contract Inference for Frama-C</strong><br>
    <em>J. Amilon, Z. Esen, D. Gurov, C. Lidström, P. Rümmer</em>. Book chapter in Guide to Software Verification with Frama-C.
    <div class="mt-2 mb-3">
      <a href="https://link.springer.com/chapter/10.1007/978-3-031-55608-1_13" class="btn btn-sm btn-secondary" target="_blank" rel="noopener">URL</a>
      <button class="btn btn-sm btn-secondary" type="button" data-bs-toggle="collapse" data-bs-target="#abs-amilon2024">Abstract</button>
      <button class="btn btn-sm btn-secondary" type="button" data-bs-toggle="collapse" data-bs-target="#bib-amilon2024">BibTeX</button>
    </div>
    <div class="collapse" id="abs-amilon2024"><div class="card card-body bg-light text-dark p-3"><em>Using tools for deductive verification, such as Frama-C, typically imposes substantial work overhead in the form of manually writing annotations. In this chapter, we investigate techniques for alleviating this problem by means of automatic inference of ACSL specifications. To this end, we present the Frama-C plugin Saida, which uses the assertion-based model checker TriCera as a back-end tool for inference of function contracts. TriCera transforms the program, and specifications provided as assume and assert statements, into a set of constrained Horn clauses (CHC), and relies on CHC solvers for the verification of these clauses. Our approach assumes that a C program consists of one entry-point (main) function and a number of helper functions, which are called from the main function either directly or transitively. Saida takes as input such a C  program, where the main function is annotated with an ACSL function contract, and translates the contract into a harness function, comprised mainly of assume and assert statements. The harness function, together with the original program, is used as input for TriCera and, from the output of the CHC solver, TriCera infers pre- and post-conditions for all the helper functions in the C program, and translates them into ACSL function contracts. We illustrate on several examples how Saida can be used in practice, and discuss ongoing work on extending and improving the plugin.</em></div></div>
    <div class="collapse" id="bib-amilon2024"><pre class="card card-body bg-light text-dark p-3">{% raw %}@Inbook{Amilon2024,
author="Amilon, Jesper
and Esen, Zafer
and Gurov, Dilian
and Lidstr{\"o}m, Christian
and R{\"u}mmer, Philipp",
editor="Kosmatov, Nikolai
and Prevosto, Virgile
and Signoles, Julien",
title="An Exercise in Mind Reading: Automatic Contract Inference for Frama-C",
bookTitle="Guide to Software Verification with Frama-C: Core Components, Usages, and Applications",
year="2024",
publisher="Springer International Publishing",
address="Cham",
pages="553--582",
isbn="978-3-031-55608-1",
doi="10.1007/978-3-031-55608-1_13",
url="https://doi.org/10.1007/978-3-031-55608-1_13"
}
{% endraw %}</pre></div>
  </li>
  <li>
    <span class="badge bg-secondary float-end">2023</span>
    <span class="badge bg-warning text-dark float-end me-1">Distinguished Paper</span>
    <strong>Automatic Program Instrumentation for Automatic Verification</strong><br>
    <em>J. Amilon, Z. Esen, D. Gurov, C. Lidstöm, P. Rümmer</em>. In: Int. Conf. on Computer-Aided Verification (<a href="http://www.i-cav.org/2023/" target="_blank" rel="noopener">CAV 2023</a>).
    <div class="mt-2 mb-3">
      <a href="https://link.springer.com/chapter/10.1007/978-3-031-37709-9_14" class="btn btn-sm btn-secondary" target="_blank" rel="noopener">URL</a>
      <a href="https://arxiv.org/abs/2306.00004" class="btn btn-sm btn-secondary" target="_blank" rel="noopener">URL (extended preprint)</a>
      <a href="https://arxiv.org/pdf/2306.00004" class="btn btn-sm btn-secondary" target="_blank" rel="noopener">PDF (extended preprint)</a>
      <button class="btn btn-sm btn-secondary" type="button" data-bs-toggle="collapse" data-bs-target="#abs-amilon2023">Abstract</button>
      <button class="btn btn-sm btn-secondary" type="button" data-bs-toggle="collapse" data-bs-target="#bib-amilon2023">BibTeX</button>
    </div>
    <div class="collapse" id="abs-amilon2023"><div class="card card-body bg-light text-dark p-3"><em>In deductive verification and software model checking, dealing with certain specification language constructs can be problematic when the back-end solver is not sufficiently powerful or lacks the required theories. One way to deal with this is to transform, for verification purposes, the program to an equivalent one not using the problematic constructs, and to reason about its correctness instead. In this paper, we propose instrumentation as a unifying verification paradigm that subsumes various existing ad-hoc approaches, has a clear formal correctness criterion, can be applied automatically, and can transfer back witnesses and counterexamples. We illustrate our approach on the automated verification of programs that involve quantification and aggregation operations over arrays, such as the maximum value or sum of the elements in a given segment of the array, which are known to be difficult to reason about automatically. We implement our approach in the MonoCera tool, which is tailored to the verification of programs with aggregation, and evaluate it on example programs, including SV-COMP programs.</em></div></div>
    <div class="collapse" id="bib-amilon2023"><pre class="card card-body bg-light text-dark p-3">{% raw %}@InProceedings{10.1007/978-3-031-37709-9_14,
author="Amilon, Jesper
and Esen, Zafer
and Gurov, Dilian
and Lidstr{\"o}m, Christian
and R{\"u}mmer, Philipp",
editor="Enea, Constantin
and Lal, Akash",
title="Automatic Program Instrumentation for Automatic Verification",
booktitle="Computer Aided Verification",
year="2023",
publisher="Springer Nature Switzerland",
address="Cham",
pages="281--304",
isbn="978-3-031-37709-9"
}
{% endraw %}</pre></div>
  </li>
  <li>
    <span class="badge bg-secondary float-end">2022</span>
    <strong>TriCera: Verifying C Programs Using the Theory of Heaps</strong><br>
    <em>Zafer Esen, Philipp Rümmer</em>. In: Formal Methods in Computer-Aided Design (<a href="https://fmcad.org/FMCAD22/" target="_blank" rel="noopener">FMCAD 2022</a>).
    <div class="mt-2 mb-3">
      <a href="https://repositum.tuwien.at/handle/20.500.12708/81374" class="btn btn-sm btn-secondary" target="_blank" rel="noopener">URL</a>
      <a href="https://repositum.tuwien.at/bitstream/20.500.12708/81374/1/Esen-2022-TRICERA%20Verifying%20C%20Programs%20Using%20the%20Theory%20of%20Heaps-vor.pdf" class="btn btn-sm btn-secondary" target="_blank" rel="noopener">PDF</a>
      <a href="https://fmcad.org/FMCAD22/presentations/13%20-%20Reachability%20and%20safety%20verification/05_esen.pdf" class="btn btn-sm btn-secondary" target="_blank" rel="noopener">Slides</a>
      <button class="btn btn-sm btn-secondary" type="button" data-bs-toggle="collapse" data-bs-target="#abs-esen2022tricera">Abstract</button>
      <button class="btn btn-sm btn-secondary" type="button" data-bs-toggle="collapse" data-bs-target="#bib-esen2022tricera">BibTeX</button>
    </div>
    <div class="collapse" id="abs-esen2022tricera"><div class="card card-body bg-light text-dark p-3"><em>TriCera is an automated, open-source verification tool for C programs based on the concept of Constrained Horn Clauses (CHCs). In order to handle programs operating on heap, TriCera applies a novel theory of heaps, which enables the tool to hand off most of the required heap reasoning directly to the underlying CHC solver. This leads to a cleaner interface between the language-specific verification front-end and the language-independent CHC back-end, and enables verification tools for different programming languages to share a common heap back-end. The paper introduces TriCera, gives an overview of the theory of heaps, and presents preliminary experimental results using SV-COMP benchmarks.</em></div></div>
    <div class="collapse" id="bib-esen2022tricera"><pre class="card card-body bg-light text-dark p-3">{% raw %}@InProceedings{EsenTriCera,
  author={Esen, Zafer and Rümmer, Philipp},
  booktitle={2022 Formal Methods in Computer-Aided Design (FMCAD)}, 
  title={Tricera: Verifying C Programs Using the Theory of Heaps}, 
  year={2022},
  pages={380-391},
  doi={10.34727/2022/isbn.978-3-85448-053-2_45}}
{% endraw %}</pre></div>
  </li>
  <li>
    <span class="badge bg-secondary float-end">2022</span>
    <strong>An SMT-LIB Theory of Heaps</strong><br>
    <em>Zafer Esen, Philipp Rümmer</em>. In: Int. Workshop on Satisfiability Modulo Theories (<a href="https://smt-workshop.cs.uiowa.edu/2022/" target="_blank" rel="noopener">SMT 2022</a>).<br>
    <em>(Recommended reference for the theory of heaps.)</em>
    <div class="mt-2 mb-3">
      <a href="https://ceur-ws.org/Vol-3185/paper1180.pdf" class="btn btn-sm btn-secondary" target="_blank" rel="noopener">PDF</a>
      <button class="btn btn-sm btn-secondary" type="button" data-bs-toggle="collapse" data-bs-target="#abs-esen2022smt">Abstract</button>
      <button class="btn btn-sm btn-secondary" type="button" data-bs-toggle="collapse" data-bs-target="#bib-esen2022smt">BibTeX</button>
    </div>
    <div class="collapse" id="abs-esen2022smt"><div class="card card-body bg-light text-dark p-3"><em>Constrained Horn Clauses (CHCs) are an intermediate program representation that can be generated by several verification tools, and that can be processed and solved by a number of Horn solvers. One of the main challenges when using CHCs in verification is the encoding of heap-allocated data-structures: such data-structures are today either represented explicitly using the theory of arrays, or transformed away with the help of invariants or refinement types, defeating the purpose of CHCs as a representation that is language-independent as well as agnostic of the algorithm implemented by the Horn solver. This paper presents an SMT-LIB theory of heaps tailored to CHCs, with the goal of enabling a standard interchange format for programs with heap data-structures. We introduce the syntax of the theory of heaps, define its semantics in terms of axioms and using a reduction to SMT-LIB arrays and data-types, provide an experimental evaluation and outline possible extensions and future work.</em></div></div>
    <div class="collapse" id="bib-esen2022smt"><pre class="card card-body bg-light text-dark p-3">{% raw %}@inproceedings{EsenHeap22,
  author       = {Zafer Esen and
                  Philipp R{\"{u}}mmer},
  editor       = {David D{\'{e}}harbe and
                  Antti E. J. Hyv{\"{a}}rinen},
  title        = {An {SMT-LIB} Theory of Heaps},
  booktitle    = {Proceedings of the 20th Internal Workshop on Satisfiability Modulo
                  Theories co-located with the 11th International Joint Conference on
                  Automated Reasoning {(IJCAR} 2022) part of the 8th Federated Logic
                  Conference (FLoC 2022), Haifa, Israel, August 11-12, 2022},
  series       = {{CEUR} Workshop Proceedings},
  volume       = {3185},
  pages        = {38--53},
  publisher    = {CEUR-WS.org},
  year         = {2022},
  url          = {https://ceur-ws.org/Vol-3185/paper1180.pdf},
}{% endraw %}</pre></div>
  </li>
  <li>
    <span class="badge bg-secondary float-end">2021</span>
    <strong>Reasoning in the Theory of Heap: Satisfiability and Interpolation</strong><br>
    <em>Zafer Esen, Philipp Rümmer</em>. In: Logic-Based Program Synthesis and Transformation (<a href="https://link.springer.com/chapter/10.1007/978-3-030-68446-4_9" target="_blank" rel="noopener">LOPSTR 2020</a>). (Invited Paper)
    <div class="mt-2 mb-3">
      <a href="https://link.springer.com/chapter/10.1007/978-3-030-68446-4_9" class="btn btn-sm btn-secondary" target="_blank" rel="noopener">URL</a>
      <a href="http://www.philipp.ruemmer.org/publications/lopstr2020.pdf" class="btn btn-sm btn-secondary" target="_blank" rel="noopener">PDF (preprint)</a>
      <button class="btn btn-sm btn-secondary" type="button" data-bs-toggle="collapse" data-bs-target="#abs-esen2021reasoning">Abstract</button>
      <button class="btn btn-sm btn-secondary" type="button" data-bs-toggle="collapse" data-bs-target="#bib-esen2021reasoning">BibTeX</button>
    </div>
    <div class="collapse" id="abs-esen2021reasoning"><div class="card card-body bg-light text-dark p-3"><em>In recent work, we have proposed an SMT-LIB theory of heap tailored to Horn-clause verification. The theory makes it possible to lift verification approaches for heap-allocated data-structures to a language-independent level, and this way factor out the treatment of heap in verification tools. This paper gives an overview of the theory, and presents ongoing research on decision and interpolation procedures.</em></div></div>
    <div class="collapse" id="bib-esen2021reasoning"><pre class="card card-body bg-light text-dark p-3">{% raw %}@InProceedings{10.1007/978-3-030-68446-4_9,
author="Esen, Zafer
and R{\"u}mmer, Philipp",
editor="Fern{\'a}ndez, Maribel",
title="Reasoning in the Theory of Heap: Satisfiability and Interpolation",
booktitle="Logic-Based Program Synthesis and Transformation",
year="2021",
publisher="Springer International Publishing",
address="Cham",
pages="173--191",
isbn="978-3-030-68446-4"
}
{% endraw %}</pre></div>
  </li>
</ul>

### <i class="fas fa-file-archive"></i>  Technical Reports & Abstracts

<ul>
  <li>
    <span class="badge bg-secondary float-end">2025</span>
    <span class="badge bg-light text-dark float-end me-1">Under Submission</span>
    <strong>Sound and Complete Invariant-Based Heap Encodings (Technical Report)</strong><br>
    <em>Zafer Esen, Philipp Rümmer, Tjark Weber</em>.
    <div class="mt-2 mb-3">
      <a href="https://arxiv.org/abs/2504.15844" class="btn btn-sm btn-secondary" target="_blank" rel="noopener">URL</a>
      <a href="https://arxiv.org/pdf/2504.15844" class="btn btn-sm btn-secondary" target="_blank" rel="noopener">PDF</a>
      <button class="btn btn-sm btn-secondary" type="button" data-bs-toggle="collapse" data-bs-target="#abs-esen2025sound">Abstract</button>
      <button class="btn btn-sm btn-secondary" type="button" data-bs-toggle="collapse" data-bs-target="#bib-esen2025sound">BibTeX</button>
    </div>
    <div class="collapse" id="abs-esen2025sound"><div class="card card-body bg-light text-dark p-3"><em>Verification of programs operating on mutable, heap-allocated data structures poses significant challenges due to potentially unbounded structures like linked lists and trees. In this paper, we present a novel relational heap encoding leveraging uninterpreted predicates and prophecy variables, reducing heap verification tasks to satisfiability checks over integers in constrained Horn clauses (CHCs). To the best of our knowledge, our approach is the first invariant-based method that achieves both soundness and completeness for heap-manipulating programs. We provide formal proofs establishing the correctness of our encodings. Through an experimental evaluation we demonstrate that our method significantly extends the capability of existing CHC-based verification tools, allowing automatic verification of programs with heap previously unreachable by state-of-the-art tools. </em></div></div>
    <div class="collapse" id="bib-esen2025sound"><pre class="card card-body bg-light text-dark p-3">{% raw %}@misc{esen2025soundcompleteinvariantbasedheap,
      title={Sound and Complete Invariant-Based Heap Encodings (Technical Report)}, 
      author={Zafer Esen and Philipp Rümmer and Tjark Weber},
      year={2025},
      eprint={2504.15844},
      archivePrefix={arXiv},
      primaryClass={cs.LO},
      url={https://arxiv.org/abs/2504.15844}, 
}{% endraw %}</pre></div>
  </li>
  <li>
    <span class="badge bg-secondary float-end">2021</span>
    <strong>A Theory of Heap for Constrained Horn Clauses (Extended Technical Report)</strong><br>
    <em>Zafer Esen, Philipp Rümmer</em>. CoRR abs/2104.04224.
    <div class="mt-2 mb-3">
      <a href="https://arxiv.org/abs/2104.04224" class="btn btn-sm btn-secondary" target="_blank" rel="noopener">URL</a>
      <a href="https://arxiv.org/pdf/2104.04224" class="btn btn-sm btn-secondary" target="_blank" rel="noopener">PDF</a>
      <button class="btn btn-sm btn-secondary" type="button" data-bs-toggle="collapse" data-bs-target="#abs-esen2021tr">Abstract</button>
      <button class="btn btn-sm btn-secondary" type="button" data-bs-toggle="collapse" data-bs-target="#bib-esen2021tr">BibTeX</button>
    </div>
    <div class="collapse" id="abs-esen2021tr"><div class="card card-body bg-light text-dark p-3"><em>Constrained Horn Clauses (CHCs) are an intermediate program representation that can be generated by several verification tools, and that can be processed and solved by a number of Horn solvers. One of the main challenges when using CHCs in verification is the encoding of heap-allocated data-structures: such data-structures are today either represented explicitly using the theory of arrays, or transformed away with the help of invariants or refinement types, defeating the purpose of CHCs as a representation that is language-independent as well as agnostic of the algorithm implemented by the Horn solver. This paper presents an SMT-LIB theory of heap tailored to CHCs, with the goal of enabling a standard interchange format for programs with heap data-structures. We introduce the syntax of the theory of heap, define its semantics in terms of axioms and using a reduction to SMT-LIB arrays and data-types, and discuss its properties and outline possible extensions and future work.</em></div></div>
    <div class="collapse" id="bib-esen2021tr"><pre class="card card-body bg-light text-dark p-3">{% raw %}@misc{esen2021theoryheapconstrainedhorn,
      title={A Theory of Heap for Constrained Horn Clauses (Extended Technical Report)}, 
      author={Zafer Esen and Philipp Rümmer},
      year={2021},
      eprint={2104.04224},
      archivePrefix={arXiv},
      primaryClass={cs.LO},
      url={https://arxiv.org/abs/2104.04224}, 
}{% endraw %}</pre></div>
  </li>
  <li>
    <span class="badge bg-secondary float-end">2021</span>
    <strong>A Theory of Heap for Constrained Horn Clauses</strong><br>
    <em>Zafer Esen, Philipp Rümmer</em>. Abstract at 32nd Nordic Workshop on Programming Theory (<a href="http://icetcs.ru.is/nwpt21/" target="_blank" rel="noopener">NWPT 2021</a>).
    <div class="mt-2 mb-3">
      <a href="https://icetcs.github.io/nwpt21/abstracts/paper26.pdf" class="btn btn-sm btn-secondary" target="_blank" rel="noopener">PDF</a>
      <button class="btn btn-sm btn-secondary" type="button" data-bs-toggle="collapse" data-bs-target="#bib-esen2021nwpt">BibTeX</button>
    </div>
    <div class="collapse" id="bib-esen2021nwpt"><pre class="card card-body bg-light text-dark p-3">{% raw %}@misc{EsenRuemmer2021NWPT,
  title     = {A Theory of Heap for Constrained Horn Clauses},
  author    = {Zafer Esen and Philipp R{\"u}mmer},
  booktitle = {32nd Nordic Workshop on Programming Theory},
  year      = {2021}
}{% endraw %}</pre></div>
  </li>
  <li>
    <span class="badge bg-secondary float-end">2020</span>
    <strong>Towards an SMT-LIB Theory of Heap</strong><br>
    <em>Zafer Esen, Philipp Rümmer</em>. Presentation only abstract in 18th International Workshop on Satisfiability Modulo Theories (<a href="http://smt-workshop.cs.uiowa.edu/2020/program.shtml" target="_blank" rel="noopener">SMT 2020</a>).
    <div class="mt-2 mb-3">
      <a href="https://ceur-ws.org/Vol-2854/abstract4.pdf" class="btn btn-sm btn-secondary" target="_blank" rel="noopener">PDF</a>
      <a href="https://www.youtube.com/live/B3ML9vGituk?si=7gFe9lPV2OTfBfgT&t=2567" class="btn btn-sm btn-secondary" target="_blank" rel="noopener">Talk (YouTube)</a>
    </div>
  </li>
</ul>

### <i class="fas fa-bullhorn"></i>  Invited Talks

<ul>
  <li>
    <span class="badge bg-secondary float-end">2022</span>
    <strong>Eldarica and TriCera: Towards an Open Verification Framework</strong><br>
    <em>Zafer Esen</em>. At: Democratizing Software Verification Workshop (<a href="https://smackers.github.io/democratizing-software-verification-workshop-2022/" target="_blank" rel="noopener">DSV 2022</a>).
  </li>
  <li>
    <span class="badge bg-secondary float-end">2021</span>
    <strong>Towards Automatic Verification of Unsafe Rust with Constrained Horn Solvers</strong><br>
    <em>Z. Esen, P. Rümmer, A. Stjerna</em>. At: Workshop on Rust for High-Integrity and Safety-Critical Systems (<a href="https://sites.google.com/view/rustverify2021" target="_blank" rel="noopener">RustVerify 2021</a>).
  </li>
</ul>