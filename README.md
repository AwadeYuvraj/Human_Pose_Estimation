# Human Pose Estimation with OpenCV

This project demonstrates human pose estimation using OpenCV's Deep Neural Network (DNN) module. It uses a pre-trained TensorFlow model (`graph_opt.pb`) to detect and connect key points of the human body in an input image. The results are visualized with key points and skeletal connections overlayed on the input image.

---

## Features

- Detects 18 human body key points, including shoulders, elbows, wrists, knees, and ankles.
- Uses OpenCV DNN for fast inference.
- Interactive UI built with Streamlit for uploading and visualizing images.
- Adjustable confidence threshold for detecting key points.

---

## Requirements

To run this project, you need:

- Python 3.10.4 or later
- Necessary Python packages (see below)
- Pre-trained TensorFlow model file (`graph_opt.pb`)

---

## Installation

### Step 1: Clone the Repository

```bash
git clone https://github.com/AwadeYuvraj/Human_Pose_Estimation.git
cd Human_Pose_Estimation
```

### Step 2: Set Up Python Environment

1. Install [Miniconda](https://docs.conda.io/en/latest/miniconda.html) or [Anaconda](https://www.anaconda.com/products/distribution).
2. Create a new environment with Python 3.10.4:
   ```bash
   conda create -n pose_estimation python=3.10.4 -y
   conda activate pose_estimation
   ```

### Step 3: Install Dependencies

Install the required Python packages:

```bash
pip install -r requirements.txt
```

### Step 4: Add the TensorFlow Model

Download the `graph_opt.pb` file (pre-trained model) and place it in the project directory.

---

## Usage

Run the Streamlit app:

```bash
streamlit run estimation_app.py
```

1. Upload an image with a clear view of the human body.
2. Adjust the confidence threshold slider as needed.
3. View the processed image with detected key points and pose connections.

---
### Example Output Image:
## Output
![image](https://github.com/user-attachments/assets/9a7f35f3-559b-4141-a769-d1e00685ce13)
![image](https://github.com/user-attachments/assets/95031cb7-24a5-4c8a-8af6-0ab654929319)
![image](https://github.com/user-attachments/assets/626ceaac-db20-4703-bbf1-84d0aedc9678)


## Contributing

Feel free to fork the repository and create pull requests with improvements or bug fixes. Contributions are welcome!

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

- OpenCV for the DNN module
- TensorFlow for the pre-trained model
- Streamlit for interactive UI

