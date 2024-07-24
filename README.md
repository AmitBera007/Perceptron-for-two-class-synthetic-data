# Perceptron-for-two-class-synthetic-data
This project allows for the annotation of 2D points using keyboard inputs and implements the Perceptron Learning Algorithm with different initialization strategies.

## Requirements
- numpy
- matplotlib
- pandas

You can install the necessary packages using pip:
```
pip install numpy matplotlib pandas
```
## Usage
### Annotate Points
Run gui_inputs.py to annotate points on a 2D plot using keyboard inputs. The keys '1', '2', ...,'7' are used to classify points. Press 'esc' to finish annotation.
```
python gui_inputs.py
```
The annotated points will be saved in a CSV file.

### Perceptron Learning
Run perceptron_2d_data.ipynb to read the annotated points from the CSV file and apply the Perceptron Learning Algorithm with different initializations. 
The results will be plotted.

## Files
- **`gui_inputs.py`** Script for annotating 2D points.
- **`perceptron_2d_data.ipynb`** Script for applying the Perceptron Learning Algorithm.
