# seed-count
This aims at counting Arabidopsis thaliana T2 seeds carrying FAST reporter genes from bright field and fluorescent images, and calculate the segregation rates of each line.

Make sure that the files are named as: <construct#>_<Line#>(<image#>).jpg (for fluorescent images) and <construct#>_<Line#>(<image#>)_BF.jpg (for bright field images)

## How to use
1. Download or clone it to the folder containing all the images and run SeedCounting_All_in_One.ipynb on jupyter notebook. 
2. Use 'QuickCheck' = True to check if all the images are given proper thresholds. 
3. If there is some problem with the threshold, run 'FluCount' or 'BFCount' with 'Test = True' to see all possible threshold methods.
4. If everything is correct, the counts will be generated in a csv file named 'Counts.csv'
