

# Lunches with Data Challenges - Weekly meet-ups

[ Home](https://IVI-M.github.io/R-Ottawa/) --  [ Resources](resources.md) -- [ Community](community.md) -- [Lunches with Data Challenges](meetups.md) -- [ R101](101.md)


### Dial-in details


Topic: "Lunch and Learn: CMPUT101 using R" (Building Data Science App from the scratch - together).   
Lead by: Dmitry Gorodnichy  
Time: Every Wednesday and Friday at 12:20-12:55 Ottawa Time (Eastern US and Canada)    
<!-- Join Zoom Meeting: [https://us04web.zoom.us/j/337086550](https://us04web.zoom.us/j/337086550)    -->

Join Zoom Meeting:   [https://us04web.zoom.us/j/337086550](https://us04web.zoom.us/j/337086550?pwd=c202L3NhVlJyQVlIYTE5WTB4ZktQUT09) 
   
Meeting ID: 337 086 550     
Password: 19350706    

<!-- Password: 
*please contact the organizer or get it from
[GCCollab](https://gccollab.ca/discussion/view/4482867/enlunches-with-data-challenges-on-wednesdays-on-rfr)* -->

---


Since 2020/04/22 "Lunches with Data Challenges" meetings have become "Lunch and Learn: CMPUT101 using R" sessions.   
Please go [R101](101.md) page for all information related to these sessions.


See also:

- [List of various discussed data challenges](challenges.md) 
- [Collection of open R codes repositories in GitHub related to Ottawa and Canada](r-on-github-for-Canada.md)
- [ Resources](resources.md): for many other resources in R

---


####  Topics available for discussion

- [https://itrack.shinyapps.io/covid](https://itrack.shinyapps.io/covid/):   
Interactive Web App to better visualize and predict the spread of Covid19 pandemic [(LinkedIn article](https://www.linkedin.com/pulse/interactive-web-app-visualize-predict-spread-covid19-gorodnichy/))
  - accessing remote data: from GitHub (JHU database), from Google Docs (UofT database)
  - fast data manipulation using `data.table`
  - strategies for dealing with data abnomalities
  - use of `plotly` (interactive graphs), `DT` (interactive data tables), `dygraph`(interactive time-series visualizations)
  - `shiny` (interactive menus)
  - `rmarkdown`, `flexdashboard` - automated generation of reports and dashboards 
    - static self-contained html reports (which can be shared by email or locally),  vs.  
    - dynamic Web Apps reports/apps (which need to be hosted on the R server)
  - short-term forecasting 101 (features, assumptions, predictive models)
  - reproducible data science
  - functional, modular, scalable, agile programming
  - software Engineering 101 (naming conventions, splitting and sourcing, source control, github)
  
- [https://itrack.shinyapps.io/border/](https://itrack.shinyapps.io/border/)   
Predicting and optimizing Border Wait Time using Artificial Intelligence  [(LinkedIn article](https://www.linkedin.com/pulse/predicting-optimizing-border-wait-time-using-dmitry-gorodnichy/))
  - use of `leaflet` (interactive map)
  - building predictive models / machine learning
  - machine learning 101 (features, assumptions, predictive models), 
    - short-term vs. long-term forecasting
  - operations reseach 101 (resource optimization, constraint satisfaction)
  - running simulations  using `simmer`
  
- [https://itrack.shinyapps.io/PSES/](https://itrack.shinyapps.io/PSES/):   
Improving Public Service performance using Public Service Employee Surveys and Data Science [(LinkedIn article](https://www.linkedin.com/pulse/analyzing-improving-public-service-performance-using-data-gorodnichy/))
  - **Compare to**: PSES Power BI Visualization Tool from [https://hranalytics-analytiquerh.tbs-sct.gc.ca](https://hranalytics-analytiquerh.tbs-sct.gc.ca)
  - graphics and annotations with `ggplot2`
  - nested menus in `shiny`
  - `flexdashboard` layouts and options
  - data aggregation using `data.table`
  - automated report generation using `knitr` and `glue`


- **Automated Stress/Lie Detection:** Coding and research techniques explored in joint projects with [San Diego State University and University of Arizona](https://newscenter.sdsu.edu/sdsu_newscenter/news_story.aspx?sid=76505), and  [University of Ottawa](https://www.data-action-lab.com/2020/02/27/research-partnership-started-between-uottawa-and-cbsa-in-the-field-of-artificial-intelligence/) 
  - analyzing factors: correlations - library(corrgram),   library(corrplot), two-sample tests, and mixed-effect analysis:  lmer, glmer, nlmer, glm
  - complex modeling / machine learning / pattern recognition / neural networks using library(caret) (inc. rpart, randomForest
  - false positive, false negatives, precisions, error trade-off and other performance evaluations tricks: library(PRROC)
  - cool visualizations using: library(ggrepel); library(ggpubr);   library("gridExtra"); library(png)
  - library(eyetrackingR)


Check  [ R-101 ](https://github.com/IVI-M/R-Ottawa/tree/master/r101) for samples of discussed R codes.   
Back to [R Ottawa](https://ivi-m.github.io/R-Ottawa/). 
