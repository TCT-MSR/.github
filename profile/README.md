# An Ethereum-compatible blockchain that explicates and ensures design-level safety properties for smart contracts (TCT)

Smart contracts are crucial elements of decentralized technologies, but they face significant obstacles to trustworthiness due to security bugs and trapdoors. To address the core issue, we propose a technology that enables programmers to focus on design-level properties rather than specific low-level attack patterns. Our proposed technology, called **Theorem-Carrying-Transaction (TCT)**, combines the benefits of runtime checking and symbolic proof. Under the TCT protocol, every transaction must carry a theorem that proves its adherence to the safety properties in the invoked contracts, and the blockchain checks the proof before executing the transaction. The unique design of TCT ensures that the theorems are provable and checkable in an efficient manner. We believe that TCT holds a great promise for enabling provably secure smart contracts in the future. As such, we call for collaboration toward this vision.

If you are interested, our paper is here: https://arxiv.org/ftp/arxiv/papers/2304/2304.08655.pdf.

Also we have a video to introduce how TCT works:

[![Theorem-Carrying-Transaction](https://res.cloudinary.com/marcomontalbano/image/upload/v1685374706/video_to_markdown/images/youtube--pMiEGCuKIBI-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=pMiEGCuKIBI "Theorem-Carrying-Transaction")
