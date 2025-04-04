# The Database of Religious History exploratory analysis
## or *Many questions about questions in The Database of Religious History*
### Overview
This project takes the form of an essay with code chunks and data visualization. It takes a critical stance towards the biggest available religious studies database from the point of view of data analysis and comparative studies of religion. 
To make this project data from [The Database of Religious History](https://religiondatabase.org/) website was analyzed using R language and then HTML report was made using Quarto. 

### Features 
Project explores two problems with the database: questions with little to none variance and unorganized labels. To do so there are multiple graphs included, like the one shown below. 

![image](https://github.com/user-attachments/assets/ca96e567-a81a-4831-9f9f-52a81dd3c683)

To visualize data that could not be easily plotted in two dimensions, an interactable graph was employed showing the relationship between labels, how many times it was used and how many labels entry to this type used on average. 

![database](https://github.com/user-attachments/assets/d2ef2d02-23cf-4fc4-9ee1-b91f9bacec41)

All the code is included in foldable chunks, as this project was the final submission for Data Analysis in R class at Jagiellonian University.

![database1](https://github.com/user-attachments/assets/7b3ade95-e0ae-49f7-b273-d92b25c00b8d)


### 3. Running the projects
To just view the essay: 
1. Clone repository locally
2. Open `Religious-History-database.html` file

To run the code yourself:
1. Clone repository locally
2. Unpack `data.rar`
3. `cd` to the project directory
4. Install the dependencies if needed 
5. Run the project in command line `quarto render Religious-History-database.qmd`

#### 3.1. Dependencies
* [Quarto](https://quarto.org/)
* [ggplot2](https://ggplot2.tidyverse.org/)
* [Tidyverse](https://www.tidyverse.org/)
* [Plotly](https://plotly.com/r/)
* [Patchwork](https://patchwork.data-imaginist.com/)
* [RColorBrewer](https://cran.r-project.org/web/packages/RColorBrewer/index.html)
