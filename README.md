# Assignment 2: Image Segmentation and Evaluation

## Table of Contents

1. [N-Cut using Intensity Similarity Measure](#n-cut-using-intensity-similarity-measure)
   - [Implementation](#implementation)
   - [Modification and Testing](#modification-and-testing)
   - [Results](#results)
2. [N-Cut using Color Similarity Measure](#n-cut-using-color-similarity-measure)
   - [Implementation](#implementation-1)
   - [Modification and Testing](#modification-and-testing-1)
   - [Results](#results-1)
3. [Segmentation using ResNet-based FCN](#segmentation-using-resnet-based-fcn)
4. [Segmentation using MobileNetv2](#segmentation-using-mobilenetv2)
5. [Comparison Between Models](#comparison-between-models)
6. [Comparison with N-Cut](#comparison-with-n-cut)
7. [Observations and Challenges](#observations-and-challenges)

## N-Cut using Intensity Similarity Measure

### Implementation

- Implemented N-Cut algorithm using intensity similarity measure.
- Calculated similarity between pixels based on intensity.
- Computed weight matrix using feature proximity and spatial proximity terms.
- Applied cutoff distance for weight calculation.

### Modification and Testing

- Tested N-Cut on various test images.
- Applied image modifications: rotation and adding Gaussian noise.
- Tuned parameters like threshold distance and eigenvalue threshold for better results.

### Results

- Detailed results for test images and modifications.

## N-Cut using Color Similarity Measure

### Implementation

- Implemented N-Cut using color similarity measure based on HSV values.
- Computed color similarity and weight matrix.

### Modification and Testing

- Tested N-Cut with color similarity on resized test images.
- Adjusted threshold distances and eigenvalue thresholds.

### Results

- Detailed results for test images and modifications using color similarity.

## Segmentation using ResNet-based FCN

- Implemented a custom dataset.
- Split train and validation using provided text files.
- Applied data transformations and loaded data using data loader.
- Used FCN ResNet50 model with pixel-wise and mean IOU evaluation.

## Segmentation using MobileNetv2

- Implemented a custom dataset.
- Split train and validation data.
- Modified MobileNetv2 for semantic segmentation.
- Trained the model and evaluated pixel-wise and mean IOU.

## Comparison Between Models

- Compared FCN ResNet50 and MobileNetv2 models in terms of accuracy and IOU.

## Comparison with N-Cut

- Compared N-Cut segmentation results with FCN models.
- Analyzed differences and similarities between the approaches.

## Observations and Challenges

- Summarized observations and challenges faced during the assignment.
