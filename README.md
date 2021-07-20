# Statistics with Julia From the Ground Up

This is a workshop prepared for [JuliaCon2021](https://juliacon.org/2021/). See the [abstract](https://pretalx.com/juliacon2021/talk/A9KZCY/).

![A sample animation created during the workshop](sample_animation.gif)

In order to run the workshop make sure that you have Julia executable installed (it was tested under Julia 1.6.0 and 1.6.2).

One way to run the workshop is to run as follows:
1. Clone this [workshop repository](https://github.com/yoninazarathy/JuliaCon2021-StatisticsWithJuliaFromTheGroundUp) to a local folder on your computer (or download the zip file).
2. Start Julia in your local folder using the `julia` command.
3. If you don't have IJulia installed install it via (`]` puts you in package manager mode):
```
] 
add IJulia
```
Then hit backspace to exit the package manager.

4. Start Jupyter Notebook with:
```
using IJulia
notebook()
```
The first time you run `notebook` you may be asked if to install `Conda`. Recommended to hit `y`.

5. In the Jupyter envionrment that opens in your web browser, navigate to the correct folder which you downloaded, open the *Workshop.ipynb* file, and run the first few cells up to the section `Why Julia?`. These cells will install the needed packages in the enviornment for the workshop. This will take considerable time but only needs to be run once. Note the line with `using RCall` is commented out. If you have R installed on your system you may uncomment it (delete `#uncomment if using R: `). 

You can also consider:
- A version of the repository with [all output](https://github.com/yoninazarathy/JuliaCon2021-StatisticsWithJuliaFromTheGroundUp/blob/master/Workshop-with-output.ipynb) or look at it in [nbviewer](https://nbviewer.jupyter.org/github/yoninazarathy/JuliaCon2021-StatisticsWithJuliaFromTheGroundUp/blob/master/Workshop-with-output.ipynb#home).



Some key links:
* [JuliCon 2021](https://juliacon.org/2021/)
* [YouTube link to the workshop](https://www.youtube.com/watch?v=IlPoU5Yr2QI).
* [A nearly parallel workshop on DataFrames.jl](https://pretalx.com/juliacon2021/talk/FXZXMB/)
* [Statistics with Julia: Fundamentals for Data Science, Machine Learning and Artificial Intelligence](https://statisticswithjulia.org/)