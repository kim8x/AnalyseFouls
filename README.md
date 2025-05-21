#Multi-View Football Foul Detection Framework
This repository provides an advanced system designed to identify fouls in soccer matches using synchronized multi-camera footage. Leveraging deep learning and multi-view video analysis, it offers an efficient pipeline for foul detection and localization on the pitch.

Overview
Foul detection in football matches is a challenging task, often requiring multiple viewpoints to capture the context and details of player interactions. This project implements a multi-view video approach to automatically detect fouls using synchronized camera feeds, enabling accurate and robust identification of fouling events.

Our solution builds on state-of-the-art computer vision and deep learning techniques applied to the SoccerNet dataset and its extensions.

Key Features
Multi-Camera Input: Processes multiple synchronized video streams to leverage complementary views for enhanced foul detection accuracy.

Deep Learning Architecture: Employs a convolutional neural network with temporal and spatial modeling to detect fouls.

Event Localization: Detects the precise timing and positioning of fouls on the soccer pitch.

Benchmark Dataset: Compatible with SoccerNet and Multi-View Foul datasets, providing access to labeled video clips and annotations.

Evaluation Metrics: Includes scripts for standard evaluation measures such as mean Average Precision (mAP) and temporal localization accuracy.

Getting Started
Requirements
Python 3.7+

PyTorch 1.8+

OpenCV

Numpy

Additional dependencies listed in requirements.txt
