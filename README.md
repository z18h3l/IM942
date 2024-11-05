java c
IM942 Visualisation 
‘Graphical Report ‘- guidelines
This second piece of coursework gives you the opportunity to develop your own coding and visualisation skills in R. You will produce a visualisation using the data on Australian wildfires that is provided on Moodle. To find out more about the data please follow the links below. 
As introduced in the week 4 lecture, there is some controversy surrounding a visualisation of the fires. Using the same data, you have the opportunity to develop your design, which may be in response to the ‘fake news’ map censored by Instagram, or may take another direction.
1.   You have some freedom in what question you approach through the visualisation. What
would make a salient visualisation? Maybe your visualisation could compare techniques? Or emulate and explore an aspect of a design produced by a news outlet? Or could you explore some of the other dimensions of the data?
2.   You will provide some analysis and critique of your visualisation, and you can provide a personal reflection on how this has influenced your understanding about ‘visualisation’ .
3.   You will provide the R code for your visualisation in an appendix. This is mandatory. The
work will be your own and if you used a code snippet that you found on the web it must be referenced as such (e.g. creator, data, and source). Likewise, if you take inspiration from someone else’s work reference it or acknowledge it. Coding can be a very social activity but the work should be your own and indicate where it is not. Apply the same standards you would to the text, and if in doubt aska member of staff about how this should be approached. Note that the TunrItIn will recognise code which is not your own! 
4.    Your report will explain what you did, how you did it, and why you did it in that way. It is a short report so please summarise the important decision points rather than giving a blow by blow story of what happened “ … and then I loaded in the data which seemed to work fine at first but I had togo back and check that I had done it properly as my first line of code didn’t work, so I asked a friend and they said I hadn’tdone it properly so I looked up the issue on the internet. Boiled the kettle and made a cup of tea, and then found out I had a comma missing which I then put in and the code worked…” 
5.    Provide your main visualisation as figure 1 and on the first page of your report after the title and student number, but before the introduction. The visualisation must work within the constraints of the A4 page of your report (accounting for the margins). Your visualisation should be produced so it can be understood without the main text, i.e. provide sufficient titles, subtitles, annotations and a reference to the data should be added. You could think about it as producing a graphic that could be tweeted. Design the visualisation for the report and not how it is seen in the graphics device in R studio - i.e. take care with point and font sizes and labelling.
Data 
•    See the IM921 Moodle page for the csv file and the ‘readme’ text file from the download.
•    The data was downloaded via NASA’s FIRMS interface (Fire Information for Resource
Management System) -https://firms.modaps.eosdis.nasa.gov/map/#z:5;c:137.4,-27.9;t:adv- points;d:2019-12-05..2020-01-05;l:dark_gray,firms_viirs,firms_modis_a,firms_modis_t 
•    The lecture notes (Week 4 Part 3) have a variety of links to resources.
Common problems 
• Plotting thousands of points in one plot so they overlay each other. Why not recognise that occlusion issue and work with it? Can you respond to such issues in the design?
• Using the RGB ‘primary colours’ (green for land, blue for sea and red for fires). R can produce ‘any’ colour. Use a ‘colour picker’ and do some research (see below).
• Not carrying out any visual research. Why not provide three sources of visual inspiration? They could be previous visualisation work, inspiration for colour or methodological, for example.
• Saying that, objectively, your visualisation succeeds in every way. Can you articulate why something is subjective? That might lead you to a more balanced, critical argument.
• Trying to show everything. You will not be able to. The data has 95361 observation across
14 variables and, more importantly, the human perceptual and cognitive systems are limited. What does showing everything even show?
• Not stat代 写IM942 VisualisationR
代做程序编程语言ing a purpose for the visualisation or setting up a scenario. On what basis is your design effective? Or impactful? Why does it work? Or not? Adding more context and constraints to the design will inform. the design process and later direct provide some direction to the critique and analysis.
• Not asking for help early on. 
• Ignoring the notes below. 
Notes (some key notes are in bold)
• No interactive plots. 
• No Rainbow colour schemes (unless you are using it tactically). 
• No ggPlot unless there is a methodological rationale. 
• After 4-5 coding labs, and the work you have done outside of the labs, it is not expected that you have become an expert “visualiser” or have miraculously become a software engineer. The expectations are set by the level of the material you have been given and what it is feasible to do in this time. 
• Images other than your final design can be used to illustrate your design process (again, please be concise rather than providing every single visual you produced), or to show material which you took inspiration from. 
• Research the data and investigate if any visualisations have been produced from this data. 
There are limitations on how much we can understand from the documentation. This is a very real situation in the world of work. Put effort into understanding this aspect of the data – i.e. what is difficult to know – and recognise these limits where important in the report, and you may also incorporate that into your design. 
•    The general notes from coursework 1 apply. For example, rigorous referencing, reference    materials, use of images, referencing images, terminology (your visualisation should not be described as ‘pretty’) …
•    This is a graphical analysis rather than a statistical analysis. It is acceptable for you to use
statistical outputs in your visualisation if want to, however they will only be considered in terms of what they add to your visualisation.
•    If you think your visualisation is perfect then think again. Are there really no areas where your visualisation could be improved or where its form. limits its function?
•    You can decide how you design it. You may design it yourself, or, get some inspiration from
elsewhere. Remember to reference your inspirations! There is a whole world of inspiration you could draw from that includes but is not limited to visualisation outputs. However, remain
critical about what you did and why. If you chose something you thought was “cool” don’ttry to hide that. Recognise what made it “cool” and explain it in the report. A few places to get started include:
Accurat Studio / Giorgia Lupi  |https://www.accurat.it/works/ 
IBM Design Language |https://www.ibm.com/design/language/inspiration 
Nicolas Feltron |http://feltron.com/ 
Mortiz Stefaner  |http://truth-and-beauty.net/ 
Ben Fry  Fathom |https://fathom.info/projects/ 
Periscopic |http://www.periscopic.com/our-work 
•    Make it clear what you are trying to achieve with the visualisation. Is it for Exploring, Explaining, Exhibiting (Expositing), Evaluating or Exaggerating some aspect of the data and the visualisation?
•    There are limits to what we can process and understand visually (as we have discussed in class). A clean, salient graphic may well support you goals more effectively than trying to show every skill you have developed and every data point that the graphic has to offer.
•    You can produce avisualisation that is composed of multiple visualisations, for example by
combining plots in a layout. However, if you stitch to different visualisations together it is
obviously better that you did it for a reason rather than adding an extra pie chart just because.
•    To get the referencing information for R you can type ‘citation()’ into the console. You can use
the returned text – e.g. R Core Team (2017). R: A language and environment for statistical computing. R Foundation for Statistical Computing, Vienna, Austria. URLhttps://www.R-project.org/ - and format it according to your referencing style, or enter the bibtex entry in your reference management software. You can use the citation function for packages also – e.g. ‘citation(package="base"). 
•    Remember, if you think what you have done is ‘pretty’ then please pause to consider if you can define ‘pretty’! What is ‘pretty’?







         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
