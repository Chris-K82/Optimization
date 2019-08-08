2. Back propogation is a combination of Autodiff and steepest descent; this means that, rather than
   manually computing gradient at each iterative step, it is computed simultaneously using the
   principles of the chain rule from calculus to obtain the derivative of each previous neural layer.
   The separation, idealogically, of these two terms is in the difference between imperative
   programming vs functional.