---
title: "A Probabilistic Model of the Bitcoin Blockchain"

# Authors
authors:
- Marc Jourdan
- Sebastien Blandin
- Laura Wynter
- Pralhad Deshpande

date: "2018-11-07"
doi: "10.1109/CVPRW.2019.00337"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: 2019 IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshops
publication_short: CVPRW 2019

abstract: The Bitcoin transaction graph is a public data structure organized as transactions between addresses, each associated with a logical entity. In this work, we introduce a complete probabilistic model of the Bitcoin Blockchain, setting the basis for follow-up AI applications on Bitcoin transactions. We first formulate a set of conditional dependencies induced by the Bitcoin protocol at the block level and derive a corresponding fully observed graphical model of a Bitcoin block. We then extend the model to include hidden entity attributes such as the functional category of the associated logical agent and derive asymptotic bounds on the privacy properties implied by this model. At the network level, we show evidence of complex transaction-to-transaction behavior and present a relevant discriminative model of the agent categories. Performance of both the block-based graphical model and the network-level discriminative model are evaluated on a subset of the public Bitcoin Blockchain.

tags: ["Bitcoin", "Privacy", "Generative models", "Bipartite graph"]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
 - name: Arxiv
   url: https://arxiv.org/abs/1812.05451

url_pdf: 'jourdan19a.pdf'
---
