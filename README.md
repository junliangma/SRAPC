#####Automatic image segmentation using salient key point extraction and star shape prior
=====

**Xiangli Liao**, Hongbo Xu, Yicong Zhou, Kunqian Li, Wenbing Tao, Qiuju Guo, Signal Processing, 2014

	Abstract: In this paper, a new unsupervised segmentation method is proposed.
	The method integrates the star shape prior of the image object with salient point 
	detection algorithm. In the proposed method, the Harris salient point detection is first 
	 applied to the color image to obtain the initial salient points. A regional contrast based 
	 saliency extraction method is then used to select rough object regions in the image. To 
	 restrict the distribution of salient points, an adaptive threshold segmentation is applied 
	 to the saliency map to get the saliency mask. And then the salient region points can be 
	 obtained by placing the saliency mask on the initial Harris salient points. In order to 
	 make sure the salient points which we get are inside the image object thus the star 
	 shape constraint can be applied to the graph cuts segmentation, the Affinity 
	 Propagation (AP) clustering is employed to find the salient key points among the 
	 salient region points. Finally, these salient key points are regarded as foreground 
	 seeds and the star shape prior is introduced to graph cuts segmentation framework to 
	 extract the foreground object. Extensive experiments and comparisons on public 
	 database are provided to demonstrate the good performance of the proposed method.
