# awesome-video-understanding-backbone


This comprehensive collection for video processing backbone(Tentative in CN ver.)
# 早期方法(2014-2015)

- DeepVideo: 首次将CNN引入视频理解
    
    > A. Karpathy, G. Toderici, S. Shetty, T. Leung, R. Sukthankar, and L. Fei-Fei, “Large-scale video classification with convolutional neural networks,” in CVPR, 2014.
    > 
    
    > S. Ji, W. Xu, M. Yang, and K. Yu, “3d convolutional neural networks for human action recognition,” IEEE Transactions on Pattern Analysis and Machine Intelligence, vol. 35, no. 1, pp. 221–231, 2013.
    > 
- 两流网络(Two-stream): 结合CNN和IDT捕捉运动信息
    
    > C. Feichtenhofer, A. Pinz, and A. Zisserman, “Convolutional two-stream network fusion for video action recognition,” in Proceedings of the IEEE conference on computer vision and pattern recognition, 2016, pp. 1933–1941.
    > 

# 长视频理解方法(2015-2016)

- LSTM: 处理长序列视频
    
    > J. Yue-Hei Ng, M. Hausknecht, S. Vijayanarasimhan, O. Vinyals, R. Monga, and G. Toderici, “Beyond short snippets: Deep networks for video classification,” in Proceedings of the IEEE conference on computer vision and pattern recognition, 2015, pp. 4694–4702.
    > 
- TSN(时序分段网络): 分析和聚合视频片段
    
    > L. Wang, Y. Xiong, Z. Wang, Y. Qiao, D. Lin, X. Tang, and L. Van Gool, “Temporal segment networks: Towards good practices for deep action recognition,” in European conference on computer vision. Springer, 2016, pp. 20–36.
    > 
- 编码方法: Fisher Vectors、Bi-Linear、VLAD编码
    
    > M. Sekma, M. Mejdoub, and C. B. Amar, “Human action recognition based on multi-layer fisher vector encoding method,” Pattern Recognition Letters, vol. 65, pp. 37–43, 2015.
    > 
    
    > A. Diba, V. Sharma, and L. Van Gool, “Deep temporal linear encoding networks,” in Proceedings of the IEEE conference on Computer Vision and Pattern Recognition, 2017, pp. 23292338.
    > 
    
    > I. Mironica ̆, I. C. Dut ̧a ̆, B. Ionescu, and N. Sebe, “A modified vector of locally aggregated descriptors approach for fast video classification,” Multimedia Tools and Applications, vol. 75, pp. 9045–9072, 2016.
    > 
    
    > H. Li, L. Zhang, D. Zhang, L. Fu, P. Yang, and J. Zhang, “Transvlad: Focusing on locally aggregated descriptors for fewshot learning,” in European Conference on Computer Vision. Springer, 2022, pp. 524–540.
    > 

# 3D CNN时代(2016-2018)

- C3D: 引入3D CNN
    
    > D. Tran, L. Bourdev, R. Fergus, L. Torresani, and M. Paluri, “Learning spatiotemporal features with 3d convolutional networks,” in Proceedings of the IEEE international conference on computer vision, 2015, pp. 4489–4497.
    > 
- I3D: 基于2D CNN(Inception)架构扩展到3D
    
    > J. Carreira and A. Zisserman, “Quo vadis, action recognition? a new model and the kinetics dataset,” in proceedings of the IEEE Conference on Computer Vision and Pattern Recognition, 2017, pp. 6299–6308.
    > 
- 2D到3D的架构改进:
    - R3D(基于ResNet)
        
        > K. He, X. Zhang, S. Ren, and J. Sun, “Deep residual learning for image recognition,” in Proceedings of the IEEE conference on computer vision and pattern recognition, 2016, pp. 770–778.
        > 
        
        > K. Hara, H. Kataoka, and Y. Satoh, “Learning spatio-temporal features with 3d residual networks for action recognition,” in Proceedings of the IEEE International Conference on Computer Vision (ICCV) Workshops, Oct 2017.
        > 
    - MFNet(基于ResNeXt)
        
        > S. Xie, R. Girshick, P. Dollar, Z. Tu, and K. He, “Aggregated residual transformations for deep neural networks,” in Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition (CVPR), July 2017.
        > 
        
        > Y. Chen, Y. Kalantidis, J. Li, S. Yan, and J. Feng, “Multifiber networks for video recognition,” in Proceedings of the European Conference on Computer Vision (ECCV), September 2018.
        > 
    - STC(基于SENet)
        
        > J. Hu, L. Shen, and G. Sun, “Squeeze-and-excitation networks,” in Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition (CVPR), June 2018.
        > 
        
        > A. Diba, M. Fayyaz, V. Sharma, M. M. Arzani, R. Yousefzadeh, J. Gall, and L. Van Gool, “Spatio-temporal channel correlation networks for action classification,” in Proceedings of the European Conference on Computer Vision (ECCV), September 2018.
        > 

# 效率优化阶段(2018-2019)

