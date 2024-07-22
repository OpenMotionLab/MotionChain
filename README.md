<div align= "center">
    <h1> Official repo for MotionChain</h1>

</div>

<div align="center">
    <h3> MotionChain: Conversational Motion Controllers via Multimodal Prompts</h3>

<p align="center">
  <a href="https://arxiv.org/pdf/2404.01700">Arxiv Paper</a> •
  Demo •
  <a href="#️-faq">FAQ</a> •
  <a href="#-citation">Citation</a>
</p>

</div>

<div align="center">
</div>

## Intro MotionChain

MotionChain is a unified
vision-motion-language generative pre-trained model, which performs **conversational**
generation tasks via **multi-modal** inputs with language models.

<details open="open">
    <summary><b>Technical details</b></summary>

Recent advancements in language models have demonstrated their adeptness in conducting multi-turn dialogues and retaining conversational context. However, this proficiency remains largely unexplored in other multimodal generative models, particularly in human motion models. By integrating multi-turn conversations in controlling continuous virtual human movements, generative human motion models can achieve an intuitive and step-by-step process of human task execution for humanoid robotics, game agents, or other embodied systems. In this work, we present MotionChain, a conversational human motion controller to generate continuous and long-term human motion through multimodal prompts. Specifically, MotionChain consists of multi-modal tokenizers that transform various data types such as text, image, and motion, into discrete tokens, coupled with a Vision-Motion-aware Language model. By leveraging large-scale language, vision-language, and vision-motion data to assist motion-related generation tasks, MotionChain thus comprehends each instruction in multi-turn conversation and generates human motions followed by these prompts. Extensive experiments validate the efficacy of MotionChain, demonstrating state-of-the-art performance in conversational motion generation, as well as more intuitive manners of controlling and interacting with virtual humans.

<img width="1194" alt="pipeline" src="./assets/images/pipeline.png">
</details>

## 🚩 News

- [2024/07/15] [Conversation dataset](https://huggingface.co/datasets/OpenMotionLab/MotionChain_Conv) released. 
- [2024/04/02] Upload paper and init project 🔥🔥🔥

## ⚡ Quick Start

<!-- <details>
  <summary><b>Setup and download</b></summary>

</details> -->

## ▶️ Demo

<!-- <details>
  <summary><b>Webui</b></summary>


</details> -->

## 👀 Visualization

## ⚠️ FAQ

<details> <summary><b>Question-and-Answer</b></summary>

</details>
</details>

## 📖 Citation

If you find our code or paper helps, please consider citing:

```bibtex
@misc{jiang2024motionchain,
      title={MotionChain: Conversational Motion Controllers via Multimodal Prompts},
      author={Biao Jiang and Xin Chen and Chi Zhang and Fukun Yin and Zhuoyuan Li and Gang YU and Jiayuan Fan},
      year={2024},
      eprint={2404.01700},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```

## Acknowledgments

Thanks to [BEDLAM](https://github.com/pixelite1201/BEDLAM), [TMR](https://github.com/Mathux/TMR), [vector-quantize-pytorch](https://github.com/lucidrains/vector-quantize-pytorch), [Motion-GPT](https://github.com/OpenMotionLab/MotionGPT), [Motion-latent-diffusion](https://github.com/ChenFengYe/motion-latent-diffusion), [T2m-gpt](https://github.com/Mael-zys/T2M-GPT), [TEMOS](https://github.com/Mathux/TEMOS), [ACTOR](https://github.com/Mathux/ACTOR), [HumanML3D](https://github.com/EricGuo5513/HumanML3D) and [joints2smpl](https://github.com/wangsen1312/joints2smpl), our code is partially borrowing from them.

## License

This code is distributed under an [MIT LICENSE](LICENSE).

Note that our code depends on other libraries, including SMPL, SMPL-X, PyTorch3D, and uses datasets which each have their own respective licenses that must also be followed.
