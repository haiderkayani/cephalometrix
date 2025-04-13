---
layout: page
title: Features
permalink: /features/
---

### 🛠️ Features

CephalometriX offers a range of functions for image and landmark processing.

### Image Processing

### 🔹 `calculate_new_dimensions`
**Rescales images while maintaining the aspect ratio.**
```python
def calculate_new_dimensions(height, width, max_size: int=512):
```

### 🔹 `resize`
**Resizes the image and adjusts landmark positions accordingly.**
```python
def resize(image: np.ndarray, landmarks: np.ndarray = None, dimensions: tuple = (int, int)):
```

### 🔹 `rescale`
**Applies scaling and offset transformations to images.**
```python
def rescale(image, scale: float, offset: int = 0, dtype: str = "float32"):
```

### 🔹 `normalize_landmarks`
**Normalizes landmark coordinates relative to image dimensions (0 to 1 scale).**
```python
def normalize_landmarks(landmarks: np.ndarray, height: int, width: int, num_landmarks: int = 19):
```

### 🔹 `denormalize_landmarks`
**Converts normalized landmark coordinates back to absolute pixel positions.**
```python
def denormalize_landmarks(landmarks: np.ndarray, height: int, width: int, num_landmarks: int = 19):

```