# Audio-Filter
 The following code describes different methods of creating echoing filters for an audio file. The following functions are supposed to mimic performing a convolution with the impulse response.
 
* First function is for multi echo filter
  * Utilizing varying ranges for alpha R and N to get the right echo
  * ![image](https://user-images.githubusercontent.com/89094185/197247256-4b7039ce-0add-49ba-8aa2-4ddd65272a37.png)


* Second function is for feedback comb filter
  * Utilizes R and alpha to get a diminishing echo for the response
  * ![image](https://user-images.githubusercontent.com/89094185/197247290-e7234c3b-d4a4-4c1c-81a2-2cc7952bb1af.png)
 
* Source: https://github.com/spatialaudio/signals-and-systems-lecture/blob/master/discrete_systems_time_domain/convolution_room_IR.ipynb