- 3D分解方法:
    - S3D
        
        > S. Xie, C. Sun, J. Huang, Z. Tu, and K. Murphy, “Rethinking spatiotemporal feature learning: Speed-accuracy trade-offs in video classification,” in Proceedings of the European Conference on Computer Vision (ECCV), September 2018.
        > 
    - ECO
        
        > M. Zolfaghari, K. Singh, and T. Brox, “Eco: Efficient convolutional network for online video understanding,” in Proceedings of the European conference on computer vision (ECCV), 2018, pp. 695–712.
        > 
    - P3D
        
        > Z. Qiu, T. Yao, and T. Mei, “Learning spatio-temporal representation with pseudo-3d residual networks,” in proceedings of the IEEE International Conference on Computer Vision, 2017, pp. 5533–5541.
        > 
- 长时序建模:
    - LTC
        
        > G. Varol, I. Laptev, and C. Schmid, “Long-term temporal convolutions for action recognition,” IEEE Transactions on Pattern Analysis and Machine Intelligence, vol. 40, no. 6, pp. 1510–1517, 2018
        > 
    - T3D
        
        > A. Diba, M. Fayyaz, V. Sharma, A. H. Karami, M. M. Arzani, R. Yousefzadeh, and L. V. Gool, “Temporal 3d convnets: New architecture and transfer learning for video classification,” CoRR, vol. abs/1711.08200, 2017. [Online]. Available: http://arxiv.org/abs/1711.08200
        > 
    - Non-local
        
        > X. Wang, R. Girshick, A. Gupta, and K. He, “Non-local neural networks,” in Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition (CVPR), June 2018.
        > 
    - V4D
        
        > S. Zhang, S. Guo, W. Huang, M. R. Scott, and L. Wang, “V4d: 4d convolutional neural networks for video-level representation learning,” in International Conference on Learning Representations, 2019.
        > 
- 高效架构:
    - CSN
        
        > D. Tran, H. Wang, L. Torresani, and M. Feiszli, “Video classification with channel-separated convolutional networks,” in Proceedings of the IEEE/CVF international conference on computer vision, 2019, pp. 5552–5561.
        > 
    - SlowFast
        
        > C. Feichtenhofer, H. Fan, J. Malik, and K. He, “Slowfast networks for video recognition,” in Proceedings of the International Conference on Computer Vision (ICCV), 2019.
        > 
    - X3D
        
        > C. Feichtenhofer, “X3d: Expanding architectures for efficient video recognition,” in Proceedings of the IEEE/CVF conference on computer vision and pattern recognition, 2020, pp. 203–213.
        > 

# Transformer时代(2020-至今)

- ViT的引入
- 视频Transformer模型:
    - TimeSformer
        
        > G. Bertasius, H. Wang, and L. Torresani, “Is space-time attention all you need for video understanding?” in ICML, vol. 2, no. 3, 2021, p. 4.
        > 
    - VidTr
        
        > X. Li, Y. Zhang, C. Liu, B. Shuai, Y. Zhu, B. Brattoli, H. Chen, I. Marsic, and J. Tighe, “Vidtr: Video transformer without convolutions,” arXiv e-prints, pp. arXiv–2104, 2021.
        > 
    - ViViT
        
        > A. Arnab, M. Dehghani, G. Heigold, C. Sun, M. Luˇci ́c, and C. Schmid, “Vivit: A video vision transformer,” in Proceedings of the IEEE/CVF international conference on computer vision, 2021, pp. 6836–6846.
        > 
    - MViT
        
        > H. Fan, B. Xiong, K. Mangalam, Y. Li, Z. Yan, J. Malik, and C. Feichtenhofer, “Multiscale vision transformers,” in Proceedings of the IEEE/CVF international conference on computer vision, 2021, pp. 6824–6835.
        > 

## 主要发展趋势:

1. 从简单CNN到复杂架构
2. 从短视频处理到长视频理解
3. 从性能优先到同时注重效率
4. 从CNN主导到Transformer架构的兴起

## 重要数据集:

- UCF-101
    
    > K. Soomro, A. R. Zamir, and M. Shah, “Ucf101: A dataset of 101 human actions classes from videos in the wild,” in Proceedings of the 2012 IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2012.
    > 
- HMDB51
    
    > H. Kuehne, H. Jhuang, E. Garrote, T. Poggio, and T. Serre, “Hmdb: A large video database for human motion recognition,” in Proceedings of the International Conference on Computer Vision (ICCV), 2011.
    > 
- Kinetics-400
    
    > W. Kay, J. Carreira, K. Simonyan, B. Zhang, C. Hillier, S. Vijayanarasimhan, F. Viola, T. Green, T. Back, P. Natsev et al., “The kinetics human action video dataset,” arXiv preprint arXiv:1705.06950, 2017.
    > 
- Something-Something
    
    > R. Goyal, S. Ebrahimi Kahou, V. Michalski, J. Materzynska, S. Westphal, H. Kim, V. Haenel, I. Fruend, P. Yianilos, M. Mueller-Freitag et al., “The” something something” video database for learning and evaluating visual common sense,” in Proceedings of the IEEE international conference on computer vision, 2017, pp. 5842–5850.
    >
