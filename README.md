# Circle-U-CourseMapping
Webscraping programs tailor made for specific Circle U Universities course catalogues, so search for courses with a given keyword/s in the description. 

# Notes on setup and installations
The following requires anaconda prompt and jupyter lab. 

Opening anaconda prompt, create a new environment by typing: 
conda create --name coursemapping python=3.8

Activate your environment: 
conda activate coursemapping

You should now see (coursemapping) instead of (base) in the command line. Make installations one at a time like this:
conda install webdriver_manager
conda install -c conda-forge selenium
conda install -c conda-forge pandas
conda install -c conda-forge time
conda install ipykernel

You cannot work in an ipykernel for this program, you have to make your own type of kernel specifically for the selenium package. You do it by typing this in the command line: 
python -m ipykernel install --user --name=coursemapping

Now you can open jupyter lab by typing “jupyter lab” in the anaconda command prompt. When you open jupyter lab you will find a dropdown menu in the top right-hand corner where you can now change your kernel type to coursemapping instead of ipykernel. Now the imports in the files provided in this repository will not fail. 




