# <center> Adult to child voice conversion </center>

<center> University of Sheffield </center>

<center> MINI lab </center>

 
<!--  ### Introduction-->

  
<!-- ## Model Overview-->
<!--img src="imgs/model.png" alt="My architecture diagram" /-->


## Demo
#### CycleGAN-VC2
| Minaii | Octavia | Octavia_to_minaii (cyclegan) | Octavia_to_minaii (preprocessed) | 

| <audio src="audios/gan_Minaii_TF064.wav" controls preload></audio> | <audio src="audios/gan_Octavia_TF064.wav" controls preload></audio> | <audio src="audios/Octavia_TF064_vc.wav" controls preload></audio> | <audio src="audios/Octavia_TF064_warp.wav" controls preload></audio>|


#### Diffusion based VC
| Minaii | Octavia | Octavia_to_minaii (diffusion) |Octavia_to_minaii (diffusion +warp) | 

| <audio src="audios/diff_Minaii_TF064.wav" controls preload></audio> | <audio src="audios/diff_Octavia_TF064.wav" controls preload></audio> | <audio src="audios/diff_Octavia_TF064_converted496.wav" controls preload></audio> | <audio src="audios/diff_Octavia_TF064_warp.wav" controls preload></audio> |

#### Flow based VC
| Minaii | Octavia | Octavia_to_minaii (flow) |Octavia_to_minaii (flow +warp) | 

| <audio src="audios/blow_minaii_james_52.wav" controls preload></audio> | <audio src="audios/blow_octavia_james_52.wav" controls preload></audio> | <audio src="audios/blow_converted.wav" controls preload></audio> | <audio src="audios/blow_warp.wav" controls preload></audio> |

#### VAE based VC
| Minaii | Octavia | Octavia_to_minaii (VAE) |Octavia_to_minaii (VAE +warp) | 

| <audio src="audios/Minaii_TF065.wav" controls preload></audio> | <audio src="audios/Octavia_TF065.wav" controls preload></audio> | <audio src="audios/Octavia_TF065_conv.wav" controls preload></audio> | <audio src="audios/Octavia_TF065_warp.wav" controls preload></audio> |




