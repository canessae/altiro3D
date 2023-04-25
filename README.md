### altiro3D: 2D-to-3D image and video conversion library for free-view LCD (starting from a single imagine or frame)

altiro3D is a free, extended C++ Library [(-see releases)](https://github.com/canessae/altiro3D/releases/) developed to reconstruct reality from a given single imagine (e.g., .png, .jpg) or flat video (e.g., .mp4). This is done generating a
light-field (or Native) image -see ["User's Manual"](https://github.com/canessae/altiro3D/blob/main/altiro3D-UserManual-v3.pdf)

<picture>
  <img alt="Visual Abstract" src="https://user-images.githubusercontent.com/84878752/230509598-98cba7fb-59fc-4129-b569-0f15221348ec.png" width="683" height="385">
</picture>

The several altiro3D command lines provide the following features:
• Create Native (i.e., 3D image) from Photo using MiDaS-small.
• Create Native from Photo using MiDaS-large.
• Create Native from a given original camera’s RGB image and depth image.
• Create Native from a given Quilt (N×M).
• Create Native from sorted N-views (i.e., sequential set of plain images) stored
in a given directory.
• Convert Quilt views to 2D video (.mp4).
• Convert given 2D video to Native 3D video (.mp4).
All these forms of Native images/videos consisting of light-fields can be correctly
displayed on a specific slanted, lenticular screen such as the Looking Glass (LG) Portrait.


#### Install

		sudo dpkg -i altiro3D-x.x.x-Linux.deb

Set the path to the working directory

		source /opt/altiro3D/bin/setupvars.sh

#### Run examples
		cd /opt/altiro3D/bin/examples
		./run_examples-1.sh 
			...

#### Uninstall

		sudo dpkg -r altiro3D

-------------------------------------------------
#### 2D Photo (input) and 2D Video

<picture>
  <img alt="3D Photo" src="https://user-images.githubusercontent.com/84878752/226052585-650fcb74-323f-491d-84d1-9f771430f069.jpg" width="132">
</picture>
<picture>
  <img alt="3D Photo" src="https://user-images.githubusercontent.com/84878752/226045600-1ccf40d2-79ad-4755-b818-ee9b7748bcf1.gif" width="132" height="234">
</picture>

#### Native 3D Photo and Native 3D Video

<picture>
  <img alt="3D Photo" src="https://user-images.githubusercontent.com/84878752/226053973-53c25d4a-4bfc-4b2f-a2a0-85cabfae1229.png" width="182">
</picture>
<picture>
  <img alt="3D Photo" src="https://user-images.githubusercontent.com/84878752/226071241-cadf9821-43be-4db9-badc-709ce0aec0b1.gif" width="182">
</picture>

#### 3D Video Display on Looking Glass Portrait

<picture>
  <img alt="3D Photo" src="https://user-images.githubusercontent.com/84878752/226109704-924bf271-ca22-4e3f-ac9d-0c8af370f1d4.gif" width="182">
</picture>

##

<picture>
  <img alt="Logo" src="https://user-images.githubusercontent.com/84878752/224785497-60c3ef3c-f341-4485-8194-dcfae28c8bd3.png" width="80">
</picture>

#### Citation

If this software (including any part of it) is useful for you, please cite

```bibtex
@misc{altiro3D:
  title = {{Scene representation from single image and novel view synthesis}},
  author = {E. Canessa, L. Tenze},
  doi = {10.48550/arXiv.2304.11161},
  url = {https://arxiv.org/abs/2304.11161},
  publisher = {arXiv},
  year = {2023},
}
```
