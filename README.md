# Gentlest Tensorflow

## Goal

Tensorflow (TF) is Google’s attempt to put the power of Deep Learning into the hands of developers around the world. It comes with a beginner & an advanced tutorial, as well as a course on Udacity. However, the materials attempt to introduce both ML and TF concurrently to solve a multi-feature problem — character recognition, which albeit interesting, unnecessarily convolutes understanding. Gentlest Tensorflow attempts to overcome that by showing how to do linear regression for a single feature problem, and expand from there.

## Code

All the code are in `/code` directory:

* linear_regression_one_feature.py
  * ML with linear regression for a single feature
    * Example: predict house price from house size (single feature)
* linear_regression_one_feature_with_tensorboard.py
  * Add visualization for 'ML for single feature' with Tensorboard
    * Use tf.scalar_summary, tf.histogram_summary to collect data for variables that we want to visualize
    * Use `scope` to collapse TF network graph in to expandable/collapsible black boxes to faciliate visualization
* linear_regression_one_feature_using_mini_batch_with_tensorboard.py
  * Perform 'stochastic/mini-batch/batch' Gradient Descent with TF
  * The CUSTOMIZABLE section contains all the configurations that we can tweak, e.g., batch size, etc.
