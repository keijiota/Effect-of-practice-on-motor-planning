# Effect-of-practice-on-motor-planning
This repository shares the experimental data in Ota et al. (2016, <em>Scientific Reports</em>). 
- Ota, K., Shinya, M., & Kudo, K. (2016). Sub-optimality in motor planning is retained throughout 9 days practice of 2250 trials. Scientific reports, 6, 37181.

We conducted a 9 days learning experiment where subjects performed a motor decision task. In each day, they performed the task for 5 blocks. One block consists of 50 trials of response selection. See Ota et al. 2016 for the details. 

# Data structure
There is a 1-by-15 cell in the mat file "learningexp.mat". <br>
Each cell corresponds to the data for each participant (15 participants were collected). 

In each cell, it includes a 50-by-6-by-45 matrix. <br>
Rows represent the number of trials from the 1st to 50th trial in each block. <br>
The third dimension is the number of blocks from the 1st to 45th block. <br>
Colmuns are as follows. <br> 
  First column: foreperiod (sec) <br>
  Second column: reference time (sec) <br>
  Third column: response time (sec) <br>
  Forth column: reference time minus response time  <br>
  Fifth column: score (points) <br>
  Sixth column: total score (points) <br>

Some data are filled with NaN (Not a number) because the data are completely missing or excluded from the analysis due to outliear trials (> +-2.5 SD from the mean response time). 

Please let me know if you have any questions. 
Please cite the article in the case you reuse the data. 
