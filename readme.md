```python3
import kagglehub

# Download latest version
path = kagglehub.model_download("kaggle/yolo-v5/tfLite/tflite-tflite-model")

print("Path to model files:", path)
```

### where save data 
```python
import kagglehub

# Specify the location to save the model
save_location = "/desired/save/location"  # Replace with your preferred directory path

# Download the latest version of the model to the specified location
path = kagglehub.model_download("kaggle/yolo-v5/tfLite/tflite-tflite-model", path=save_location)

print("Path to model files:", path)
```
