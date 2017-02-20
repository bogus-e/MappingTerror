#Remembering Lynching: A Digital Memorial

## Abstract
A [physical memorial](http://eji.org/news/eji-announces-plans-to-build-museum-and-national-lynching-memorial) for the victims of lynching is in the works, and a schema for a [memorial reading](http://journals.sagepub.com.ezproxy.gc.cuny.edu/doi/abs/10.1177/2332649215583841) has been developed by some educators. Such projects are important to make the history of racist ideas and action visible, so that  Utilizing data on lynching in the postbellum South made available by sociologists, I propose the creation of a tool that announces the anniversaries of victim's killings as a mode to spread awareness about this dark chapter of U.S. history. The project will create or utilize an existing online archive of available materials on known lynching victims, develop a script to summarize information and a link to more materials, and feed this to other platforms, such as a webpage, social media, and/or an embedded text box that can be incorporated on other websites. 

## Deliverables
1. A complete, web-integrated collection of records of individual lynching victims that contains available information such as:
  1. the location, time, and date of the lynching
  1. the race, age, occupation, and family status of the victim
  1. any information on the mob (usually only race)
  1. materials such as newspaper articles, essays, books, or perhaps, photographs that describe the lynching
1. A script that compares the current date with dates of past lynchings and returns all matching records
1. A script that pulls information from the record and creates a statement in English 
1. A means by which to publicize the memorial

## Roles
### Project manager 
- Determines task timing and dependencies through consultation and research, as well as how to integrate independent work streams without redundancy
- Ensures that project choices will satisfy requirements
- Schedules meetings and establishes deadlines

Skills: Listening; attention to detail

### Archivist and Database Administrator
- Determines and acts on needs for data management, including how data will be stored, accessed, and modified
- Lead decisions around use and representation of data
- Understands all data requirements for features, as well as limitations of available data
- Manipulates data to necessary standards

Skills: SQL; Advanced Excel; OpenRefine or similar; understanding of metadata and archives

### Developer
- Develops scripts to interface with data and APIs
- Customize existing frameworks as needed to meet project requirements
- Leads front-end development 

Skills: Automation (likely in Python); basic algorithm knowledge; SQL; HTML/CSS and some JS

### Interface Designer and Project Advocate
- Leads decisions on textual and visual representation of the project
- Plans and executes strategy to increase project visibility
- Assists in front-end development
- Responds to inquiries
- Leads team in discussions of concerns and ethical questions

Skills: Knowledge of social media; communication skills; design skills 



## Needs and Resources
### Data
Perhaps the best source of lynching data is the Tolnay-Beck-Bailey inventory, which I have access to. There are severe limitations in spatial and temporal representation: it includes lynching data on 10 Southern states (noteably excluding Texas) between 1882-1930. See Cook (2012) for an excellent review of lynching data. 
### Archive
In addition to data, this project would ideally be able to link to all available information on each victims, including newspaper articles written about the lynching. The above inventory was used to create an [online database of lynching victims](http://lynching.csde.washington.edu/#/search). Using this page would make the project very easy. However, the only materials it has are internal records of lynching confirmations and census manuscript page on which the victim appears. While valuable, it includes neither the actual newspaper articles nor the data derived Bailey and Tolnay (2015) from the census records. 

##Bibliography
Bailey, Amy Kate, and Stewart E. Tolnay. 2015. Lynched: The Victims of Southern Mob Violence. Chapel Hill: The University of North Carolina Press.

Bailey, Amy Kate, Jason Leiker, Andrew Gutierrez, Eric C. Larson, and Serena Mitchell. 2015. “Memorializing Lynch Victims.” Sociology of Race and Ethnicity 1 (3): 454–459. doi:10.1177/2332649215583841.

Cook, Lisa D. 2012. “Converging to a National Lynching Database: Recent Developments and the Way Forward.” Historical Methods: A Journal of Quantitative and Interdisciplinary History 45 (2): 55–63. doi:10.1080/01615440.2011.639289.

Tolnay, Stewart E., and E. M. Beck. 1995. A Festival of Violence: An Analysis of Southern Lynchings, 1882-1930. Urbana: University of Illinois Press.

