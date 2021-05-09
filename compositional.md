1. It is important to keep a track of signboards in a traffic scene. 
2. We observe that Faster RCNNs trained on a IDD-Detection do not work well on a IDD-Traffic-Sign-Occlusion. 
3. We observe that the failure case frames of IDSO are occluded by trees, poles, and cars. [STATS]
4. A compositional model understands grammar and heirarchy of objects in a scene. 
5. Compositional models theoretically should isolate foreground and background of the occluded object and therefore classfiy the object based on detected "semantic" parts which are the vMF kernels in the dataset. 
6. Here, is the compositional net from Adam Kortelewski, et. al from JHU for classification in 10 steps: 
8. The idea is to learn parts of the image like this - and detect the presence of these parts via template matching. 
9. The paper adds mixture models because MMs can represent a more flexible distribution (model choice). The authors want to sort of group the images in subgroups where each group represents a similar orientation feature. Orientation and not color, or anyother feature because for this problem statements modelling the spatial correlation of parts. A bus's left wheel and right wheel feature correlation. 
10. 
