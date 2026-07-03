# Physics-Informed Neural Networks for a One-Dimensional Elastoviscoplastic Model
Physics-Informed Neural Network（PINN）は、観測データへの適合だけでなく、微分方程式や構成則などの物理的制約を損失関数に組み込むことで、物理法則と整合する解を学習する手法である。本ノートブックでは、周期的なひずみ入力を受ける1次元Bingham--Voigt型弾粘塑性モデルを題材として、PINNの基礎的な実行・実装の方法を学ぶことを目的としている。特に、少数の応力観測から応力応答と塑性ひずみ履歴を再構成し、物理残差を用いない通常のニューラルネットワーク回帰との違いを確認する。

Physics-Informed Neural Networks (PINNs) are neural-network-based methods that incorporate physical constraints, such as differential equations and constitutive laws, into the loss function in addition to fitting observational data. This notebook aims to introduce the basic implementation and use of PINNs through a simple one-dimensional Bingham--Voigt-type elastoviscoplastic model under cyclic strain loading. In particular, the notebook demonstrates how stress response and plastic strain history can be reconstructed from sparse stress observations, and compares the result with standard neural-network regression without physics residuals.


