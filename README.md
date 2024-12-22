# Weather Image Classification

This project involves classifying images of various weather phenomena using a dataset containing labeled images across multiple weather-related categories. The dataset is structured into subfolders, each representing a unique weather class.

## Dataset Information

### Dataset Path
The dataset is located at `/kaggle/input/weather-image-classification/dataset` and contains images categorized into the following 11 classes:

- **hail**
- **rainbow**
- **frost**
- **rime**
- **fogsmog**
- **snow**
- **rain**
- **glaze**
- **lightning**
- **sandstorm**
- **dew**

### Dataset Statistics

- **Total Classes:** 11
- **Total Images:** 6,862

#### Class Distribution:
| Class         | Image Count |
|---------------|-------------|
| hail          | 591         |
| rainbow       | 232         |
| frost         | 475         |
| rime          | 1,160       |
| fogsmog       | 851         |
| snow          | 621         |
| rain          | 526         |
| glaze         | 639         |
| lightning     | 377         |
| sandstorm     | 692         |
| dew           | 698         |

### Dataset Summary:
- **Mean Images per Class:** 623.82
- **Median Images per Class:** 621
- **Standard Deviation:** 232.91

## Exploratory Data Analysis (EDA)

### Class Distribution Visualization
We explored the class distribution using:

- **Pie Chart:** Visualized the proportional representation of each class.
- **Bar Plot:** Highlighted the number of images per class with statistical indicators (mean and median).

### Image Preview
We displayed sample images from each class to understand their visual characteristics. These images were processed using the Python Imaging Library (PIL) and visualized using Matplotlib.

## Libraries Used
- **Pandas**: For handling tabular data.
- **NumPy**: For numerical operations.
- **Matplotlib**: For creating static visualizations.
- **Seaborn**: For enhanced visualization.
- **Plotly Express**: For interactive pie charts.
- **Pillow (PIL)**: For image processing.
- **Glob**: For file management.

## Code Workflow
1. **Dataset Loading:**
   - Read the dataset directory.
   - Extract file paths and corresponding labels.

2. **Data Preprocessing:**
   - Randomly shuffled the dataset.
   - Stored file paths and labels in a structured DataFrame.

3. **Exploratory Analysis:**
   - Displayed sample images for initial understanding.
   - Analyzed class distributions.

4. **Visualization:**
   - Created pie charts and bar plots for class distribution.

## Results and Observations
- The dataset is imbalanced, with some classes (e.g., rainbow) having significantly fewer images compared to others (e.g., rime).
- Visual inspection of sample images helped confirm proper labeling and dataset integrity.

## Future Work
- Implement data augmentation techniques to address class imbalance.
- Train and evaluate a deep learning model for image classification.
- Explore transfer learning using pre-trained models like ResNet or EfficientNet.

## Getting Started

1. **Prerequisites:**
   Ensure the following libraries are installed:
   ```bash
   pip install numpy pandas matplotlib seaborn pillow plotly
   ```

2. **Run the Notebook:**
   Use the Kaggle environment or a local Jupyter Notebook to execute the code.

3. **Explore Results:**
   Review the generated visualizations and summaries.

## Acknowledgments
- Dataset: The dataset for this project is sourced from the Kaggle competition "Weather Image Classification".
- Tools: Thanks to Kaggle for providing the computational environment and support.

## Contact
For questions or feedback, please feel free to reach out through Kaggle or via email.

