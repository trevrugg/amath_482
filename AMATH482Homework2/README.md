This report presents the development and implementation of a classification algorithm for humanoid robot
OptimuS-VD’s movement recognition. OptimuS-VD records joint movements as Euler angles, which are
transformed into xyz coordinates. PCA is applied to reduce the dimensionality of movement data, enabling
visualization and classification of walking, jumping, and running. The following report evaluates the ef-
fectiveness of diﬀerent PCA truncations in retaining energy, establishes ground truth labels, and trains a
classifier based on centroids in PCA space. Finally, test samples are classified, and accuracy is analyzed.
