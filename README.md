# 2021: A Year Full of Amazing AI papers- A Review<br/> 📌 *[work in progress...]*
## A curated list of the latest breakthroughs in AI by release date with a clear video explanation, link to a more in-depth article, and code.

While the world is still recovering, research hasn't slowed its frenetic pace, especially in the field of artificial intelligence. More, many important aspects were highlighted this year, like the ethical aspects, important biases, governance, transparency and much more. Artificial intelligence and our understanding of the human brain and its link to AI are constantly evolving, showing promising applications improving our life's quality in the near future. Still, we ought to be careful with which technology we choose to apply.

>"Science cannot tell us what we ought to do, only what we can do."<br/>- Jean-Paul Sartre, Being and Nothingness

Here are the most interesting research papers of the year, in case you missed any of them. In short, it is curated list of the latest breakthroughs in AI and Data Science by release date with a clear video explanation, link to a more in-depth article, and code (if applicable). Enjoy the read!

**The complete reference to each paper is listed at the end of this repository.**<br/>
*This is a work in progress... Star this repository to stay up to date!* ⭐️

Maintainer: [louisfb01](https://github.com/louisfb01)

Subscribe to my [newsletter](http://eepurl.com/huGLT5) - The latest updates in AI explained every week.


*Feel free to [message me](https://www.louisbouchard.ai/contact/) any interesting paper I may have missed to add to this repository.*

*Tag me on **Twitter** [@Whats_AI](https://twitter.com/Whats_AI) or **LinkedIn** [@Louis (What's AI) Bouchard](https://www.linkedin.com/in/whats-ai/) if you share the list!*

<!-- ### Watch a complete 2020 rewind in 15 minutes

[![Watch the video](https://imgur.com/xzZT1ll.png)](https://youtu.be/DHBclF-8KwE)

--- -->

Missed last year? Check this out: [2020: A Year Full of Amazing AI papers- A Review](https://github.com/louisfb01/Best_AI_paper_2020)


## The Full List
- [DALL·E: Zero-Shot Text-to-Image Generation from OpenAI [1]](#1)
- [VOGUE: Try-On by StyleGAN Interpolation Optimization [2]](#2)
- [Taming Transformers for High-Resolution Image Synthesis [3]](#3)
- [Thinking Fast And Slow in AI [4]](#4)
- [Automatic detection and quantification of floating marine macro-litter in aerial images [5]](#5)
- [ShaRF: Shape-conditioned Radiance Fields from a Single View [6]](#6)
- [Generative Adversarial Transformers [7]](#7)
- [We Asked Artificial Intelligence to Create Dating Profiles. Would You Swipe Right? [8]](#8)
- [Swin Transformer: Hierarchical Vision Transformer using Shifted Windows [9]](#9)
- [IMAGE GANS MEET DIFFERENTIABLE RENDERING FOR INVERSE GRAPHICS AND INTERPRETABLE 3D NEURAL RENDERING [10]](#10)
- [Deep nets: What have they ever done for vision? [11]](#11)
- [todo [12]](#12)
- [todo [13]](#13)
- [todo [14]](#14)
- [todo [15]](#15)
- [todo [16]](#16)
- [todo [17]](#17)
- [todo [18]](#18)
- [todo [19]](#19)
- [todo [20]](#20)
- [todo [21]](#21)
- [todo [22]](#22)
- [todo [23]](#23)
- [todo [24]](#24)
- [todo [25]](#25)
- [todo [26]](#26)
- [todo [27]](#27)
- [todo [28]](#28)
- [todo [29]](#26)
- [todo [30]](#27)
- [todo [31]](#28)
- [Paper references](#references)

---

## DALL·E: Zero-Shot Text-to-Image Generation from OpenAI [1]<a name="1"></a>
OpenAI successfully trained a network able to generate images from text captions. It is very similar to GPT-3 and Image GPT and produces amazing results.

* Short Video Explanation:<br/>
[<img src="https://imgur.com/Czdyuce.png" width="512"/>](https://youtu.be/DJToDLBPovg)
* Short read: [OpenAI’s DALL·E: Text-to-Image Generation Explained](https://www.louisbouchard.ai/openais-dall-e-text-to-image-generation-explained/)
* Paper: [Zero-Shot Text-to-Image Generation](https://arxiv.org/pdf/2102.12092.pdf)
* Code: [Code & more information for the discrete VAE used for DALL·E](https://github.com/openai/DALL-E)


## VOGUE: Try-On by StyleGAN Interpolation Optimization [2]<a name="2"></a>
Google used a modified StyleGAN2 architecture to create an online fitting room where you can automatically try-on any pants or shirts you want using only an image of yourself.

* Short Video Explanation:<br/>
[<img src="https://imgur.com/FQL9bwU.png" width="512"/>](https://youtu.be/i4MnLJGZbaM)
* Short read: [The AI-Powered Online Fitting Room: VOGUE](https://medium.com/towards-artificial-intelligence/the-ai-powered-online-fitting-room-vogue-5f77c599832)
* Paper: [VOGUE: Try-On by StyleGAN Interpolation Optimization](https://vogue-try-on.github.io/static_files/resources/VOGUE-virtual-try-on.pdf)


## Taming Transformers for High-Resolution Image Synthesis [3]<a name="3"></a>
Tl;DR: They combined the efficiency of GANs and convolutional approaches with the expressivity of transformers to produce a powerful and time-efficient method for semantically-guided high-quality image synthesis.

* Short Video Explanation:<br/>
[<img src="https://imgur.com/0zUY1tm.png" width="512"/>](https://youtu.be/JfUTd8fjtX8)
* Short read: [Combining the Transformers Expressivity with the CNNs Efficiency for High-Resolution Image Synthesis](https://medium.com/towards-artificial-intelligence/combining-the-transformers-expressivity-with-the-cnns-efficiency-for-high-resolution-image-synthesis-31c6767547da)
* Paper: [Taming Transformers for High-Resolution Image Synthesis](https://compvis.github.io/taming-transformers/)
* Code: [Taming Transformers](https://github.com/CompVis/taming-transformers)


## Thinking Fast And Slow in AI [4]<a name="4"></a>
Drawing inspiration from Human Capabilities Towards a more general and trustworthy AI & 10 Questions for the AI Research Community.

* Short Video Explanation:<br/>
[<img src="https://imgur.com/H8X58lb.png" width="512"/>](https://youtu.be/3nvAaVSQxs4)
* Short read: [Third Wave of AI | Thinking Fast and Slow](https://www.louisbouchard.ai/third-wave-of-ai-thinking-fast-and-slow/)
* Paper: [Thinking Fast And Slow in AI](https://arxiv.org/abs/2010.06002)


## Automatic detection and quantification of floating marine macro-litter in aerial images [5]<a name="5"></a>
Odei Garcia-Garin et al. from the University of Barcelona have developed a deep learning-based algorithm able to detect and quantify floating garbage from aerial images. They also made a web-oriented application allowing users to identify these garbages, called floating marine macro-litter, or FMML, within images of the sea surface.

* Short Video Explanation:<br/>
[<img src="https://imgur.com/MmlYblV.png" width="512"/>](https://youtu.be/2dTSsdW0WYI)
* Short read: [An AI Software Able To Detect and Count Plastic Waste in the Ocean](https://pub.towardsai.net/an-ai-software-able-to-detect-and-count-plastic-waste-in-the-ocean-7211aa0baf89)
* Paper: [Automatic detection and quantification of floating marine macro-litter in aerial images: Introducing a novel deep learning approach connected to a web application in R, Environmental Pollution](https://doi.org/10.1016/j.envpol.2021.116490)
* [Click here for the code](https://github.com/amonleong/MARLIT)


## ShaRF: Shape-conditioned Radiance Fields from a Single View [6]<a name="6"></a>
Just imagine how cool it would be to just take a picture of an object and have it in 3D to insert in the movie or video game you are creating or in a 3D scene for an illustration.

* Short Video Explanation:<br/>
[<img src="https://imgur.com/WV6lq5s.png" width="512"/>](https://youtu.be/gHkkrNMlGNg)
* Short read: [ShaRF: Take a Picture From a Real-Life Object, and Create a 3D Model of It](https://pub.towardsai.net/sharf-take-a-picture-from-a-real-life-object-and-create-a-3d-model-of-it-c6809806b32)
* Paper: [ShaRF: Shape-conditioned Radiance Fields from a Single View](https://arxiv.org/abs/2102.08860)
* [Click here for the code](http://www.krematas.com/sharf/index.html)


## Generative Adversarial Transformers [7]<a name="7"></a>
They basically leverage transformers’ attention mechanism in the powerful StyleGAN2 architecture to make it even more powerful!

* Short Video Explanation:<br/>
[<img src="https://imgur.com/CJzGHxa.png" width="512"/>](https://youtu.be/HO-_t0UArd4)
* Short read: [GANsformers: Scene Generation with Generative Adversarial Transformers](https://whats-ai.medium.com/generative-adversarial-transformers-gansformers-explained-bf1fa76ef58d)
* Paper: [Generative Adversarial Transformers](https://arxiv.org/pdf/2103.01209.pdf)
* [Click here for the code](https://github.com/dorarad/gansformer)


## We Asked Artificial Intelligence to Create Dating Profiles. Would You Swipe Right? [8]<a name="8"></a>
Would you swipe right on an AI profile? Can you distinguish an actual human from a machine? This is what this study reveals using AI-made-up people on dating apps.

* Short Video Explanation:<br/>
[<img src="https://imgur.com/VKZrTBH.png" width="512"/>](https://youtu.be/IoRH5u13P-4)
* Short read: [Would You Swipe Right on an AI Profile?](https://pub.towardsai.net/would-you-swipe-right-on-an-ai-profile-98dc8a4451ec)
* Paper: [We Asked Artificial Intelligence to Create Dating Profiles. Would You Swipe Right?](arxiv_link)
* [Click here for the code](https://colab.research.google.com/drive/1VLG8e7YSEwypxU-noRNhsv5dW4NfTGce#forceEdit=true&sandboxMode=true&scrollTo=aeXshJM-Cuaf)


## Swin Transformer: Hierarchical Vision Transformer using Shifted Windows [9]<a name="9"></a>
Will Transformers Replace CNNs in Computer Vision? In less than 5 minutes, you will know how the transformer architecture can be applied to computer vision with a new paper called the Swin Transformer.

* Short Video Explanation:<br/>
[<img src="https://imgur.com/r9aL2iU.png" width="512"/>](https://youtu.be/QcCJJOLCeJQ)
* Short read: [Will Transformers Replace CNNs in Computer Vision?](https://pub.towardsai.net/will-transformers-replace-cnns-in-computer-vision-55657a196833)
* Paper: [Swin Transformer: Hierarchical Vision Transformer using Shifted Windows](https://arxiv.org/abs/2103.14030v1)
* [Click here for the code](https://github.com/microsoft/Swin-Transformer)


## IMAGE GANS MEET DIFFERENTIABLE RENDERING FOR INVERSE GRAPHICS AND INTERPRETABLE 3D NEURAL RENDERING [10]<a name="10"></a>
This promising model called GANverse3D only needs an image to create a 3D figure that can be customized and animated!

* Short Video Explanation:<br/>
[<img src="https://imgur.com/JJ5UAEp.png" width="512"/>](https://youtu.be/dvjwRBZ3Hnw)
* Short read: [Create 3D Models from Images! GANverse3D & NVIDIA Omniverse](https://www.louisbouchard.ai/ganverse3d/)
* Paper: [IMAGE GANS MEET DIFFERENTIABLE RENDERING FOR INVERSE GRAPHICS AND INTERPRETABLE 3D NEURAL RENDERING](https://arxiv.org/pdf/2010.09125.pdf)


## Deep nets: What have they ever done for vision? [11]<a name="11"></a>
"I will openly share everything about deep nets for vision applications, their successes, and the limitations we have to address."

* Short Video Explanation:<br/>
[<img src="imgur_link.png" width="512"/>](https://youtu.be/GhPDNzAVNDk)
* Short read: [What is the state of AI in computer vision?](https://www.louisbouchard.ai/ai-in-computer-vision/)
* Paper: [Deep nets: What have they ever done for vision?](https://arxiv.org/abs/1805.04025)


## title_goes_here [12]<a name="12"></a>
my_text_goes_here

* Short Video Explanation:<br/>
[<img src="imgur_link.png" width="512"/>](youtube_link)
* Short read: [article_title](article_link)
* Paper: [paper_title](arxiv_link)
* [Click here for the code](github_link)


## title_goes_here [13]<a name="13"></a>
my_text_goes_here

* Short Video Explanation:<br/>
[<img src="imgur_link.png" width="512"/>](youtube_link)
* Short read: [article_title](article_link)
* Paper: [paper_title](arxiv_link)
* [Click here for the code](github_link)


## title_goes_here [14]<a name="14"></a>
my_text_goes_here

* Short Video Explanation:<br/>
[<img src="imgur_link.png" width="512"/>](youtube_link)
* Short read: [article_title](article_link)
* Paper: [paper_title](arxiv_link)
* [Click here for the code](github_link)


## title_goes_here [15]<a name="15"></a>
my_text_goes_here

* Short Video Explanation:<br/>
[<img src="imgur_link.png" width="512"/>](youtube_link)
* Short read: [article_title](article_link)
* Paper: [paper_title](arxiv_link)
* [Click here for the code](github_link)


## title_goes_here [16]<a name="16"></a>
my_text_goes_here

* Short Video Explanation:<br/>
[<img src="imgur_link.png" width="512"/>](youtube_link)
* Short read: [article_title](article_link)
* Paper: [paper_title](arxiv_link)
* [Click here for the code](github_link)


## title_goes_here [17]<a name="17"></a>
my_text_goes_here

* Short Video Explanation:<br/>
[<img src="imgur_link.png" width="512"/>](youtube_link)
* Short read: [article_title](article_link)
* Paper: [paper_title](arxiv_link)
* [Click here for the code](github_link)


## title_goes_here [18]<a name="18"></a>
my_text_goes_here

* Short Video Explanation:<br/>
[<img src="imgur_link.png" width="512"/>](youtube_link)
* Short read: [article_title](article_link)
* Paper: [paper_title](arxiv_link)
* [Click here for the code](github_link)


## title_goes_here [19]<a name="19"></a>
my_text_goes_here

* Short Video Explanation:<br/>
[<img src="imgur_link.png" width="512"/>](youtube_link)
* Short read: [article_title](article_link)
* Paper: [paper_title](arxiv_link)
* [Click here for the code](github_link)


## title_goes_here [20]<a name="20"></a>
my_text_goes_here

* Short Video Explanation:<br/>
[<img src="imgur_link.png" width="512"/>](youtube_link)
* Short read: [article_title](article_link)
* Paper: [paper_title](arxiv_link)
* [Click here for the code](github_link)


## title_goes_here [21]<a name="21"></a>
my_text_goes_here

* Short Video Explanation:<br/>
[<img src="imgur_link.png" width="512"/>](youtube_link)
* Short read: [article_title](article_link)
* Paper: [paper_title](arxiv_link)
* [Click here for the code](github_link)


## title_goes_here [22]<a name="22"></a>
my_text_goes_here

* Short Video Explanation:<br/>
[<img src="imgur_link.png" width="512"/>](youtube_link)
* Short read: [article_title](article_link)
* Paper: [paper_title](arxiv_link)
* [Click here for the code](github_link)


## title_goes_here [23]<a name="23"></a>
my_text_goes_here

* Short Video Explanation:<br/>
[<img src="imgur_link.png" width="512"/>](youtube_link)
* Short read: [article_title](article_link)
* Paper: [paper_title](arxiv_link)
* [Click here for the code](github_link)


## title_goes_here [24]<a name="24"></a>
my_text_goes_here

* Short Video Explanation:<br/>
[<img src="imgur_link.png" width="512"/>](youtube_link)
* Short read: [article_title](article_link)
* Paper: [paper_title](arxiv_link)
* [Click here for the code](github_link)


## title_goes_here [25]<a name="25"></a>
my_text_goes_here

* Short Video Explanation:<br/>
[<img src="imgur_link.png" width="512"/>](youtube_link)
* Short read: [article_title](article_link)
* Paper: [paper_title](arxiv_link)
* [Click here for the code](github_link)


## title_goes_here [26]<a name="26"></a>
my_text_goes_here

* Short Video Explanation:<br/>
[<img src="imgur_link.png" width="512"/>](youtube_link)
* Short read: [article_title](article_link)
* Paper: [paper_title](arxiv_link)
* [Click here for the code](github_link)


## title_goes_here [27]<a name="27"></a>
my_text_goes_here

* Short Video Explanation:<br/>
[<img src="imgur_link.png" width="512"/>](youtube_link)
* Short read: [article_title](article_link)
* Paper: [paper_title](arxiv_link)
* [Click here for the code](github_link)


## title_goes_here [28]<a name="28"></a>
my_text_goes_here

* Short Video Explanation:<br/>
[<img src="imgur_link.png" width="512"/>](youtube_link)
* Short read: [article_title](article_link)
* Paper: [paper_title](arxiv_link)
* [Click here for the code](github_link)


## title_goes_here [29]<a name="29"></a>
my_text_goes_here

* Short Video Explanation:<br/>
[<img src="imgur_link.png" width="512"/>](youtube_link)
* Short read: [article_title](article_link)
* Paper: [paper_title](arxiv_link)
* [Click here for the code](github_link)


## title_goes_here [30]<a name="30"></a>
my_text_goes_here

* Short Video Explanation:<br/>
[<img src="imgur_link.png" width="512"/>](youtube_link)
* Short read: [article_title](article_link)
* Paper: [paper_title](arxiv_link)
* [Click here for the code](github_link)


## title_goes_here [31]<a name="31"></a>
my_text_goes_here

* Short Video Explanation:<br/>
[<img src="imgur_link.png" width="512"/>](youtube_link)
* Short read: [article_title](article_link)
* Paper: [paper_title](arxiv_link)
* [Click here for the code](github_link)


---


### If you would like to read more papers and have a broader view, here is another great repository for you covering 2020:
[2020: A Year Full of Amazing AI papers- A Review](https://github.com/louisfb01/Best_AI_paper_2020)


*Tag me on **Twitter** [@Whats_AI](https://twitter.com/Whats_AI) or **LinkedIn** [@Louis (What's AI) Bouchard](https://www.linkedin.com/in/whats-ai/) if you share the list!*

---

## Paper references<a name="references"></a>

[1] A. Ramesh et al., Zero-shot text-to-image generation, 2021. arXiv:2102.12092

[2] Lewis, Kathleen M et al., (2021), VOGUE: Try-On by StyleGAN Interpolation Optimization.

[3] Taming Transformers for High-Resolution Image Synthesis, Esser et al., 2020.

[4] Thinking Fast And Slow in AI, Booch et al., (2020), https://arxiv.org/abs/2010.06002.

[5] Odei Garcia-Garin et al., Automatic detection and quantification of floating marine macro-litter in aerial images: Introducing a novel deep learning approach connected to a web application in R, Environmental Pollution, https://doi.org/10.1016/j.envpol.2021.116490.

[6] Rematas, K., Martin-Brualla, R., and Ferrari, V., “ShaRF: Shape-conditioned Radiance Fields from a Single View”, (2021), https://arxiv.org/abs/2102.08860

[7] Drew A. Hudson and C. Lawrence Zitnick, Generative Adversarial Transformers, (2021)

[8] Sandra Bryant et al., “We Asked Artificial Intelligence to Create Dating Profiles. Would You Swipe Right?”, (2021), UNSW Sydney blog.

[9] Liu, Z. et al., 2021, “Swin Transformer: Hierarchical Vision Transformer using Shifted Windows”, arXiv preprint https://arxiv.org/abs/2103.14030v1

[10] Zhang, Y., Chen, W., Ling, H., Gao, J., Zhang, Y., Torralba, A. and Fidler, S., 2020. Image gans meet differentiable rendering for inverse graphics and interpretable 3d neural rendering. arXiv preprint arXiv:2010.09125.

[11] Yuille, A.L., and Liu, C., 2021. Deep nets: What have they ever done for vision?. International Journal of Computer Vision, 129(3), pp.781–802, https://arxiv.org/abs/1805.04025.

[12] todo

[13] todo

[14] todo

[15] todo

[16] todo

[17] todo

[18] todo

[19] todo

[20] todo

[21] todo

[22] todo

[23] todo

[24] todo

[25] todo

[26] todo

[27] todo

[28] todo

[29] todo

[30] todo

[31] todo

