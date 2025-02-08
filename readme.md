# Storylock Holmes: The AI Detective Agent in the IPverse at Story Protocol.
![storylock](https://github.com/user-attachments/assets/f4e3ead2-2c86-4b9a-8658-3888b1c821db)

## Links:

[Slides](https://docs.google.com/presentation/d/1PN5nnyUUSS-baFAYp-XProzcySaU0Ith5Zdplb6FhJ8/edit#slide=id.g32f8bdbf275_0_1)

[Storylock AI Agent on X (Twitter)](https://x.com/StorylockAI)

[Storylock Frontend](https://storylock.vercel.app/)

[Frontend Code](https://github.com/Carnegie-Mellon-Blockchain/Storylock-Frontend)

[Storylock AI Agent ElizaOS](https://github.com/Carnegie-Mellon-Blockchain/Storylock-Holmes)

[AI Agent script that automatically registers user's tweets to IP](https://gist.github.com/story000/678b0101b9bdad9dda8fd96a50bcf7fc)


## Introduction

**Storylock Holmes: The AI Detective Agent in the IPverse.**

Storylock Holmes is a detective on Social Media. He won't miss any intellectual property theft on Twitter, and he can find all the details between two different versions of the same pictures. 

Storylock Holmes AI Agent protects your IP on Social Media. You can easily register your Twitter media IP on Story Protocol by Storylock with one click. Then, using the cutting-edge Computer Vision model, Storylock can find whether there are other Twitter media similar to yours regardless of the noises others put on the picture. Every time when he finds an infringement, he will send a message on X to notify the infringer to take down the picture.

He is also a good assistant for your intellectual property management. Ask him any questions about your IP, and he will give you the answers.

## Features

Key Functions of Storylock Holmes:




<img width="1399" alt="image" src="https://github.com/user-attachments/assets/14bd2cc9-9939-420b-b296-89588b46cdba" />

### 1. Easy to use IP Register and Checking:

From the [StorylockAI Website](https://storylock.vercel.app/), users can register a tweet to Story Protocol and StorylockAI database with one click. After that, the data will be indexed by Storylock. In the future, we look forward to integrating Story Protocol and other blockchain's NFT databases into StorylockAI to make it even more powerful.



### 2. **Fully Autonomous Agent live on X (Twitter)**: 
StorylockAI is a 24h Twitter Detective AI Agent based on Eliza. Every moment, he discusses IP with other users. If any users mention him in a tweet with media content, StorylockAI will check if this media is similar to other IPs that are already registered at Story Protocol by the SOTA CV Model.

<img width="1427" alt="image" src="https://github.com/user-attachments/assets/28a13d3b-4323-4f9e-af87-13568c71220a" />



### 3. **SOTA CV Model Integration**:
We leverage the state-of-the-art Vision Transformer (ViT) model, introduced in the paper "An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale" by Dosovitskiy et al. ViT extracts key features from images to assess similarities between intellectual properties, ensuring precise detection of potential infringements.

The Vision Transformer (ViT) is a BERT-like transformer encoder trained on a vast collection of images in a supervised manner, specifically using ImageNet-21k. It processes images by dividing them into fixed-size patches (16x16 resolution), which are then linearly embedded. Through training, the model learns representations that facilitate feature extraction for various downstream applications, including structuring an Intellectual Property (IP) database.

By integrating our IP database with the Story Protocol Explorer, Storylock Holmes can efficiently detect and trace intellectual property infringements, ensuring robust protection of your assets.

### 4. **IP Dispute Resolution**:
We use Story Protocol, A decentralized system to handle any IP disputes within the ecosystem, ensuring fairness and protection of creator rights. Anyone wanna register an IP asset that belongs to others to Story Protocol will get auto-blocked by Storylock Holmes.



## Bounty Writeup

### Story

Code: 

Storylock Holmes is powered by Story Protocol, leveraging its distributed and lego-like IPFI stackable architecture. Even though IP has a 61T Market, the technology in the IP area growes as slow as a turtle. Story Protocol is the only one that can provide a full-stack solution for IP protection and management, making IP protection and registration as easy as sending a tweet.

Storylock Holmes aimes to be the frontend of Story Protocol. We believe that agents will definitely be the new UI of Internet. And we want to make IP protection and management as easy as sending a tweet.


```
@misc{wu2020visual,
      title={Visual Transformers: Token-based Image Representation and Processing for Computer Vision}, 
      author={Bichen Wu and Chenfeng Xu and Xiaoliang Dai and Alvin Wan and Peizhao Zhang and Zhicheng Yan and Masayoshi Tomizuka and Joseph Gonzalez and Kurt Keutzer and Peter Vajda},
      year={2020},
      eprint={2006.03677},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
@article{dosovitskiy2020image,
  title={An image is worth 16x16 words: Transformers for image recognition at scale},
  author={Dosovitskiy, Alexey},
  journal={arXiv preprint arXiv:2010.11929},
  year={2020}
}
@article{ridnik2021imagenet,
  title={Imagenet-21k pretraining for the masses},
  author={Ridnik, Tal and Ben-Baruch, Emanuel and Noy, Asaf and Zelnik-Manor, Lihi},
  journal={arXiv preprint arXiv:2104.10972},
  year={2021}
}
@inproceedings{deng2009imagenet,
  title={Imagenet: A large-scale hierarchical image database},
  author={Deng, Jia and Dong, Wei and Socher, Richard and Li, Li-Jia and Li, Kai and Fei-Fei, Li},
  booktitle={2009 IEEE conference on computer vision and pattern recognition},
  pages={248--255},
  year={2009},
  organization={Ieee}
}
```
