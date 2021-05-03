# __CORRELATE__ - Digital Image Correlation Undergraduate Research Project

## Overview

!["CORRELATE Software](images/CORRELATE_1.png "CORRELATE Software")

Digital image correlation is a powerful computer-based technique for measuring strain fields. It works by comparing two images taken at different times and determining a mathematical description of the movement, or transformation, which an object in the pictures has undergone. A set of key points common to both images must be present. For materials with rough surfaces, it is possible to track regularly varying light and hue intensity features. For smooth surfaces typically a speckle pattern which results in high contrast between points is applied. It is not necessary to order these points as the correlation algorithm is able to handle an irregular distribution.

For this version of the software, a simplified technique is employed to pick out key points in
each image. This technique requires these points to have approximately the same color and stand out
from other objects in the image. In future iterations of the program, it will be possible to use dense speckle patterns with multiple hues
