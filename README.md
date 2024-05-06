# Face Reconstruction

## Installation
1. Clone the repository.
2. install dependencies.

```
pip install -r requirements.txt
```

# Face landmark detection
Navigate to the FaceReconstruction folder
```
cd ./FaceReconstruction
```

Run the ```generate_ply.py``` file to generate point cloud ```.ply``` file

```
python generate_ply.py
```

If cv2.error is prompted, you may need to run the following command to reinstall cv2

```
pip install opencv-python
```
