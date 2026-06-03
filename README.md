<h1 align="center">PointAction</h1>

<p align="center">
Official code repository for <em>"PointAction: 3D Points as Universal Action Representations for Robot Control"</em>.
</p>

<p align="center">
  <a href="https://oriontmt.github.io/pointaction/"><img src="https://img.shields.io/badge/Project-Website-2ea44f.svg" alt="Project Website"></a>
  <a href="https://arxiv.org/pdf/2606.03943"><img src="https://img.shields.io/badge/Paper-PDF-1f6feb.svg" alt="Paper PDF"></a>
  <a href="https://arxiv.org/abs/2606.03943"><img src="https://img.shields.io/badge/arXiv-2606.03943-b31b1b.svg" alt="arXiv"></a>
</p>

<p align="center">
  <a href="https://oriontmt.github.io/">Mutian Tong</a><sup>&dagger;</sup>,
  <a href="https://j-oyasumi.github.io/">Han Jiang</a><sup>&dagger;,*</sup>,
  <a href="https://fengq1a0.github.io/">Qiao Feng</a>,
  <a href="https://lingjie0206.github.io/">Lingjie Liu</a>,
  <a href="https://jiataogu.me/">Jiatao Gu</a>
  <br/>
  University of Pennsylvania
  <br/>
  <sup>&dagger;</sup>Equal contribution &nbsp;|&nbsp; <sup>*</sup>Work done during internship at the University of Pennsylvania
</p>

<p align="center">
  <a href="https://oriontmt.github.io/pointaction/">
    <img src="assets/teaser.png" alt="PointAction teaser" width="100%"/>
  </a>
</p>

<p align="center"><em>
PointAction bridges video prediction and robot control through explicit point-based 4D modeling. We fine-tune a foundation video model to jointly generate RGB frames and dynamic 3D pointmaps, then map these embodiment-agnostic point dynamics to executable actions via a lightweight per-arm decoder.
</em></p>

---

## 🚧 Code Release

We are actively cleaning up the training and inference codebase. **Initial release is expected by early July.** ⭐ Star this repo to be notified when the code drops.

In the meantime, please refer to:
- 📄 [Paper on arXiv](https://arxiv.org/abs/2606.03943)
- 🌐 [Project page (with interactive 4D viewers and real-robot rollouts)](https://oriontmt.github.io/pointaction/)

---

## Citation

If you find this work useful in your research, please consider citing:

```bibtex
@misc{tong2026pointaction3dpointsuniversal,
      title={PointAction: 3D Points as Universal Action Representations for Robot Control},
      author={Mutian Tong and Han Jiang and Qiao Feng and Lingjie Liu and Jiatao Gu},
      year={2026},
      eprint={2606.03943},
      archivePrefix={arXiv},
      primaryClass={cs.RO},
      url={https://arxiv.org/abs/2606.03943},
}
```
