# <center> Adult to child voice conversion </center>

<center> University of Sheffield </center>

<center> MINI lab </center>

 
<!--  ### Introduction-->

  
<!-- ## Model Overview-->
<!--img src="imgs/model.png" alt="My architecture diagram" /-->


## Demo
#### CycleGAN-VC2
| Minaii | Octavia | Octavia_to_minaii (cyclegan) | Octavia_to_minaii (post processed) | 

| <audio src="audios/gan_Minaii_TF064.wav" controls preload></audio> | <audio src="audios/gan_Octavia_TF064.wav" controls preload></audio> | <audio src="audios/Octavia_TF064_gan_vc.wav" controls preload></audio> | <audio src="audios/Octavia_TF064_gan_warp.wav" controls preload></audio>|


#### Diffusion based VC
| Minaii | Octavia | Octavia_to_minaii (diffusion) |Octavia_to_minaii (post processed) | 

| <audio src="audios/diff_Minaii_TF064.wav" controls preload></audio> | <audio src="audios/diff_Octavia_TF064.wav" controls preload></audio> | <audio src="audios/Octavia_TF064_diff_vc.wav" controls preload></audio> | <audio src="audios/Octavia_TF064_diff_warp.wav" controls preload></audio> |

#### Flow based VC
| Minaii | Octavia | Octavia_to_minaii (flow) |Octavia_to_minaii (post processed) | 

| <audio src="audios/blow_minaii_james_52.wav" controls preload></audio> | <audio src="audios/blow_octavia_james_52.wav" controls preload></audio> | <audio src="audios/Octavia_J052_blow_vc.wav" controls preload></audio> | <audio src="audios/Octavia_J052_blow_warp.wav" controls preload></audio> |

#### VAE based VC
| Minaii | Octavia | Octavia_to_minaii (VAE) |Octavia_to_minaii (post processed) | 

| <audio src="audios/Minaii_TF065.wav" controls preload></audio> | <audio src="audios/Octavia_TF065.wav" controls preload></audio> | <audio src="audios/Octavia_TF065_vae_vc.wav" controls preload></audio> | <audio src="audios/Octavia_TF065_vae_warp.wav" controls preload></audio> |




