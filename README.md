# learn_python
Learning companion notes 

## Views vs Copies in Numpy/Pandas
Views do not own any data, but "views" original data. So modifying original also modifies view.

Copies become independent from original data.

Views are handy for saving memory space and reducing runtime.


### Copies and views in Numpy
In numpy we can check whether a variable is copy or view with `variable.flags.owndata` property of the `variable' 

#### 1-D array
Slicing operation returns views

Masking and integer indexing operations return copies
